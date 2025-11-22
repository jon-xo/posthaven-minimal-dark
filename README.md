# Posthaven Minimal Dark Theme

A minimal dark Posthaven theme inspired by [brittanychiang.com](https://brittanychiang.com) - featuring modern typography, a dark blue palette, and clean layout.

## Design Inspiration

This theme takes design cues from Brittany Chiang's personal website, including:
- **Dark navy background** (#0f172a - slate-900)
- **Light headings** (#e2e8f0 - slate-200)  
- **Accent color** (#5eead4 - teal-300)
- **Muted text** (#94a3b8 - slate-400)
- **Inter font family** for modern, clean typography
- **Generous spacing** and minimal design

## Features

- ✅ Fully customizable colors (heading, background, accent, text)
- ✅ Font selection (Inter, Georgia, or system default)
- ✅ Responsive design
- ✅ Clean, accessible markup
- ✅ All 8 required Posthaven templates included

## Installation

1. Install the [posthaven_theme gem](https://github.com/posthaven/posthaven_theme):
```bash
gem install posthaven_theme
```

2. Clone this repository:
```bash
git clone https://github.com/jon-xo/posthaven-minimal-dark.git
cd posthaven-minimal-dark
```

3. Configure with your API key:
```bash
phtheme configure YOUR_API_KEY
```

4. Upload the theme:
```bash
phtheme upload
```

5. Preview and activate from your Posthaven Dashboard → Settings → Theme

## Theme Structure

Per [Posthaven theme documentation](https://theme-docs.posthaven.com), this theme includes:

```
posthaven-minimal-dark/
├── assets/
│   └── style.css          # Main stylesheet
├── config/
│   └── theme.yml          # Theme configuration ✓
├── layouts/
│   └── theme.liquid       # Main layout wrapper
├── snippets/
│   ├── header.liquid      # Site header
│   └── footer.liquid      # Site footer  
└── templates/
    ├── homepage.liquid    # Main post listing
    ├── post.liquid        # Single post view
    ├── page.liquid        # Single page view
    ├── archive.liquid     # Archive with search
    ├── author.liquid      # Author post listing
    ├── tag.liquid         # Tag post listing
    ├── tags.liquid        # All tags view
    └── missing.liquid     # 404 page
```

## Customization

After installing, customize the theme from your Posthaven Dashboard:

- **Heading Color** - Color for h1, h2, h3 elements
- **Background Color** - Main page background
- **Accent Color** - Links and highlights  
- **Text Color** - Body text color
- **Heading Font** - Choose Inter, Georgia, or system default
- **Body Font** - Choose Inter, Georgia, or system default
- **Show Social Links** - Toggle social link display

## Next Steps

**TODO:** Complete remaining template and asset files. The config/theme.yml file has been created with all customization settings.

### Required Files to Add:

1. **assets/style.css** - Main stylesheet with Inter font, color variables, and responsive layout
2. **layouts/theme.liquid** - HTML wrapper with `{{ content_for_layout }}`
3. **templates/*.liquid** - All 8 required template files
4. **snippets/*.liquid** - Reusable header/footer components (optional)

## Development

To modify this theme:

1. Edit files locally
2. Use `phtheme watch` to auto-upload changes
3. Refresh your Posthaven site to see updates

## Resources

- [Posthaven Theme Documentation](https://theme-docs.posthaven.com)
- [Liquid Template Language](https://shopify.github.io/liquid/)
- [brittanychiang.com](https://brittanychiang.com) (design inspiration)

## License

MIT License - see LICENSE file

## Credits

Design inspired by [Brittany Chiang's website](https://brittanychiang.com)  
Created by jon-xo
