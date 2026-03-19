# ☕ Get Me A Chai

A full-stack web application built with Next.js that allows users to receive support in the form of payments along with messages from others.

## 🚀 Features

* 🔐 Authentication using GitHub OAuth
* 👤 User dashboard to manage profile
* 🖼️ Profile customization (name, bio, profile image)
* 💳 Razorpay integration for secure payments
* 📊 View supporters and messages
* 🌐 Public user page for receiving support
* ⚡ Fast and optimized UI with Next.js
* 🗄️ MongoDB for storing user and transaction data

---

## 🛠️ Tech Stack

**Frontend & Backend:**

* Next.js (Full-stack framework)

**Database:**

* MongoDB

**Authentication:**

* GitHub OAuth

**Payments:**

* Razorpay API

---

## 📂 Project Structure

```
/app or /pages   # Next.js routing
/components      # Reusable UI components
/lib             # Utility functions
/models          # MongoDB schemas
/api             # API routes
/public          # Static assets
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/get-me-a-chai.git
cd get-me-a-chai
```

### 2. Install dependencies

```bash
npm install
```

### 3. Environment Variables

Create a `.env.local` file:

```env
MONGODB_URI=your_mongodb_connection_string
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000
```

---

## ▶️ Running the Project

```bash
npm run dev
```

App will run on:

```
http://localhost:3000
```

---

## 💡 How It Works

* Users sign in using GitHub
* They set up their profile and Razorpay credentials
* Each user gets a public page
* Supporters can send payments and leave messages
* Users can track all supporters and messages from their dashboard


---

## 📌 Future Improvements

* Email notifications for payments
* Advanced analytics dashboard
* Social sharing
* Mobile responsiveness improvements

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests.

---

## 📄 License

MIT License
