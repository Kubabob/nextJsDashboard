# Next.js Dashboard Portfolio
![Next.js](https://img.shields.io/badge/Next.js-14-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white)

This repository contains a  web application built with Next.js, showcasing a responsive dashboard with data visualization, authentication, and real-time updates. The project demonstrates implementation of Next.js App Router, server components, and data fetching patterns.

## Project Overview

This dashboard application focuses on three key aspects:

1. **Financial Data Management** - Tracking invoices, customers, and revenue
2. **User Authentication** - Secure login with role-based access control
3. **Responsive UI** - Fully responsive design using Tailwind CSS

## Content

The project includes:
- **Dashboard Pages**:
    - `dashboard/page.tsx` - Main dashboard with revenue metrics and latest invoices
    - `dashboard/invoices/page.tsx` - Invoice management with search and pagination
    - `dashboard/customers/page.tsx` - Customer directory with search functionality

- **Authentication System**:
    - Role-based access control
    - Secure login with credentials
    - Protected routes

- **Data Visualization** organized by:
    - Revenue charts with time-based filtering
    - Customer activity tracking
    - Invoice status monitoring

## Application Features

### Dashboard Components
- Revenue overview with charts
- Latest invoices list
- Customer activity tracking
- Search functionality

### Data Management
- Invoice creation and editing
- Customer information management
- Revenue tracking and visualization

### User Experience
- Responsive design for all devices
- Skeleton loading states
- Server-side rendering for performance

## Key Technologies

- Implemented Next.js App Router for improved routing
- Utilized React Server Components for enhanced performance
- Applied Tailwind CSS for responsive design
- Integrated authentication with NextAuth.js
- Implemented database queries with server actions

## Folder Structure

```
├── app/                      # Main application code
│   ├── dashboard/            # Dashboard pages
│   │   ├── customers/        # Customers page
│   │   ├── invoices/         # Invoices pages
│   │   └── page.tsx          # Main dashboard page
│   ├── lib/                  # Utility functions and data fetching
│   ├── ui/                   # UI components
│   └── layout.tsx            # Root layout
├── public/                   # Static assets
├── auth.ts                   # Authentication configuration
├── middleware.ts             # Request middleware
└── next.config.ts            # Next.js configuration
```

## Technologies Used

- **Next.js** - React framework with server components
- **React** - UI library
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **NextAuth.js** - Authentication for Next.js
- **Vercel** - Deployment platform

## Visualizations

The project includes visualizations of:
- Revenue trends over time
- Invoice status distribution
- Customer activity metrics
- Payment status tracking

## How to Run

1. Clone this repository
2. Install dependencies: `npm install` or `pnpm install`
3. Set up environment variables (see `.env.example`)
4. Run the development server: `npm run dev` or `pnpm dev`
5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This application is deployed on Vercel. Visit [https://next-js-dashboard-git-main-kubabobs-projects.vercel.app/](https://next-js-dashboard-git-main-kubabobs-projects.vercel.app/) to see the live version.

### Sample Credentials

To test the application, you can use these credentials:
- **Email:** user@nextmail.com
- **Password:** 123456

## License

This project is available under the MIT License.

## Acknowledgments

Special thanks to the Next.js team for their excellent documentation and examples that helped in building this project.