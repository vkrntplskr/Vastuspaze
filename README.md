# Vastuspaze - Interior Design Website

**Vastuspaze** is a responsive, multi-page website designed for an interior design firm that blends modern luxury with Vastu principles. The website showcases the company's portfolio, services, and projects while providing an interactive platform for client engagement through blogs, testimonials, and contact forms.

## 🌟 Features

  * **Responsive Design**: Fully adaptable layout that works seamlessly on desktops, tablets, and mobile devices.
  * **Interactive Home Page**: Features an automated image slider (using Swiper.js) and dynamic content sections.
  * **Service Showcase**: Detailed cards displaying various interior design services (Living Room, Kitchen, Office, etc.).
  * **Portfolio & Projects**: Visual galleries showcasing past work and design concepts.
  * **Blog Section**: A grid-based blog layout sharing interior design insights and trends.
  * **Testimonials & Reviews**:
      * Displays client success stories.
      * **Google Forms Integration**: Users can submit reviews directly through a modal dialog which connects to a Google Form.
  * **Contact & Newsletter**:
      * Functional Newsletter subscription form (integrated with Google Forms).
      * Contact form with validation and user feedback (simulated in JS).
      * FAQ accordion section.

## 🛠️ Technologies Used

  * **Frontend**: HTML5, CSS3, JavaScript (ES6)
  * **Libraries & Frameworks**:
      * [Tailwind CSS](https://tailwindcss.com/) (Used in Testimonials & Blog pages via CDN)
      * [Bootstrap 5](https://getbootstrap.com/) (Used in Services & About Us pages via CDN)
      * [Swiper.js](https://swiperjs.com/) (For the image slider)
  * **Icons**: [Remix Icon](https://remixicon.com/)
  * **Fonts**: Google Fonts (Poppins, Playfair Display)
  * **Backend / Data Collection**: Google Forms (for capturing Reviews and Newsletter subscriptions)

## 📂 Project Structure

```text
Vastuspaze/
│
├── index.html           # Landing page with hero slider and overview
├── About-us.html        # Company info, team, mission, and vision
├── Services.html        # Detailed list of design services
├── Portfolio.html       # Gallery of design work
├── Projects.html        # Showcase of specific projects
├── Blog.html            # Interior design articles
├── Testimonials.html    # Client reviews and submission form
├── Contact-us.html      # Contact form, map, and FAQs
│
├── css/                 # Stylesheets
│   ├── index.css        # Global and Home page styles
│   ├── about.css        # Specific styles for About page
│   ├── service.css      # Specific styles for Services page
│   ├── portfolio.css    # Specific styles for Portfolio page
│   ├── project.css      # Specific styles for Projects page
│   ├── contact.css      # Specific styles for Contact page
│   └── testimonial.css  # Specific styles for Testimonial page
│
├── js/                  # JavaScript Logic
│   ├── script.js        # Global scripts (Mobile menu, Slider)
│   ├── contact.js       # Contact form handling and FAQ toggle
│   └── testimonial.js   # Testimonial slider and modal logic
│
└── images/              # Project assets (WebP, JPG, etc.)
```

## 🚀 How to Run

Since this is a static website, you do not need a backend server to run it.

1.  **Clone or Download** the repository.
2.  **Extract** the files if downloaded as a ZIP.
3.  **Open** the project folder.
4.  Double-click `index.html` to open it in your default web browser.

## 📝 Configuration Details

### Google Forms Integration

The website uses **Google Forms** to handle data submission without a backend server.

  * **Newsletter (Blog.html)**: Submits email addresses to a configured Google Sheet.
  * **Reviews (Testimonials.html)**: Submits user name and review text to a configured Google Sheet via a hidden iframe.

### Customization

  * **Slider**: To change the slider images or speed, modify the `swiper-slide` divs in `index.html` and the `Slider()` function in `js/script.js`.
  * **Colors**: Global colors (like the primary blue `#00b3ff`) are defined in the CSS files. Tailwind classes are used directly in HTML for `Blog.html` and `Testimonials.html`.

## 📄 License

This project is created for educational and portfolio purposes.

-----

*© 2025 Vastuspaze. All Rights Reserved.*
