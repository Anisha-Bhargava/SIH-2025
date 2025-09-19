# Nabha Sehat Sewa

**A comprehensive healthcare management system for Nabha city, providing multi-role access for healthcare providers, patients, and administrators.**

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Authentication System](#authentication-system)
- [Multi-Language Support](#multi-language-support)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Overview

Nabha Sehat Sewa is a modern healthcare management platform designed to streamline healthcare services in Nabha city. The system supports multiple user roles including patients, doctors, nurses, pharmacists, lab technicians, and system administrators, each with tailored dashboards and functionalities.

## Features

### Multi-Role Authentication System

- **Patient Portal**: Personal health records, appointment booking, prescription tracking
- **Doctor Dashboard**: Patient management, prescription writing, appointment scheduling
- **Nurse Interface**: Patient care tracking, vital signs recording, medication administration
- **Pharmacist Panel**: Prescription management, inventory tracking, drug dispensing
- **Lab Technician**: Test result management, sample tracking, report generation
- **Admin Control**: User management, system configuration, analytics and reporting
- **Owner Access**: Complete system oversight and management


### Multi-Language Support

- **Hindi (हिंदी)**: Primary language for local users
- **English**: International standard interface
- **Punjabi (ਪੰਜਾਬੀ)**: Regional language support
- Real-time language switching without page reload


### Modern UI/UX

- Responsive design for all devices
- Dark/Light theme support
- Intuitive navigation and user experience
- Accessibility-compliant interface


### Emergency Services

- Quick access to emergency contacts
- Emergency service request system
- Priority handling for critical cases


## Tech Stack

### Frontend

- **Next.js 14**: React framework with App Router
- **TypeScript**: Type-safe development
- **Tailwind CSS**: Utility-first CSS framework
- **Shadcn/ui**: Modern component library
- **Lucide React**: Beautiful icons


### State Management

- **React Context API**: Global state management
- **React Hooks**: Local state and side effects


### Development Tools

- **ESLint**: Code linting
- **Prettier**: Code formatting
- **TypeScript**: Static type checking


## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn package manager


### Installation

1. **Clone the repository**

```shellscript
git clone https://github.com/your-username/nabha-sehat-sewa.git
cd nabha-sehat-sewa
```


2. **Install dependencies**

```shellscript
npm install
# or
yarn install
```


3. **Start the development server**

```shellscript
npm run dev
# or
yarn dev
```


4. **Open your browser**
Navigate to `http://localhost:3000`


## Authentication System

### User Roles & Access Levels

| Role | Access Level | Key Features
|-----|-----|-----
| **Patient** | Basic | Health records, appointments, prescriptions
| **Doctor** | Medical | Patient management, diagnosis, prescriptions
| **Nurse** | Care | Patient care, vital signs, medication tracking
| **Pharmacist** | Pharmacy | Prescription fulfillment, inventory
| **Lab Technician** | Laboratory | Test results, sample management
| **Admin** | Administrative | User management, system settings
| **Owner** | Full System | Complete oversight and control


### Default Owner Account

```plaintext
Email: owner@nabhasehatsewa.com
Password: Owner@123
Role: Owner
```

### Registration Process

- New users can register with email and password
- Phone number is optional during registration
- Role selection determines dashboard access
- Email verification may be required


## Multi-Language Support

The system supports three languages with complete translation coverage:

### Supported Languages

- **Hindi (हिंदी)**: `hi`
- **English**: `en`
- **Punjabi (ਪੰਜਾਬੀ)**: `pa`


### Language Features

- Real-time language switching
- Persistent language preference
- Complete UI translation
- Right-to-left text support where needed


## Project Structure

```plaintext
nabha-sehat-sewa/
├── app/                          # Next.js App Router
│   ├── auth/                     # Authentication pages
│   ├── globals.css              # Global styles
│   ├── layout.tsx               # Root layout
│   └── page.tsx                 # Home page
├── components/                   # Reusable components
│   ├── auth/                    # Authentication components
│   │   ├── login-form.tsx
│   │   └── register-form.tsx
│   ├── dashboard/               # Dashboard components
│   │   ├── dashboard-content.tsx
│   │   └── role-switcher.tsx
│   ├── ui/                      # UI components (shadcn/ui)
│   ├── language-switcher.tsx    # Language selection
│   └── theme-provider.tsx       # Theme management
├── contexts/                     # React contexts
│   ├── auth-context.tsx         # Authentication state
│   └── language-context.tsx     # Language state
├── lib/                         # Utility functions
│   ├── translations.ts          # Translation data
│   └── utils.ts                 # Helper functions
├── types/                       # TypeScript definitions
│   ├── auth.ts                  # Authentication types
│   └── language.ts              # Language types
└── README.md                    # Project documentation
```

## Usage

### For Patients

1. Register with email and select "Patient" role
2. Access personal health dashboard
3. Book appointments with healthcare providers
4. View prescription history and medical records


### For Healthcare Providers

1. Register with appropriate role (Doctor, Nurse, etc.)
2. Access role-specific dashboard
3. Manage patient information and care
4. Generate reports and prescriptions


### For Administrators

1. Use admin credentials to access system
2. Manage user accounts and permissions
3. Configure system settings
4. Generate analytics and reports


### For System Owner

1. Use owner credentials for full access
2. Oversee entire system operation
3. Manage all user roles and permissions
4. Access comprehensive system analytics


## Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint


### Environment Variables

Create a `.env.local` file for local development:

```plaintext
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

## Contributing

We welcome contributions to improve Nabha Sehat Sewa!

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


### Development Guidelines

- Follow TypeScript best practices
- Maintain consistent code formatting
- Add appropriate comments and documentation
- Test your changes thoroughly
- Ensure accessibility compliance


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Nabha City Healthcare Department** - For project requirements and support
- **Open Source Community** - For the amazing tools and libraries
- **Healthcare Professionals** - For valuable feedback and insights


## Support

For support and questions:

- Email: [support@nabhasehatsewa.com](mailto:support@nabhasehatsewa.com)
- Documentation: [Project Wiki](https://github.com/your-username/nabha-sehat-sewa/wiki)
- Issues: [GitHub Issues](https://github.com/your-username/nabha-sehat-sewa/issues)


---

**Made with ❤️ for the healthcare community of Nabha**
