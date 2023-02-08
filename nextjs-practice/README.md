This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Aditional Points of Learning
## =================================================
## Next JS is a React Framework for Production whereas React JS is a javascript library for creating user interfaces

## For any other functions will have to add third-party features for example routing etc.

## NextJS takes care of all these issues which React JS has 

==================================================
## Next JS Features

# Server-side Rendering which helps with initial load flickering and Search Engine Optimization
# NextJS gives a blended experience of server-side and client-side
# Server-side rendering means preparing the content of the page being prepared in the server
# After this initial server-side rendering still it will act as Single page application and the inner navigations can be handled by React JS
# For routing in React we use React Router we basically give an illusion to users that there are multiple pages , but actually based on the url we are just rendering the components 
# on the client side and also we prevent browser from hitting the server. ie without sending a request to server
# In React js we have to write extra code for routing
# File-based routing- Define Pages and routes with files and folders instaed of code . This will result in less code, let work
# Next JS can be used to add backend code giving it full-stack capabilities
# Storing data , getting data , authentication etc can be added to your React projects
# In React js we have a public folder with an index.html. where as in next js public folder that html file is not present
# Basically next js decides which page needs to be pre-rendered
# useRouter along with functional components can be used to extract the dynamicpath segment data
# WithRouter is used along with React class components
# to capture the id from query we can use router.query.projectid
# the router.pathname will give the path only with portfolio/[projectid]
# we can have nested dynamic segments like [clientprojectid] insside [id]
#If we want to catch all routes we can use [...slug] syntax for the same
# for example we want to render the same component for all routes like blog/2022 or blog/2022/12 or blog/2022/12/2 then we need to create a js file with syntax [...id].js under blog folder
# For navigating we usually anchor tag but this will create a new http request maling the app lose any application state. If we have any app state stored within context or redux then it will be lost
# So will have to use Link from next/Link
# We will be getting a brand new html if we are using anchor tag
# To resolve this we can use Link from next/Link. and this will not create a new html page
# href can be set as an object with pathname and query
# router.push and router.replace are used to navigate dynamically
# if we want show a custom 404 page we have to create a js file with name 404.js under pages folder

