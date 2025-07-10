## 🧪 Mini GitHub Explorer

### 🎯 Goal
Build a small web application that allows users to search for GitHub users and display their profile information along with their public repositories.

### 🧩 Features

#### 1. Search GitHub Users
- Input: GitHub username
- Fetch user data from GitHub API
- Display: avatar, username, bio, location, followers count

#### 2. List Public Repositories
- Show a paginated list of public repos (name, description, stars, language)
- Allow sorting by stars or name
- Filter by language

#### 3. Bookmark Repos
- Allow logged-in users to bookmark repos
- Store bookmarks in a database
- Display user’s bookmarks on a separate page

### ⚙️ Requirements

#### Frontend
- Next.js
- Axios or Tanstack query for API requests
- Responsive styling (CSS with Tailwind or Material)
- Component-based structure

#### Backend
- NestJS
- REST API:
  - `POST /login` (mock auth with hardcoded user)
  - `GET /bookmarks`
  - `POST /bookmarks`
- Use MySQL or Postgres
- Basic rate limiting

#### Testing
- Unit tests for one frontend component and one backend route with 85%+ backend coverage at least. You can follow TDD technique if you want

### 📝 Deliverables
- GitHub repository with README:
  - How to run frontend and backend
  - Tech stack used
  - Any assumptions made
- Deployed demo (Vercel, Render, Railway)
- Dockerize whole project, so that it can be started via only 1 command in terminal for local development

### 💡 Evaluation Criteria
- Clean code and project structure
- Git commit hygiene
- Functional API integration and pagination
- Simple, usable UI
- Bonus: auth flow, reusable components, basic tests
