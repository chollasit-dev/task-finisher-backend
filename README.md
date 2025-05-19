# Task Finisher Backend

A back-end part of Task Finisher, a complete CRUD TODO app featuring minimal,
clean, easy-to-use interface.

The purpose of this app is primarily for personal uses (may available for few
users testing) to streamline my task managing and note taking. This project is a
part of my JavaScript/TypeScript learning journey for both front-end and
back-end development in JSD9 bootcamp program.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [pnpm](https://pnpm.io/)

### Installation

Clone the repository and install dependencies:

```sh
git clone https://github.com/chollasit-dev/task-finisher-backend.git &&
cd task-finisher-backend &&
pnpm install
```

### Environment Setup

1. create `.env` to define an initial variable for loading environment
   dynamically when developing:

```sh
NODE_ENV=development

# Or for production (testing)
NODE_ENV=production
```

2. Copy the example environment file:

```sh
#
cp .env.example .env.local

# Or for production (testing)
cp .env.example .env.production
```

3. Edit either `.env.local` or `.env.production` and fill in your actual
   configuration values:

### Start the development server

Will restart on file changes for `.env*` and `src/**`

```sh
pnpm dev
```

### Run the production server

```sh
pnpm start
```

## Testing

```sh
pnpm test
```

Or if you want it to watch for changes:

```sh
pnpm test:watch
```
