# SpanTraitExt

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt`

```rust
pub trait SpanTraitExt<T, +Clone<T>, +Drop<T>>
```

## Trait functions

### pop_front_n

Removes up to `n` elements from the front of `self` and returns them in a new span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::pop_front_n`

```rust
fn pop_front_n(ref self: Span<T>, n: usize) -> Span<T>
```


### pop_back_n

Removes up to `n` elements from the back of `self` and returns them in a new span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::pop_back_n`

```rust
fn pop_back_n(ref self: Span<T>, n: usize) -> Span<T>
```


### remove_front_n

Removes up to `n` elements from the front of `self`.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::remove_front_n`

```rust
fn remove_front_n(ref self: Span<T>, n: usize)
```


### remove_back_n

Removes up to `n` elements from the back of `self`.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::remove_back_n`

```rust
fn remove_back_n(ref self: Span<T>, n: usize)
```


### concat

Clones and appends all the elements of `self` and then `other` in a single new array.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::concat`

```rust
fn concat(self: Span<T>, other: Span<T>) -> Array<T>
```


### reversed

Return a new array containing the elements of `self` in a reversed order.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::reversed`

```rust
fn reversed(self: Span<T>) -> Array<T>
```


### contains

Returns `true` if the span contains an element with the given value.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::contains`

```rust
fn contains<+PartialEq<T>>(self: Span<T>, item: @T) -> bool
```


### position

Searches for an element the span, returning its index.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::position`

```rust
fn position<+PartialEq<T>>(self: Span<T>, item: @T) -> Option<usize>
```


### occurrences

Returns the number of elements in the span with the given value.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::occurrences`

```rust
fn occurrences<+PartialEq<T>>(self: Span<T>, item: @T) -> usize
```


### min

Returns the minimum element of a span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::min`

```rust
fn min<+PartialOrd<@T>>(self: Span<T>) -> Option<T>
```


### min_position

Returns the position of the minimum element of a span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::min_position`

```rust
fn min_position<+PartialOrd<@T>>(self: Span<T>) -> Option<usize>
```


### max

Returns the maximum element of a span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::max`

```rust
fn max<+PartialOrd<@T>>(self: Span<T>) -> Option<T>
```


### max_position

Returns the position of the maximum element of a span.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::max_position`

```rust
fn max_position<+PartialOrd<@T>>(self: Span<T>) -> Option<usize>
```


### dedup

Returns a new array, cloned from `self` but removes consecutive repeated elements. If the span is sorted, this removes all duplicates.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::dedup`

```rust
fn dedup<+PartialEq<T>>(self: Span<T>) -> Array<T>
```


### unique

Returns a new array, cloned from `self` but without any duplicate.

Fully qualified path: `alexandria_data_structures::span_ext::SpanTraitExt::unique`

```rust
fn unique<+PartialEq<T>>(self: Span<T>) -> Array<T>
```


