# EvalForge

**EvalForge** is an LLM evaluation platform developed by **Rohit**. It helps teams create projects, manage datasets, configure evaluation parameters, run experiments, and review model performance through reports and charts.

## Developer

**Rohit** is the developer of EvalForge.

## Features

### Core Functionality
- **Project Management**: Organize LLM evaluations into projects with dedicated API configurations.
- **Dataset Management**: Upload datasets, synthesize datasets from sample conversations, and manage multiple datasets per project.
- **Experiment Configuration**: Create and configure evaluation parameters.
- **Real-time Evaluation**: Run experiments and monitor results.
- **Results Analysis**: Review experiment outcomes with visual reports.

### User Interface
- **Modern UI**: Built with React, TypeScript, and Tailwind CSS.
- **Responsive Design**: Works across desktop and mobile devices.
- **Component Library**: Uses shadcn/ui for consistent, accessible components.

### Authentication & Storage
- **Supabase Integration**: Secure authentication and data storage.
- **Google OAuth**: Sign in with Google accounts.
- **Data Persistence**: Projects, datasets, and experiments are securely stored.

## Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui components
- **State Management**: React Context, TanStack Query
- **Routing**: React Router DOM
- **Authentication**: Supabase Auth
- **Database**: Supabase PostgreSQL
- **Charts**: Recharts
- **Form Handling**: React Hook Form with Zod validation
- **Development**: ESLint, TypeScript, Hot Module Replacement

## Project Structure

```text
src/
├── components/          # Reusable UI components
│   ├── layout/          # Layout components
│   └── ui/              # shadcn/ui components
├── contexts/            # React contexts for state management
├── hooks/               # Custom React hooks
├── lib/                 # Utility libraries and configurations
├── pages/               # Main application pages
│   ├── datasets/        # Dataset management pages
│   └── evaluation/      # Experiment and evaluation pages
└── services/            # API services and external integrations
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/rohit-arabale/EvalForge.git
   cd EvalForge
   ```

2. **Install dependencies**
   ```bash
   npm i
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:8080`.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/amazing-feature`.
3. Commit your changes: `git commit -m "Add amazing feature"`.
4. Push to the branch: `git push origin feature/amazing-feature`.
5. Open a pull request.

## License

EvalForge is developed by Rohit. Please refer to the license file for usage terms.

## Support

For questions, issues, or feature requests, open an issue on the repository or contact Rohit.

---

**EvalForge - developed by Rohit for the AI research community.**
