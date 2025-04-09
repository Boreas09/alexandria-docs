# ArrayTraitExt

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt`

```rust
pub trait ArrayTraitExt<T, +Clone<T>, +Drop<T>>
```

## Trait functions

### append_all

Moves all the elements of `other` into `self`, leaving `other` empty.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::append_all`

```rust
fn append_all(ref self: Array<T>, ref other: Array<T>)
```


### extend_from_span

Clones and appends all the elements of `other` into `self`.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::extend_from_span`

```rust
fn extend_from_span(ref self: Array<T>, other: Span<T>)
```


### pop_front_n

Removes up to `n` elements from the front of `self` and returns them in a new array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::pop_front_n`

```rust
fn pop_front_n(ref self: Array<T>, n: usize) -> Array<T>
```


### remove_front_n

Removes up to `n` elements from the front of `self`.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::remove_front_n`

```rust
fn remove_front_n(ref self: Array<T>, n: usize)
```


### concat

Clones and appends all the elements of `self` and then `other` in a single new array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::concat`

```rust
fn concat(self: @Array<T>, other: @Array<T>) -> Array<T>
```


### reversed

Return a new array containing the elements of `self` in a reversed order.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::reversed`

```rust
fn reversed(self: @Array<T>) -> Array<T>
```


### contains

Returns `true` if the array contains an element with the given value.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::contains`

```rust
fn contains<+PartialEq<T>>(self: @Array<T>, item: @T) -> bool
```


### position

Searches for an element in the array, returning its index.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::position`

```rust
fn position<+PartialEq<T>>(self: @Array<T>, item: @T) -> Option<usize>
```


### occurrences

Returns the number of elements in the array with the given value.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::occurrences`

```rust
fn occurrences<+PartialEq<T>>(self: @Array<T>, item: @T) -> usize
```


### min

Returns the minimum element of an array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::min`

```rust
fn min<+PartialOrd<@T>>(self: @Array<T>) -> Option<T>
```


### min_position

Returns the position of the minimum element of an array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::min_position`

```rust
fn min_position<+PartialOrd<@T>>(self: @Array<T>) -> Option<usize>
```


### max

Returns the maximum element of an array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::max`

```rust
fn max<+PartialOrd<@T>>(self: @Array<T>) -> Option<T>
```


### max_position

Returns the position of the maximum element of an array.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::max_position`

```rust
fn max_position<+PartialOrd<@T>>(self: @Array<T>) -> Option<usize>
```


### dedup

Returns a new array, cloned from `self` but removes consecutive repeated elements. If the array is sorted, this removes all duplicates.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::dedup`

```rust
fn dedup<+PartialEq<T>>(self: @Array<T>) -> Array<T>
```


### unique

Returns a new array, cloned from `self` but without any duplicate.

Fully qualified path: `alexandria_data_structures::array_ext::ArrayTraitExt::unique`

```rust
fn unique<+PartialEq<T>>(self: @Array<T>) -> Array<T>
```


