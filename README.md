# 🎨 AI Image Generator (Next.js + GPT-4)

A modern web application built with **Next.js, TypeScript, and Tailwind CSS** that allows users to generate AI-powered images from text prompts.  
The application integrates with the **GPT-4 Image Generation API** (via RapidAPI) to deliver unique, high-quality images based on user input.  

---

## 📖 Table of Contents
- [🚀 Features](#-features)
- [🎯 Learning Objectives](#-learning-objectives)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Project Structure](#-project-structure)
- [✅ Best Practices Implemented](#-best-practices-implemented)
- [🔑 Requirements](#-requirements)
- [⚡ Getting Started](#-getting-started)
- [📌 Development Notes](#-development-notes)
- [🌟 Future Enhancements](#-future-enhancements)
- [📜 License](#-license)

---

## 🚀 Features
- **AI Image Generation**
  - Generate images from text prompts using GPT-4 Image API
  - Display loading indicators during generation
- **Image Gallery**
  - View history of generated images
  - Thumbnail previews with click-to-expand full image
- **Responsive UI**
  - Optimized for both desktop and mobile
  - Clean, modern Tailwind-based design
- **Custom Hooks**
  - Encapsulated logic for API requests & state handling
- **Secure API Handling**
  - API key stored in environment variables
  - Protected server-side API routes

---

## 🎯 Learning Objectives
By completing this project, you will:

- Understand and implement **React state management** with `useState`  
- Create and utilize **custom React hooks**  
- Manage **environment variables** for API keys securely  
- Implement **Next.js API routes** for server-side processing  
- Build **reusable React components** with TypeScript  
- Handle **asynchronous operations** in React (loading & error states)  
- Develop a **responsive UI** with Tailwind CSS  
- Follow **React best practices** for component structure and organization  

---

## 🛠️ Tech Stack
- **Frontend:** Next.js 13+, React 18+, TypeScript  
- **Styling:** Tailwind CSS  
- **Backend API:** Next.js API Routes  
- **AI Integration:** GPT-4 Image Generation API (RapidAPI)  
- **Package Manager:** npm or yarn  

---

## 📂 Project Structure

```
alx-project-0x07/
├── components/
│ ├── common/
│ │ └── ImageCard.tsx
│ └── layouts/
│ ├── Footer.tsx
│ ├── Header.tsx
│ └── Layout.tsx
├── constants/
│ └── index.ts
├── hooks/
│ └── useFetchData.ts
├── interfaces/
│ └── index.ts
├── pages/
│ ├── api/
│ │ └── generate-image.ts
│ ├── _app.tsx
│ └── index.tsx
├── public/
├── styles/
│ └── globals.css

```
---

## ✅ Best Practices Implemented
### Component Organisation
- Clear separation of **layout** (`Header`, `Footer`, `Layout`) and **functional** components (`ImageCard`)  
- **Reusable** components with proper typing  

### State Management
- State handled with `useState` and `useEffect`  
- Custom hook (`useFetchData`) for reusable async logic  
- Type-safe state definitions  

### API Handling
- Server-side API route (`generate-image.ts`) for secure API key usage  
- Loading and error states handled gracefully  

### Security
- API keys stored in **`.env.local`**  
- Server-side API protection from exposure  
- Input sanitisation (baseline, can be expanded)  

### UI/UX
- Responsive, mobile-friendly design with Tailwind  
- Loading spinners & user feedback  
- Image previews with full-size view  

### Type Safety
- TypeScript **interfaces** for props, components, and API responses  
- Generic typing in custom hooks  

---

## 🔑 Requirements
- Node.js **v14+**  
- Next.js **v13+**  
- React **v18+**  
- TypeScript  
- Tailwind CSS  
- GPT-4 API key (via **RapidAPI**)  
- Modern web browser  

---

## ⚡ Getting Started
```
### 1. Clone the repository
git clone https://github.com/yourusername/ai-image-generator.git
cd ai-image-generator

2. Install dependencies
npm install
# or
yarn install

3. Setup environment variables

Create a .env.local file in the root directory and add:

RAPIDAPI_KEY=your_gpt4_api_key_here

4. Run the development server
npm run dev
# or
yarn dev

Visit: http://localhost:3000 🚀
```

## 📌 Development Notes

This project evolves across versions (0x07 → 0x13):

0x07: Basic setup & layout

0x08: State management

0x09: Environment configuration

0x10: API integration

0x11: Image history tracking

0x12-0x13: Custom hooks & refinements

## The final version demonstrates:
- ✔ Clean separation of concerns
- ✔ Reusable components & hooks
- ✔ Proper TypeScript implementation
- ✔ Strong React patterns

## 🌟 Future Enhancements

- 🔐 User authentication
- 💾 Persistent storage of generated images
- ⚠️ Advanced error handling
- 🖌️ Image editing features
- 📤 Social media sharing

## 📜 License
This project is licensed under the MIT License.
Feel free to use and modify for personal or commercial projects.

>✨ Built with Next.js, TypeScript, Tailwind, and a touch of AI magic.
