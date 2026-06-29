## 🚀 About the Project

NeedLink is a service marketplace platform that connects users who need services with providers who can offer them.

The system allows users to:
- Create service requests
- Receive offers from providers
- Accept or reject offers
- Track request status in real time (pending / in progress / completed)

---

## ⚙️ Features

- 🔐 User Authentication (Login / Register)
- 🧾 Create Service Requests
- 💼 Providers can submit offers
- ✔ Users can accept or reject offers
- 📊 Dashboard for tracking requests
- 🔄 Status updates (Pending / In Progress / Completed)
- 🎨 Responsive UI using Bootstrap / Blade templates

---

## 📁 Project Structure

app/
├── Models/
├── Http/
│   ├── Controllers/
│   └── Middleware/
├── resources/
│   ├── views/
│   │   ├── auth/
│   │   ├── dashboard/
│   │   └── main/
│   └── lang/
├── routes/
├── database/
└── public/

---

## ▶️ How to run
### Backend (Laravel)
```bash
composer install
php artisan serve
