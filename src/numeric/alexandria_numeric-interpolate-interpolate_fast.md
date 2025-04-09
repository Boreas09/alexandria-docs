# interpolate_fast

Fully qualified path: `alexandria_numeric::interpolate::interpolate_fast`

```rust
pub fn interpolate_fast<
    T, +PartialOrd<T>, +Add<T>, +Sub<T>, +Mul<T>, +Div<T>, +Zero<T>, +Copy<T>, +Drop<T>,
>(
    x: T, xs: Span<T>, ys: Span<T>, interpolation: Interpolation, extrapolation: Extrapolation,
) -> T
```

