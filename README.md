# HCC Lead Gen App

This is a simple lead generation React app for HCC General Contracting.

## Setup

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Create a `.env` file in the root directory:**

   ```
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_USER_ID=your_user_id
   ```

3. **Run locally:**

   ```bash
   npm run dev
   ```

## Deploy to Vercel

- Push this project to GitHub.
- Import your repository to Vercel.
- In the Vercel dashboard, add the following Environment Variables:
  - `VITE_EMAILJS_SERVICE_ID`
  - `VITE_EMAILJS_TEMPLATE_ID`
  - `VITE_EMAILJS_USER_ID`
- Vercel will automatically detect this as a Vite app and set up the build and output folder.
- Your app will be accessible at the deployment URL provided by Vercel.

## Notes

- Make sure your `.env` file is **not** pushed to GitHub; keep your EmailJS credentials private!
- For client-side routing, the included `vercel.json` file ensures proper rewrites.
