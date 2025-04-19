# Personal Website

A minimalist personal website inspired by Paul Graham's design, with a yellowish background and focus on content and readability.

## Features

- Clean, ultra-minimalist design
- Subtle yellowish background for comfortable reading
- Mobile-responsive layout
- Separate pages for home, articles list, and about sections
- Simple HTML/CSS implementation with no build steps required

## Structure

- `index.html` - Homepage with introduction and recent articles
- `articles.html` - Complete listing of all articles by year
- `about.html` - Information about you and contact details
- `styles.css` - All styling for the website
- `articles/` - Directory containing individual article HTML files

## How to Customize

### Personal Information

1. Replace "Aryan Nayak" with your actual name throughout the site (in all HTML files)
2. Update the copyright year in the footer if needed
3. Fill in your personal information in the `about.html` file
4. Add your actual contact information and social media links

### Articles

1. For each new article:
   - Copy the template from `articles/article1.html`
   - Save it with a new filename (e.g., `articles/my-new-article.html`)
   - Update the title, date, and content
   - Link to it from `index.html` (if it's recent) and `articles.html`

2. To organize articles by year:
   - Add new year sections in `articles.html` as needed

### Styling

The CSS is designed to be simple and easy to modify:

- The site uses a yellowish background (#fffcf0) for comfortable reading
- Change the font by modifying the `font-family` property in the body selector
- Adjust colors by changing the color values
- Modify spacing with the margin and padding properties

## Deployment

To deploy this website:

1. Upload all files to your web hosting provider
2. Make sure to maintain the same directory structure
3. No server-side scripts or databases are required

## Adding Features Later

This is a simple static website. If you want to add more features later, consider:

- Adding a search functionality with JavaScript
- Implementing a dark mode toggle
- Creating an RSS feed for your articles
- Using a static site generator like Jekyll or Hugo for more complex needs

## License

Feel free to use and modify this template for your personal website. # PersonalBlog
