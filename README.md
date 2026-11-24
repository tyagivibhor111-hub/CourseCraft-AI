# CourseCraft AI 

CourseCraft AI is an AI-powered platform that simplifies the process of creating educational courses. Users can generate complete course structures by providing basic details such as course title, duration, number of chapters, and video preferences. Powered by Google Gemini AI, the platform automatically generates structured course content and integrates relevant YouTube videos for each chapter, making learning more organized and accessible.

### Features

- **User Authentication:** Secure registration and login functionality for users.
- **Course Creation:** Create courses by specifying the title, duration, number of chapters, and video preferences.
- **AI-Powered Generation:** Generate complete course structures automatically using Google Gemini AI.
- **YouTube Integration:** Automatically fetch relevant YouTube videos for individual chapters.
- **Image Storage:** Store course-related images using Firebase Storage.
- **Modern UI:** Responsive and user-friendly interface built with Shadcn UI.

### Tech Stack

- **Frontend & Framework:** Next.js
- **Database:** PostgreSQL
- **ORM:** Drizzle ORM
- **Authentication:** Clerk
- **AI Integration:** Google Gemini AI
- **Storage:** Firebase
- **UI Components:** Shadcn UI
- **Video Integration:** YouTube Data API

### Installation

1. Clone the repository:

```bash
git clone https://github.com/tyagivibhor111-hub/CourseCraftAI.git
```

2. Navigate to the project directory:

```bash
cd CourseCraft-AI
```

3. Install dependencies:

```bash
pnpm install
```

4. Configure environment variables by creating a `.env` file in the root directory:

```env
NEXT_PUBLIC_HOST_URL="http://localhost:3000"

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-key"
CLERK_SECRET_KEY="your-key"
NEXT_PUBLIC_CLERK_SIGN_IN_URL="/sign-in"
NEXT_PUBLIC_CLERK_SIGN_UP_URL="/sign-up"

NEXT_PUBLIC_GOOGLE_GEMINI_API_KEY="your-key"

NEXT_PUBLIC_DRIZZLE_DATABASE_URL="your-database-url"

NEXT_PUBLIC_FIREBASE_API_KEY="your-key"
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN="your-auth-domain"
NEXT_PUBLIC_FIREBASE_PROJECT_ID="your-project-id"
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET="your-storage-bucket"
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID="your-sender-id"
NEXT_PUBLIC_FIREBASE_APP_ID="your-app-id"
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID="your-measurement-id"

NEXT_PUBLIC_YOUTUBE_API_KEY="your-youtube-api-key"
```

5. Start the development server:

```bash
npm run dev
```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Open to Contributions

CourseCraft AI is an open-source project, and contributions are always welcome!

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Submit a pull request to the main repository.

**Let's build something great together! 🚀**