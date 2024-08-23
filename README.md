# Spotify-Landing-Page

<b>HTML Structure:</b>
Document Setup:

<!DOCTYPE html>: Declares the document type.
<html lang="en">: Defines the language for the document.
<head>: Contains metadata, including character set, viewport settings, title, CSS link, and Google Fonts link.
<body>: Contains the visible content of the webpage.
Main Layout:

Sidebar (Content):

div.content: A container for the sidebar which includes the home section, library, and language settings.
Home Section (div.home):
Displays the Spotify logo and buttons for "Home" and "Search."
Library Section (div.lib):
Contains buttons for "Your Library," "Create Playlist," and links to various legal and privacy-related pages.
Main Content Area (Main) (div.main):

Navigation Bar (nav.nav):
Includes navigation buttons and sign-up/log-in options.
Content Boxes (div.box):
Display sections like "Popular Artists," "Popular Albums," "Featured Charts," etc., with images and names for each category.
Footer (footer.footer):

Contains links for company information, communities, useful links, and Spotify plans.

<b>CSS Styling:</b>
Global Styles (*):

Resets margin and padding for all elements to ensure consistent spacing.
CSS Variables (:root):

Defines reusable color, font, and other design properties.
Body Styles (body):

Sets the height and width to cover the full viewport and applies a black background color.
Content Layout (.content):

Positioned fixed and set up as a flexbox to allow for vertical stacking of elements.
Home Section (.home):

Styled with a black background, rounded corners, and specific dimensions.
The buttons within have white text, are transparent, and use a custom font.
Library Section (.lib):

Similar styling to the home section, with additional sub-sections for buttons and links.
Main Content Styles (.main, .box):

Organized with different content areas, each represented by a .box class.
Each box contains links and images styled with specific dimensions and fonts.
Footer Styles (.footer):

Contains footer links organized in columns with headers and styled for a clean layout.

<b>Issues and Improvements:</b>
Responsive Design:
While the document uses width: 100vw and height: 100vh, it does not include media queries or specific responsive design techniques.
Accessibility:
Consider adding aria-labels or additional semantic HTML elements for better accessibility.
CSS Optimization:
The CSS could be optimized by combining similar styles and using more specific selectors to avoid redundancy.