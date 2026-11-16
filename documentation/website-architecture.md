Sweet Crumb Bakery
Website Architecture Document
1. Architecture Overview
The website will use WordPress as its Content Management System (CMS). The system architecture comprises five distinct layers:

Presentation Layer: Custom WordPress theme and tailored page layouts.
Content Layer: Static pages, dynamic blog posts, media assets, and core business information.
Functionality Layer: Integrated plugins powering form processing, search engine optimization (SEO), and custom features.
Data Layer: WordPress MySQL/MariaDB database managing content, user data, and system settings.
Hosting Environment: LocalWP environment for development, deploying to production-grade compatible WordPress hosting.

2. Website Structure
The site map encompasses the following core pages:

Home: Welcome experience, key highlights, and primary calls to action.
About Us: Bakery story, values, and team overview.
Products & Services: Catalog of baked goods, catering options, and seasonal offerings.
Custom Cake Orders: Dedicated landing page for bespoke cake requests.
Location: Physical store details, operating hours, and directions.
Blog: Bakery updates, baking tips, and news.
Contact Us: Inquiries, feedback, and direct contact channels.

3. Navigation Structure
The primary top-level navigation menu will strictly mirror the website structure for intuitive user orientation:

Home
About Us
Products & Services
Custom Cake Orders
Location
Blog
Contact Us

4. Functional Components
Contact Form
Collect customer full names.
Collect primary email addresses.
Collect specific inquiry details.
Enable secure customer submission processing.
Custom Cake Enquiry Form
Collect detailed cake specifications (flavor, size, design preferences).
Capture preferred pick-up/collection date and time.
Capture customer contact information for follow-up quotes.
Google Maps Integration
Display dynamic map of the fictional bakery location.
Assist visitors with location discovery and route planning.
Testimonials
Display clearly identified sample customer feedback for portfolio demonstration and social proof.
FAQ (Frequently Asked Questions)
Provide immediate answers to common questions regarding ingredients, lead times, ordering processes, and pickup options.
Blog Engine
Publish content marketing articles to demonstrate dynamic content management, category structure, and SEO optimization.

5. Technical Architecture
The systemic data flows for both the live environment and the development lifecycle are outlined below:

Environment Flow
Process Pathway
Primary Objective
Production Flow
Customer → Web Browser → WordPress Theme → WordPress Application → Plugins & Database
Serve cached, secure content to end users.
Development Flow
Developer → LocalWP → WordPress Local Site → GitHub Repository
Local staging, version control, and documentation.

6. Responsive Design
The platform architecture guarantees full cross-device compatibility:

Desktop Screens: Full-width layouts with enriched navigation and visuals.
Tablet Screens: Adaptive grid adjustments and medium-density UI components.
Mobile Screens: Streamlined touch-first navigation and optimized assets.

Design Principle: A strict mobile-first design approach will be applied, ensuring core user journeys are perfected on mobile viewports before scaling up to larger screen breakpoints.

7. Security Considerations
Vetted Software: Utilize strictly vetted, trusted themes and official plugin repositories.
Maintenance Lifecycle: Maintain proactive update schedules for WordPress core, active themes, and plugins.
Access Control: Enforce strong authentication standards, including complex password enforcement and Two-Factor Authentication (2FA) for administrative accounts.
Form Protection: Sanitize, validate, and protect all user input interfaces using CAPTCHA and anti-spam measures.
Repository Hygiene: Enforce strict .gitignore rules to prevent sensitive configuration files (e.g., wp-config.php), database dumps, or private credentials from being pushed to public version control.

9. Deployment Strategy
Local Development: Initial site architecture, theme integration, and functional testing will be conducted in an isolated LocalWP environment.
Production Deployment: The finalized site will be migrated to production hosting configured with optimal PHP versions and MySQL/MariaDB engines.
Version Control & Archival: GitHub will serve as the repository for custom codebase elements, theme customizations, project documentation, and visual screenshots.


