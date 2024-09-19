# Anubis' Jekyll Site

Welcome to Anubis' personal website repository. This site is built with Jekyll and serves as a blog and personal information hub. Below is a guide to the project's structure and instructions on how to get started.

## Project Structure

Here's an overview of the directory structure:

```
.
├── 404.html              # Custom 404 error page
├── about.html            # About page (HTML)
├── about.markdown        # About page (Markdown)
├── assets                # Folder for static assets
│   ├── icons             # Icons for the site
│   ├── styles            # CSS styles
│   └── wallpaper         # Background images
├── CNAME                 # Custom domain name for the site
├── _config.yml           # Jekyll configuration file
├── Gemfile               # Ruby gems used in the project
├── Gemfile.lock          # Lock file for Ruby gems
├── index.html            # Homepage (HTML)
├── index.markdown        # Homepage (Markdown)
├── _layouts              # Layout templates for Jekyll
│   └── default.html      # Default layout template
├── _posts                # Blog posts directory
│   └── 2024-09-19-welcome-to-jekyll.markdown  # Example post
├── posts                 # Static posts (if any)
├── posts.html            # Posts page (HTML)
└── robots.txt            # Robots.txt file for search engines
```

## Getting Started

To get started with this Jekyll site, follow these steps:

1. **Clone the Repository**

   Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/yourusername/anubis.github.io.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd anubis.github.io
   ```

3. **Install Dependencies**

   Make sure you have Ruby and Bundler installed. Then, install the required gems:

   ```bash
   bundle install
   ```

4. **Build and Serve the Site**

   You can build and serve the site locally using Jekyll:

   ```bash
   bundle exec jekyll serve
   ```

   This will start a local server, and you can view your site at `http://localhost:4000`.

5. **Make Changes**

   You can add or modify content in the `_posts` directory for blog posts, or edit `index.html` and other pages as needed.

6. **Deploy**

   If you're using GitHub Pages for deployment, push your changes to the `main` branch, and GitHub Pages will automatically build and deploy your site.

## Customization

- **CSS**: Update styles in `assets/styles/style.css`.
- **Images**: Place images in `assets/icons` or `assets/wallpaper`.
- **Layout**: Modify the layout in `_layouts/default.html`.
