# cursive-cached-text-view

[![crates.io](https://img.shields.io/crates/v/cursive-cached-text-view.svg)](https://crates.io/crates/cursive-cached-text-view)
[![Rust](https://github.com/night-crawler/cursive-cached-text-view/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/night-crawler/cursive-cached-text-view/actions/workflows/rust.yml)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

A drop-in replacement for `TextView` with row cache. With complex layouts and thousands of rows, 
this can improve performance significantly.

### Example

```rust
use cursive_cached_text_view::CachedTextView;

fn main() {
    let mut view = CachedTextView::new("sample", 5);
    // the rest is the same as TextView
}
```
