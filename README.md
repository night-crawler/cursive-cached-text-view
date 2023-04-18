# cursive-cached-text-view

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
