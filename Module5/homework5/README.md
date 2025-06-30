# Catppuccin Contact Form

A beautiful, responsive contact form built with HTML5 and SASS, featuring the Catppuccin color scheme.

## Features

- 🎨 Beautiful Catppuccin Mocha color palette
- 📱 Fully responsive design with media queries
- 🔧 Built with SASS for maintainable code
- ⚡ Modern CSS features (backdrop-filter, gradients)
- 📝 5+ input fields with icons
- 🎯 Accessible and user-friendly design

## Technologies Used

- HTML5
- SASS/SCSS
- CSS3
- Font Awesome Icons

## Live Demo

[View Live Site](https://your-username.github.io/N215/Module5/homework5/)

## Project Structure

```
homework5/
├── index.html
├── scss/
│   ├── main.scss
│   ├── _variables.scss
│   ├── _base.scss
│   ├── _form.scss
│   └── _responsive.scss
├── css/
│   └── style.css
└── README.md
```

## Setup

1. Clone this repository
2. Navigate to Module5/homework5
3. Compile SASS to CSS:
   ```bash
   sass scss/main.scss css/style.css --watch
   ```
4. Open `index.html` in your browser

## Color Palette

This project uses the Catppuccin Mocha color scheme:
- Base: #1e1e2e
- Text: #cdd6f4
- Blue: #89b4fa
- Mauve: #cba6f7
- Green: #a6e3a1

## Form Features

- **Full Name** - Text input with user icon
- **Email Address** - Email input with envelope icon
- **Phone Number** - Tel input with phone icon
- **Company/Organization** - Text input with building icon
- **Website URL** - URL input with globe icon
- **Message** - Textarea with comment icon

## Responsive Design

The form includes comprehensive media queries for:
- Mobile devices (≤480px)
- Tablets (481px-768px)
- Desktop (769px-1024px)
- Large screens (≥1201px)
- Landscape orientation handling

## SASS Architecture

The project follows a modular SASS structure:
- `_variables.scss` - Color palette and design tokens
- `_base.scss` - Global styles and resets
- `_form.scss` - Form-specific styles
- `_responsive.scss` - Media queries
- `main.scss` - Main import file

## License

MIT License
