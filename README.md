# Full-Stack URL Shortener

A modern, full-stack URL shortener built with React, Supabase, ShadCN, and Tailwind CSS. This app lets users shorten long URLs, manage links, and track analytics with a sleek and responsive interface.

## Features

- **User Authentication** (powered by Supabase)
- **URL Shortening & Customization**
- **Link Analytics (clicks, devices, locations)**
- **Real-Time Updates**
- **Beautiful UI with ShadCN & Tailwind CSS**

## Tech Stack

- **Frontend:** React, ShadCN, Tailwind CSS
- **Backend & Database:** Supabase (PostgreSQL)
- **Deployment:** Vercel / Netlify (optional for production)

## Getting Started (Local Development)

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [Supabase Account](https://supabase.com/)

### Setup Instructions

1. **Clone the Repository:**

```bash
git clone https://github.com/abhijeethere1/url-shortener.git
cd url-shortener
```

2. **Install Dependencies:**

```bash
npm install
```

3. **Configure Supabase:**

- Create a new project on Supabase.
- Copy your **API URL** and **Anon Key**.
- Create a `.env.local` file in the project root and add:

```env
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-anon-key
```

4. **Run the Development Server:**

```bash
npm run dev
```

5. **Access the App:**

Visit: `http://localhost:5173`



## Deployment

You can deploy the app easily using [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com/). Just link the GitHub repo, add the environment variables, and hit deploy!



