# Personal Portfolio Website

A responsive personal portfolio website built from scratch using **HTML5 and CSS3**. The project presents a developer profile through dedicated sections for introduction, about information, services, featured work, and contact details.

The project focuses on building a complete portfolio interface using core web-development technologies without relying on a frontend framework or build system.

## ✨ Features

* Responsive portfolio layout
* Navigation bar with section-based navigation
* Mobile-friendly hamburger menu
* Animated welcome/intro section
* Hero section with developer introduction
* About Me section
* Skills, experience, and education tabs
* Services section
* Portfolio / featured works section
* Contact form interface
* Social media section
* Responsive styling for different screen sizes
* Custom image and icon assets
* Clean single-page website structure

## 🖥️ Website Sections

### 🏠 Home

The landing section introduces the developer with:

* Portfolio branding
* Navigation menu
* Welcome animation
* Frontend Developer introduction
* Short professional description
* Profile/hero image

### 👨‍💻 About

The About section contains:

* Developer introduction
* Profile image
* Skills
* Experience
* Education
* Web development and application-development information

### 🛠️ Services

The services area presents:

* Web Design
* UI/UX Design
* App Design

Each service includes a short description and a "Learn more" interface.

### 💼 Portfolio

The Works section showcases example projects such as:

* Social Media App
* Online Shopping App
* Music App

Each project contains a visual preview and project description.

### 📩 Contact

The contact section provides:

* Name input
* Email input
* Message textarea
* Send Message button
* Social media links/icons
* Email contact
* Phone contact

## 🧰 Tech Stack

| Technology       | Purpose                                         |
| ---------------- | ----------------------------------------------- |
| **HTML5**        | Website structure and semantic content          |
| **CSS3**         | Styling, layout, responsiveness, and animations |
| **Font Awesome** | UI/service icons                                |
| **Image Assets** | Profile, project, and social-media visuals      |

The repository contains no JavaScript framework, package manager, or backend service; the website is implemented as a static HTML/CSS project.

## 📁 Project Structure

```text
portfolio/
│
├── index.html
├── styles.css
│
├── Dev.avif
├── img.jpg
├── home img.png
│
├── work1.jpeg
├── work2.jpeg
├── work3.jpeg
│
├── youtube.png
├── whatsapp.png
├── linkedin.png
├── facebook.png
├── insta.png
├── telegram.png
│
├── send.png
└── contact.png
```

The current repository contains the main HTML document, stylesheet, profile/project images, and social/contact assets.

## 🏗️ Project Architecture

The project follows a simple static website architecture:

```text
                    Portfolio Website
                           │
                           ▼
                     index.html
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
           Header         Main         Footer
             │             │             │
             ▼             ▼             ▼
          Navigation    About/Services   Contact
          + Hero        + Portfolio      + Socials
                           │
                           ▼
                       styles.css
                           │
                           ▼
                Responsive UI + Animations
```

## 🚀 Getting Started

### Prerequisites

No special framework or package manager is required.

You only need:

* A modern web browser
* A code editor such as VS Code
* Git (optional, for cloning)

## 📥 Installation

### 1. Clone the repository

```bash
git clone https://github.com/VaibhavDubey95u/portfolio.git
```

### 2. Navigate to the project

```bash
cd portfolio
```

### 3. Open the website

Since this is a static HTML/CSS project, you can simply open:

```text
index.html
```

in your browser.

### Recommended: VS Code Live Server

If you use Visual Studio Code, install the **Live Server** extension and open the project with it.

Then right-click:

```text
index.html
```

and select:

```text
Open with Live Server
```

## 🎨 Customization

You can personalize the portfolio by editing `index.html`.

### Personal Information

Update:

* Name
* Professional title
* About section
* Skills
* Experience
* Education
* Services
* Contact information

### Project Information

Update the project cards in the Portfolio section:

```html
<h3>Project Name</h3>
<p>Project description...</p>
```

Replace the existing project images with your own images.

### Styling

All major visual styling is contained in:

```text
styles.css
```

You can customize:

* Colors
* Typography
* Spacing
* Layout
* Responsive breakpoints
* Animations
* Navigation
* Cards
* Portfolio effects

## 📱 Responsive Design

The stylesheet contains responsive CSS rules to adapt the layout for smaller screens.

The navigation includes a mobile hamburger-menu mechanism using a checkbox/label approach rather than requiring a JavaScript navigation framework.

## 🌐 Deployment

Because this is a static website, it can be deployed using any static hosting platform.

Typical deployment options include:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages
* Any standard static web server

No backend server or database is required for the current implementation.

## 🔮 Future Improvements

Potential improvements for future versions include:

* [ ] Replace placeholder content with complete professional information
* [ ] Add real project links and GitHub repositories
* [ ] Connect the contact form to a backend/email service
* [ ] Add downloadable resume functionality
* [ ] Improve accessibility and semantic HTML
* [ ] Add SEO metadata and Open Graph tags
* [ ] Optimize images for faster loading
* [ ] Add project filtering
* [ ] Add dark/light theme support
* [ ] Add more advanced animations
* [ ] Add a dedicated project-details section
* [ ] Add analytics

## 📌 Project Status

**Status:** Completed static portfolio prototype

The current version demonstrates the structure and styling of a personal developer portfolio using core frontend technologies.

## 👨‍💻 Author

**Vaibhav Dubey**

Software Engineering Student | Full-Stack Development | AI/ML Enthusiast

GitHub: [@VaibhavDubey95u](https://github.com/VaibhavDubey95u)

## 📄 License

No explicit open-source license is currently included in the repository.

If you plan to distribute or allow others to reuse the project, consider adding an appropriate license.

---

⭐ If you find this project useful, consider giving the repository a star.
