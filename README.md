# Portfolio

Root of my portfolio website combining the client frontend and server backend.

[![Node][node shield]][node website]
[![TypeScript][typescript shield]][typescript website]
[![react][react shield]][react website]
[![React Router][react router shield]][react router website]
[![Express][express shield]][express website]
[![SASS][sass shield]][sass website]
[![TailwindCSS][tailwind shield]][tailwind website]
[![Vite][vite shield]][vite website]
[![Prettier][prettier shield]][prettier website]
[![ESLint][eslint shield]][typescript eslint website]
[![npm][npm shield]][npm website]
![Git][git shield]
[![GitHub][github shield]][github repo]

## Client frontend

The frontend contains 4 navigable pages and an error page and implements a
[react][react website] based interface utilizing [TailwindCSS][tailwind website]
for its styling. Below is a breakdown of the frontend webpages or more info can
be found (if available) in the [client frontend repo][client frontend github repo]:

- ### About page

  The About page contains a short relatively candid description of myself and
  interests and a little bit about my history.

- ### Portfolio page

  The Portfolio page contains a list of projects I have worked on with short
  descriptions of each project and links to their respective GitHub repositories
  and deployed versions if applicable.

- ### Contact page

  The Contact page provides a form that allows users to message me in addition
  to an email address I can be contacted at. The form requires a name, an email
  address and/or a phone number for reply purposes, and the message to be sent
  to me.

- ### Resume page

  The Resume page contains more specific information about which technologies I
  have experience with, what features I implemented and was responsible for in
  the projects I worked on, and my qualifications and work experience.

- ### Error page

  The error page is displayed when a user navigates to a page that does not exist.

## Server backend

The backend is an [express][express website] server providing the sole
functionality of sending a message when the [contact page](#contact-page)'s
message form is submitted. More info (if available) can be found in the
[server backend repo][server backend github repo].

## Scripts

This package contains 4 scripts useful for development:

- `npm run dev`

  Runs both the react client front end and express backend locally.

- `npm run build`

  Builds the client front end and server backend distributable packages.

- `npm run clean`

  Deletes the build output directories.

- `npm run react`

  Runs only the react client frontend locally.

- `npm run express`

  Runs only the express server backend locally.

- `npm start` and `npm run start`

  Builds the distributable react frontend and express server backend packages
  and starts the express server.

[node shield]: https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white "node"
[node website]: https://nodejs.org/en/about "node"
[typescript shield]: https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white "TypeScript"
[typescript website]: https://www.typescriptlang.org/ "TypeScript"
[sass shield]: https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white "SASS"
[sass website]: https://sass-lang.com/ "SASS"
[react shield]: https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB "React"
[react website]: https://react.dev/ "React"
[react router shield]: https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white "React Router"
[express shield]: https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB "Express"
[express website]: https://expressjs.com/ "Express"
[react router website]: https://www.npmjs.com/package/react-router "React Router"
[tailwind shield]: https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white "TailwindCSS"
[tailwind website]: https://tailwindcss.com "TailwindCSS"
[vite shield]: https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white "Vite"
[vite website]: https://vitejs.dev "Vite"
[prettier shield]: https://img.shields.io/badge/prettier-ff69b4.svg?style=for-the-badge&logo=prettier&logoColor=white "Prettier"
[prettier website]: https://prettier.io/ "Prettier"
[eslint shield]: https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white "TypeScript ESLint"
[typescript eslint website]: https://typescript-eslint.io/ "TypeScript ESLint"
[npm shield]: https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white "npm"
[npm website]: https://www.npmjs.com/ "npm"
[git shield]: https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white "Git"
[github shield]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white "github"
[github repo]: https://github.com/SnapperGee/portfolio "GitHub repo"
[client frontend github repo]: https://github.com/SnapperGee/portfolio-client "Client frontend GitHub repo"
[server backend github repo]: https://github.com/SnapperGee/portfolio-server "Server backend GitHub repo"
