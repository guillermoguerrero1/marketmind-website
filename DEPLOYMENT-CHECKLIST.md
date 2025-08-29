# HostGator Migration Deployment Checklist

## Pre-Migration
- [ ] Backup all current website files
- [ ] Verify HostGator hosting account is active
- [ ] Confirm domain marketmindplatform.com is registered and pointing to HostGator
- [ ] Have HostGator cPanel login credentials ready

## File Preparation
- [ ] All HTML files updated with new domain references
- [ ] CSS files ready for upload
- [ ] JavaScript files ready for upload
- [ ] Image assets organized in assets/ folder
- [ ] .htaccess file created and ready
- [ ] Error pages (404.html, 500.html) created

## HostGator Setup
- [ ] Log into HostGator cPanel
- [ ] Navigate to File Manager
- [ ] Access public_html directory
- [ ] Clear any existing files (if starting fresh)

## File Upload
- [ ] Upload index.html to public_html/
- [ ] Upload privacy-policy.html to public_html/
- [ ] Upload support.html to public_html/
- [ ] Upload css/ folder with styles.css
- [ ] Upload js/ folder with main.js
- [ ] Upload assets/ folder with all images
- [ ] Upload .htaccess file to public_html/
- [ ] Upload 404.html to public_html/
- [ ] Upload 500.html to public_html/

## Domain Configuration
- [ ] Verify domain is properly configured in cPanel
- [ ] Check DNS settings are correct
- [ ] Test domain resolves to HostGator servers

## SSL Certificate
- [ ] Enable SSL certificate in cPanel
- [ ] Verify HTTPS is working
- [ ] Test .htaccess HTTPS redirect

## Testing
- [ ] Visit https://marketmindplatform.com/
- [ ] Test all navigation links
- [ ] Verify CSS styling is applied
- [ ] Test JavaScript functionality
- [ ] Check mobile responsiveness
- [ ] Test error pages (404, 500)
- [ ] Verify all images display correctly
- [ ] Test contact email links

## Performance & Security
- [ ] Verify .htaccess rules are working
- [ ] Check browser caching is enabled
- [ ] Test GZIP compression
- [ ] Verify security headers are set
- [ ] Test file permissions (644 for files, 755 for folders)

## Post-Migration
- [ ] Update any external links pointing to old domain
- [ ] Update Google Analytics (if using)
- [ ] Update Google Search Console (if using)
- [ ] Test website on multiple devices
- [ ] Monitor website performance
- [ ] Set up monitoring for downtime

## Final Verification
- [ ] Website loads correctly on all major browsers
- [ ] All functionality works as expected
- [ ] SSL certificate is active and working
- [ ] Domain redirects properly
- [ ] No broken links or missing resources
- [ ] Website performance is acceptable

## Contact Information
- **HostGator Support**: Available 24/7 via live chat and phone
- **Emergency Contact**: Your web developer or IT team
- **Domain Registrar**: If you need to update DNS settings

## Notes
- Keep old website running until migration is 100% complete
- Test thoroughly before switching DNS
- Monitor website for 24-48 hours after migration
- Have rollback plan ready if issues arise
