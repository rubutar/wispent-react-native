### Wispent

Wispent is a lightweight personal expense tracking app built with React Native and TypeScript, designed with a clean, scalable architecture inspired by MVVM and modern iOS development practices.
The goal of this project is to explore how far a well-structured React Native codebase can go while remaining simple, predictable, and production-ready.

## ✨ Features (Planned)
- Track daily income and expenses
- Simple, fast data entry
- Clear spending overview
- Local-first data persistence
- Cross-platform support (iOS & Android)
- Scalable architecture for future growth

⚠️ This project is under active development. Features will be introduced incrementally.

## Architecture

Wispent follows a feature-based folder structure with a clear separation of concerns:
- View – UI components and screens
- ViewModel – Business logic and state management
- Core – Shared services, utilities, and storage
- Theme – Centralized design tokens
- This structure is inspired by MVVM / Clean Architecture commonly used in native iOS development.

src/
 ├── app/
 ├── features/
 ├── core/
 └── theme/

## Tech Stack
- React Native (CLI)
- TypeScript
- React Navigation
- AsyncStorage / MMKV (planned)

## Project Goals
- Maintain clean and readable code
- Keep logic testable and isolated
- Avoid unnecessary complexity
- Stay close to native platform mental models

Be fully App Store & Play Store ready

## Status
- Project initialization
- Base navigation setup
- Core architecture scaffolding
- Expense tracking MVP
- Local persistence
- App Store / Play Store readiness

## Notes
This project is part of a broader effort to bridge native iOS development practices with cross-platform React Native development, focusing on long-term maintainability rather than quick prototypes.

📄 License

MIT License
