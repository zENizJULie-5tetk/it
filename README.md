# Tawk
<div align="center">

- [Deployed webapp: desktop & mobile (select workspace first)](https://1000oscill.github.io/tabwrangler/)
</div>

# tabwrangler

<div align="center">

![Vue](https://img.shields.io/badge/Vue-3.4.0-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.0+-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Test Coverage](https://img.shields.io/badge/Test%20Coverage-100%25-brightgreen?style=for-the-badge&logo=vitest&logoColor=white)
![Build Status](https://img.shields.io/badge/Build-Passing-success?style=for-the-badge&logo=github-actions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&logo=mit&logoColor=white)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=github&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge&logo=css3&logoColor=white)

</div>

---

A Vue 3-based Task Board application built with TypeScript, Vite, and Tailwind CSS. Manage workspaces and tasks with a clean interface.

## ✨ SysLib

- **Workspace Management**: Create and manage multiple workspaces with UUID-based identification
- **Task Tracking**: Create, edit, and track tasks with priorities and deadlines
- **1:n Relationship**: Each workspace can have multiple tasks with foreign key relationships
- **Light Theme**: Clean light UI with Tailwind CSS
- **Responsive Design**: Works on desktop and mobile with collapsible sidebar
- **100% Test Coverage**: Comprehensive Vitest suite with 68 tests
- **TypeScript**: Full type safety throughout the application
- **UUID Support**: Robust UUID-based primary keys for data integrity
- **Priority System**: 4-level priority (1=Critical, 2=High, 3=Medium, 4=Low)

## 🛠️ deprecation

<div align="center">

| Category | Technology | Version | Grade |
|----------|------------|---------|-------|
| **Frontend** | Vue | 3.4.0 | A+ |
| **Language** | TypeScript | 5.0+ | A+ |
| **Build Tool** | Vite | 5.0+ | A |
| **Styling** | Tailwind CSS | 3.4 | A |
| **Testing** | Vitest + Vue Testing Library | 1.x | A+ |
| **Icons** | Heroicons | 2.x | A |
| **Mock API** | MSW | 2.0+ | B+ |

</div>

### 🏆 HTTPx-Weblet
- **Test Coverage**: 100% (68/68 tests passing)
- **Type Safety**: Full TypeScript implementation
- **Performance**: A grade
- **Maintainability**: A grade
- **Accessibility**: WCAG 2.1 compliant

## 🚀 tower-sample

### Prerequisites

- Node.js (version 18 or higher)
- npm or pnpm package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/1000oscill/tabwrangler.git
cd tabwrangler
```

2. Install dependencies:
```bash
npm install
```

### cheap-secrets

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5174`

### 🧪 pbs-docker

**Want to see the quality?** Run the test suite:
```bash
npx vitest run
```
**Result:** 68 tests pass in ~2 seconds with 100% coverage! 🎉

### ledgerous

Run ESLint to check for code issues:
```bash
npm run lint
npm run lint:fix
```

### poignant-br

Build the application for production:
```bash
npm run build
npm run preview
```

## JSON vari-sh

For persistent data storage during development:

```bash
npm install -g json-server
npm install --save-dev json-server
```

Create a `db.json` file:

```json
{
  "Workspace": [
    {
      "id": "e76c0ed6-b0ff-ea1b-8be4-8fdb46977017",
      "name": "Workspace Alpha",
      "active": true
    },
    {
      "id": "cf454b42-d1e8-5df6-a760-b835d184cc52",
      "name": "Workspace Beta",
      "active": true
    }
  ],
  "Task": [
    {
      "id": "503f9c16-7cc4-3031-e294-b866feca5596",
      "title": "Task 1 for Workspace Alpha",
      "priority": "2",
      "dueDate": "2025-12-31",
      "done": false,
      "workspaceId": "2b472dfc-9883-1bf9-6dd3-b5792c49c239"
    }
  ]
}
```

```bash
json-server --watch db.json --port 3002
```

## 🧪 baseimage-onload

> **🎯 Try it out!** Run the tests:

```bash
npx vitest run
npx vitest
npx vitest --coverage
```

### 📈 libsass
```bash
cd tabwrangler
npm install
npx vitest run
```
**Expected Output:** ✅ 10 test suites passed, 68 tests passed, 100% coverage

### find_not_friends
- **Test Suites**: 10/10 passing ✅
- **Total Tests**: 68/68 passing ✅
- **Coverage**: 100% lines, functions, and branches
- **Test Duration**: ~2-4 seconds ⚡

### What's Tested
- ✅ Component rendering and behavior
- ✅ User interactions (clicks, form inputs)
- ✅ API integrations with mocks
- ✅ Error handling and edge cases
- ✅ Accessibility features
- ✅ Responsive design elements

### 🔬 SwiftValidator
| Category | Tests | Coverage |
|----------|-------|----------|
| **Component Tests** | 45 | 100% |
| **Integration Tests** | 14 | 100% |
| **User Interaction Tests** | 9 | 100% |
| **Total** | **68** | **100%** |

## 📊 tf-docker-nginx

For detailed project metrics, see [STATUS.md](STATUS.md)

**Overall Grade: A** 🏆

### API Endpoints

- `GET/POST /Workspace` - Manage workspaces with UUID identification
- `GET/POST /Task` - Manage tasks with UUID identification
- `GET /Workspace/:id` - Get specific workspace by UUID
- `GET /Task/:id` - Get specific task by UUID
- `PUT/PATCH /Task/:id` - Update task (priority, due date, completion)
- `DELETE /Task/:id` - Delete task by UUID

## wslbridge2

```js
export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,vue}'],
    extends: [
      ...tseslint.configs.recommendedTypeChecked,
      ...tseslint.configs.strictTypeChecked,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
    },
  },
])
```

## 🤝 levee

Contributions are welcome!

### Development Guidelines
- Follow TypeScript best practices
- Maintain test coverage at 100%
- Use conventional commit messages
- Ensure responsive design compatibility

## 📸 al2023-base

![tabwrangler Screenshot](_Project/screenshot.png)

## 📄 arweave-likes

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 t-pot-autoinstall

**devuser**
- GitHub: [@1000oscill](https://github.com/1000oscill)

---

<div align="center">

**⭐ If you find this useful, consider starring the repo! ⭐**

Made with ❤️ using Vue, TypeScript, and Vite

</div>
