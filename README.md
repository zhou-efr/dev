# Zhou EFR's Portfolio

This is a portfolio website built with Next.js, TypeScript, and Tailwind CSS. It showcases my skills, experiences, certifications, and projects.

## Getting Started

First, install the dependencies:

```sh
npm install
```

Then, run the development server:

```sh
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the website.

## Content modifications
All content is stored in the `/src/data` directory. The content is stored in JSON files, and the structure of the JSON files is as follows:

```json
{
  "title": [
    {
      "item": "item",
    }
  ]
}
```

The website supports multiple languages. To add a new language, add a new directory in `/src/data` with the language code as the name. Then, add a JSON file for each section in the website. You'll also need to add the language to the path in the `generateStaticParams()` function in `/src/app/[[...lang]]/page.tsx` as well as in the `/src/data/index.ts` file.

## Building and Running in Production
To build the application, simply push to the `main` branch. The application will be built and deployed to GitHub pages automatically. 
#   d e v  
 