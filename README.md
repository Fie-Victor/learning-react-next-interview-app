### VICVIDEOCALL


## Description

Using React, Next.js, Convex, Stream, and Clerk, we built a Video Interview Call app for recruiters. A recruiter can manage and schedule interviews, then send a link to a candidate to connect to the call.  

Once connected, the candidate has access to a code editor and problems on the platform. The candidate can share their screen and attempt to resolve the problems online.  

The app is deployed on Vercel. Check it out here: [Here][project-link] 

### Role of Each Technology:

- **[React][react-link]**: We use React as the core framework for designing the UI.  
- **[Next.js][nextjs-link]**: We use Next.js to handle backend tasks, and it works seamlessly with React.  
- **[Convex][convex-link]**: Convex is our database provider, used to store our data online.  
- **[Clerk][clerk-link]**: Clerk handles authentication and user connection, so we don't have to manage those concerns.  
- **[Stream][stream-link]**: Stream provides all the necessary features for video call functionality.  

---




## Getting Started (if you want to try it locally)

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


Second, as we use convex as dataBase, ( in your local env):

```bash
npx convex dev
```



This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

We deployed it on vercel, try it here: [App Video](https://learning-react-next-interview-app.vercel.app/)

### Links  

- [Project Link][project-link]  
- [React][react-link]  
- [Next.js][nextjs-link]  
- [Convex][convex-link]  
- [Clerk][clerk-link]  
- [Stream][stream-link]  

[project-link]: https://learning-react-next-interview-app.vercel.app/  
[react-link]: https://react.dev  
[nextjs-link]: https://nextjs.org  
[convex-link]: https://convex.dev  
[clerk-link]: https://clerk.dev  
[stream-link]: https://getstream.io  

