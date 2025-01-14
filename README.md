# tutorforall-website
 tutorforall-website

# Image Optimization Guidelines

## Directory Structure
```
assets/images/
├── logo/                  # Logo variations
│   ├── logo.jpeg         # Original logo
│   ├── logo-small.jpeg   # Small version for mobile
│   └── favicon.ico       # Website favicon
├── hero/                 # Hero section images
│   ├── home-hero.jpg
│   └── about-hero.jpg
├── experts/             # Expert profile images
│   ├── expert1.jpg
│   └── expert2.jpg
├── blog/               # Blog post images
│   ├── featured/
│   └── posts/
└── testimonials/      # Student testimonial images
```

## Image Size Guidelines

1. Logo Images:
   - Header Logo: 160x64px
   - Footer Logo: 100x40px
   - Favicon: 32x32px

2. Hero Images:
   - Desktop: 1920x1080px
   - Mobile: 750x1000px

3. Expert Profile Images:
   - Large: 400x400px
   - Thumbnail: 100x100px

4. Blog Images:
   - Featured: 800x400px
   - Post Thumbnails: 400x200px

5. Testimonial Images:
   - Profile Pictures: 120x120px

## Optimization Guidelines

1. Use WebP format with JPEG fallback
2. Compress all images using tools like TinyPNG
3. Include proper alt text for SEO
4. Lazy load images below the fold
5. Use responsive images with srcset
6. Keep image file sizes under:
   - Hero images: 200KB
   - Regular images: 100KB
   - Thumbnails: 30KB
[![Netlify Status](https://api.netlify.com/api/v1/badges/8cad57d4-4252-483d-838e-a762f4f3b4b2/deploy-status)](https://app.netlify.com/sites/cloudoftutors/deploys)
