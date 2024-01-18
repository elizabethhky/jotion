# Welcome to Jotion!
This project was created and closely follows the [tutorial](https://www.youtube.com/watch?v=0OaDyjB9Ib8&t=364s) by CodeWithAntonio. 
Please check out his work and support his channel! 

My account on Notion ran out of space...so I created a replica!
It is officially deployed [here](https://jotion-taupe.vercel.app/), so check it out if you'd like 😊

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## For Local Deployment
### Requirements
Please set up an account for the following softwares if you have not already done so:
* [Convex](https://www.convex.dev/) - the backend software for this project
* [Clerk](https://clerk.com/) - for user authentication
* [Edgestore](https://edgestore.dev/) - for uploading files

### Steps 
1. Create a copy of the `.env.sample` file and rename it to be `.env.local` in your root directory.
2. Find the values for the following variables in the above websites and paste them in your `.env.local` file.
3. Run the development server using `npm run dev`.
4. Open a new terminal and run the backend server using `npx convex dev`.
5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## For Production
### Requirements
The app is deployed using [vercel](https://vercel.com/). Set up an account there if you have not done so.

### Steps
You may follow a detailed tutorial [here](https://docs.convex.dev/production/hosting/vercel) on to deploy this app with vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/)
