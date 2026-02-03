# Images Directory

This directory is ready for your website images.

## Recommended Structure

```
images/
├── logo/
│   └── rim-rescue-logo.png (or .svg)
├── before-after/
│   ├── job1-before.jpg
│   ├── job1-after.jpg
│   ├── job2-before.jpg
│   ├── job2-after.jpg
│   └── ...
└── general/
    └── workshop.jpg (for About page)
```

## Image Guidelines

- **Before/After Photos**: Use high-quality images showing clear before and after results
- **File Format**: JPG for photos, PNG for logos with transparency
- **Naming**: Use descriptive, lowercase names with hyphens (e.g., `audi-kerb-damage-before.jpg`)
- **Size**: Optimize images for web (aim for under 500KB per image)
- **Dimensions**: Recommended 800x600px or similar for gallery images

## Adding Images to the Site

1. Place images in appropriate subdirectories
2. Update the HTML `<div class="image-placeholder">` elements with `<img>` tags
3. Example: `<img src="images/before-after/job1-before.jpg" alt="Kerb damage before repair">`

The website is designed to work with image placeholders now, but will display real images beautifully once they're added.
