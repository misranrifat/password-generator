# Password Generator

A secure and user-friendly password generator web application that provides multiple password generation modes to meet different security needs.

## Live Demo

Try the password generator online: [https://password-generator-ch1.pages.dev/](https://password-generator-ch1.pages.dev/)

## Features

- **Multiple Generation Modes**:
  - Random: Generate cryptographically secure random passwords
  - Memorable: Create passwords using common words for easier memorization
  - PIN: Generate numeric PIN codes

- **Customizable Options**:
  - Adjustable password length (4-64 characters)
  - Toggle numbers inclusion
  - Toggle symbols inclusion
  - Real-time password generation

- **User Interface**:
  - Clean, modern design
  - Responsive layout for mobile and desktop
  - One-click copy to clipboard
  - Instant password refresh

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd password-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Development Mode

Run the application in development mode with auto-restart:

```bash
npm run dev
```

### Production Mode

Start the application in production mode:

```bash
npm start
```

The application will be available at `http://localhost:3000`


## Security Features

- Client-side password generation (no server-side storage)
- Cryptographically secure random number generation
- No password transmission over network
- Immediate clipboard clearing after copy