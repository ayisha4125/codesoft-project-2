# Smokehouse & Bun — Burger Week

A modern, responsive restaurant landing page for **Smokehouse & Bun**, built around a limited-time Burger Week promotion.

## Overview

The website showcases:

* Burger Week promotional hero section
* Featured burger menu
* Meal combos
* Upcoming restaurant events
* First-order discount promotion
* Table reservation form
* Restaurant contact information
* Responsive mobile navigation
* Interactive reservation confirmation

## Features

### 🍔 Hero Section

The homepage introduces Burger Week with:

* "7 days · flame-grilled · 100% fresh" tagline
* Burger Week promotional heading
* Order Now and Book a Table buttons
* Signature burger statistics
* Starting price of **$8.99**

### 🍟 Popular Menu

The page features four signature burgers:

| Burger               |  Price |
| -------------------- | -----: |
| Smoky BBQ Bacon      | $10.50 |
| Double Smash Classic |  $9.25 |
| Firehouse Jalapeño   | $10.95 |
| Mushroom Swiss       |  $9.75 |

Each menu item includes an image, description, and category badge.

### 🥤 Meal Combos

Three meal options are available:

* **Solo Stack** — $12.99
* **Double Trouble** — $21.99
* **Family Feast** — $44.99

### 🎵 Events

The website includes upcoming events:

* **August 15** — Flame & Vinyl Night
* **August 22** — Grill Masters Showdown
* **September 3** — Kids Eat Free Sunday

### 🎁 Promotion

New customers can receive **20% off their first order** using:

`FIRSTBITE`

### 📅 Reservations

The reservation form collects:

* Full name
* Date
* Time
* Number of guests
* Phone number
* Special requests

The form currently works as a front-end demonstration. On submission, it displays **"Table Reserved ✓"**, then resets after a short delay.

> **Note:** The reservation form does not currently send reservation data to a server or database.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Google Fonts

  * Baloo 2
  * Nunito Sans
* Unsplash for food photography

The HTML imports `styles.css` as its main stylesheet and loads the Google Fonts externally.

## Project Structure

```text
project/
├── index.html
├── styles.css
└── README.md
```

## Getting Started

### 1. Download or clone the project

Place the project files in the same directory.

### 2. Make sure the stylesheet exists

The HTML expects:

```text
styles.css
```

in the same directory as `index.html`.

### 3. Open the website

Open `index.html` directly in a modern web browser.

Alternatively, run it through a local development server.

For example, with VS Code, you can use the **Live Server** extension.

## Navigation

The main navigation links to sections within the same page:

```text
Home
Menu
Combos
Events
Reserve
```

These correspond to the page sections `#top`, `#menu`, `#choose`, `#events`, and `#reserve`.

## Contact Information

**Smokehouse & Bun**

221 Grillhouse Ave
Chennai, TN 600001

Phone: +1 (800) 555-0199
Email: [hello@smokehouseandbun.com](mailto:hello@smokehouseandbun.com)

## Business Hours

**Monday – Friday:** 11:00 AM – 10:00 PM
**Saturday – Sunday:** 10:00 AM – 11:00 PM

## JavaScript Functionality

The page contains two main interactive behaviors:

### Mobile Navigation

The navigation toggle opens and closes the mobile menu and updates the `aria-expanded` attribute for accessibility.

### Reservation Form

The reservation form prevents the default browser submission and temporarily changes the button text to:

```text
Table Reserved ✓
```

After approximately 2.4 seconds, the button returns to its original state and the form is reset.

## Customization

You can customize the website by editing:

### Restaurant information

Update the address, phone number, email, and opening hours in `index.html`.

### Menu

Add or modify burgers inside the menu section.

### Pricing

Change prices directly within the corresponding menu and combo cards.

### Images

The current food photography uses externally hosted Unsplash images. Replace the image URLs with your own images if required.

### Styling

Most visual customization should be done in:

```text
styles.css
```

## Future Improvements

Potential improvements include:

* Connect the reservation form to a backend
* Add online ordering functionality
* Add a shopping cart
* Integrate a payment gateway
* Add real social-media links
* Add restaurant location/map integration
* Add form validation and error messages
* Store reservations in a database
* Add SEO metadata
* Optimize and locally host images
* Add accessibility improvements
* Add a CMS for managing menu items and events

## License

This project is provided for demonstration and development purposes.

Restaurant branding, menu information, contact details, and promotional content should be updated before using the website commercially.

---

**Smokehouse & Bun © 2026**
*Made with grill marks & good buns.*
