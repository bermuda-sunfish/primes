primes
======

![Rust](https://github.com/bermuda-sunfish/primes/workflows/Rust/badge.svg)

A prime generator for Rust.

This package is available on [crates.io](git@github.com:wackywendell/primes.git) as `primes`.

This package provides an iterator over `all` primes, generating them lazily as it goes.

The simplest usage is simply to create an `Iterator`:

```
use primes::PrimeSet;

let mut pset = PrimeSet::new();

for (ix, n) in pset.iter().enumerate().take(10) {
    println!("Prime {}: {}", ix, n);
}
```

For more examples, see  [the full documentation](http://wackywendell.github.io/primes)!
