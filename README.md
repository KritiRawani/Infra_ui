# Infra_ui

A modern, responsive web portal to showcase India's construction and infrastructure sectors, projects, and services. Built with HTML, CSS, and JavaScript.

## Features

- **Fixed Navigation Bar:**
  - Smooth scrolling navigation with active link highlighting.
  - Mobile-friendly hamburger menu.

- **Home Section:**
  - Welcome message and animated image.

- **Services Section:**
  - Grid of service cards with icons and descriptions.

- **About Section:**
  - Platform mission and description.

- **Sectors Section:**
  - Dynamically generated cards for various infrastructure sectors (e.g., Residential, Commercial, Industrial, etc.).
  - Each sector displays an icon, name, a button to view an image, and a price below the image.
  - Images and prices are managed via JavaScript (`script.js`).

- **Gallery Section:**
  - Responsive image grid.
  - Click any image to open a lightbox modal for a larger view.

- **Submit Section:**
  - Form for users to submit their own projects (name, email, title, description, image).
  - Shows a success alert and resets on submit.

- **Contact Section:**
  - Contact details and a form for user messages.
  - Shows a success alert and resets on submit.

- **Responsive Design:**
  - Fully responsive layout for desktop, tablet, and mobile.
  - Custom CSS for all breakpoints.

- **Modern UI/UX:**
  - Uses Font Awesome icons.
  - Subtle animations and hover effects.
  - Clean, professional look.

## Project Structure

```
Contruction & Infrastructure/
├── images/                # All sector and gallery images
├── index.html             # Main HTML file
├── script.js              # All JavaScript logic (dynamic sectors, forms, navigation, gallery)
├── styles.css             # All custom styles and responsive rules
└── README.md              # Project documentation (this file)
```

## How Sectors Work
- All sector data (name, icon, image, price) is in the `sectors` array in `script.js`.
- Sectors are rendered dynamically into the `.sections-container` div.
- Each sector card has a button to toggle the image and price display.
- You can easily add/edit sectors or prices by updating the `sectors` array.

## How to Run
1. **Clone or Download:**
   - Download the project folder or clone the repository.
2. **Open in Browser:**
   - Open `index.html` directly in your web browser (no build step needed).
3. **(Optional) Edit Content:**
   - Update images in the `images/` folder.
   - Edit sector data, prices, or text in `script.js` and `index.html`.

## Customization
- **Add/Change Sectors:** Edit the `sectors` array in `script.js`.
- **Change Images:** Replace or add images in the `images/` folder and update paths in `script.js`.
- **Update Styles:** Modify `styles.css` for colors, layout, or animations.

## Credits
- **Icons:** [Font Awesome](https://fontawesome.com/)
- **Images:** Provided in the `images/` folder (replace with your own as needed).

## License
This project is for educational/demo purposes. Replace images and content as per your needs. 