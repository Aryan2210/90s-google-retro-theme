# **Retro Google-Themed Search Engine**

## **Overview**
This project is a retro 90s-themed replica of Google's homepage designed for a hackathon. It features search functionality, a lucky search option, an informational "About Google" page, and dynamic results fetched using Google Custom Search Engine (CSE). The project is built using HTML, CSS, and JavaScript, and it uses Google's APIs for search functionality.

---

## **Features**
1. **Retro Themed Design**:
   - Inspired by 90s web design with pixelated styles, gradient backgrounds, and animations.

2. **Functional Search**:
   - The "Google Search" button fetches search results dynamically from Google's Custom Search API.
   - The "I'm Feeling Lucky" button redirects to the top search result.

3. **Dynamic Pages**:
   - A `search-results.html` page to display search results.
   - A `lucky-result.html` page to showcase the first result dynamically.
   - An `about-google.html` page with historical information about Google.

4. **Email Subscription**:
   - A simple email subscription form with validation and a confirmation alert.

5. **Responsive Design**:
   - Works seamlessly on both desktop and mobile devices.

6. **Custom Styling**:
   - Retro gradients, animations, and pixelated elements to match the 90s aesthetic.

---

## **Setup Instructions**

### **1. Prerequisites**
- A text editor (e.g., VSCode, Sublime Text).
- A web browser (e.g., Chrome, Firefox).
- A Google account to set up the Custom Search Engine (CSE) API.

### **2. Setting Up Google CSE**
1. **Create a Custom Search Engine**:
   - Visit the [Custom Search Engine](https://cse.google.com/cse/) page and create a new search engine.
   - Note down the **Search Engine ID (CX)**.

2. **Get an API Key**:
   - Visit the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a project and enable the **Custom Search API**.
   - Generate an API key for the project.

3. Replace the placeholders (`YOUR_API_KEY` and `YOUR_CSE_ID`) in the JavaScript code with your actual API key and Search Engine ID.

---

## **How to Run**

1. Download or clone this repository:
   ```bash
   git clone https://github.com/Aryan2210/90s-google-retro-theme.git
   ```
2. Open `google.html` in any web browser.
3. Use the following:
   - Search using the input box and "Google Search" button.
   - Use the "I'm Feeling Lucky" button to jump to the top result.

---

## **Code Details**

### **Homepage (`google.html`)**
- Provides the main interface with search input, navigation links, and subscription form.
- Includes retro animations and pixelated styling.
- Scripts handle search queries and validate form input.

### **Search Results (`search-results.html`)**
- Displays search results dynamically using the Google Custom Search API.
- Includes pagination for navigating results.

### **Lucky Result (`lucky-result.html`)**
- Redirects to the top result of the search query dynamically.
- Displays the title and snippet of the result with a clickable link.

### **About Google (`about-google.html`)**
- Provides historical information about Google in a retro design.
- Includes links to the homepage.

---

## **Customization**

### **Styling**
- Modify the CSS styles in the `<style>` sections of each file.
- Add more animations or effects to enhance the retro look.

### **API Integration**
- Replace the placeholder API keys and Search Engine IDs with your own credentials.

### **Additional Features**
- Add a backend for storing email subscriptions.
- Enhance the design with more retro elements like marquee text or pixel fonts.

---

## **Meta Tags**
Each page includes meta tags for SEO and sharing:
```html
<meta name="description" content="A retro Google-themed search engine homepage created for a hackathon.">
<meta name="keywords" content="Google, retro, hackathon, 90s theme, search engine">
<meta name="author" content="Aryan Nandu">
```

---

## **Known Issues**
1. **API Rate Limits**:
   - Ensure your API usage is within the free tier limits or upgrade as needed.

2. **No Backend for Email Subscriptions**:
   - The email subscription form currently only validates and displays a confirmation alert.

3. **Search Results Limited to CSE**:
   - Only results from the configured Custom Search Engine will appear.

---

## **Future Enhancements**
1. Add a 404 error page for undefined routes.
2. Integrate a database to store email subscriptions.
3. Include more retro design features like blinking text or ASCII art.

---

## **License**
This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

## **Credits**
- **Designer & Developer**: Aryan Nandu
- **API Provider**: Google Custom Search API
