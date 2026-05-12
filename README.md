# Akussa Real Estate - Multi-Page Website

This project has been successfully converted from a single-page website to a comprehensive multi-page website with separate HTML files for each section.

## Pages Overview

### 1. **index.html** (Home Page)
- Landing page with hero section
- Featured properties
- Services overview
- Property listings (Exclusive Listings)
- Testimonials
- CTA section
- FAQ section

### 2. **about.html** (About Us Page)
- Company mission and values
- About the Akussa team
- Company information
- Company image and content

### 3. **services.html** (Services Page)
- Buy a Property service
- Sell Your Home service
- Rent a Property service
- Property Management service
- Detailed service descriptions

### 4. **properties.html** (Properties Page)
- Modern Family Home (San Diego, CA)
- Downtown Apartment (Chicago, IL)
- Luxury Beachfront Villa (Miami, FL)
- Cozy Suburban Townhouse (Austin, TX)
- View property details with pricing and specifications

### 5. **location.html** (Locations Page)
- San Francisco properties
- Los Angeles properties
- London properties
- Perth properties
- Browse properties by location

### 6. **agent.html** (Our Agents Page)
- Amanda Rivera - Property Consultant
- David Chen - Listings Specialist
- Olivia Martinez - Buyer's Agent
- Mark Thompson - Leasing Expert
- Contact an Agent button

### 7. **contact.html** (Contact Us Page)
- Contact form with fields:
  - First Name
  - Last Name
  - Email
  - Phone
  - Message
- Beautiful contact image
- Professional contact layout

## Navigation Structure

All pages include:
- **Navigation Bar**: Links to all 6 inner pages (About, Services, Properties, Location, Agent, Contact)
- **Logo**: Clickable logo linking to home page (index.html)
- **Footer**: Consistent footer with links to all pages
- **Responsive Design**: Mobile-friendly layout

## File Structure

```
/
├── index.html          (Home page)
├── about.html          (About page)
├── services.html       (Services page)
├── properties.html     (Properties page)
├── location.html       (Locations page)
├── agent.html          (Agents page)
├── contact.html        (Contact page)
├── 6803a881e3d0ac48627a685e/
│   ├── css/            (Stylesheets)
│   └── js/             (JavaScript files)
└── js/                 (jQuery)
```

## How to Navigate

1. Click the **Akussa logo** to go back to the home page from any page
2. Use the **navigation menu** at the top to jump to any section
3. Use the **footer links** to navigate between pages
4. All internal links are properly configured for seamless navigation

## Styling & Resources

- CSS files are shared across all pages from the `6803a881e3d0ac48627a685e/css/` directory
- JavaScript libraries (jQuery, Webflow) are loaded from the shared directories
- Images are hosted on Webflow CDN and properly referenced in all pages
- All styling and animations are preserved from the original single-page design

## Key Features

✓ **Multi-page structure** with separate HTML files
✓ **Consistent navigation** across all pages
✓ **Unique content** for each page section
✓ **Proper page routing** (no hash links, real page navigation)
✓ **Mobile responsive** design
✓ **Professional styling** maintained
✓ **All animations and interactions** preserved
✓ **SEO-friendly** page titles and descriptions

## How to Deploy

1. Upload all HTML files to your web server
2. Keep the directory structure intact (especially `6803a881e3d0ac48627a685e/` folder)
3. All external resources will load from Webflow CDN
4. No additional configuration needed

## Notes

- The original single-page design has been distributed across 7 focused pages
- Each page has a specific purpose and unique content
- Internal linking redirects users properly between pages
- The home page serves as the main landing page with overview content
