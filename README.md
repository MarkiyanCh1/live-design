# ![Figma](/public/assets/favicon.ico) Live Design

[![Figma](/public/assets/logo.svg)](https://github.com/MarkiyanCh1/live-design)

Welcome to the real-time Figma Clone project!

This project aims to replicate the functionality of Figma with real-time collaboration features using a stack of popular technologies including Next.js, TypeScript, Liveblocks, Fabric.js, Shadcn, and Tailwind CSS.

This collaborative design platform empowers users with multi-cursor functionality, real-time chat, reaction expressions, active user monitoring, comment annotations, shape creation, image integration.

## 🌐 Live Website

- The application is live and hosted on Vercel. You can access it [here](https://livedesign.vercel.app/).

## 📸 Screenshot

- Live Design
  ![Figma Page](/public/screenshot.png)

## 🌟 Features

- **Multi Cursors**: See where other users are editing in real-time.
- **Cursor Chat**: Communicate with collaborators through cursor chat.
- **Reactions**: React to changes and collaborate with expressive reactions.
- **Active Users**: See who else is currently editing the canvas.
- **Comment Bubbles**: Leave comments and annotations directly on the canvas.
- **Creating Different Shapes**: Draw and create various shapes on the canvas.
- **Uploading Images**: Easily upload images to the canvas for reference or design elements.
- **Customization**: Customize elements and shapes according to your design needs.
- **Freeform Drawing**: Sketch and draw freely on the canvas.
- **Undo/Redo**: Easily undo or redo actions to fine-tune your designs.
- **Keyboard Actions**: Perform actions quickly using keyboard shortcuts.
- **History**: View the history of changes made on the canvas.
- **Deleting**: Remove unwanted elements from the canvas.
- **Scaling**: Scale elements for precise adjustments.
- **Moving**: Easily move elements around the canvas.
- **Clearing**: Clear the canvas to start fresh.
- **Exporting Canvas**: Export your designs for further use or sharing.

## 🎹 Hotkeys

- **/**: Open live cursor chat
- **e**: Open reactions
- **esc**: Close
- **ctrl+z**: Undo
- **ctrl+y**: Redo
- **ctrl+c**: Copy
- **ctrl+v**: Paste

## 🛠️ Technologies Used

- **NextJS 14**: A React framework for building server-rendered and static websites, offering features like routing, data fetching, and image optimization.
- **TypeScript**: A superset of JavaScript that adds optional static typing for better code maintainability and catching errors early.
- **TailwindCSS**: A utility-first CSS framework that provides a rapid way to style web applications.
- **Shadcn**: A collection of beautifully designed re-usable components that you can copy and paste into your apps.
- **Liveblocks**: Enables real-time collaboration features in web applications, allowing multiple users to edit and interact with the same data simultaneously.
- **Fabric**: A JavaScript library for working with vector graphics on web pages, facilitating creation, manipulation, and interaction with shapes and objects.
- **Jspdf**: A client-side JavaScript library used to generate PDF documents directly in the browser, allowing users to download or print data in PDF format.

## 🚀 Installation

To install and run this project locally on your machine, follow the steps below.

1. Clone the repository:

```bash
git clone https://github.com/MarkiyanCh1/live-design.git
```

2. Navigate into the project directory:

```bash
cd live-design
```

3. Install dependencies:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
```

4. Start the application:

```bash
npm run dev
```

The application will start running on http://localhost:3000.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## If you find this project useful, please consider giving it a star ⭐. Your support is greatly appreciated!

Happy coding! 💻
