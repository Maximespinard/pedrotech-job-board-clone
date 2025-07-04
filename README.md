# Job Board – Prisma & Next.js (Learning Project)

This project is based on a YouTube tutorial by PedroTech.  
I built it mainly to learn how to use **Prisma** and **PostgreSQL** in a fullstack web app context.

👉 Tutorial video: [Watch on YouTube](https://www.youtube.com/watch?v=gimSKEsWYb4)

---

## 🔧 Tech Stack

- Next.js 15
- Prisma
- PostgreSQL (via Neon)
- GraphQL
- Tailwind CSS
- TypeScript

---

## ✅ Features

- Create and post job offers (for authenticated users)
- Apply to jobs
- Filter jobs by type and location
- User dashboard to manage jobs and applications
- Basic authentication setup

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
