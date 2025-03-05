📁 scm-technology-project
├── 📁 backend
│   ├── 📁 config
│   │   ├── db.js  // MongoDB Connection
│   ├── 📁 controllers
│   │   ├── authController.js  // User Authentication
│   │   ├── orderController.js  // Order Management
│   │   ├── productController.js  // Product Management
│   ├── 📁 middleware
│   │   ├── authMiddleware.js  // JWT & Role-based Access
│   ├── 📁 models
│   │   ├── Order.js
│   │   ├── Product.js
│   │   ├── User.js
│   ├── 📁 routes
│   │   ├── authRoutes.js
│   │   ├── orderRoutes.js
│   │   ├── productRoutes.js
│   ├── server.js  // Main Server File
│   ├── package.json  // Dependencies
│   ├── .env  // Environment Variables
├── 📁 frontend
│   ├── 📁 src
│   │   ├── 📁 components
│   │   │   ├── Navbar.js
│   │   │   ├── ProductList.js
│   │   │   ├── OrderTracking.js
│   │   ├── 📁 pages
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   ├── 📁 utils
│   │   │   ├── api.js  // API Calls
│   │   ├── App.js  // Main Component
│   │   ├── index.js  // React Entry Point
│   ├── package.json  // Dependencies
│   ├── .env  // Frontend Configurations
│   ├── tailwind.config.js  // Tailwind CSS
├── README.md  // Project Documentation
