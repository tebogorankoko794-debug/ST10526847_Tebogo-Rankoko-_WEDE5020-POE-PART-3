# Kelly's Burger Website – Part 3 (WEDE5020)

**Learner:** Tebogo Rankoko  
**Student number:** ST10526847  
**Course:** Web Development (Introduction) – WEDE5020  
**Project:** Kelly's Burger

## 1. Project overview
This is an updated beginner-level website for Kelly's Burger, a South African fast-food business concept. It uses HTML5 for page structure, CSS3 for styling and responsive layouts, and JavaScript for interactive features.

## 2. Pages included
- `index.html` – home page and introduction.
- `about.html` – business history, mission, vision, values and FAQ accordion.
- `products.html` – full product menu with search, category filtering and sorting.
- `burgers.html` – burger category.
- `drinks.html` – drinks category.
- `enquiries.html` – product/order enquiry form with HTML and JavaScript validation.
- `contacts.html` – contact details, service-area map and general contact form.
- `login.html` – front-end login demonstration only.

## 3. Part 3 functionality
- Products are stored in a JavaScript array and dynamically displayed on the menu pages.
- Search filters products by name and description.
- Category filtering and sorting by price/name are available.
- FAQ accordion expands and collapses when selected.
- A supplied burger photograph is displayed on burger cards and opens in a lightbox when clicked.
- Enquiry form validates required fields, email, South African phone number format, message length and quantity.
- Contact form validates details and prepares a message using the visitor's default email application (`mailto:`).
- Feedback messages are displayed on the page.
- Navigation hover/focus states, CSS transitions and responsive layouts improve usability.

**Important form limitation:** This is a static front-end assignment. The enquiry form demonstrates validation and confirmation in the browser; it does not save information to a database or send it to a server. The contact form opens the user's email application for review and sending. A real business website would need a secure server-side form service or backend.

## 4. SEO and accessibility
- Each page has a unique title and meta description.
- Relevant keywords, headings and descriptive image alt text are included.
- Pages link to each other through the navigation and footer.
- `robots.txt` and `sitemap.xml` are included.
- The layout uses a mobile viewport, responsive breakpoints and flexible grids.
- Form labels, required fields, focus styles and status messages improve accessibility.
- Images use lazy loading where relevant; the map iframe also uses lazy loading.

## 5. Running the website
1. Extract the ZIP file.
2. Open the `Kellys_Burger_Website` folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension.
4. Navigate through the menu and test the product search, filter, sort, FAQ and forms.

## 6. Changelog – Part 3 updates
| Area | Update made | Reason / feedback addressed |
|---|---|---|
| Part 2 feedback | Added a detailed changelog and this README. | Part 2 feedback awarded 5/10 for feedback updates and 2/5 for the README because the development record was not detailed enough. |
| References | Added a reference list below and links to relevant technical documentation. | Part 2 feedback awarded 0/5 for references. |
| SEO | Added unique page titles, descriptions, keywords, heading structure, internal links, `robots.txt` and `sitemap.xml`. | Implements the Part 3 on-page and additional SEO requirements. |
| Dynamic content | Product cards are generated from a JavaScript product array. | Implements the requirement to dynamically load product listings. |
| Search and sorting | Added search, category filtering and sorting by price/name. | Implements the Part 3 product search/filter requirement. |
| Interactive elements | Added an FAQ accordion, CSS transitions and a product lightbox framework. | Implements interactive elements and image gallery/lightbox support when product images are added. |
| Enquiry form | Added product, enquiry type, quantity, contact details and message fields with browser and JavaScript validation. | Addresses the required product/order enquiry form and error handling. |
| Contact form | Added general message type, full message, validation and a prepared email to the stated business email address. | Addresses the separate general contact form requirement. |
| Responsive design | Retained and improved mobile/tablet layouts, navigation, grids and form layouts. | Builds on the strong responsive-design marks received in Part 2. |
| CSS typography | Standardised headings, body text, spacing, form labels and text sizes. | Part 2 feedback awarded 3/5 for typography and recommended more consistent styling. |
| CSS decoration | Improved consistent colour use, cards, buttons, hover/focus states and transitions. | Part 2 feedback awarded 4/5 for decoration and colour. |
| Security and performance | Used client-side validation, avoided storing passwords, kept scripts external and used lightweight CSS/JavaScript. | Addresses the Part 3 security and page-speed guidance at a basic static-site level. |

## 7. Part 2 feedback summary and response
The Part 2 result was **76/100**. Strong areas included the external stylesheet (10/10), pseudo-classes (10/10), responsive media queries (10/10), responsive layout adjustments (5/5), typography adjustments (5/5), navigation adjustments (5/5) and image adjustments (5/5).

Areas needing attention were:
- Feedback changes/changelog: 5/10.
- Typography styling: 3/5.
- GitHub commits: 0/5 (feedback stated no repository was provided).
- README: 2/5.
- Changelog: 2/5.
- References: 0/5.

The current update documents the changes, improves typography and adds references. **The learner must still create/use their own GitHub repository, make multiple descriptive commits, push the project, and deploy it.** Those actions cannot be completed from this local project ZIP because they require access to the learner's GitHub/deployment accounts.

## 8. GitHub submission steps
1. Sign in to GitHub and create a new repository named `kellys-burger-website`.
2. Copy the extracted project files into the repository folder.
3. Open a terminal in that folder and run:

```bash
git init
git add .
git commit -m "Initial Part 3 website structure and SEO"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/kellys-burger-website.git
git push -u origin main
```

4. Make further meaningful changes and commit them separately, for example:

```bash
git add .
git commit -m "Add dynamic product search and sorting"
git push

git add .
git commit -m "Add validated enquiry and contact forms"
git push

git add .
git commit -m "Update README changelog and SEO files"
git push
```

Replace `YOUR-USERNAME` with your own GitHub username. Do not submit the example URL.

## 9. Free deployment steps
**GitHub Pages:** Open the repository on GitHub → Settings → Pages → choose deployment from the `main` branch and `/ (root)` → Save. Wait for GitHub to publish the site, then copy the published URL into the submission.

Alternatively, sign in to Netlify, choose to add/import an existing project, connect the GitHub repository, and deploy using the default settings for this static website. Submit the real deployment URL after confirming it works.

## 10. References
- Google. (n.d.). *Search Engine Optimization (SEO) Starter Guide*. https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- MDN Web Docs. (n.d.). *HTML forms*. https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms
- MDN Web Docs. (n.d.). *Constraint validation*. https://developer.mozilla.org/en-US/docs/Web/HTML/Constraint_validation
- MDN Web Docs. (n.d.). *Document Object Model (DOM)*. https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model
- MDN Web Docs. (n.d.). *CSS media queries*. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- Google. (n.d.). *Build and submit a sitemap*. https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap
- GitHub Docs. (n.d.). *Configuring a publishing source for your GitHub Pages site*. https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Netlify Docs. (n.d.). *Deploy overview*. https://docs.netlify.com/site-deploys/overview/
