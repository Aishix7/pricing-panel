# pricing-panel
pricing-panel page
Price Tiers Web Page
Project Overview
This project consists of a simple, responsive web page that displays pricing tiers for different subscription plans (Personal, Small Team, and Enterprise). The web page has been styled using a separate CSS file and utilizes the Google Fonts service for typography.

Technologies Used:
HTML5: The structure of the web page.
CSS3: Styling for the web page.
Google Fonts: The "Open Sans" font is used to enhance readability.
File Structure
The project consists of the following two main files:

index.html: This file contains the structure and content of the pricing plans.
pricingpanel.css: This file contains the styling rules for the pricing table.
index.html
Description:
DOCTYPE & Language: The page is defined using HTML5 and set to the English language.
Meta Tags: Character encoding is set to UTF-8, and the viewport is optimized for responsiveness on mobile devices.
Google Fonts: The "Open Sans" font is imported from Google Fonts.
Content: The page includes three pricing tiers — Personal (Free), Small Team ($150), and Enterprise ($400). Each pricing plan features:
A representative image
A header for the plan name
A list of features
A price display
A call-to-action button (Sign up/Free trial)
Structure:
Container: The pricing plans are wrapped inside a div with the class panel to ensure they are grouped together and styled uniformly.
Pricing Plans: Each plan is structured within a div with the class pricing-plan. The plan includes:
An image (pricing-img)
A header for the plan name (pricing-header)
A list of features (pricing-features)
A price label (pricing-price)
A button for user interaction (pricing-button)
Classes:
.panel: Container for the pricing plans.
.pricing-plan: Individual pricing plans (Personal, Small Team, Enterprise).
.pricing-header: Plan headers (e.g., "Personal", "Small Team").
.pricing-features: Feature list for each pricing plan.
.pricing-price: Displays the plan price.
.pricing-button: Call-to-action buttons, with an additional .is-featured class for highlighted plans.
pricingpanel.css
Description:
The CSS file is responsible for styling the HTML structure. It ensures the page is responsive, visually appealing, and easy to read.

Key Features:
Resets: Basic CSS reset is applied to remove default margins, paddings, and borders for consistent cross-browser rendering.
Font: The Open Sans font is used throughout the page.
Flexbox Layout: Flexbox is used to center the pricing panel both vertically and horizontally, making it responsive and adaptable to various screen sizes.
Pricing Plan Styles: Each pricing plan is styled with borders, padding, and hover effects for better user interaction.
Button Styling: The call-to-action buttons have hover effects, and the featured plan (Small Team) has a special highlighted style.
Responsive Design: Media queries are used to adapt the layout for larger screens by displaying pricing plans horizontally instead of stacked vertically.
Classes:
.panel: Applies basic styles and dimensions to the pricing table container.
.pricing-plan: Styles each pricing plan individually with borders and padding.
.pricing-img: Ensures the images fit within the space.
.pricing-header: Styles for the pricing plan titles.
.pricing-features: List of features for each pricing plan.
.pricing-price: Styles for the price tag of each plan.
.pricing-button: Styles for buttons, including hover and focus states. The is-featured class adds extra styling for the Small Team plan.
Responsive Breakpoints:
@media (min-width: 900px): When the screen is 900px or wider, the pricing plans are displayed side by side using Flexbox.
