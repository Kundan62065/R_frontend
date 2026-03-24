# React + Vite



#######################          Project Description            ################

Developed a full-stack Real-Time Shift Management System for Indian Railways to monitor and manage duty hours of Loco Pilots and Train Managers. The system tracks live duty hours, triggers automated alerts at critical thresholds (8hr, 9hr, 11hr, 14hr), and enables administrators to plan crew relief operations in real-time.

Key Features to Mention:

Real-time duty hour monitoring using Socket.IO with automatic alerts at 8, 9, 11, and 14-hour thresholds
Role-based access control (SUPERADMIN / ADMIN / USER) with JWT authentication and approval workflow
Shift lifecycle management — create, monitor, plan relief, and complete shifts with full audit logs
Live dashboard showing active shifts, critical alerts, and crew status with auto-refreshing timers
Completed shifts report with Excel export functionality and duty hour analytics
User management with pending approval system for new registrations
Deployed backend on Render (Node.js) and frontend on Vercel with MongoDB Atlas cloud database
-----------------------------------------------------------------------------------------------------------------------------------------

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
