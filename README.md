# Rust blog-io dead:beef::1 

Based on Awesome blog and fasterthanlime.

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

## Run the blog
- Install rust on your Operating System [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)
- Clone the Repo
- `cd blog-io`
- `cargo run`
- The blog runs on localhost:8080
