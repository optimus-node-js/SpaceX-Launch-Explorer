# 🚀 SpaceX Launch Explorer

A React-based web application to explore SpaceX launches with advanced features like sorting, filtering, searching, and pagination. Built with React, Vite, TypeScript, Mantine UI, Zustand for state management, and powered by the SpaceX API.

![SpaceX Launch Explorer Screenshot](https://res.cloudinary.com/dnqvg9dhl/image/upload/v1727381662/Untitled_ysr63j.png)

## 🛠 Features

- **Launch Listings**: View a list of SpaceX launches with search, filter, and sort capabilities.
- **Launch Details**: Detailed view of individual launches, including information about the rocket, success status, and links to resources like webcast, articles, and Wikipedia.
- **Pagination**: Efficient pagination with customizable page size.
- **Search & Filter**: Search for launches by name and filter by success/failure status.
- **Sorting**: Sort launches by ascending or descending date.
- **Authentication**: Token-based authentication for accessing private routes.
- **Responsive Design**: Fully responsive UI for all screen sizes.
- **State Management**: Zustand for managing global state in a scalable and performant way.

## 🎨 Tech Stack

- **Frontend**: React, TypeScript, Vite
- **UI Components**: Mantine UI, Axios, React-Query
- **State Management**: Zustand
- **API**: SpaceX API v4
- **Backend** (To be implemented): MongoDB for session management, token-based authentication

## 📂 Directory Structure

```
.
├── .env
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
├── vite.config.ts
└── src
    ├── App.scss
    ├── App.tsx
    ├── main.tsx
    ├── style.scss
    ├── vite-env.d.ts
    ├── components
    │   └── Logout.tsx
    ├── pages
    │   ├── Landing.tsx
    │   ├── Login.tsx
    │   ├── SpaceXDetailPage.tsx
    │   ├── SpaceXResourceList.tsx
    │   └── css
    │       ├── Landing.scss
    │       ├── SpaceXDetailPage.scss
    │       └── SpaceXResourceList.scss
    ├── routes
    │   └── PrivateRoute.tsx
    ├── store
    │   ├── auth.store.ts
    │   ├── launch.store.ts
    │   └── ui.store.ts
    ├── styles
    │   └── abstracts
    │       ├── _colours.scss
    │       ├── _fonts.scss
    │       └── index.scss
    └── theme
        └── index.ts

```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (>= 14.x)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/optimus-node-js/SpaceX-Launch-Explorer.git
cd spacex-launch-explorer
```

2. Install dependencies:

```bash
npm install
# OR
yarn install
```

3. Set up environment variables by creating a `.env` file in the root directory:

```
VITE_SPACEX_API_URL=https://api.spacexdata.com/v4
```

### Running the Application

To start the application locally:

```bash
npm run dev
```

Then open [http://localhost:5175](http://localhost:5175) to view the application in your browser.

### Production Build

To build the application for production:

```bash
npm run build
```

### Linting

Lint the code for consistent formatting:

```bash
npm run lint
```

## 🧑‍💻 API Integration

We use the SpaceX API to fetch launch data. Here are the key API routes used in the project:

- `GET /launches` – Fetches all launches.
- `GET /launches/:id` – Fetches details of a specific launch.

## 🛠 Authentication

- Token-based authentication has been implemented for securing private routes.
- User session data is stored securely in MongoDB.

## 🎯 Bonus Features

- **Gallery Images**: View images related to rockets on the SpaceX detail page.
- **Fairing and Core Details**: View fairing and core information for each launch.
- **Back Navigation**: Easily navigate back to the resource list using the back button on the detail page.

## 🧪 Testing (Planned)

We plan to integrate testing using:
- Jest for unit testing.
- Cypress for end-to-end testing.

---

### 🌟 Contributions

We welcome contributions! Please fork the repository and create a pull request if you’d like to contribute.

---

### 📬 Contact

If you have any questions or suggestions, feel free to reach out:

- **GitHub**: [Rahul Vishwakarma](https://github.com/optimus-node-js)
- **Email**: karmarahul67@gmail.com

---

## 👤 Author

**Rahul Vishwakarma** — Senior Full Stack Developer · Ahmedabad, India

[![Portfolio](https://img.shields.io/badge/Portfolio-rahul--vishwakarma--portfolio.vercel.app-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://rahul-vishwakarma-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Vishwakarma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-vishwakarma-101346192)
[![Email](https://img.shields.io/badge/Email-karmarahul67%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karmarahul67@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-optimus--node--js-181717?style=flat-square&logo=github)](https://github.com/optimus-node-js)

If you find this project useful, consider giving it a ⭐.
