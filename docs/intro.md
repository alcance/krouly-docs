---
sidebar_position: 1
---

# Tutorial Intro

Let's discover **Krouly in 10 minutes**.

## Getting Started

Get started by **[cloning a new repository to your prefered environment](https://www.github.com/kroulyhq/krouly)**.

Or try, (coming soon) **[Krouly Cloud](https://krouly.ai/login)**.

```bash
git clone git@github.com:kroulyhq/krouly.git
```

### What you'll need

- [Go](https://go.dev/dl/) version 18.0 or above:
  - When installing Go, make sure you have your GOPATH configured and install dependencies.

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

> To install dependencies in Go you can use: `go mod tidy` inside the folder

## Generate a new client

Generate a new Krouly client using the **default template**.

The classic template will automatically be added to your project inside `client` folder after you run the command:

```bash
krouly create app-name
```

You can type this command into Command Prompt preferebly within each service folder for now to avoid errors.

The command also installs all necessary dependencies you need to run Krouly.

## Start client

Run the development server:

```bash
cd ..
cd client/app-name/webapp
krouly run app-name
```

The `cd` command changes the directory you're working with. In order to work with your newly created Krouly site, you'll need to navigate the terminal there.

The `krouly run app-name` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

At this point you have a completed web app inside `client/app-name/webclient`, you can use the `useKroulyStorage` custom hook to retrieve data from the source that will be setup in the next chapter.