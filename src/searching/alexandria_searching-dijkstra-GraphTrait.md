# GraphTrait

Graph trait.

Fully qualified path: `alexandria_searching::dijkstra::GraphTrait`

```rust
pub trait GraphTrait
```

## Trait functions

### new

Create a new graph instance.

Fully qualified path: `alexandria_searching::dijkstra::GraphTrait::new`

```rust
fn new() -> Graph<Nullable<Span<Node>>>
```


### add_edge

add an edge to graph

Fully qualified path: `alexandria_searching::dijkstra::GraphTrait::add_edge`

```rust
fn add_edge(ref self: Graph<Nullable<Span<Node>>>, source: u32, dest: u32, weight: u128)
```


### shortest_path

return shortest path from s

Fully qualified path: `alexandria_searching::dijkstra::GraphTrait::shortest_path`

```rust
fn shortest_path(ref self: Graph<Nullable<Span<Node>>>, source: u32) -> Felt252Dict<u128>
```


### adj_nodes

return shortest path from s

Fully qualified path: `alexandria_searching::dijkstra::GraphTrait::adj_nodes`

```rust
fn adj_nodes(ref self: Graph<Nullable<Span<Node>>>, source: felt252) -> Nullable<Span<Node>>
```


