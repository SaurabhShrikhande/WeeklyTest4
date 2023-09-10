# WeeklyTest4
HTML explanation :
<!DOCTYPE html>: Declares the document type and version of the HTML as HTML5.
<html lang="en">: Defines the root element of an HTML document with the language attribute set to English.
<meta charset="UTF-8" />: Specifies the character encoding for the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport settings for responsive web design.
<title>Weekly Test 4</title>: Sets the title of the web page to "Weekly Test 4."
<link rel="stylesheet" href="style.css">: Links an external CSS file (style.css) to style the HTML content.
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">: Links an external CSS file (Font Awesome) for icon styles.
<body oncontextmenu="return false;">: Defines the document's body and disables the context menu when right-clicking.
<header>: Represents the header section of the web page.
<nav class="navbar">: Defines a navigation bar within the header.
<h2 class="logo"><a href="#">LOGO</a></h2>: Defines a logo with a link inside the header.
<input type="checkbox" id="menu-toggler">: Creates a checkbox input element for mobile menu toggling.
<ul class="all-links">: Defines an unordered list for navigation links.
<li><a href="#home">Home</a></li>: Represents a list item with a link to the "Home" section.
<section class="homepage" id="home">: Defines a section with the "homepage" class and "home" id.
<div class="content">: Contains content within the homepage section.
<a href="#services">Our Services</a>: Creates a link to the "Services" section.
<h2>Our Services</h2>: Represents a level 2 heading for the "Services" section.
<ul class="cards">: Defines an unordered list for service cards.
<li class="card">: Represents a list item for a service card.
<img src="https://media.timeout.com/images/105658195/image.jpg" alt="img">: Inserts an image with a source and alternative text.
<h3>Tents</h3>: Represents a level 3 heading for the "Tents" card.
<p>Experience comfort and protection with our high-quality camping tents.</p>: Provides a description for the "Tents" card.
<section class="about" id="about">: Defines the "About Us" section with a class and id.
<h2>About Us</h2>: Represents a level 2 heading for the "About Us" section.
<div class="row company-info">: Creates a row for company information.
<h3>Our Story</h3>: Represents a level 3 heading for the company's story.
<p>Experience the excellence of our camping gear and services...adventurer can rely on us for their camping needs.</p>: Provides content for the company's story.
<div class="row mission-vision">: Creates a row for mission and vision statements.
<h3>Our Mission</h3>: Represents a level 3 heading for the mission statement.
<p>At Camping Gear Experts, our mission is to equip outdoor enthusiasts...create unforgettable camping experiences.</p>: Provides content for the mission statement.
<h3>Our Vision</h3>: Represents a level 3 heading for the vision statement.
<p>Our vision is to become the go-to destination for camping enthusiasts...create unforgettable camping experiences.</p>: Provides content for the vision statement.
<div class="row team">: Creates a row for the team information.
<h3>Our Team</h3>: Represents a level 3 heading for the team section.
<ul>: Defines an unordered list for listing team members.
<li>John Doe - Founder and CEO</li>: Lists the name and role of a team member.
<section class="contact" id="contact">: Defines the "Contact Us" section with a class and id.
<h2>Contact Us</h2>: Represents a level 2 heading for the "Contact Us" section.
<div class="row">: Creates a row for contact information and a contact form.
<div class="col information">: Defines a column for contact details.
<div class="contact-details">: Contains contact details.
<p><i class="fas fa-map-marker-alt"></i> 123 Campsite Avenue, Wilderness, CA 98765</p>: Displays a location icon and address.
<div class="col form">: Defines a column for a contact form.
<form>: Creates a form element for user input.
<input type="text" placeholder="Name*" required>: Defines a text input field for the name.
<input type="email" placeholder="Email*" required>: Defines an email input field for the email address.
<textarea placeholder="Message*" required></textarea>: Defines a textarea for user messages.
<button id="submit" type="submit">Send Message</button>: Creates a button to submit the contact form.


CSS Explanation-
@import: Imports an external font from Google Fonts.
*: Applies styles to all elements on the page.
scroll-behavior: Enables smooth scrolling for the HTML element.
background: Sets the background color or image for the body element.
position: Defines the positioning of the header element.
z-index: Specifies the stacking order of elements, giving the header a higher priority.
display: Defines how elements within the navbar are displayed.
padding: Adds spacing inside the navbar elements.
max-width: Sets the maximum width of the navbar.
align-items: Aligns navbar items vertically.
justify-content: Aligns navbar items horizontally.
input#menu-toggler: Hides the menu toggler input element.
#hamburger-btn: Hides the hamburger button.
list-style: Removes default list styles from navbar items.
margin-left: Adds left margin to the logo and anchor elements.
text-decoration: Removes underlines from anchor elements and adds hover effects.
background-image: Sets a background image for the homepage section.
background-position: Defines the position of the background image.
background-size: Sets the size of the background image.
background-attachment: Fixes the background image in place.
content: Generates pseudo-elements for styling.
height: Sets the height of the homepage section.
width: Sets the width of the homepage section.
position: Defines the positioning of the homepage content.
font-size: Sets the font size for the homepage heading and text.
font-weight: Specifies the font weight for the homepage heading.
color: Sets the text color for various elements.
text-shadow: Adds a shadow effect to text.
text-transform: Transforms text to uppercase.
border-radius: Rounds the corners of elements.
box-shadow: Adds a shadow effect to elements.
text-align: Aligns text within elements.
aspect-ratio: Specifies the aspect ratio of images.
resize: Defines whether an element can be resized by the user.
outline: Sets an outline style for input elements.
cursor: Specifies the mouse cursor style.
transition: Adds smooth transitions for hover effects.
media screen and (max-width: 860px): Defines responsive styles for screens up to 860px in width.
media screen and (max-width: 560px): Defines responsive styles for screens up to 560px in width.
