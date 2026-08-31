# Precision Auto Care

A modern, responsive single-page website for **Precision Auto Care**, a professional automotive repair and maintenance garage based in Nairobi, Kenya.

## Features

- **Responsive design** for desktop, tablet, and mobile devices
- Modern automotive-themed UI with gradient backgrounds and animations
- Fixed navigation header with smooth scrolling
- Hero section with a prominent appointment call-to-action
- Six automotive service categories
- Service feature tags and starting prices
- Animated business statistics
- Appointment/service request form
- Contact and garage information
- Responsive mobile layout
- Image fallback placeholders when service images are unavailable
- Scroll-based header styling
- No external frameworks or libraries required

## Services

The website currently showcases:

| Service                     | Starting Price |
| --------------------------- | -------------: |
| Engine Diagnostics & Repair |         $89.99 |
| Brake Services              |        $129.99 |
| Oil Change & Fluid Services |         $39.99 |
| Vehicle Inspection          |         $49.99 |
| Electrical Systems          |         $79.99 |
| Suspension & Steering       |        $149.99 |

Each service includes a description, relevant service features, and an image.

## Project Structure

```text
precision-auto-care/
├── index.html
├── images/
│   ├── engine-diagnostics.jpg
│   ├── brake-service.jpg
│   ├── oil-change.jpg
│   ├── vehicle-inspection.jpg
│   ├── electrical-systems.jpg
│   └── suspension.jpg
└── README.md
```

## Getting Started

### 1. Clone or download the project

```bash
git clone <your-repository-url>
cd precision-auto-care
```

### 3. Open the website

Simply open:

```text
index.html
```

in a modern web browser.

For local development, you can also use a simple HTTP server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Technologies

This project is lightweight and uses:

- **HTML5** — page structure and content
- **CSS3** — layout, responsive design, gradients, transitions, and animations
- **Vanilla JavaScript** — interactions and dynamic behavior
- **CSS Grid & Flexbox** — responsive layouts
- **Intersection Observer API** — statistics counter animation

## Responsive Design

The website adapts its layout for smaller screens.

On screens below 768px:

- The navigation links are hidden
- The hero heading is reduced in size
- Service cards switch to a single-column layout
- Contact content becomes a single-column layout
- Statistics are displayed in a two-column grid

## Appointment Form

The contact section contains a service request form collecting:

- Full name
- Email address
- Phone number
- Requested service
- Vehicle details and reported issues

The form currently operates entirely on the client side. On submission, it displays a confirmation message and resets the form.

## Contact Information

**Precision Auto Care**

📍 Nairobi, Kenya
📞 +254 743 313 064

### Business Hours

- Monday–Friday: 7:30 AM–6:00 PM
- Saturday: 8:00 AM–4:00 PM
- Sunday: Emergency Only
- Emergency service: 24/7 towing & emergency repairs

## Design

The visual design uses a dark blue and red automotive-inspired color palette.

Key design elements include:

- Gradient backgrounds
- Rounded service cards
- Hover elevation effects
- Animated hero content
- Glass-style fixed navigation
- Responsive grids
- Smooth scrolling
- Animated statistics counters

The primary page background uses a dark-blue-to-red gradient, while service and contact sections use lighter backgrounds for contrast.

## Future Improvements

Potential enhancements include:

- [ ] Connect appointment requests to a backend
- [ ] Add real appointment scheduling
- [ ] Add Google Maps integration
- [ ] Add customer reviews/testimonials
- [ ] Add an FAQ section
- [ ] Add WhatsApp contact integration
- [ ] Add service detail pages
- [ ] Add dark/light theme support
- [ ] Add accessibility improvements
- [ ] Add SEO and Open Graph metadata
- [ ] Optimize and compress service images
- [ ] Add form validation and error handling
- [ ] Add analytics

## About

**Precision Auto Care** is a professional automotive service garage providing repair, maintenance, diagnostics, inspections, electrical services, and suspension/steering work.

> Quality service you can trust.
