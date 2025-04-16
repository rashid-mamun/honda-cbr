# Honda CBR Website

This is a static website showcasing the Honda CBR 300R and other featured motorcycles. It includes sections for featured bikes, latest news, social media posts, a dealer locator, client testimonials, and frequently asked questions. The site is built using HTML, CSS, Bootstrap, and JavaScript, and is hosted on GitHub Pages.

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Interactive Elements**: Includes a purchase modal, accordion for FAQs, and a dealer locator form.
- **Social Media Integration**: Displays Honda's social media posts with YouTube video embeds.
- **Accessibility**: Uses semantic HTML, ARIA attributes, and proper alt texts for images.
- **Modern Styling**: Leverages Bootstrap and custom CSS with Google Fonts (Poppins).

## Project Structure

```
honda-cbr-website/
├── css/
│   ├── bootstrap.min.css
│   └── style.css
├── images/
│   ├── bike-1.png
│   ├── bike-2.png
│   ├── bike-3.png
│   ├── c-1.png
│   ├── c-2.png
│   ├── c-4.png
│   ├── faq.png
│   ├── feature-bike.jpg
│   ├── header-bike.png
│   ├── user-1.png
│   ├── user-2.png
│   └── user-3.png
├── js/
│   └── bootstrap.bundle.min.js
├── index.html
└── README.md
```

## Getting Started

### Prerequisites

- **Git**: Install Git from git-scm.com.
- **Web Browser**: Any modern browser (Chrome, Firefox, etc.) to view the site.
- **Text Editor**: VS Code or similar for editing files.

### Local Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/<your-username>/honda-cbr-website.git
   cd honda-cbr-website
   ```

2. **Serve Locally**:

   - Use a local server to preview the site:

     ```bash
     python -m http.server 8000
     ```

   - Open `http://localhost:8000` in your browser.


## Dependencies

- **Bootstrap 5**: For responsive layout and components (`css/bootstrap.min.css`, `js/bootstrap.bundle.min.js`).
- **Font Awesome**: For icons (`https://kit.fontawesome.com/33d61158f6.js`).
- **Google Fonts**: Poppins font (`https://fonts.googleapis.com/css2?family=Poppins`).