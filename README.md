# DSA Problem Tracker

A comprehensive Data Structures and Algorithms (DSA) problem-tracking platform that seamlessly integrates with platforms like LeetCode and GeeksforGeeks.

## Features

- **Problem Management**: Add, update, and delete DSA problems with metadata
- **Progress Tracking**: Track your progress on individual problems (not started, attempted, completed)
- **Advanced Filtering**: Filter problems by topics, difficulty, companies, and search by title
- **Analytics Dashboard**: View statistics about your progress and problem distribution
- **LeetCode Integration**: Import problems from LeetCode
- **User Management**: Admin and user roles with appropriate permissions
- **Persistent Storage**: Uses PostgreSQL for reliable data storage

## Tech Stack

- **Frontend**: React with TypeScript, TailwindCSS, Shadcn UI components
- **Backend**: Express.js with TypeScript
- **Database**: PostgreSQL with Drizzle ORM
- **Authentication**: Session-based auth with Passport.js
- **State Management**: React Query for server state
- **Form Handling**: React Hook Form with Zod validation

## Getting Started

### Prerequisites

- Node.js 16+
- PostgreSQL database

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/himanchalkaushale/DSA-Companion.git
   cd dsa-problem-tracker
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file with the following variables:
   ```
   DATABASE_URL=postgres://user:password@localhost:5432/dsa_tracker
   ```

4. Push the schema to the database:
   ```
   npm run db:push
   ```

5. Start the development server:
   ```
   npm run dev
   ```

## Usage

- **Adding Problems**: Go to the Admin Dashboard to add new problems
- **Tracking Progress**: Mark problems as attempted or completed from the Problems page
- **Viewing Statistics**: Check your progress on the Dashboard or Profile page

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
