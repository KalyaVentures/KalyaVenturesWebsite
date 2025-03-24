# KalyaVenturesWebsite
# KalyaVentures LLC Website

This is the official website for KalyaVentures LLC, showcasing our two primary businesses:
- NityaPOD: Print-on-demand products
- AmaraDigital: Digital products

## Setup

This website uses Tailwind CSS via CDN for styling. No build process is required.

## Deployment

### GitHub Pages Deployment

1. Create a new GitHub repository
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Under "Source", select "main" branch
5. Click "Save"

Your site will be available at: `https://[your-username].github.io/[repository-name]`

### Custom Domain Setup (Optional)

1. Purchase a domain name
2. In your domain provider's DNS settings, add these records:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```
3. Add a CNAME record:
   ```
   Type: CNAME
   Name: www
   Value: [your-username].github.io
   ```
4. In your GitHub repository:
   - Go to Settings > Pages
   - Under "Custom domain", enter your domain
   - Check "Enforce HTTPS"

## Development

To modify the website:
1. Edit `index.html`
2. Test locally by opening the file in a browser
3. Commit and push changes to GitHub

## Contact

For any questions, please contact: contact@kalyaventures.com
