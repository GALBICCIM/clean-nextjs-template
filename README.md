# Next.js Tailwind CSS Starter

This project provides a ready-made starter template for **Next.js** developers, pre-configured with **Tailwind CSS** for seamless styling.

## Installation

1. Clone this repository and remove existing git history:

```bash
git clone <url> my-project
cd my-project
rm -rf .git
```

2. Install dependencies:

```bash
npm i
```

3. Configure Prettier by creating a `.prettierrc` file in the project root:

```json
// .prettierrc

{
	// Add other settings as needed (e.g., tabWidth, printWidth)
	"plugins": ["prettier-plugin-tailwindcss"],
	"tailwindStylesheet": "./src/app/globals.css"
}
```

4. Start the development server:

```bash
npm run dev
```

Enjoy your development!
