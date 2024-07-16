### Summary

**Functional Specifications:**
- Created a single-page application using data from Xero service.
- Developed a UI to display the balance sheet from the received JSON.

**Non-Functional Specifications:**
- Tested on multiple browsers (Chrome, Safari, Firefox, Edge) and OS (Mac, Windows).
- Enhanced performance to minimize unnecessary re-rendering.
- Used TypeScript for defining component props and function types.
- Implemented functional components and React Hooks.
- Followed clean code practices with Prettier for code formatting.

**Code Structure:**
- **Common Folder:** Contains folders for assets, components, constants, services, etc.
- **Component Folder:** Includes sub-folders for tests and CSS files for associated components.

**Tech Choices:**
- ReactJS for component-based architecture.
- TypeScript for predictable, robust, and error-proof components.
- Functional components.
- Axios for API calls due to its advantages over fetch.
- Plain CSS for now; TailwindCSS preferred for scalable applications.

**Unit Tests:**
- Proposed tests include mocking data list API, checking default and changed routes, ensuring correct navigation, and verifying data display with date filters.

**Further Improvements:**
- Enhance device responsiveness for mobile phones and tablets.
- Implement authentication/authorization for improved security.

### Additional Aspects

- **Best Practices and Clean Code:**
  - Used TSLint and Prettier.
  - Maintained standard files and folder structure.
  - Emphasized code readability and maintainability.
  - Focused on decent UI/UX and styling.
  - Implemented error handling with try/catch blocks and proposed Error Boundary Component.

**How to Run the Code Locally:**
1. Clone the main branch of the repo.
2. Run `npm install` in the terminal.
3. Run `npm run dev` to start the server.
4. The app runs on `localhost:3000`.

The app is deployed at - https://yashwant-kumar.netlify.app/

**Error Handling:**
- Wrapped network calls in try/catch blocks.
- Proposed adding an Error Boundary Component.

**Security:**
- No user input displayed on screen; future plans to sanitize inputs to prevent XSS attacks.
