# Паттерны

## Creational (порождающие)

Порождающие паттерны занимаются механизмами создания объектов.
Они позволяют создавать объекты с определенными характеристиками в различных ситуациях, обеспечивая гибкость и удобство управления процессом создания объектов.
Порождающие паттерны обеспечивают инкапсуляцию создания объектов, а также приводят к уменьшению связанности между компонентами системы.

### Singleton

Singleton гарантирует существование только одного экземпляра класса и предоставляет глобальную точку доступа к этому экземпляру.
Он часто используется, когда требуется обеспечить единственный экземпляр класса, например, для доступа к глобальным ресурсам, конфигурации, или для создания центрального объекта управления в приложении.

### Factory Method

Предназначен для создания объектов, но оставляет подклассам решение о том, какой класс создавать. Таким образом, он делегирует создание объектов дочерним классам, позволяя им предоставлять специфичные для них реализации создания объектов.

### Abstract Factory

Abstract Factory предоставляет интерфейс, группирующий другие фабрики.

### Prototype

Применяется для создания копий объектов, сохраняя при этом их структуру.

### Builder

Используется для пошагового создания сложных объектов с использованием одного и того же процесса построения. Он позволяет создавать различные конфигурации объекта, изолируя детали конструирования от самого объекта.

### Decorator

Предназначен для добавления функциональности объекту без изменения его структуры. Декораторы оборачивают объект, добавляя новое поведение или изменяя существующее.

## Structural (структурные)

Рассматривают образование более крупных структур из объектов и классов

### Facade

Предназначен для скрытия сложной логики. Упрощает работу с системой, предоставляя более высокоуровневый интерфейс.

### Proxy (заместитель)

Предоставляет заменитель для другого объекта, чтобы контролировать доступ к нему.

### Adapter

Позволяет объектам с несовместимыми интерфейсами работать вместе.

### Composite

Позволяет обращаться к отдельным объектам и их композициям единообразно.

### Bridge

Разделяет абстракцию и реализацию, позволяя им изменяться независимо друг от друга.

### Flyweight

Позволяет использовать общие объекты для представления множества подобных объектов, сэкономив ресурсы.

## Behavioral (поведенческие)

Связаны с распределением обязанностей между объектами и описывают структуру и шаблоны для передачи сообщений / связи между компонентами.

### Mediator (посредник)

Нужен для того, чтобы уменьшить связанность классов между собой и устанавливает все необходимые связи внутри себя. Приводит к большей расширяемости классов.

### Iterator

Предоставляет механизм последовательного доступа к элементам коллекции без раскрытия её внутренней структуры.
