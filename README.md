🌐 Tourism Static Website
📝 Overview
This is a static tourism website designed to showcase popular tourist destinations across India. The website provides an interactive user interface with multiple sections, including:

Home

About Us

Contact Us

Detailed views of famous tourist places.

It serves as a frontend template without backend integration.

✨ Features
✅ Responsive Navigation Bar

Links to Home, About Us, Contact Us, and Help sections.

✅ Landing Page

Includes a call to action for login and registration.

✅ Tourist Places Section

Cards displaying popular destinations:

Tirumala

Taj Mahal

Golden Temple

Mysore Palace

Varanasi

✅ Detailed Views

Each place has:

Image carousel slider

Descriptive content

✅ Login Form

Basic fields: Name and Password (for simulation)

✅ Footer Section

Quick links

Contact information

Location details

✅ Dynamic Section Toggling

JavaScript display() function to show/hide sections dynamically.

🛠️ Technologies Used
HTML5

CSS (including Bootstrap 4.5.2)

JavaScript (for interactive display)

External Libraries:

Bootstrap CSS and JS via CDN

jQuery Slim

Popper.js (for Bootstrap components)

🗂️ Project Structure
Section	Description
sectionmainpage	Main landing page with navigation and introductory content
sectionHome	Home section with welcome text and navigation buttons
sectionFavouritePlaces	Cards displaying tourist places with images and short descriptions
sectionTajMahalDetailedView	Detailed view with carousel and description for Taj Mahal
sectionGoldenTempleDetailedView	Detailed view with carousel and description for Golden Temple
...other detailed views...	Similar structure for Tirumala, Mysore Palace, Varanasi
sectionform	Login form section
sectioncontactpage	Footer section with quick links and contact information

▶️ How to Use
Navigate using the top bar to switch sections.

Explore tourist destinations by clicking cards.

View Details in dedicated sections with image carousels.

Return using Back buttons.

Simulate Login by filling out the form (no backend validation).

⚠️ Notes
Some image paths are local (file://). Replace with relative paths or hosted URLs before deployment.

The display() function for toggling sections must be defined in your JavaScript file (or implemented if missing).

This website is purely static and does not include any backend functionality or persistent storage.

