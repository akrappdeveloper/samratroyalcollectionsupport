# Samrat Royal Collection Support Website

A customer support website for Samrat Royal Collection with contact form, live chat, FAQ, and more.

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation
1. Clone or download the project files.
2. Navigate to the project directory:
   ```bash
   cd samrat-royal-collection-support
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Build CSS
1. To generate the minified CSS for production:
   ```bash
   npm run build
   ```
   This creates `public/css/styles.css`.
2. For development with live reloading:
   ```bash
   npm run watch
   ```

### Form Setup
- The contact form uses Formspree (`https://formspree.io/f/xjkbdwzp`).
- Sign up at [Formspree](https://formspree.io) with `samratroyalcollection@gmail.com` to receive form submissions.
- Update the `action` attribute in `index.html` if you get a new Formspree endpoint.

### Live Chat
- Live chat is powered by Tawk.to (`https://embed.tawk.to/671b4b3d2480f8b4e49b32d7/1ic0k4v5l`).
- Create a Tawk.to account and replace the script in `index.html` with your widget ID if needed.

### Hosting
1. Copy `index.html`, `thank-you.html`, and the `public` folder to your hosting platform (e.g., Netlify, Vercel, GitHub Pages).
2. Ensure the file structure is maintained:
   ```
   /
   ├── index.html
   ├── thank-you.html
   ├── public/
   │   ├── css/
   │   │   ├── styles.css
   ```

### Customization
- Update social media links in the footer (`index.html`) with your actual profiles.
- Modify FAQ content in `index.html` to reflect your policies.
- Adjust colors and styles in `tailwind.config.js` or `src/input.css` for branding.

### Testing
- Test the form by submitting a message and checking `samratroyalcollection@gmail.com`.
- Verify the live chat widget via Tawk.to's dashboard.
- Check responsiveness on mobile, tablet, and desktop.

## Features
- Responsive design
- Contact form (sends to `samratroyalcollection@gmail.com`)
- Tawk.to live chat
- Chatbot support placeholder
- FAQ section
- Social media links
- Thank-you page
- SEO optimization
- Accessibility (ARIA labels, keyboard navigation)
- Back-to-top button

For further assistance, contact the developer or refer to [Tailwind CSS documentation](https://tailwindcss.com/docs).