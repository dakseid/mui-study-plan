# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is enabled on this template. See [this documentation](https://react.dev/learn/react-compiler) for more information.

Note: This will impact Vite dev & build performances.

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

mui-study-plan/
│── README.md                 # Overview, study plan, resources
│── package.json              # Dependencies (React + MUI)
│── src/
│   ├── index.js              # Entry point
│   ├── App.js                # Main app wrapper
│   ├── theme.js              # Custom theme setup
│   │
│   ├── week1/
│   │   ├── day1-basics/      # Typography + theme practice
│   │   ├── day2-layouts/     # Grid & Box layouts
│   │   ├── day3-buttons/     # Buttons + navbar
│   │   ├── day4-forms/       # Login & signup forms
│   │   ├── day5-cards/       # Product card
│   │   ├── day6-dialogs/     # Shopping cart drawer
│   │   └── day7-landing/     # Mini project: landing page
│   │
│   ├── week2/
│   │   ├── day8-tables/      # User table w/ avatars
│   │   ├── day9-theming/     # Dark mode toggle
│   │   ├── day10-navigation/ # Tabs + dashboard nav
│   │   ├── day11-styling/    # SX prop + styled components
│   │   ├── day12-animations/ # Collapse + transitions
│   │   ├── day13-dashboard/  # E-commerce dashboard setup
│   │   └── day14-final/      # Final project: dashboard
│   │
│   └── components/           # Reusable components
│       ├── Navbar.js
│       ├── Footer.js
│       ├── ProductCard.js
│       └── CustomDialog.js
│
└── public/
    └── index.html


📅 2-Week MUI (Material UI) Study Plan
Week 1: Foundations + Core Components

Day 1 – Setup & Basics

Install MUI in a React project (npx create-react-app mui-demo or Next.js).

Explore themes, typography, and color system.

Practice: Create a homepage with a custom theme + typography styles.

Day 2 – Layouts & Grids

Learn Box, Container, Grid, Stack for layouts.

Practice: Build a responsive 2-column layout with a header and footer.

Day 3 – Buttons & Icons

Work with Button, IconButton, Fab (Floating Action Button).

Practice: Create a navigation bar with buttons and icons.

Day 4 – Forms & Inputs

Learn TextField, Checkbox, Radio, Switch, Select, Autocomplete.

Practice: Build a login + signup form using form inputs.

Day 5 – Cards & Lists

Work with Card, CardContent, CardActions, List, ListItem.

Practice: Create a product card (image, title, price, button).

Day 6 – Dialogs & Modals

Learn Dialog, Drawer, Snackbar, Tooltip.

Practice: Build a shopping cart drawer that slides in from the side.

Day 7 – Mini Project 1
👉 Build a Responsive Landing Page

Navbar with logo + menu

Hero section with button

Features grid with cards

Footer

Week 2: Advanced Topics + Real Projects

Day 8 – Data Display

Explore Table, DataGrid, Avatar, Badge, Chip.

Practice: Create a user list table with avatars and actions.

Day 9 – Advanced Theming

Learn about custom themes, dark mode, theme overrides.

Practice: Add dark mode toggle to your app.

Day 10 – Navigation

Learn Tabs, BottomNavigation, Breadcrumbs.

Practice: Build a tabbed dashboard with 3 sections.

Day 11 – Styling Approaches

Learn SX prop, styled(), global styles, emotion.

Practice: Recreate your landing page using the sx prop.

Day 12 – Animations & Transitions

Use Collapse, Fade, Grow, Slide, Zoom transitions.

Practice: Animate a card list on load.

Day 13 – Integration Project Setup
👉 Start a Mini E-Commerce Dashboard

Sidebar navigation (Drawer + List)

Dashboard cards (sales, users, revenue)

DataGrid for product list

Day 14 – Final Project Completion
👉 Finish your E-Commerce Dashboard

Add dark mode toggle

Add product modal (Dialog)

Add responsive design with Grid & Stack