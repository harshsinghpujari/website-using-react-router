# Website Using React Router

This is a React-based website built to practice and demonstrate routing with **React Router**. It includes multiple sections like Home, About, Contact, and a special GitHub section that dynamically fetches your GitHub profile data. The project is structured with a Layout and uses modern React Router features including loaders and nested routing.

## 🚀 Features

- React Router v6 setup
- Navigation using `Link`
- Layout with `Outlet` for nested routing
- **GitHub section**:
  - Fetches profile picture
  - Displays follower count
  - Uses `loader` to pre-fetch data
- Simple, component-based structure
- Clean page organization

## 🌐 Live Demo

👉 [https://website-using-react-router.netlify.app/](https://website-using-react-router.netlify.app/)

## 📂 Project Structure

src/
components/
Header.jsx
pages/
Home.jsx
About.jsx
Contact.jsx
Github.jsx
Layout.jsx
main.jsx


## 🛠️ Tech Stack

- React
- React Router DOM
- Vite (as the build tool)
- GitHub REST API (for profile data)

## 💻 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/harshsinghpujari/website-using-react-router.git
```

2. **Install dependencies:**

```bash
npm install

```


3. **Run the development server:**

```bash
npm run dev
```


🎯 Learning Goals

    Implement React Router v6 with nested routes using Outlet

    Understand how to use the loader pattern to fetch data before rendering

    Practice dynamic API calls to GitHub’s REST API

    Gain confidence in building a simple multi-page React site with reusable layouts


📝 License

This project is open-source and free to use for learning.
