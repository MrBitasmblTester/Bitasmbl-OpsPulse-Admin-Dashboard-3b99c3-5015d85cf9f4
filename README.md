# Bitasmbl-OpsPulse-Admin-Dashboard-3b99c3-5015d85cf9f4

## Description
An intern-level full-stack project to build an ASP.NET Core API and React-based admin dashboard for monitoring and managing system entities, focusing on end-to-end problem solving and basic CRUD workflows.

## Tech Stack
- ASP.NET Core
- React

## Requirements
- Implement full CRUD API for StatusItems with validation and basic error handling.
- Use React state to build a dashboard where admins can list, search, create, edit and delete StatusItems.
- Wire up a simple authentication check for admin calls between React and ASP.NET Core.

## Installation
bash
git clone https://github.com/MrBitasmblTester/Bitasmbl-OpsPulse-Admin-Dashboard-3b99c3-5015d85cf9f4.git
cd Bitasmbl-OpsPulse-Admin-Dashboard-3b99c3-5015d85cf9f4


ASP.NET Core:
bash
dotnet restore
dotnet build


React:
bash
cd client
npm install


## Usage
ASP.NET Core:
bash
dotnet run

React:
bash
cd client
npm start


## Implementation Steps
1. Define StatusItem model and validation rules in ASP.NET Core.
2. Implement ASP.NET Core controllers for full CRUD on StatusItems with basic error handling.
3. Configure routing to expose StatusItem CRUD endpoints.
4. Add a simple authentication check for admin API calls in ASP.NET Core.
5. Set up React app structure and components for the admin dashboard.
6. Use React state to list and search StatusItems from the API.
7. Implement create, edit, and delete StatusItems in React using the API.
8. Integrate the authentication check in React when calling admin endpoints.

## API Endpoints
- Create StatusItem
- Read StatusItems
- Update StatusItem
- Delete StatusItem