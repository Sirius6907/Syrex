# ⚡ Syrex: AI-Powered Project Builder

Syrex is a sophisticated, full-stack AI App and Website builder designed to transform high-level requirements into fully functional, production-ready digital products.

## 🚀 Capabilities

- **Intelligent Scaffolding**: Automatically generates project structures using modern best practices.
- **AI Generation Engine**: Real-time generation of components, logic, and landing pages.
- **Seamless Deployment**: Integrated workflows for deploying generated apps immediately.
- **Cross-Platform Support**: Built with Electron (Forge) for 
desktop capability alongside web-based generations.

## 🛠️ Technical Arsenal

- **Framework**: Next.js with App Router for high-performance web experiences.
- **Database Architecture**: Drizzle ORM with Type-safe migrations.
- **Desktop Strategy**: Electron Forge for desktop distribution.
- **Testing Suite**: Comprehensive E2E testing with Playwright and unit testing via Vitest.
- **Performance**: High-efficiency workers and shared packages for modular scaling.
- **Design System**: Shadcn/UI for a clean, professional aesthetic.

## 🏗️ Project Structure

- `src/`: Main application logic.
- `worker/`: AI processing and background tasks.
- `packages/`: Shared components and utilities.
- `drizzle/`: Database schemas and migration configurations.
- `e2e-tests/`: Automated browser testing.

## 🚦 Setup & Development

1. **Install Dependencies**:
   ```bash
   npm install
   ```
2. **Database Setup**:
   Configure your environment variables and run migrations:
   ```bash
   npx drizzle-kit push
   ```
3. **Run in Development**:
   ```bash
   npm run dev
   ```

---
Developed by **Chandan Kumar Behera** | Part of the Syrex AI Ecosystem
