
                                  YUKTHI
                  Tech Fest Website — St. Mary's College, Thrissur
                        https://yukthismc.onrender.com/
================================================================================

Yukthi is the official website for the Yukthi Tech Fest event conducted at
St. Mary's College, Thrissur. Built with HTML, CSS, and JavaScript on the
frontend, powered by a Node.js/Express backend with MongoDB for data
management, and bundled using Webpack.

--------------------------------------------------------------------------------
FEATURES
--------------------------------------------------------------------------------

  • Event information and schedule pages
  • Intro, event listing, and main landing pages
  • Sponsor showcase section
  • Image gallery with event photos
  • Sitemap for SEO
  • Deployed live on Render

--------------------------------------------------------------------------------
TECH STACK
--------------------------------------------------------------------------------

  Frontend         : HTML, CSS, JavaScript
  Backend          : Node.js, Express.js
  Database         : MongoDB, Mongoose
  Bundler          : Webpack, CSS Loader, Style Loader
  Email            : Nodemailer
  Deployment       : Render

--------------------------------------------------------------------------------
PROJECT STRUCTURE
--------------------------------------------------------------------------------

  Yukthi/
  |-- dist/                    # Webpack build output
  |-- node_modules/            # Project dependencies
  |-- src/
  |   `-- index.js             # Main JS entry point
  |-- website/
  |   |-- images/              # Event photos, logo, sponsor images
  |   |   |-- logo.png
  |   |   |-- sp2.png / sp3.png / sp4.jpg
  |   |   `-- 1.jpg, 2(1).jpeg ... 2(18).jpeg
  |   |-- index.html           # Landing page
  |   |-- event.html           # Events page
  |   |-- intro.html           # Intro page
  |   |-- style.css            # Stylesheet
  |   |-- script.js            # Frontend scripts
  |   `-- webpack.config.js    # Webpack configuration
  |-- server.js                # Express server entry point
  |-- package.json             # Project metadata & scripts
  |-- package-lock.json        # Dependency lock file
  |-- sitemap.xml              # SEO sitemap
  |-- LICENSE                  # MIT License
  `-- README.md

--------------------------------------------------------------------------------
INSTALLATION & SETUP
--------------------------------------------------------------------------------

1. Clone Repository
   git clone https://github.com/Ccdrisya/Yukthi.git
   cd Yukthi

2. Install Dependencies
   npm install

3. Configure Environment
   Create a .env file in the root directory:

   PORT=3000
   MONGO_URI=your_mongodb_connection_string

4. Build Frontend Assets
   npx webpack --config website/webpack.config.js

5. Start the Server
   node server.js

   Visit: http://localhost:3000/

--------------------------------------------------------------------------------
LIVE DEMO
--------------------------------------------------------------------------------

  https://yukthismc.onrender.com/

--------------------------------------------------------------------------------
KEY PAGES
--------------------------------------------------------------------------------

  Landing Page     -->  website/index.html
  Events Page      -->  website/event.html
  Intro Page       -->  website/intro.html
  Server Entry     -->  server.js
  JS Entry Point   -->  src/index.js

--------------------------------------------------------------------------------
CONTRIBUTING
--------------------------------------------------------------------------------

  1. Fork the repository
  2. Create your feature branch
  3. Commit your changes
  4. Submit a pull request

--------------------------------------------------------------------------------
LICENSE
--------------------------------------------------------------------------------

  This project is licensed under the MIT License.

--------------------------------------------------------------------------------
AUTHORS & CONTRIBUTORS
--------------------------------------------------------------------------------

  yukthismc
  Ccdrisya (Drisya C C)

  Yukthi Tech Fest — St. Mary's College, Thrissur

================================================================================
