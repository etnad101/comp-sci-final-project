# comp-sci-final-project

## main.rs

```Rust
mod components;
mod pages;
mod backend;
mod stores;
mod tests;
use pages::app::App;

fn main() {
    yew::Renderer::<App>::new().render();
}
```