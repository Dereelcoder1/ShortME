# ShortMe 🚀

ShortMe is a modern, high-performance URL shortener designed to transform long, cluttered links into clean, manageable URLs instantly. 

> [!IMPORTANT]
> This project is currently in active development. The frontend is being built with **React (TypeScript)** and powered by **Appwrite** for the backend-as-a-service.

## ✨ Planned Features
*   ⚡ **Instant Shortening:** Fast redirection and unique slug generation.
*   🔗 **Custom Aliases:** Create branded or personalized links (e.g., `short.me/my-link`).
*   📊 **Analytics:** Track click counts and visitor trends using Appwrite Databases.
*   🔐 **Authentication:** Secure user accounts via [Appwrite Auth](appwrite.io).
*   🛡️ **Secure:** Built-in protection against malicious links.

## 🛠️ Tech Stack
- **Frontend:** [React.js](react.dev) (with TypeScript `.tsx`)
- **Backend:** [Appwrite](appwrite.io) (Database, Auth, and Functions)
- **Styling:** [Tailwind CSS](tailwindcss.com)
- **Icons:** Lucide React

## 🚀 Getting Started (Development)

### Prerequisites
* [Node.js](nodejs.org) (v18+)
* An [Appwrite Cloud](cloud.appwrite.io) account or self-hosted instance.

### Installation
1. **Clone the repo:**
   
   git clone github.com/Dereelcoder1/Shortme
   cd shortme
Use code with caution.

Install dependencies:
npm install
Use code with caution.

Environment Setup:
Create a .env file in the root directory:
env
VITE_APPWRITE_ENDPOINT=cloud.appwrite.io
VITE_APPWRITE_PROJECT_ID=your_project_id
Use code with caution.

Run the development server:
bash
npm run dev
Use code with caution.

🏗️ Roadmap
Initial React + Vite setup
Appwrite project configuration
URL validation logic
User Dashboard for link management
Click analytics implementation
📄 License
This project is licensed under the MIT License.
{
