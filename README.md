# TypeScript Boilerplate

This is a basic TypeScript boilerplate project set up with ESLint, Prettier, Jest for testing, and Git.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purposes.

### Prerequisites

Ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install project dependencies:

   ```bash
   npm install
   ```

3. Build the project:

   ```bash
   npx tsc
   ```

4. Run and watch the project:
   ```bash
   npm run start-dev
   ```

## Usage

- Start writing your TypeScript code in the `src` directory.
- Write your tests in the `src/__tests__` directory.
- Run your tests using:

  ```bash
  npx jest
  ```

- Lint your code using:

  ```bash
  npx eslint 'src/**/*.{ts,tsx}'
  ```

- Format your code using:
  ```bash
  npx prettier --write 'src/**/*.{ts,tsx}'
  ```

## Project Structure

```plaintext
project-root-directory/
|-- src/
|   |-- index.ts
|-- .eslintrc.json
|-- .gitignore
|-- .prettierrc
|-- jest.config.js
|-- package.json
|-- tsconfig.json
|-- README.md
```

## License

This project is licensed under the MIT License.
