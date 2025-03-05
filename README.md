# AnantaAI - Pioneering Intelligent Automation

This is the official website for AnantaAI, a company focused on AI-driven solutions and intelligent automation.

## Project Structure

```
ai_startup/
├── css/
│   └── styles.css
├── images/
│   └── hero-ai.svg
├── js/
│   └── script.js
├── index.html
├── admin.html
├── .env
├── package.json
└── README.md
```

## Features

- Responsive design that works on all devices
- Modern UI with smooth animations
- Interactive elements using JavaScript
- Contact form with validation and database storage
- Admin panel to view contact form submissions
- Sections for showcasing AI solutions and services
- Testimonials section with client feedback

## Getting Started

To run the website with the backend:

1. Make sure you have Node.js and MongoDB installed on your system
2. Install the required dependencies:
   ```
   npm install
   ```
3. Start MongoDB on your local machine or update the MongoDB URI in the `.env` file
4. Start the server:
   ```
   npm start
   ```
5. Visit `http://localhost:3002` in your web browser

### Admin Panel

To access the admin panel and view contact form submissions:
1. Start the server as described above
2. Visit `http://localhost:3002/admin.html` in your web browser

## Deployment

To deploy the website:

1. Set up a production-ready MongoDB instance
2. Configure environment variables in the `.env` file for production
3. Build the frontend using a bundler like Webpack or Rollup
4. Deploy the built frontend to a hosting platform like AWS S3 or Netlify
5. Deploy the backend to a Node.js hosting platform like Heroku or AWS Elastic Beanstalk
6. Configure the backend to connect to the production MongoDB instance

## Customization

### Changing Colors

The color scheme can be easily modified by editing the CSS variables in the `:root` selector in `css/styles.css`:

```css
:root {
    --primary-color: #4a6cf7;
    --secondary-color: #6a2cf7;
    --accent-color: #f74a8a;
    /* Other color variables */
}
```

### Adding Content

To add more content or sections:

1. Edit the `index.html` file to add new sections following the existing structure
2. Add corresponding styles in `css/styles.css`
3. If needed, extend the functionality in `js/script.js`

### Images

Replace or add images in the `images/` directory. The hero image is an SVG that can be customized directly in the code.

## Browser Compatibility

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

Potential improvements for the future:
- Add a blog section
- Implement a dark mode toggle
- Create case study pages
- Add authentication for the admin panel
- Implement email notifications for new contact submissions
- Add data export functionality for contact submissions
- Create a dashboard with analytics for website traffic
- Implement internationalization support for multiple languages

## License

This project is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

 2025 AnantaAI. All rights reserved.
