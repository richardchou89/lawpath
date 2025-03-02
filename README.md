This project has been deployed to Vercel. Test it [here](https://lawpath-konami99s-projects.vercel.app/).

It can also be started from local.

# Local installation

1. Clone into your local
2. `npm install`
3. `npm run dev`

The app should start running on port 3000.

![image](https://github.com/user-attachments/assets/39982ab0-5294-4656-8df1-2a3de187d7cf)

# Basic structure

![image](https://github.com/user-attachments/assets/ed633131-5f51-4a01-b9c5-0d023973c7d7)

Frontend: frontend is a standard Nextjs app.

GraphQL server: is mounted on API routes by using `@as-integrations/next` package.

Proxy: proxy class is created by extending `RESTDataSource` from `@apollo/datasource-rest` package.

# Design

This project was styled by using Tailwindcss, and is responsive.

Mobile view:

![image](https://github.com/user-attachments/assets/33e1fd93-327a-44af-86c5-15577023a97a)

Desktop view:

![image](https://github.com/user-attachments/assets/79554e2c-7966-4019-92a3-92063e51373a)
