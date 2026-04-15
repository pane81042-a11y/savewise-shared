# SaveWise Shared

SaveWise Shared contains reusable logic shared across SaveWise services and applications.

It centralizes constants, validation rules, utility helpers, shared types, and common business logic to keep the platform consistent and maintainable.

## Features

- Shared constants
- Validation schemas
- Utility helpers
- Shared error messages
- Common formatting helpers
- Reusable domain rules

## Tech Stack

- JavaScript or TypeScript
- Zod, Joi, or shared validation library of choice

## Getting Started

### 1. Clone the repository
```bash
git clone <your-savewise-shared-repo-url>
cd savewise-shared
```
### 2. Install dependencies
```bash
npm install
```
### 3. Build or link locally
Use your preferred package linking or workspace strategy during development.
### Scripts
```bash
npm run dev
npm run build
npm run lint
```
 ## Purpose
 This repository helps reduce duplication and keeps validation and business rules aligned across the SaveWise ecosystem.

 ## Related Repositories
 - SaveWise Client
 - SaveWise API
 - SaveWise Auth Service
 - SaveWise UI
 - SaveWise Infra
