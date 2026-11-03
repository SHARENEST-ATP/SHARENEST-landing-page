# Sharenest

**Borrow what you need from your own community.**

Sharenest is a request-first borrowing platform concept designed to make borrowing easier and safer within verified communities. Instead of searching through public listings, members post requests for items they need. Other members who own those items can voluntarily offer to lend them.

This repository contains the **Sharenest landing page and early promotional prototype**, built to introduce the concept, explain how it works, and collect interest from potential users.

## About Sharenest

People often buy items they only need temporarily. Sharenest aims to reduce unnecessary purchases by connecting people who need something with people in their own trusted communities who are willing to lend it.

The platform is designed for communities such as:

- Universities and student groups
- Student accommodation
- Apartment and residential communities
- Workplaces

## Key Features

The landing page includes:

- **Responsive Design** – Layout adapts to desktop, tablet, and mobile screens.
- **Animated Intro** – Branded splash screen with skip functionality.
- **Interactive Concept Demonstration** – Animated example showing how a borrowing request, lending offer, and agreement work.
- **How It Works** – Four-step explanation of the borrowing process.
- **Platform Features** – Overview of Sharenest's planned functionality.
- **Team Section** – Introduction to the development team.
- **Waitlist Form** – Form for collecting interest from potential users.

## Platform Concept

Sharenest is designed around several core principles:

- **Verified Communities** – Access limited to approved members of participating communities.
- **Request-First Borrowing** – Members request items instead of relying on existing listings.
- **Voluntary Lending** – Owners decide whether they want to offer an item.
- **Borrowing Agreements** – Both parties confirm lending dates, handover details, and any applicable fees.
- **Condition Records** – Item condition can be recorded during handover and return.
- **Privacy and Accountability** – Community-focused access, reporting, and transaction feedback.

*These describe the intended platform functionality. This repository currently contains the landing page, not the complete borrowing application or its backend.*

## Technologies Used

- **HTML5** – Page structure and content.
- **CSS3** – Styling, responsive layouts, animations, and visual effects.
- **JavaScript** – Splash screen behaviour, waitlist validation, and form submission.
- **Google Fonts** – Nunito typography.
- **Formspree** – Planned waitlist form handling.

No frontend frameworks, package installations, or build tools required.

## Getting Started

### Run Locally

1. Clone repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Navigate into project folder:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Start a local server:

   ```bash
   python -m http.server 8000
   ```

4. Open browser and visit:

   ```text
   http://localhost:8000
   ```

You can also open `index.html` directly in your browser.

## Project Structure

```text
Sharenest/
│
├── index.html
│
└── assets/
    ├── favicon.png
    ├── sharenest-emblem.png
    ├── sharenest-logo.jpg
    └── social-preview.jpg
```

## Configuration Before Deployment

A few placeholders must be updated before publishing:

**1. Website Domain**

Replace `https://YOURDOMAIN` in `index.html` with actual deployed domain. Update canonical URL and Open Graph metadata.

**2. Waitlist Form**

Replace placeholder Formspree endpoint:

```html
action="https://formspree.io/f/YOUR_FORM_ID"
```

with actual Formspree form endpoint. Waitlist submissions will not work until this is configured.

**3. Social Media Links**

Add official social media URLs in footer when available.

## Deployment

This project can be hosted using GitHub Pages.

1. Push project files to GitHub repository.
2. Open repository **Settings**.
3. Navigate to **Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Select `main` branch and `/ (root)` folder.
6. Save settings.

GitHub Pages will generate a public URL for the landing page.

## Accessibility

Landing page includes:

- Semantic HTML structure.
- Skip-to-content navigation.
- Visible keyboard focus indicators.
- Form labels and validation feedback.
- Reduced-motion support for visitors who prefer less animation.

## Development Team

**Team CS-30**  
Agile Team Project  
Informatics Institute of Technology (IIT)  
University of Westminster

## Contact

For enquiries and project-related information:

**Email:** hello.sharenest@gmail.com

---

*Sharenest – Nurturing community through sharing.*
