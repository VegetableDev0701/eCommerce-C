# Ciseco E-Commerce

> Discover a seamless shopping experience at our e-commerce haven. Browse an extensive selection of products from top brands, enjoy secure transactions, and relish swift deliveries. Elevate your online shopping journey with user-friendly navigation and exclusive deals. Shop effortlessly, anytime, anywhere, and redefine convenience with our digital marketplace.

## Overview

Explore curated deals and trending products on our inviting e-commerce homepage. Instantly find what you need for a delightful shopping experience.

![ciseco-ecommerce](./ciseco-ecommerce.png)

## Features

- Total **17** Pages
  - Home `x1`
  - Product Detail `x1`
  - Product Filter `x1`
  - Auth `x3`
  - Dashboard `x11`
- Authentication & Role Authorization `Admin`, `Seller` & `Buyer`
- Real-Time Cart & Update Activity
- Admin & Seller Dashboard
- Secure Channel Bypass
- Advance Search Filter
- Advance Product Filter
- Avatar, Thumbnail & Gallery Review
- Fully Responsive for `Mobile`, `Tablet`, `Laptop` & `Desktop`
- Intuitive and user-friendly design

## Tech Stack

- Framework: `Next.Js 13 App Directory`
- State Container: `Redux Toolkit`
- Styling: `Tailwind CSS`
- Icons: `React Icons`
- Database: `MongoDB`
- ORM: `Mongoose`
- Linting: `ESLint`
- Formatter: `Prettier`
- Work Management: `Asana`
- Backend Directory: `Node.Js Express Server`

## Technologies

| Client                  | Server                    |
| ----------------------- | ------------------------- |
| @reduxjs/toolkit        | bcryptjs                  |
| autoprefixer            | cloudinary                |
| eslint                  | colors                    |
| eslint-config-next      | cors                      |
| next                    | dotenv                    |
| postcss                 | express                   |
| react                   | jsonwebtoken              |
| react-dom               | mongoose                  |
| react-icons             | multer                    |
| react-redux             | multer-storage-cloudinary |
| tailwind-scrollbar-hide | validator                 |
| tailwindcss             | nodemon                   |
| @tailwindcss/forms      |

# Development

## Clone Repository

```bash
git clone https://github.com/devhasibulislam/ciseco-ecommerce.git
cd ciseco-ecommerce

cd client
yarn install

cd ..

cd server
yarn install
```

## Environment Setup

### Client Side

```bash
NEXT_PUBLIC_BASE_URL="http://localhost:8080/api"
```

### Server Side

```bash
# Port number
PORT=8080

# Origin URL
ORIGIN_URL="http://localhost:3000"

# MongoDB Atlas URI
DB_Name="ciseco-template"
ATLAS_URI="YOUR_MONGODB_ATLAS_URI"

# JWT secret
TOKEN_SECRET="JWT_TOKEN"

# Cloudinary credentials
CLOUD_NAME="CLOUDINARY_CLOUD_NAME"
API_KEY="CLOUDINARY_API_KEY"
API_SECRET="CLOUDINARY_API_SECRET"
```

# Important Links

- [x] `Client Side` Live Link: [Click Here](https://ciseco-csr.vercel.app/)
- [x] `Server Side` Live Link: [Click Here](https://ciseco-ssr.vercel.app/)
- [x] `Dashboard Reference` Link: [Click Here](https://loopinfosol.in/themeforest/ekka-html-v33/ekka-admin/index.html)
- [x] `Reference Site` Live Link: [Click Here](https://chisnghiax.com/ciseco/)

# Author

Developer: [Hasibul Islam](https://devhasibulislam.vercel.app/)
Designer: [Sadia Khanum](https://www.facebook.com/devsadiakhan)
