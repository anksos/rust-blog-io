# Rust blog-io dead:beef::1 

## dead:beef::1 blog structure

```rust
- blog-io/
    - posts/
        - my-first-article/
            - post_frontmatter.toml
            - post.md
    - src/
        - handlers/
            - home_handlers.rs
            - mod.rs
            - post_handler.rs
        - lib.rs
        - main.rs
        - static/
            - css/
                - index.css
        - tailwind/
            - base.css
            - package.json
            - tailwind.config.js
        - templates/
            - base.html
            - home.html
            - post.html
        - Cargo.toml
- .gitignore
- LICENSE
- README.md

```