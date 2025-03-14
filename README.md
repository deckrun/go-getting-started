# Getting Started with Go on Deckrun

This is an example of an application that uses Go and Deckrun to build and deploy a simple web server.

## Prerequisites

- Deckrun CLI installed and set up
- Docker installed
- A Cluster created on Deckrun

## Deploy the Application

### 1. Clone this repository

```bash
git clone git@github.com:deckrun/go-getting-started.git
```

### 2. Change into the project directory

```bash
cd go-getting-started
```

### 3. Create a New App on Deckrun

```bash
deck init
```

### 4. Deploy the application

```bash
deck deploy
```

### 5. Open the application in your browser

Use the URL provided in the output of the `deck deploy` command
