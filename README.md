# Realistic Load Testing with Artillery and Playwright

This workshop centered on conducting realistic load testing for the Mataffären web application by combining Artillery with Playwright.

# How to setup
 **Clone repo**:
git clone <your-repository-url>

 **Install Dependencies**:
Ensure that you have Node.js installed, then install the required packages:

```bash
npm install
```

 **Build the Project**:
Build the Vite/React project to create the `dist` folder:

```bash
npm run build
```

 **Start the Backend**:
Run the backend to serve the application:
```bash
npm run backend
```

 **Run the Load Test with Artillery**:
Open another terminal window and run the load test:

```bash
npm run load-test
```

**Run the Load Test with Artillery and Playwright**:

```bash
npm run playwright-test
```