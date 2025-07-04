# Job Board – Prisma & Next.js (Learning Project)

This project is based on a YouTube tutorial by PedroTech.  
I built it mainly to learn how to use **Prisma** and **PostgreSQL** in a fullstack web app context.

👉 Tutorial video: [Watch on YouTube](https://www.youtube.com/watch?v=gimSKEsWYb4)

---

## 🔧 Tech Stack

- Next.js 15
- Prisma
- PostgreSQL (via Neon)
- NextAuth
- Tailwind CSS
- TypeScript

---

## ✅ Features

- Post Job Offers Authenticated users can post new job offers with title, description, type, and location.
- Advanced Search Filter jobs by keyword, type (Full-time, Part-time, Contract), and location — all with Prisma query filters.
- User Dashboard Users can view their posted jobs and see how many applicants each job has received.
- Job Applications Users can apply for any job. The dashboard lists all applications with statuses.
- Dynamic Routes & Pages Each job has its own dynamic detail page with full information and "Apply" button.
- Authentication & Authorization Users must be signed in to post jobs or apply for them.

---

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/Maximespinard/pedrotech-job-board-clone.git
cd pedrotech-job-board-clone
```

2. Install dependencies:

```bash
npm install
```

3. Set up your `.env` file with your Neon PostgreSQL connection:

```env
DATABASE_URL="your_neon_database_url"
```

4. Generate and migrate the database:

```bash
npx prisma generate
npx prisma migrate dev --name init
```

5. Start the dev server:

```bash
npm run dev
```

App will run on: `http://localhost:3000`

---

## 📚 Notes

This project is for **learning purposes only** and closely follows the original tutorial.  
I may update or modify it further as I experiment with new features.
