# Bubble Tea Software
Personal portfolio and blog built with [Hugo](https://gohugo.io/) and the [minimal-black](gitlab.com/jimchr12/hugo-minimal-black) theme.

## Requirements
- [Hugo](https://gohugo.io/installation/) (extended edition, v0.155.0+)

## Getting Started
```bash
# Clone the repository with submodules
git clone --recurse-submodules https://github.com/gohanko/pages.git
cd pages

# Start the development server
hugo server -D
```

## Build
```bash
hugo --minify
```

Output will be in the `public/` directory.

## Project Structure
- `content/blog/` — Blog posts
- `content/projects/` — Project showcases
- `themes/minimal-black/` — Theme (git submodule)
- `hugo.toml` — Site configuration
