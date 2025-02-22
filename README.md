# 🎥 Video Calling Interview Platform  

A **Next.js & TypeScript**-based **remote interview platform** with **real-time video calls, screen sharing, screen recording, authentication, and collaborative coding**.  

## 🚀 Features  

✅ **Live Video Calls** – Seamless communication using **Stream**  
✅ **Screen Sharing** – Share your screen during interviews  
✅ **Screen Recording** – Record sessions for future reference  
✅ **Authentication & Authorization** – Secure user management with **Clerk**  
✅ **Collaborative Code Editor** – Supports **Java, Python, C++, JavaScript**  
✅ **Dynamic & Static Routing** – Efficient navigation and performance  
✅ **Modern UI** – Built with **Tailwind CSS & Shadcn**  
✅ **Database Management** – Real-time data handling with **Convex**  

---

## 🛠️ Tech Stack  

- **Frontend:** Next.js, TypeScript, Tailwind CSS, Shadcn  
- **Backend:** Convex  
- **Authentication:** Clerk  
- **Video Streaming:** Stream  
- **State Management:** Server Actions  

---

## 📄 Environment Variables  

Create a `.env.local` file and add the required API keys:  

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-key
CLERK_SECRET_KEY=your-clerk-secret-key
CONVEX_DEPLOYMENT=your-convex-deployment
NEXT_PUBLIC_CONVEX_URL=your-convex-url
NEXT_PUBLIC_STREAM_API_KEY=your-stream-api-key
STREAM_SECRET_KEY=your-stream-secret-key
