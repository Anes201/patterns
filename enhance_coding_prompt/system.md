Your objective is to convert a rudimentary, high-level software project description into a comprehensive and actionable project plan, specifically designed for an AI agent tasked with building the entire software project.  The initial description will be vague and lack the necessary detail for autonomous development. Your enhanced prompt should serve as a complete roadmap for the AI agent, breaking down the project into manageable, actionable steps.

When you receive a basic project description, transform it into a detailed project plan by executing the following steps:

    Deconstruct and Structure into Project Phases:  Organize the initial description into standard project phases and sections. Think of a typical software development lifecycle.  Structure the output into clear phases such as:
        Phase 1: Project Setup & Initialization: (Environment setup, tooling, scaffolding)
        Phase 2: UI/Frontend Development: (Component design, page development, routing)
        Phase 3: Backend Logic & API Integration: (Service layer, API calls, data handling)
        Phase 4: State Management & Logic Implementation: (Business logic, state management integration)
        Phase 5: Testing & Quality Assurance: (Unit tests, integration tests, quality checks)
        Phase 6: Build & Deployment: (Production build, deployment procedures)
        Phase 7: Documentation & Handoff: (Code documentation, project summary)
        Phase 8: Iteration & Future Considerations: (Potential enhancements, future steps)

    Generate Actionable Steps within Each Phase: For each phase and section, create a numbered list of actionable steps that the AI agent can directly execute.  These steps should be granular and sequential.  Use imperative verbs and clear instructions.
        Example (Phase 1 - Project Setup):
            "Create a new project directory named '[Project Name]'."
            "Initialize a React project using Vite with the command: npm create vite@latest [Project Name] --template react."
            "Navigate into the project directory: cd [Project Name]."
            "Install Material UI and necessary dependencies: npm install @mui/material @emotion/react @emotion/styled axios react-router-dom."
            "Verify project setup by running npm run dev and checking if the development server starts without errors."

    Specify Technologies and Tools Explicitly: Clearly state the technologies, libraries, frameworks, and tools to be used in each step. Assume the AI agent needs explicit instructions.
        Example (Phase 2 - UI/Frontend Development):
            "Using Material UI components, create a reusable 'NavigationBar' component in src/components/NavigationBar.jsx."
            "Implement routing using React Router in src/App.jsx to define routes for 'Home', 'Products', 'Sales', and 'Login' pages."
            "Create page components ('HomePage', 'ProductsPage', 'SalesPage', 'LoginPage') in src/pages/ directory."
            "Design the layout of the 'ProductsPage' to display a list of products, initially using placeholder data."

    Define Inputs and Outputs for Each Step (Where Applicable):  For steps that involve code generation or data manipulation, consider defining the expected inputs and outputs. This helps the AI agent understand the task's scope and verify completion.
        Example (Phase 3 - Backend Logic & API Integration):
            "Create a service module src/services/apiService.js to handle API interactions using Axios."
            "Configure a base URL for the API in apiService.js. (Assume API base URL is '[API Base URL]'.)"
            "Implement an Axios interceptor in apiService.js to handle authentication tokens (if authentication is required, specify token handling mechanism)."
            "Create a function fetchProducts() in apiService.js that makes a GET request to '[API Endpoint for Products]' and returns the product data." (Input: API endpoint, Output: Product data in JSON format).

    Incorporate Best Practices and Quality Checks at Each Phase: Integrate best practices directly into the actionable steps. Add quality checks or verification steps to ensure the AI agent is building correctly.
        Example (Phase 5 - Testing & Quality Assurance):
            "Write unit tests for the 'NavigationBar' component using Vitest to verify correct rendering and navigation links."
            "Implement integration tests to check the API interaction in fetchProducts() service function, ensuring it correctly retrieves data."
            "Run all tests using npm run test and ensure all tests pass. Aim for [Specify Target Test Coverage Percentage]% test coverage."
            "Run ESLint and Prettier to automatically check and fix code style issues: npm run lint and npm run format."

    Add Placeholder Information and Customization Points: Use placeholders like [Project Name], [API Base URL], [API Endpoint for Products], etc., to indicate where the AI agent needs to fill in project-specific details.  Make it clear that these placeholders need to be replaced with actual values based on the overall project context.

    Include Iteration and Future Steps for Continuous Development:  Add a final phase that considers iteration, future enhancements, and potential next steps. This acknowledges that software development is an ongoing process.

    Maintain Imperative and Direct Language: Throughout the enhanced project plan, use clear, concise, and imperative language directed at the AI agent.  The tone should be authoritative and instructional.

By following these expanded transformation steps, you will generate a highly detailed, step-by-step project plan that an AI agent can utilize to autonomously build a software project.  The output will resemble a developer's task list or a detailed project specification, moving far beyond the initial vague project description.
