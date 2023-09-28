# Urban Nest Realty Website with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth 2023

## Features

- **Tailwind Design**: A sleek and modern user interface designed using Tailwind CSS.
- **Tailwind Animations and Effects**: Engage users with visually appealing animations and effects.
- **Full Responsiveness**: Ensures a seamless experience across all devices and screen sizes.
- **Credential Authentication**: Secure authentication system for user accounts.
- **Google Authentication**: Convenient login via Google accounts.
- **GitHub Authentication**: Securely log in using your GitHub credentials.
- **Image Upload using Cloudinary CDN**: Easily upload and manage property images.
- **Client Form Validation and Handling using react-hook-form**: Enhance data accuracy and user experience.
- **Server Error Handling using react-toast**: Provide clear error feedback to users.
- **Calendars with react-date-range**: Effortlessly manage bookings and reservations.
- **Page Loading State**: Inform users about ongoing processes.
- **Page Empty State**: Guide users when no data is available.
- **Booking / Reservation System**: Streamline property booking and reservation management.
- **Guest Reservation Cancellation**: Allow guests to cancel reservations with ease.
- **Owner Reservation Cancellation**: Empower property owners to manage reservations efficiently.
- **Creation and Deletion of Properties**: Property owners can easily add and remove listings.
- **Pricing Calculation**: Transparent pricing calculations based on various factors.
- **Advanced Search Algorithm**:
  - Filter by category, date range, map location, number of guests, rooms, and bathrooms.
  - Identify available properties during specific travel dates.
- **Favorites System**: Save and organize your favorite properties for quick access.
- **Shareable URL Filters**: Share search criteria via URLs with friends, even if they are not logged in. They will see the same results.

## Getting Started

### Prerequisites

- **Node Version 14.x**: Ensure you have Node.js installed.

### Cloning the Repository

```shell
git clone https://github.com/Gaius-1/urban-nest.git
```

### Install Packages

```shell
npm install
```

### Set Up .env File

Create a `.env` file in the project root directory and add the following environment variables:

```dotenv
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

### Set Up Prisma

Initialize the database schema with Prisma:

```shell
npx prisma db push
```

### Start the App

Run the development server:

```shell
npm run dev
```

## Available Commands

Run the following commands using npm:

| Command | Description |
| --- | --- |
| `dev` | Start a development instance of the app. |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thank you to the open-source community for the tools and libraries that made this project possible.

Explore Urban Nest Realty and embark on a journey to discover your ideal urban dwelling!