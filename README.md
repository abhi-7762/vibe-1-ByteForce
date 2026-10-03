# LawazZa — Internal Mobility Desk 🛺

> Book, manage, and track Toto rides between College, Station, and Office.

## 🚀 Setup

### 1. Prerequisites
- Node.js 18+
- A free MongoDB Atlas account

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Environment Variables
Edit `.env.local`:
```env
MONGODB_URI=mongodb+srv://<user>:<pass>@cluster0.xxxxx.mongodb.net/lawazza
NEXTAUTH_SECRET=<any-random-32-char-string>
NEXTAUTH_URL=http://localhost:3000
```

### 4. Run Locally
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000)

---

## 👤 Roles
| Role | Capabilities |
|------|-------------|
| Student / Employee | File trip requests, view trips, view history |
| Rider | Accept trips, mark pickup (boarded/missed), mark done |

## 🔄 Trip Lifecycle
`pending` → `accepted` (or `clash`) → `pickup` → `done`

## 🛠️ Tech Stack
- **Next.js 14** (App Router)
- **MongoDB Atlas** + Mongoose
- **NextAuth.js** (Credentials)
- **Vanilla CSS**

## 📂 Repo Name
`vibe-1-<team-name>`
