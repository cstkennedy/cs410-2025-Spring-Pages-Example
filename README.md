# Example GitHub Pages Site

# Quick Links

  - [GitHub Pages Site](https://cstkennedy.github.io/cs410-2025-Spring-Pages-Example/)
  - [GitHub Repository](https://github.com/cstkennedy/cs410-2025-Spring-Pages-Example)


## HTML & CSS Reference

  - [HTML](https://www.w3schools.com/html/default.asp)
  - [CSS](https://www.w3schools.com/css/default.asp)
  - [Bootstrap](https://www.w3schools.com/bootstrap5/index.php)


## JavaScript Reference

T.B.W.


# Notes

By default `README.md` will be used as your GitHub Pages site's `index.html`
(i.e., landing/home page).


## Code Snippets

Code snippets are denoted with triple backticks followed by the language.

```rust
#[derive(Debug, Error, PartialEq)]
pub enum StrategyError {
    #[error("{:?}", .0)]
    ParseError(#[from] std::num::ParseIntError),
    #[error("{:?}", .0)]
    BoardError(#[from] BoardError),
    #[error("{:?}", .0)]
    OutOfMovesError(String),
}
```

```python
 _KNOWN_SHAPES: dict[str, Callable[[None | list[float]], Shape]] = {
    # ...
}
```




