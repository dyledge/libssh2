# libssh2 source code style guide

- 4 level indent
- spaces-only (no tabs)
- open braces on the if/for line:

  ```
  if (banana) {
      go_nuts();
  }
  ```

- keep source lines shorter than 80 columns
- See `libssh2-style.el` for how to achieve this within Emacs
