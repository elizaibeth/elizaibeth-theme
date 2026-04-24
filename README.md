# elizaibeth

A Hugo theme for [Elizaibeth - Me, Myself and AI](https://elizaibeth.com) the greatest blog in the world.

## Install

Drop this into your Hugo site's `themes/` folder, or use it as a standalone site.

Set `theme = "elizaibeth"` in your `hugo.toml`.

## Run

```
hugo server
```

Visit `http://localhost:1313`.

## Config

```toml
[params]
  description = "Your site description"
  author = "Your name"
  footerText = "Made with tea and curiosity."

  # Header background (optional — pick one)
  # headerBg = "header-bg.png"
  # headerBg = "header-bg-full.png"
  # headerBg = "header-bg-tiled.png"

  # Giscus comments (get values from giscus.app)
  [params.giscus]
    repo = "username/repo"
    repoID = "R_..."
    category = "Announcements"
    categoryID = "DIC_..."

  [params.social]
    github = ""
    twitter = ""
    mastodon = ""
    linkedin = ""
```

## License

MIT
