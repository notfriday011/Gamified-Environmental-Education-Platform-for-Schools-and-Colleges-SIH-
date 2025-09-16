# Overview

EcoLearn is a gamified environmental education platform designed for schools and colleges. The platform teaches sustainability through interactive games, quizzes, and real-world eco-tasks. Students earn eco-points for environmental actions like tree plantation, waste segregation, and energy saving. The system features leaderboards for class/school competitions, digital badges for recognition, and a unique Carbon Credit Tracker for measuring environmental impact.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **UI Library**: Shadcn/UI components built on top of Radix UI primitives for accessibility
- **Styling**: TailwindCSS with custom design system following environmental theme
- **State Management**: TanStack React Query for server state management
- **Form Handling**: React Hook Form with Zod validation through @hookform/resolvers

## Backend Architecture
- **Runtime**: Node.js with Express.js server
- **Language**: TypeScript with ES modules
- **Database ORM**: Drizzle ORM for type-safe database operations
- **API Pattern**: RESTful endpoints with shared TypeScript schemas between client and server
- **Session Management**: Express session with PostgreSQL session store using connect-pg-simple

## Database Design
- **Database**: PostgreSQL (configured for Neon serverless)
- **Schema Management**: Drizzle Kit for migrations and schema management
- **Type Safety**: Full type safety from database to frontend using Drizzle's type inference
- **Current Schema**: Basic user authentication system with plans for gamification features

## Design System
- **Color Palette**: Eco-friendly green primary colors with earth tones and sky blue accents
- **Typography**: Inter font family for consistency
- **Component Architecture**: Modular component system with variants using class-variance-authority
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
- **Gamification Elements**: Progress bars, badge systems, point counters, and leaderboards

## Development Environment
- **Monorepo Structure**: Shared schemas and utilities between client and server
- **Hot Reloading**: Vite for frontend and TSX for backend development
- **Path Aliases**: Configured for clean imports (@/, @shared/, @assets/)
- **Type Checking**: Strict TypeScript configuration across the entire codebase

## Key Architectural Decisions

### Shared Schema Pattern
The application uses a shared schema approach where database schemas, validation, and types are defined once in the `shared/` directory and consumed by both client and server. This ensures type safety and reduces duplication.

### Component-First UI Architecture
The UI is built using a comprehensive component library based on Radix UI primitives, providing accessibility out of the box while maintaining design consistency through the custom theme system.

### Gamification-Ready Structure
The architecture is designed to support gamification features with progress tracking, badge systems, and competitive elements, aligning with the educational gaming objectives.

# External Dependencies

## Database Services
- **Neon**: Serverless PostgreSQL database hosting
- **Drizzle ORM**: Type-safe database operations and migrations

## UI and Styling
- **Radix UI**: Accessible component primitives for complex UI elements
- **TailwindCSS**: Utility-first CSS framework for styling
- **Lucide React**: Icon library for consistent iconography
- **Google Fonts**: Inter font family for typography

## Development Tools
- **Vite**: Frontend build tool and development server
- **TSX**: TypeScript execution for backend development
- **ESBuild**: Fast JavaScript bundler for production builds

## Form and Validation
- **React Hook Form**: Form state management and validation
- **Zod**: Schema validation library
- **@hookform/resolvers**: Integration between React Hook Form and Zod

## Additional Libraries
- **TanStack React Query**: Server state management and caching
- **Date-fns**: Date manipulation and formatting
- **Class Variance Authority**: Type-safe component variants
- **CLSX & Tailwind Merge**: Conditional and merged CSS classes