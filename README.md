# Get Started
Starting a new code project? Look here first to select the right technologies.

## What is this?
This is a collection of guides for starting new projects. It's a living document that will be updated as we learn more about what works and what doesn't.

## How do I use this?
1. Read the [Introduction](#introduction) to understand the philosophy behind this document.
2. Read the [Guidelines](#guidelines) to understand the criteria for selecting technologies.
3. Read the [Technologies](#technologies) to understand the technologies we use and why.
4. Read the [Resources](#resources) to find more information about the technologies we use.

## Introduction
The goal of this document is to help you select the right technologies for your project. By standardizing on a set of technologies, we can maintain a consistent codebase and make it easier to onboard new developers.

Since we jump between projects frequently, it's important that we can quickly get up to speed on a new codebase. That's why we've selected some standard technologies you *should* use, or have a good reason not to use.

## Guidelines
- We use [TypeScript](https://www.typescriptlang.org/) for all projects on web, server and IoT. It's a superset of JavaScript that adds static typing and other features. It's a great way to write code that's easier to maintain and less error-prone. Because it can be used on web, server and IoT, it's a great way to share code between projects.
- We use [React](https://reactjs.org/) for all new web projects.
- All code should be stored in GitHub, with documentation bundled in the same repository.
- We use automation to build, test and deploy our code. This ensures that we can deploy code quickly and reliably.

## Technologies
### Web
- [Next.js](https://nextjs.org/) is a framework for building web applications with React.
- [Vercel](https://vercel.com/) is a platform for hosting Next.js applications. It also supports serverless functions to link to a database or other services.

### Serverless Functions
We use serverless functions to build our backend. It's a great way to build a scalable backend without having to manage servers. Depending on what you're building, you may want to use a different service.

- [Vercel](https://vercel.com/) is a platform for hosting Next.js applications. It also supports serverless functions to link to a database or other services. Building a web frontend? Include the serverless functions in the same repository.
- [Digital Ocean App Platform](https://www.digitalocean.com/products/app-platform/) is a platform for hosting serverless functions.

### Stateful backend
Can't use a serverless function? You can use a stateful backend to run your code.

- [Digital Ocean App Platform](https://www.digitalocean.com/products/app-platform/) is a managed platform for hosting stateful backend services. It supports Node.js, Python, PHP, Ruby, Go, Java, and Docker.

### Database
Depending on your needs, you can pick between a NoSQL and SQL database. NoSQL is great for prototyping, but some more complicated queries are easier to write in SQL.

- [Firebase Firestore](https://firebase.google.com/docs/firestore) is a NoSQL database that's easy to use and scales automatically.
- [Digital Ocean Managed MySQL](https://www.digitalocean.com/products/managed-databases/) is a managed MySQL service.

### IoT
We manage IoT devices (mostly Raspberry Pis) with [Balena](https://www.balena.io/). It's a great way to manage a fleet of devices and deploy code to them. We can push code to all devices without having to physically connect to each one.

- [BalenaCloud](https://www.balena.io/cloud/) is a platform for managing IoT devices. It supports Raspberry Pi, Intel NUC, and other devices.
- [BalenaOS](https://www.balena.io/os/) is a lightweight operating system for IoT devices. It lets us run Docker containers on our devices.

### CI/CD
We use GitHub Actions for CI/CD. Services like Vercel and Digital Ocean App Platform have built-in support for GitHub Actions.

## Resources
- [TypeScript](https://www.typescriptlang.org/)
- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Vercel](https://vercel.com/)
- [Digital Ocean App Platform](https://www.digitalocean.com/products/app-platform/)
- [Firebase Firestore](https://firebase.google.com/docs/firestore)
- [Digital Ocean Managed MySQL](https://www.digitalocean.com/products/managed-databases/)
- [Balena](https://www.balena.io/)
- [BalenaCloud](https://www.balena.io/cloud/)
- [BalenaOS](https://www.balena.io/os/)
- [GitHub Actions](https://docs.github.com/en/actions)
