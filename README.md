# Dwello - Urban Living Assistant (Landing Page)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A responsive, modern landing page for **Dwello**, a unified platform designed to eliminate the friction of settling into a new city. This project serves as the primary digital storefront, showcasing the core services and value proposition for individuals relocating to Greater Noida.

---

### ▶️ [Live Demo URL](https://your-username.github.io/dwello-project/) `(Replace with your deployment link)`

![Dwello Landing Page Screenshot](https://via.placeholder.com/1200x600.png?text=Dwello+Website+Screenshot)
*(Replace the placeholder URL with a screenshot of your live project)*

---

## 📋 Table of Contents

1.  [Problem Statement](#-problem-statement)
2.  [Our Solution](#-our-solution)
3.  [Key Features](#-key-features)
4.  [Technology Stack](#-technology-stack)
5.  [Project Setup & Installation](#-project-setup--installation)
6.  [Code Highlights](#-code-highlights)
7.  [License](#-license)
8.  [Contact](#-contact)

---

## 🎯 Problem Statement

Relocating to a new city, especially for students and young professionals, is a fragmented and stressful process. Newcomers face significant challenges:
* **Finding Housing:** Navigating high brokerage fees, unverified listings, and a lack of transparency.
* **Essential Setup:** The high upfront cost and logistical hassle of purchasing or sourcing essential appliances.
* **Daily Services:** Identifying trustworthy and reliable local help like cooks, cleaners, and tiffin services without local contacts.

This creates a significant barrier to settling in comfortably and quickly.

## ✨ Our Solution

Dwello addresses these challenges by providing a centralized, transparent, and trust-based ecosystem. This landing page is the first point of contact, designed to communicate our commitment to:

* **Convenience:** A single platform for housing, rentals, and local services.
* **Trust:** Physically verified listings and community-rated service providers.
* **Affordability:** A lowest brokerage guarantee and cost-effective rental options to reduce the financial burden on newcomers.

---

## 🚀 Key Features

This landing page is not just static; it incorporates several interactive elements to engage users and demonstrate functionality.

* **Interactive Hero Section:**
    * **Tabbed Search Interface:** Users can seamlessly switch between searching for `Homes`, `Rentals`, and `Services`, with the input placeholder updating dynamically via JavaScript.

* **Value Proposition Banners:**
    * **"Free Documentation" Offer:** A high-visibility banner highlighting the limited-time offer of free rental agreements and police verification to attract first-time users.
    * **Key Metrics Display:** A clean, four-column layout showcasing social proof and trust signals (`150+ Verified Listings`, `Lowest Brokerage Guarantee`, etc.).

* **On-Demand Service Marketplace (`The Hub`):**
    * A clear, icon-driven grid explaining the pay-per-use model for essential services like cooks, Wi-Fi, cleaning, and repairs.
    * Subtle hover animations on service cards to improve user interaction.

* **Animated Feature Spotlight (Bill Splitting):**
    * An immersive, dark-themed section that animates on scroll using the **Intersection Observer API**.
    * Features a detailed phone mockup with animated list items to visually represent the bill-splitting functionality.

* **Detailed Service & Property Sections:**
    * Curated cards for top property listings with essential details (rent, location, configuration).
    * Dedicated sections explaining the process for both renters ("How It Works") and property owners ("List Your Property").

* **Fully Responsive Design:**
    * A mobile-first approach ensures a seamless experience on all devices, from phones to desktops.
    * Includes a JavaScript-powered collapsible hamburger menu for mobile navigation.

---

## 🛠️ Technology Stack

This project is built with a focus on performance and simplicity, requiring no complex build tools. All assets are served via CDNs.

* **Structure & Semantics:** `HTML5`
* **Styling:**
    * **Tailwind CSS (v3 via CDN):** A utility-first CSS framework for rapid and consistent UI development.
    * **Custom CSS:** In-line `<style>` block for bespoke animations, hover effects, and a custom font implementation.
* **Interactivity & DOM Manipulation:**
    * **Vanilla JavaScript (ES6):** Used for the mobile menu toggle, dynamic search bar, and the on-scroll animation logic.
    * **Intersection Observer API:** Efficiently triggers animations for the "Bill Split" section when it enters the viewport.
* **Assets:**
    * **Font Awesome (v6 via CDN):** For a comprehensive and scalable icon set.
    * **Google Fonts:** The 'Poppins' font family is used for modern and clean typography.

---

## ⚙️ Project Setup & Installation

To run this project locally, no package manager (like npm) or bundler is needed.

1.  **Clone the Repository**
    ```sh
    git clone [https://github.com/your-username/dwello-project.git](https://github.com/your-username/dwello-project.git)
    ```

2.  **Navigate into the Directory**
    ```sh
    cd dwello-project
    ```

3.  **Open in Your Browser**
    Simply double-click the `index.html` file, or right-click and choose "Open with" your preferred web browser (e.g., Chrome, Firefox).

That's it! The page will render completely with all styles and scripts loaded from the CDNs.

---

## 💡 Code Highlights

A few notable aspects of the implementation:

* **Efficient Animations:** The use of the `IntersectionObserver` is a modern, performance-friendly alternative to scroll-event listeners for triggering animations, preventing layout thrashing.
* **Utility-First with Customization:** The project primarily uses Tailwind's utility classes but demonstrates how to add custom styles (`card-hover`, keyframe animations) for unique design requirements without ejecting from the framework's philosophy.
* **Accessibility:** Semantic HTML tags (`<nav>`, `<main>`, `<section>`) are used to improve SEO and accessibility. `aria-label` attributes are used on icon-only buttons.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

---

## 📧 Contact

Created by [Your Name] - [your.email@example.com]

Project Link: [https://github.com/your-username/dwello-project](https://github.com/your-username/dwello-project)
