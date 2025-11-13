🧩 RapidSiteKit
RapidSiteKit is a sleek, intuitive, and powerful front-end development toolkit built to help developers create responsive, modern, and elegant web interfaces quickly. Designed with flexibility and accessibility in mind, RapidSiteKit provides a collection of responsive CSS utilities, ready-to-use JavaScript components, and customizable UI patterns to speed up your workflow — whether you're building a portfolio, dashboard, or enterprise-grade web app.

🚀 Features


⚡ Lightweight & Fast: Built for performance and optimized for quick load times.


🧱 Prebuilt Components: Ready-to-use UI elements — buttons, modals, navbars, forms, alerts, and more.


🎨 Responsive Design: Mobile-first grid system and flexible layout utilities.


🛠️ Customizable: Easy to override variables, themes, and components using SCSS.


♿ Accessible by Default: WCAG-compliant markup and ARIA support.


🔄 Integration Friendly: Works seamlessly with frameworks like React, Vue, Angular, or plain HTML.


🧰 Build Tool Support: Compatible with npm, yarn, and modern bundlers (Webpack, Vite, Parcel).



📦 Installation
You can install RapidSiteKit in multiple ways depending on your setup:
Option 1: Download
Download the latest version directly from the releases page.
Option 2: Clone via Git
bashCopy codegit clone https://github.com/your-username/rapidsitekit.git

Option 3: Install via npm
bashCopy codenpm install rapidsitekit

Option 4: Install via Yarn
bashCopy codeyarn add rapidsitekit

Option 5: Install via Composer
bashCopy codecomposer require your-username/rapidsitekit


🧩 Usage
After installation, include the CSS and JS files in your project:
HTML Example
htmlCopy code<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RapidSiteKit Demo</title>
  <link rel="stylesheet" href="node_modules/rapidsitekit/dist/css/rapidsitekit.min.css">
</head>
<body>

  <nav class="rsk-navbar">
    <div class="rsk-container">
      <a href="#" class="rsk-brand">RapidSiteKit</a>
    </div>
  </nav>

  <div class="rsk-container">
    <button class="rsk-btn rsk-btn-primary" onclick="rskAlert('Welcome to RapidSiteKit!')">
      Click Me
    </button>
  </div>

  <script src="node_modules/rapidsitekit/dist/js/rapidsitekit.min.js"></script>
</body>
</html>


⚙️ Customization
You can customize styles using SCSS variables or utility classes.
Example:
scssCopy code// Override theme colors
$primary-color: #4f46e5;
$secondary-color: #10b981;
@import "rapidsitekit/scss/rapidsitekit.scss";


🧠 Examples
RapidSiteKit includes multiple example templates to get started quickly:


Landing Page Template


Admin Dashboard Layout


Portfolio Showcase


Login/Register UI


Explore the /examples directory in the repository for ready-to-use templates.

🧑‍💻 Contributing
We welcome contributions from the community!
To contribute:


Fork the repo


Create a feature branch


Commit your changes


Submit a pull request


Please follow our contribution guidelines for coding standards and PR format.
