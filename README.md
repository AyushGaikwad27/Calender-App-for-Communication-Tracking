# Calendar Application for Communication Tracking

## Overview

This project is a React-based Calendar Application designed to help maintain strong professional relationships by tracking communications with various companies. It provides a centralized platform for logging past interactions, planning future communications, and managing engagement frequency.

## Features

- **Admin Module**: Manage companies and communication methods.
- **User Module**: Visualize and manage communication tasks.
- **Reporting and Analytics Module** (optional): Gain insights into communication effectiveness and trends.

## Project Structure

```
calendar-app
├── public
│   ├── index.html
│   └── favicon.ico
├── src
│   ├── components
│   │   ├── AdminModule
│   │   ├── UserModule
│   │   ├── ReportingModule (optional)
│   │   └── Common
│   ├── services
│   ├── utils
│   ├── App.tsx
│   ├── index.tsx
│   └── styles
├── package.json
├── tsconfig.json
└── README.md
```

## Setup Instructions

1. **Clone the repository**:

   ```
   git clone <repository-url>
   cd calendar-app
   ```

2. **Install dependencies**:

   ```
   npm install
   ```

3. **Run the application**:
   ```
   npm start
   ```
   The application will be available at `http://localhost:3000`.

## Functionality

- **Admin Module**: Admins can add, edit, and delete companies and communication methods.
- **User Module**: Users can view company communications, log new communications, and manage notifications.
- **Calendar View**: Users can visualize past and upcoming communications.

## Known Limitations

- The Reporting and Analytics Module is optional and may not be fully implemented.
- User authentication is not included in this version.

## Future Enhancements

- Implement user authentication and role management.
- Enhance the Reporting and Analytics Module with more detailed insights.
