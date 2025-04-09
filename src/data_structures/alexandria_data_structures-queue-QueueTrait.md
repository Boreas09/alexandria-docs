# QueueTrait

Fully qualified path: `alexandria_data_structures::queue::QueueTrait`

```rust
pub trait QueueTrait<T>
```

## Trait functions

### new

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::new`

```rust
fn new() -> Queue<T>
```


### enqueue

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::enqueue`

```rust
fn enqueue(ref self: Queue<T>, value: T)
```


### dequeue

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::dequeue`

```rust
fn dequeue(ref self: Queue<T>) -> Option<T>
```


### peek_front

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::peek_front`

```rust
fn peek_front(self: @Queue<T>) -> Option<Box<@T>>
```


### len

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::len`

```rust
fn len(self: @Queue<T>) -> usize
```


### is_empty

Fully qualified path: `alexandria_data_structures::queue::QueueTrait::is_empty`

```rust
fn is_empty(self: @Queue<T>) -> bool
```


