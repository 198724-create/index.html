# House of Pizza

**Author:** Leo Herrera 
**Course:** Project 01
**Deployed Site:** https://198724-create.github.io/index.html/

## Overview
House of Pizza is a single-page class project showcasing a fictional pizzeria.  
It features a tomato-on-black theme, a picture menu, an image carousel gallery, contact form, hours, and reviews.  
The page uses anchor navigation to jump between sections.

## Features / How to Use
- **Navigation bar** links to Menu, Gallery, About, Contact, Hours, Reviews.
- **Menu grid** with six pizzas (images, descriptions, prices).
- **Gallery** implemented as a Bootstrap carousel (auto-slides + prev/next controls).
- **Contact form** with required fields (First Name, Email, Comment).  
- **Responsive layout** (grid + Bootstrap) so it works on mobile.
- **Dark theme** with tomato accents.

## User Stories
-As a visitor, I want a menu with images, prices, and short descriptions so I can decide what to order.
-As a visitor, I want to see the restaurant name and nav bar so I can jump to sections quickly.
-As a visitor, I want contact info and a form so I can reach out with questions.

## Wireframes
Hand-drawn wireframes are included in `/docs/wireframes/`:
[Website Sketch](docs/wireframes/leo.jpeg)

## Technologies Used
- HTML5
- CSS3 (custom stylesheet at `css/style.css`)
- Bootstrap 5 (carousel + grid helpers)

## Getting Started (Local)
1. Clone the repo  
   ```bash
   git clone https://github.com/<198724-create>/<index.html>.git
   cd <index.html>

## Deployment (GitHub Pages)

The app is hosted on **GitHub Pages**:  
[https://<198724-create>.github.io/<index.html>/](https://<198724-create>.github.io/<index.html>/)

**Steps:**
1. Go to `Settings → Pages`
2. Under **Source**, choose **Deploy from branch**.
3. Select **Branch:** `main` and **Folder:** `/ (root)`.
4. Save changes and wait ~1 min for deployment.

## Validation

- HTML validated with [W3C Validator](https://validator.w3.org/).
- No errors; only warnings/info accepted per rubric.

## Future Improvements
- Hook the contact form to **Formspree** to receive real submissions.
- Add a **menu detail page** with toppings picker or nutrition info.
- Add a **reviews form** with client-side validation.

## Credits / Attribution

- All pizza images are placeholders for class use.
- Built by Leo for educational purposes.


[docs/wireframes/leo.jpeg]: docs/wireframes/leo.jpeg