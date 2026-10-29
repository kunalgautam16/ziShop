
# ZiShop - E-commerce Website

ZiShop is an e-commerce website built using Next.js, TypeScript, and Tailwind CSS. Users can browse products, manage their shopping cart, save favorites, and create an account.

## Technologies Used

- Next.js
- React.js
- TypeScript
- Redux Toolkit
- Tailwind CSS
- Sanity.io

## Features

- Responsive user interface
- Product listing and product details
- User login and signup
- Shopping cart management
- Favorites list
- Dark and light themes
- English and Persian language support
- Product management using Sanity.io

## Pages

- Home
- Login and Signup
- Products
- Product Details
- Shopping Cart
- Favorites
- About

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/kehyshow/E-Commerce-OnlineShop.git
cd E-Commerce-OnlineShop
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Sanity.io

Create a project on Sanity.io and obtain the project ID and API token.

Add the project ID to `lib/client.ts`.

Create a `.env` file in the root directory and add the required token:

```env
NEXT_PUBLIC_SANITY_TOKEN=your_token_here
```

Use the environment variable name expected by the project code. Never commit API tokens or secrets to GitHub.

### 4. Start Sanity Studio

Open a terminal in the Sanity project directory and run:

```bash
sanity start
```

### 5. Run the Development Server

From the project root, run:

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

## Contributing

Contributions are welcome. You can fork the repository, make changes, and submit a pull request.
