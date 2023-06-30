# Netlify/React: Starter Cloud template

This template demonstrates how to deploy a React Single-Page Application (SPA) to Netlify. This React code sample builds the API server using the React Router 6 library.

Visit the ["Netlify Security: Developer Guides"](https://developer.auth0.com/resources/guides/cloud/netlify) section of the ["Auth0 Developer Resources"](https://developer.auth0.com/resources) to explore how you can deploy secured applications with Auth0 to Netlify.

## Why Use Auth0?

Auth0 is a flexible drop-in solution to add authentication and authorization services to your applications. Your team and organization can avoid the cost, time, and risk that come with building your own solution to authenticate and authorize users. We offer tons of guidance and SDKs for you to get started and [integrate Auth0 into your stack easily](https://developer.auth0.com/resources/code-samples/full-stack).

## Set Up and Run the React Project

Install the project dependencies:

```bash
npm install
```

For simplicity and convenience, the starter React consumes data from a message service to hydrate the user interface.

Execute this command to run your React application:

```bash
npm run dev
```

Visit [`http://localhost:8888/`](http://localhost:8888/) to access the starter application.

In the starter project, all the starter React application routes are public. However, you can use Auth0 to get an ID token to hydrate the user profile information present on the `/profile` page with information from a real user. With Auth0, you can also get an access token to make a secure call to an external API to hydrate the messages present in the `/protected` and `/admin` pages.
