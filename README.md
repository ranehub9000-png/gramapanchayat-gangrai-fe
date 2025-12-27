# Gangrai Gram Panchayat Website

Official website for Gangrai Gram Panchayat, Taluka Chiplun, District Ratnagiri, Maharashtra.

## Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional government-style design
- **Google Maps Integration**: Location map with embedded Google Maps
- **Bilingual Support**: Devanagari and English text
- **Accessibility**: Proper semantic HTML and ARIA labels
- **Government Schemes**: Information about Pradhanmantri Gharkul Yojana
- **Contact Information**: Office address and contact details
- **Image Gallery**: Showcasing Gharkul scheme implementation

## Files Structure

```
gramapanchayat-gangrai-fe/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with responsive design
├── script.js       # JavaScript for interactivity
├── README.md       # This file
└── images/         # Images folder
    ├── gangrai-gp-logo.png
    ├── gangrai-grampanchayat.png
    ├── pradhanmanthri-garkul-construction.png
    └── vijay-badare-bandle/  # Gharkul scheme images
```

## Setup Instructions

### Basic Setup (No API Key Required)

The website works out of the box with an embedded Google Maps iframe. Simply open `index.html` in a web browser.

### Advanced Setup (Interactive Google Maps)

To use the interactive Google Maps with markers:

1. Get a Google Maps API Key:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select an existing one
   - Enable "Maps JavaScript API" and "Geocoding API"
   - Create credentials (API Key)
   - Restrict the API key to your domain (recommended for production)

2. Update the HTML:
   - Open `index.html`
   - Find the line: `<!-- <script async defer src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap"></script> -->`
   - Uncomment it and replace `YOUR_API_KEY` with your actual API key
   - Comment out or remove the embedded iframe code in the script section

## Customization

### Update Village Information

Edit the following sections in `index.html`:
- Village Overview cards
- Population statistics table
- Contact information
- Office hours

### Change Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e40af;      /* Main blue color */
    --secondary-color: #fbbf24;    /* Accent yellow */
    --accent-color: #059669;       /* Green accent */
}
```

### Update Logo

The logo is located at `images/gangrai-gp-logo.png`. Replace with your own design if needed.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## About Pradhanmantri Gharkul Yojana

The website includes information and images about the Pradhanmantri Gharkul Yojana (PM Housing Scheme), which provides financial assistance to poor and underprivileged families for house construction.

## License

This website is created for official use by Gangrai Gram Panchayat, Government of Maharashtra.

## Contact

For any queries or updates, contact the Gram Panchayat office.

---

**Government of Maharashtra** | **Gangrai Gram Panchayat**

