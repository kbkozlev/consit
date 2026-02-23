# consit

`consit` is a Hugo theme for consulting and business websites.  
It is built for a clean corporate presentation with ready-made sections for services, blog content, careers, and contact information.

## Features

- Responsive business-focused layout
- Services and positions/careers sections
- Blog list and post templates
- Contact page structure
- SEO-friendly metadata support
- Configurable header, hero, and footer

## Requirements

- Hugo Extended `>= 0.118.0`

## Install

### Option 1: Use as a theme in an existing Hugo site

1. Go to your Hugo site root:

```bash
cd /path/to/your-hugo-site
```

2. Add this theme:

```bash
git submodule add https://github.com/kbkozlev/consit.git themes/consit
```

3. Set the theme in your `hugo.toml`:

```toml
theme = "consit"
```

4. Start the dev server:

```bash
hugo server -D
```

### Option 2: Run this repository directly

1. Clone the project:

```bash
git clone https://github.com/kbkozlev/consit.git
cd consit
```

2. Start Hugo:

```bash
hugo server -D
```

## Configuration

Front-page configuration is in `hugo.toml`, including:

- Header menu and logo (`[params.header]`)
- Hero section (`[params.hero]`)
- Services (`[params.services]`)
- Blog section (`[params.blog]`)
- Footer columns and links (`[params.footer]`)
- SEO defaults (`[params.seo]`)

The configuration for the `about`, `blog`, `contact` etc. is made in the `_index.md` page of each section.
