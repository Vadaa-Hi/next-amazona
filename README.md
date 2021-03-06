This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
"# next-amazona"

1. Introduction
   1. What you will learn
   2. What you will build
   3. What Packages you will use
2. Install Tools
   1. VS code
   2. Chrome
   3. Node.js
   4. MongoDB
3. Create Next App
   1. npx create-next-app
   2. add layout component
   3. add header, main and footer
4. Add Styles
   1.Add css to header, main and footer

5. Fix styles

   1. Add \_documents.js
   2. Add code to fix styling issue

6. List Products

   1. Add data.js
   2. Add images
   3. Render products

7. Add header links
   1. Add cart and login link
   2. use next/link and mui/link
   3. Add css classes for header links
8. Create Product Details Page
   1. Create 3 columns
   2. Show image in first column
   3. Show product info in second column
   4. Show add to cart action on third column
   5. add styles
9. Create Product Details Page
   1. Create 3 columns
   2. Show image in first column
   3. Show product info in second column
   4. Show add to cart action on third column
   5. Add styles
10. Add MaterialUI Theme
    10 1. Create theme
    10 2. Use theme provider
    10 3. Add h1 and h2 styles
    10 4. Set theme colors
11. Create Application Context
    1. Define context and reducer
    2. Set darkMode flag
    3. Create store provider
    4. Use it on layout
12. Connect to MongoDB
    1. Install mongodb
    2. Install mongoose
    3. Define connect and disconnect
    4. Use it in the api
13. Create Products API
    1. Create product model
    2. Seed sample data
    3. Create/api/products/index.js
    4. Create product api
14. Fetch Products From API
    1. Use getServerSideProps()
    2. Get product from db
    3. Return data as props
    4. Use it in product screen too
15. Implement Add to cart
    15 1. Define cart in context
    15 2. Dispatch add to cart action
    15 3. Set click event handler for button
16. Create Cart Screen
    1. Create cart.js
    2. Redirect to cart screen
    3. Use context to get cart items
    4. List items in cart items
17. Convert Cart Screen To Dynamic Component
    16 1. Use next/dynamic
    16 2. Wrap cart in dynamic without ssr
18. Update Remove Items In Cart
    1. Implement onChange for select
    2. Show notification by notistack
    3. Implement delete button handler
19. Create Login Screen
    1. Create form
    2. Add email and password field
    3. Add login button
    4. Style form
20. Create Sample Users
    1. Create user model
    2. Add sample user in seed api
21. Build Login API
    1. Use jsonwebtoken to sign token
    2. Implement login API
22. Complete Login Screen
    1. Handle form submission
    2. Add userInfo to context
    3. Save userInfo in cookies
    4. Show user name in nav bar using menu
23. Create Register Page
    1. Create form
    2. Implement backend API
    3. Redirect user to redirect page
24. Login and Register Form Validation
    1. Install react-hoo-form
    2. Change input to controller
    3. Use notistack to show errors
25. Create Shipping Page
    1. Create form
    2. Add address fields
    3. Save in Contect and Cookies
26. Create Payment Page
    1. Create form
    2. Add radio button
    3. Save method in context
27. Create Place Order Page
    1. Display order info
    2. Show order summary
    3. Add place order button
28. Implement Place Order Action
    1. Create click handler
    2. Send ajax request
    3. Clear cart
    4. Redirect to roder screen
    5. Create backend API
29. Create Order Details Page
    1. Create API to order info
    2. Create payment, shipping ant items
    3. Create order summary
30. Pay Order By PayPal
    1. Install paypal button
    2. Use it in order screen
    3. Implement pay order API
31. Display Orders History
    1. Create orders API
    2. Show orders in profile screen
32. Update User Profile
    1. Create profile screen
    2. Create update profile API
