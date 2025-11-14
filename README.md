# Blog Frontend

This is the frontend of TheOdinProject's Blog API. The focus of this project was to 
learn about API's basics and security. Prior to this project I was creating the backend and frontend
in one directory but I have split the two for this one and made a API only backend.

## Features

- Creating, Login and Logging out users.
- View post.
- Users can add comments to post.

## Getting Started

### Prerequisties

In order for the frontend to function you will need the backend up and running.
- https://github.com/GravityCodes/blog-back-end

1. Clone the repository to your local machine
```sh
git clone git@github.com:GravityCodes/blog-front-end.git
```
2. Navigate to the project directory
```sh
cd blog-front-end
```
3. Install the required dependencies
```sh
npm install
```
4. Setup environement variables.(take a look at .env.examples)

5. Start the development server
```sh
npm run dev
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

# Tech Used

- [Astro](https://astro.build/) - Web Framework used in this project.
- [editorjs-html](https://github.com/pavittarx/editorjs-html) - Parse Editor.js clean data to html.
