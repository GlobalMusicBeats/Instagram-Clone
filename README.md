<div align="center">

  <img src="https://user-images.githubusercontent.com/99184393/195982647-048bc778-f82d-427c-b28b-78b1156d158d.png" alt="logo" width="205" height="auto" />
  
  <h1>Instagram Clone with React.JS</h1>
  
  <p>
Instagram 2.0 with REACT.JS! (Next.js, NextAuth.js v4.17.0, Tailwind CSS, Firebase v9, Image Uploading, Google Authentication,, Instagram Profile)
  </p>
  
  
<!-- Badges -->

<a href="https://projects-seven-peach.vercel.app" target="_blank">![](https://img.shields.io/website-up-down-green-red/http/monip.org.svg)</a>
![](https://img.shields.io/badge/Maintained-Yes-indigo)
![](https://img.shields.io/github/forks/SashenJayathilaka/Instagram-Clone.svg)
![](https://img.shields.io/github/stars/SashenJayathilaka/Instagram-Clone.svg)
![](https://img.shields.io/github/issues/SashenJayathilaka/Instagram-Clone)
![](https://img.shields.io/github/last-commit/SashenJayathilaka/Instagram-Clone)

<h4>
    <a href="https://projects-seven-peach.vercel.app">View Demo</a>
  <span> · </span>
    <a href="https://github.com/SashenJayathilaka/Instagram-Clone/blob/master/README.md">Documentation</a>
  <span> · </span>
    <a href="https://github.com/SashenJayathilaka/Instagram-Clone/issues">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/SashenJayathilaka/Instagram-Clone/issues">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  - [Screenshots](#camera-screenshots)
  - [Tech Stack](#space_invader-tech-stack)
  - [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  - [Prerequisites](#bangbang-prerequisites)
  - [Installation](#gear-installation)
  - [Run Locally](#running-run-locally)
  - [Deployment](#triangular_flag_on_post-deployment)
- [Contact](#handshake-contact)

<!-- About the Project -->

## :star2: About the Project

<!-- Screenshots -->

### :camera: Screenshots

<div align="center">
<a href="https://projects-seven-peach.vercel.app/" target="_blank"><img  src='https://user-images.githubusercontent.com/99184393/188783926-2478a323-2472-4b4e-ae49-583e88700848.gif' alt='image'/></a>
</div>

## <a href="https://projects-seven-peach.vercel.app" target="_blank">LIVE DEMO 💥</a>

![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)
![forthebadge](https://forthebadge.com/images/badges/for-you.svg)
![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)

### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://#/">Typescript</a></li>
    <li><a href="https://nextjs.org/">Next.js</a></li>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://tailwindcss.com/">TailwindCSS</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://firebase.google.com">Firebase</a></li>
  </ul>
</details>
<br />

<table>
    <tr>
        <td>
<a href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="" width="30" height="30" /></a>
        </td>
                        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/183096870-fdf58e59-d78c-44f4-bd1c-f9033c16d907.png" alt="Google" width="30" height="30" /></a>
        </td>
                        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/179383376-874f547c-4e6f-4826-850e-706b009e7e2b.png" alt="" width="30" height="30" /></a>
        </td>
                        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/180462270-ea4a249c-627c-4479-9431-5c3fd25454c4.png" alt="" width="30" height="30" /></a>
        </td>
                                <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/177784603-d69e9d02-721a-4bce-b9b3-949165d2edeb.png" alt="" width="30" height="30" /></a>
        </td>
                                <td>
<a href="#"><img src="https://raw.githubusercontent.com/atulmy/oauth/master/web/public/images/social/instagram.svg" alt="" width="30" height="30" /></a>
        </td>
    </tr>
</table>

## :toolbox: Getting Started

### :bangbang: Prerequisites

- Sign up for a Firebase account <a href='https://firebase.google.com'>HERE</a>
- Install Node JS in your computer <a href='https://nodejs.org/en/'>HERE</a>

<!-- Env Variables -->

### :key: Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXTAUTH_URL`

`GOOGLE_CLIENT_ID`

`NEXT_PUBLIC_SECRET`

`GOOGLE_CLIENT_SECRET`

`NEXT_PUBLIC_BASE_URL`

`NEXT_PUBLIC_FIREBASE_APP_ID`

`NEXT_PUBLIC_FIREBASE_API_KEY`

`NEXT_PUBLIC_FIREBASE_PROJECT_ID`

`NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN`

`NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET`

`NEXT_PUBLIC_FIREBASE_MESSAGING_SET`


### :gear: Installation

Install my-project with npm

```
npx create-next-app instagram_clone
```

```
cd instagram_clone
```

Install dependencies

### :test_tube: Install Tailwind CSS with Next.js

#### Install Tailwind CSS

Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both `tailwind.config.js` and `postcss.config.js`.

```
npm install -D tailwindcss postcss autoprefixer
```

```
npx tailwindcss init -p
```

#### Configure your template paths

Add the paths to all of your template files in your `tailwind.config.js` file.
<br>

```
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

#### Add the Tailwind directives to your CSS

Add the `@tailwind` directives for each of Tailwind’s layers to your `./styles/globals.css` file.

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Install dependencies

<a href="https://github.com/SashenJayathilaka/Instagram-Clone/blob/master/package.json" target="_blank">🔶 Other Dependency Info</a>

<!-- Run Locally -->

### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/SashenJayathilaka/Instagram-Clone.git
```

Install dependencies
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

```bash
  npm install
```

## Getting Started

Start the server
First, run the development server:

```bash
  npm run dev
```

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

<!-- Deployment -->

### :triangular_flag_on_post: Deployment

To deploy this project run

##### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## :handshake: Contact

Your Name - [@twitter_handle](https://twitter.com/SashenHasinduJ) - sashenjayathilaka95@gmail.com

Project Link: [https://github.com/SashenJayathilaka/Instagram-Clone.git](https://github.com/SashenJayathilaka/Instagram-Clone.git)

<hr />

<div align="center">
<a href="https://projects-seven-peach.vercel.app/" target="_blank"><img  src='https://user-images.githubusercontent.com/99184393/195737045-7c3e9b89-b961-4bc5-9d69-61d2a76176ea.png' alt='image'/></a>
</div>

<br />

<div align="center">Don't forget to leave a star ⭐️</div>
