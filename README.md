
# Empowering the Nation Mobile App

## Project Overview

The Empowering the Nation Mobile App is a cross-platform application designed to provide information, resources, and tools for community empowerment, skills development, and education. The app is built using React Native and Expo, and is designed to closely match the look, feel, and functionality of the Empowering the Nation web application.

## Features

- Home page with branding and mission statement
- About Us section
- Courses listing and detailed course information
- Events calendar and event details
- Testimonials from learners and partners
- Contact form for user inquiries
- Fee Calculator for course cost estimation
- Donate Now button for community support
- Custom navigation header and footer
- Themed UI with light/dark mode support

## Technologies Used

- React Native (Expo)
- TypeScript
- React Navigation
- Custom components for header, footer, and UI elements
- Local asset management for images and fonts

## Installation & Running the App

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd EmpoweringTheNationMobile
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Start the Expo development server**
   ```bash
   npx expo start
   ```
4. **Run on your device or emulator**
   - Scan the QR code with Expo Go (Android/iOS)
   - Or launch on an Android emulator/iOS simulator from the Expo Dev Tools

## Project Structure

- `app/` — Main application screens and navigation
- `components/` — Reusable UI components (Header, Footer, etc.)
- `constants/` — Theme and color definitions
- `assets/` — Images and fonts
- `hooks/` — Custom React hooks
- `scripts/` — Utility scripts

## Development Approach

The app was developed with a focus on:
- Pixel-perfect fidelity to the web app design
- Accessibility and usability (following best practices)
- Modular, reusable code structure
- Type safety with TypeScript
- Responsive layouts for different device sizes




## Design Features & User Interface

This project was created by Khanyisa Shikwambana, Rixile Ndlovu, and Success Khangale.

The Empowering the Nation Mobile App is designed for clarity, accessibility, and a modern user experience. Below are the key design features:

### Layout & Navigation
- Custom header at the top of every screen with the Empowering the Nation logo and brand colors.
- Main navigation is available via a horizontal scrollable header and a bottom tab bar (on mobile devices).
- Active navigation links are highlighted for clear orientation.
- The "Donate Now" button is always visible in the header for quick access.

### Buttons
- **Primary buttons** (e.g., Donate Now) use a bold orange background (`#ea580c`) with white text for high visibility.
- **Navigation links** are pill-shaped. The active link uses a soft orange background (`#ffedd5`) and bold text, while the Courses link uses a green highlight (`#bbf7d0`) when active.
- All buttons have rounded corners and padding for a modern, touch-friendly feel.

### Color Palette
- **Orange:** `#ea580c` (primary accent, used for buttons and highlights)
- **Green:** `#15803d` (secondary accent, used for branding and active Courses link)
- **Light Green:** `#bbf7d0` (Courses active background)
- **Soft Orange:** `#ffedd5` (active navigation background)
- **White:** `#fff` (background)
- **Gray:** `#374151` (text), `#fdba74` (borders)
- The app supports both light and dark modes, adapting to the device theme.

### Forms & Inputs
- Contact screen features clearly labeled input fields with rounded borders and ample spacing.
- Fee Calculator uses simple numeric inputs and a prominent calculate button.

### Imagery & Icons
- All images are locally stored for fast loading and offline access.
- Icons are used for visual cues (e.g., awards, events) and styled to match the color palette.

### Typography
- Headings use bold, colored text for emphasis (orange or green, depending on context).
- Body text is clear and readable, with consistent font sizes and spacing.

### How to Navigate
1. **Home:** Start on the Home screen to see the mission and quick links.
2. **Header Navigation:** Tap any link in the header (About Us, Courses, Events, Testimonials, Contact, Fee Calculator) to jump to that section. The active section is highlighted.
3. **Tab Bar (if available):** Use the bottom tab bar for quick switching between main sections.
4. **Donate Now:** Tap the orange Donate Now button in the header to access the donation screen from anywhere.
5. **Explore Content:** Scroll through courses, events, and testimonials. Tap on a course or event for more details.
6. **Contact & Calculator:** Use the Contact form to send a message, or the Fee Calculator to estimate course costs.
7. **Back Navigation:** Use the device back button or navigation controls to return to previous screens.

### Layout & Navigation
- The app uses a custom header at the top of every screen, featuring the Empowering the Nation logo and brand colors.
- Main navigation is accessible via the header (horizontal scrollable links) and a tab bar at the bottom (on mobile devices).
- Each navigation link highlights when active, making it clear which section the user is viewing.
- The Donate Now button is always visible in the header for quick access.

### Buttons
- **Primary buttons** (e.g., Donate Now) use a bold orange background (`#ea580c`) with white text for high visibility and call-to-action emphasis.
- **Navigation links** are styled as pill-shaped buttons. The active link uses a soft orange background (`#ffedd5`) and bold text, while the Courses link uses a green highlight (`#bbf7d0`) when active.
- All buttons have rounded corners and padding for a modern, touch-friendly feel.

### Color Palette
- **Orange:** `#ea580c` (primary accent, used for buttons and highlights)
- **Green:** `#15803d` (secondary accent, used for branding and active Courses link)
- **Light Green:** `#bbf7d0` (Courses active background)
- **Soft Orange:** `#ffedd5` (active navigation background)
- **White:** `#fff` (background)
- **Gray:** `#374151` (text), `#fdba74` (borders)
- The app supports both light and dark modes, automatically adapting to the device theme.

### Forms & Inputs
- The Contact screen features clearly labeled input fields with rounded borders and ample spacing.
- The Fee Calculator uses simple numeric inputs and a prominent calculate button.

### Imagery & Icons
- All images are locally stored for fast loading and offline access.
- Icons are used for visual cues (e.g., awards, events) and are styled to match the color palette.

### Typography
- Headings use bold, colored text for emphasis (orange or green, depending on context).
- Body text is clear and readable, with consistent font sizes and spacing.

## How to Navigate the App

1. **Home:** Start on the Home screen to see the mission and quick links.
2. **Header Navigation:** Tap any link in the header (About Us, Courses, Events, Testimonials, Contact, Fee Calculator) to jump to that section. The active section is highlighted.
3. **Tab Bar (if available):** Use the bottom tab bar for quick switching between main sections.
4. **Donate Now:** Tap the orange Donate Now button in the header to access the donation screen from anywhere.
5. **Explore Content:** Scroll through courses, events, and testimonials. Tap on a course or event for more details.
6. **Contact & Calculator:** Use the Contact form to send a message, or the Fee Calculator to estimate course costs.
7. **Back Navigation:** Use the device back button or navigation controls to return to previous screens.

## Reference List (Harvard Style)


- Apple Human Interface Guidelines. (2025). Apple Developer. Available at: https://developer.apple.com/design/human-interface-guidelines/ (Accessed: 9 September 2025).
- Department of Higher Education and Training (DHET). (2020). National Skills Development Plan (NSDP) 2030. Pretoria: Government of South Africa.
- Empowering the Nation. (2025). About Us. Johannesburg: Empowering the Nation Training Centre.
- Garrett, J.J. (2011). The Elements of User Experience: User-Centered Design for the Web and Beyond. 2nd ed. Berkeley: New Riders.
- Google Material Design. (2025). Material Design Guidelines. Available at: https://m3.material.io/ (Accessed: 9 September 2025).
- Herrington, M., Kew, J. and Mwanga, A. (2022). Global Entrepreneurship Monitor: South Africa Report. Cape Town: University of Cape Town.
- International Labour Organization (ILO). (2019). Skills Development and Employment: A Global Perspective. Geneva: ILO.
- Krug, S. (2014). Don’t Make Me Think, Revisited: A Common Sense Approach to Web Usability. 3rd ed. San Francisco: New Riders.
- Mozilla Developer Network (MDN). (2025). HTML, CSS and JavaScript Documentation. Available at: https://developer.mozilla.org (Accessed: 9 September 2025).
- Nielsen, J. (1995). 10 Usability Heuristics for User Interface Design. Nielsen Norman Group. Available at: https://www.nngroup.com/articles/ten-usability-heuristics/ (Accessed: 9 September 2025).
- React Native. (2025). React Native Documentation. Available at: https://reactnative.dev/docs (Accessed: 9 September 2025).
- Shneiderman, B., Plaisant, C., Cohen, M., Jacobs, S., Elmqvist, N., & Diakopoulos, N. (2016). Designing the User Interface: Strategies for Effective Human-Computer Interaction. 6th ed. Boston: Pearson.
- Statistics South Africa (Stats SA). (2023). Quarterly Labour Force Survey. Pretoria: Stats SA. Available at: https://www.statssa.gov.za (Accessed: 9 September 2025).
- W3C. (2025). World Wide Web Consortium (W3C) Standards. Available at: https://www.w3.org/standards/ (Accessed: 9 September 2025).
- World Bank. (2020). The Future of Work in Africa: Harnessing the Potential of Digital Technologies for All. Washington DC: World Bank.
