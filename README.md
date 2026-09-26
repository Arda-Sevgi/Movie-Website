# Somewhere Only We Know – Movie Website

A responsive and accessible promotional website for the fictional film **Somewhere Only We Know**.

The project combines front-end web development with multimedia design, including a film poster, studio logo, radio advertisement, interactive elements, and an accessibility and responsiveness report.

## 🎬 Project Overview

The website was created as a multimedia-focused movie website for **Luminary Pictures**.

It consists of five HTML pages:

- **Home** – Introduces the film, its genre, story, and cast.
- **Poster** – Presents the film poster and information about its creation.
- **Logo** – Showcases the Luminary Pictures studio logo.
- **Audio** – Contains the film's radio advertisement and transcript.
- **Report** – Documents the accessibility and responsive design decisions used throughout the website.

The project focuses on creating a visually engaging website while maintaining accessibility and usability across different screen sizes.

## ✨ Features

### Responsive Design

- Responsive layouts for desktop, tablet, and mobile devices
- CSS Grid for multi-column layouts
- Flexbox for navigation and flexible content
- Responsive typography using `clamp()`
- Responsive images and SVG graphics
- Media queries for different screen sizes
- Responsive cast carousel

### Accessibility

The website was designed with **WCAG 2.2** accessibility principles in mind.

Accessibility features include:

- Semantic HTML5 elements
- Skip-to-main-content navigation
- ARIA labels and attributes
- `aria-current` for the active navigation page
- Descriptive image `alt` text
- Keyboard-accessible interactive elements
- Visible keyboard focus states
- Accessible SVG implementation
- Audio transcript for the radio advertisement
- Colour contrast considerations
- Native HTML5 audio controls

### Interactive Elements

- Responsive cast carousel
- Keyboard navigation
- Logo background/theme toggle
- Audio player
- Expandable audio transcript
- Responsive navigation

## 🎨 Multimedia Content

The project also includes original multimedia assets created using different tools.

### Film Poster

The film poster was created using **Photopea** and exported as a PNG.

The design features:

- Two character silhouettes
- Edinburgh train platform setting
- Rain and autumn leaves
- Atmospheric lighting
- Layered visual effects

### Studio Logo

The **Luminary Pictures** logo was designed in Photoshop and recreated as an inline SVG for the website.

Using SVG allows the logo to scale without losing visual quality.

### Radio Advertisement

The film's radio advertisement was produced using **BandLab**.

The audio combines:

- Rain and nature ambience
- Piano music
- Train station ambience
- AI-generated voice-over
- Multiple audio tracks and volume adjustments

The final advertisement was exported as an MP3 file.

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**
- **SVG**
- **CSS Grid**
- **Flexbox**
- **Responsive Design**
- **ARIA**
- **WCAG 2.2 Accessibility Principles**

### Creative Tools

- Photopea
- Adobe Photoshop
- BandLab
- ElevenLabs

## 📂 Project Structure

```text
Movie-Site/
│
├── index.html
├── poster.html
├── logo.html
├── audio.html
├── report.html
├── style.css
├── main.js
│
├── images/
│   ├── poster_workspace.png
│   ├── logo_workspace.png
│   └── audio_workspace.png
│
└── audio/
    └── radio-advert.mp3
```

> File names may vary depending on the current version of the repository.

## 🚀 Getting Started

This is a static front-end website and does not require a backend or database.

### Clone the Repository

```bash
git clone https://github.com/Arda-Sevgi/Movie-Site.git
```

Navigate to the project directory:

```bash
cd Movie-Site
```

Open `index.html` in a web browser.

Alternatively, the project can be run using a local development server such as the **Live Server** extension in Visual Studio Code.

## 📱 Responsive Breakpoints

The website adapts its layout according to the available screen width.

Examples include:

- **Desktop:** Multi-column layouts and larger navigation elements
- **Tablet:** Reduced content widths and adjusted grids
- **Mobile:** Single-column layouts, compact navigation, and smaller typography

The cast carousel also adjusts the number of visible cards depending on the screen width.

## ♿ Accessibility Approach

Accessibility was considered throughout the development process rather than being added as a separate feature at the end.

Examples include:

```html
<a class="skip-link" href="#main-content">
    Skip to main content
</a>
```

and:

```html
<nav role="navigation" aria-label="Main navigation">
```

Interactive controls also use appropriate ARIA attributes where necessary, while decorative SVG elements are hidden from screen readers using `aria-hidden="true"`.

The audio advertisement includes a text transcript to provide an alternative for users who cannot hear or play the audio.

## 📚 Learning Objectives

This project helped develop practical experience with:

- Structuring websites using semantic HTML
- Creating responsive layouts with CSS
- Using CSS Grid and Flexbox
- Implementing responsive typography
- Creating interactive functionality with JavaScript
- Working with SVG graphics
- Implementing accessibility features
- Using ARIA attributes
- Designing keyboard-accessible interfaces
- Working with multimedia content
- Integrating audio into a website
- Creating and organising digital media assets

## 🔮 Possible Improvements

Potential future improvements include:

- Adding a dark mode using `prefers-color-scheme`
- Replacing placeholder cast images with real project assets
- Adding an `aria-live` region to provide carousel updates to screen-reader users
- Conducting testing with real screen readers and users with disabilities
- Further optimising images and multimedia assets
- Adding additional JavaScript interactions

## 👤 Author

**Arda Sevgi**

GitHub: [Arda-Sevgi](https://github.com/Arda-Sevgi)
