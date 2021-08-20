# AzaleaBook - Theme for mdbook

![Issues](https://img.shields.io/github/issues/IrvanAhmadP/azaleabook-theme)
![Forks](https://img.shields.io/github/forks/IrvanAhmadP/azaleabook-theme)
![Stars](https://img.shields.io/github/stars/IrvanAhmadP/azaleabook-theme)
![License](https://img.shields.io/github/license/IrvanAhmadP/azaleabook-theme)

## Preview

| Light | Dark |
| :---: | :--: |
| ![Azaleabook Light](preview/AzaleaBook-Theme-1.webp) | ![Azaleabook Dark](preview/AzaleaBook-Theme-2.webp) |

## Usage

- Create a book with the command `mdbook init`.

  ```txt
  mdbook init <directory>
  ```

- Clone theme from github.

  ```txt
  cd <directory>
  git clone https://github.com/IrvanAhmadP/azaleabook-theme.git
  ```

- Delete preview folder.

- Config `book.toml`.

  ```toml
  [output.html]
  theme = "azaleabook-theme"
  default-theme = "azaleabook-light"
  preferred-dark-theme = "azaleabook-dark"
  ```
