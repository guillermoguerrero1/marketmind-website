# Assets Folder Structure Guide

## Required Assets for MarketMind Platform

Create an `assets/` folder in your `public_html/` directory with the following structure:

```
assets/
├── favicon.ico          # Website favicon (16x16 or 32x32 pixels)
├── hero-app.png         # Main hero section app preview image
├── screenshot-1.png     # Dashboard screenshot
├── screenshot-2.png     # Trade entry screenshot  
├── screenshot-3.png     # Analytics screenshot
├── app-store-badge.png  # App Store download badge
└── google-play-badge.png # Google Play download badge
```

## Image Specifications

### favicon.ico
- **Size**: 16x16, 32x32, or 48x48 pixels
- **Format**: ICO format
- **Purpose**: Browser tab icon

### hero-app.png
- **Size**: 600x800 pixels (or similar aspect ratio)
- **Format**: PNG with transparency support
- **Purpose**: Main hero section app preview

### Screenshots (screenshot-1.png, screenshot-2.png, screenshot-3.png)
- **Size**: 800x600 pixels (or similar aspect ratio)
- **Format**: PNG or JPG
- **Purpose**: App screenshots for features section

### App Store Badge (app-store-badge.png)
- **Size**: 200x60 pixels
- **Format**: PNG
- **Purpose**: iOS App Store download button

### Google Play Badge (google-play-badge.png)
- **Size**: 200x60 pixels
- **Format**: PNG
- **Purpose**: Google Play Store download button

## Image Optimization Tips

1. **Compress images** to reduce file size while maintaining quality
2. **Use appropriate formats**:
   - PNG for images with transparency
   - JPG for photographs
   - WebP for modern browsers (optional)
3. **Optimize dimensions** to match display requirements
4. **Consider lazy loading** for better performance

## Alternative Solutions

If you don't have the exact images:

### App Store Badges
- Download official badges from Apple Developer and Google Play Console
- Use placeholder images temporarily
- Create custom badges matching your brand

### Screenshots
- Use placeholder images (800x600) with descriptive text
- Create mockups using design tools
- Use stock photos temporarily

### Hero Image
- Use a placeholder app mockup
- Create a simple illustration
- Use a relevant stock photo

## File Upload Process

1. **Create assets folder** in HostGator public_html directory
2. **Upload all image files** to the assets folder
3. **Verify file permissions** (644 for files, 755 for folders)
4. **Test image loading** on your website
5. **Check for broken images** in browser developer tools

## Troubleshooting

### Images Not Displaying
- Check file paths in HTML
- Verify files were uploaded to correct location
- Check file permissions
- Clear browser cache

### Poor Image Quality
- Ensure original images are high resolution
- Don't scale up small images
- Use appropriate image formats
- Consider responsive images for different screen sizes

### Slow Loading
- Compress images appropriately
- Consider using WebP format
- Implement lazy loading
- Use CDN for image delivery (optional)
