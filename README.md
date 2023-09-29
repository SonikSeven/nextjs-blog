# Next.js Blog

## Overview

This project is a Next.js blog that showcases the simplicity and power of Next.js for creating a server-rendered personal blog. The blog features a homepage, an about section, and dynamic routes for individual blog posts. Built using Next.js, it leverages static generation for pages and incorporates styling with CSS modules for a modular and scalable approach to styling.

## Features

- **Next.js Framework**: Built on top of Next.js for server-side rendering and static site generation.
- **Dynamic Routes**: Utilizes Next.js dynamic routes for blog posts.
- **Static Generation**: Pre-renders pages at build time using `getStaticProps` and `getStaticPaths`.
- **CSS Modules**: Leverages CSS modules for component-level styling.
- **Responsive Design**: Ensures the blog looks great on all devices.

## Requirements

- [Node.js](https://nodejs.org/)

## Installation

1. **Clone the repository**

```
git clone https://github.com/SonikSeven/nextjs-blog.git
```

2. **Navigate to the project directory**

```
cd nextjs-blog
```

3. **Install dependencies**

```
npm install
```

4. **Run the development server**

```
npm run dev
```

Navigate to [http://localhost:3000](http://localhost:3000) to view the blog.

## Structure

- `pages/api/hello.js`: API endpoint returning a simple JSON response.
- `pages/_app.js`: Main app component that wraps around every page. Includes global CSS.
- `pages/index.js`: The homepage that lists all blog posts and a brief introduction.
- `pages/posts/[id].js`: Dynamic route for individual blog posts.
- `lib/posts.js`: Utility functions to fetch and sort blog posts data.

## About

This project is based on the [Learn Next.js](https://nextjs.org/learn) tutorial by Next.js. It implements concepts and features learned from the tutorial to create a Next.js blog web application.

## License

This project is licensed under the [CC-BY 4.0 License](LICENSE.txt).
