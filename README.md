# Changelog

##Overview InviezID

<b>InviezID</b> is main project of <b>Feira Studio</b>

## Stage 010
* **New Features**
  * Introduced tabbed navigation for settings, with dedicated pages for Profile, Store, Account, and Theme management.
  * Added profile management, allowing admin users to view and update their personal information with validation and CSRF protection.
  * Enabled theme selection and updating within the settings interface.
  * Expanded language support with new UI text entries in both English and Indonesian.

* **UI/UX Improvements**
  * Redesigned settings, sidebar, and form layouts for improved navigation and usability.
  * Enhanced sidebar and topbar with updated branding and background styles.
  * Added dynamic active state highlighting for sidebar navigation.

* **Bug Fixes**
  * Improved breadcrumb navigation for better context and safety.

* **Chores**
  * Removed outdated changelog and legacy settings files.
  * Refactored routing and page structure for clearer organization and maintainability.


## Stage 009
* **New Features**
  * Introduced a user settings page with profile and store information, including editable fields and localization support.
  * Added a topbar navigation and breadcrumb navigation for improved user experience.
  * Expanded language support with additional English and Indonesian translations for profile and UI terms.

* **Style**
  * Updated and added new CSS styles for layout, navigation, settings, and utility classes.

* **Bug Fixes**
  * Improved error handling and access control for restricted directories and files.
  * Enhanced 403 and 404 error pages for clearer user feedback.

* **Chores**
  * Strengthened security by denying direct web access to sensitive directories via `.htaccess` files.
  * Improved routing to handle settings and error pages explicitly.


## Stage 008
* **New Features**
  * Added Facebook login integration, allowing users to authenticate using their Facebook accounts.
  * Facebook OAuth callback and session handling are now supported.
  * Enhanced login page with Facebook login option and improved error display.

* **Bug Fixes**
  * Corrected CSRF token variable naming in the sidebar.
  * Updated logout form to use the correct endpoint.

* **Chores**
  * Added the Facebook Graph SDK as a new dependency.


## Stage 007
* **New Features**
  * Introduced a multi-level accordion sidebar menu with expanded navigation sections for products, orders, sales, customers, and settings.
  * Sidebar now includes a fixed footer with a logout button.

* **Enhancements**
  * Sidebar navigation supports collapsible sections for improved organization and user experience.
  * Custom scrollbar and sidebar styling for a modern look and feel.

* **Localization**
  * Expanded English and Indonesian language support with new translation keys for navigation, orders, financial terms, and UI elements.

* **Security**
  * Logout action now uses a POST form with CSRF token protection instead of a direct link.

* **Bug Fixes**
  * Corrected translation for "all products" in English.


## Stage 006
* **New Features**
  * Introduced "Forgot Password" and "Reset Password" pages, allowing users to request a password reset link and set a new password securely.
  * Added password reset email functionality with secure token handling and expiry.
  * Enhanced login page with a link to the password reset process.

* **Improvements**
  * Default language selection now falls back to Indonesian if none is set.
  * OTP verification now trims whitespace from email input for improved accuracy.

* **Style**
  * Updated form footer spacing for a more compact layout.

* **Other**
  * Added new routes for password recovery and reset processes.


## Stage 005
* **New Features**
  * Introduced language selection and dynamic translation support for sidebar navigation, with both English and Indonesian options.
  * Added a fully structured sidebar with branding and navigation links, now displaying translated labels based on selected language.

* **Bug Fixes**
  * Corrected registration form validation for email, password confirmation, and checkbox input, ensuring accurate error handling and display.

* **Chores**
  * Updated meta tags for social sharing with correct image URLs and added Facebook app ID.
  * Removed unused JavaScript file from script includes.


## Stage 004

* **New Features**
  * Enhanced registration form with client-side validation and inline error messages.
  * Improved display and styling for lists and form error messages.
  * Added Open Graph and Twitter Card meta tags for better social media sharing.
  * Personalized home page greeting for logged-in users.

* **Improvements**
  * Increased security in OTP generation during registration and verification.
  * Unified and clearer error messages for account verification.
  * Sidebar and topbar now use HTML elements for improved structure.

* **Chores**
  * Updated script comments and included a new JavaScript file for input handling.


## Stage 003

* **New Features**
  * Added the ability for users to resend OTP (One-Time Password) during verification, with immediate feedback via enhanced success messages and modals.

* **Bug Fixes**
  * Improved error handling and feedback in the OTP verification process.
  * Corrected minor text errors in error messages.

* **Style**
  * Updated form footer layout and button sizing for improved visual consistency.

* **Chores**
  * Streamlined HTML structure and resource loading in header components.
  * Removed unused or redundant component files and updated inclusion logic for configuration files.
  * Enhanced security by adding CSRF validation to the logout process.


## Stage 002

* **New Features**
  * Introduced user registration with email-based OTP verification and secure login/logout functionality.
  * Added CSRF protection for forms to enhance security.
  * Integrated PHPMailer for sending OTP emails, with support for multiple languages in error messages.
  * Added a verification page and improved routing for login, registration, verification, and logout.

* **Bug Fixes**
  * Corrected form actions and improved error feedback on login and registration pages.
  * Ensured consistent button styling across the application.

* **Style**
  * Updated button styles to remove text decoration for a cleaner appearance.

* **Documentation**
  * Added comprehensive documentation and security notices for PHPMailer.

* **Chores**
  * Added Composer dependencies and autoloading for PHPMailer and related libraries.


## Stage 001

* **Style**
  * Improved responsive design for the log container and its elements, ensuring better layout and usability across various screen sizes.
  * Adjusted styling for the circle element within the log section to enhance positioning and appearance on different devices.
