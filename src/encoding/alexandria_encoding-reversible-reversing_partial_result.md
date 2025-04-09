# reversing_partial_result

Fully qualified path: `alexandria_encoding::reversible::reversing_partial_result`

```rust
pub fn reversing_partial_result<
    T,
    +Copy<T>,
    +DivRem<T>,
    +TryInto<T, NonZero<T>>,
    +Drop<T>,
    +MulAssign<T, T>,
    +Rem<T>,
    +AddAssign<T, T>,
>(
    mut word: T, mut onto: T, size: usize, step: T,
) -> (T, T)
```

