# u128_join

Join two u128 into one Parameters: - left: the left part of u128 - right: the right part of u128 - right_size: the size of right part in bytes Returns: - value: the joined u128 Examples: u128_join(0x010203, 0xaabb, 2) -> 0x010203aabb u128_join(0x010203, 0, 2) -> 0x0102030000

Fully qualified path: `alexandria_bytes::utils::u128_join`

```rust
pub fn u128_join(left: u128, right: u128, right_size: usize) -> u128
```

