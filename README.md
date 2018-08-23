CPU Time Measurement Library
============================

[Documentation](https://docs.rs/cpu-time) |
[Github](https://github.com/tailhook/cpu-time) |
[Crate](https://crates.io/crates/cpu-time)


A simple and idiomatic interface for measurement CPU time:

```rust

let start = process_time();
# .. do something ..
let cpu_time: Duration = start.elapsed();
println!(" {:?}");

```


License
=======

Licensed under either of

* Apache License, Version 2.0,
  (./LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license (./LICENSE-MIT or http://opensource.org/licenses/MIT)
  at your option.

Contribution
------------

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.

