# MerkleTreeTrait

MerkleTree trait.

Fully qualified path: `alexandria_merkle_tree::merkle_tree::MerkleTreeTrait`

```rust
pub trait MerkleTreeTrait<T>
```

## Trait functions

### new

Create a new merkle tree instance.

Fully qualified path: `alexandria_merkle_tree::merkle_tree::MerkleTreeTrait::new`

```rust
fn new() -> MerkleTree<T>
```


### compute_root

Compute the merkle root of a given proof.

Fully qualified path: `alexandria_merkle_tree::merkle_tree::MerkleTreeTrait::compute_root`

```rust
fn compute_root(ref self: MerkleTree<T>, current_node: felt252, proof: Span<felt252>) -> felt252
```


### verify

Verify a merkle proof.

Fully qualified path: `alexandria_merkle_tree::merkle_tree::MerkleTreeTrait::verify`

```rust
fn verify(ref self: MerkleTree<T>, root: felt252, leaf: felt252, proof: Span<felt252>) -> bool
```


### compute_proof

Compute a merkle proof of given leaves and at a given index.

Fully qualified path: `alexandria_merkle_tree::merkle_tree::MerkleTreeTrait::compute_proof`

```rust
fn compute_proof(ref self: MerkleTree<T>, leaves: Array<felt252>, index: u32) -> Span<felt252>
```


