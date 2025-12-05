# TeamSync - Collaborative Task Management System

**TeamSync** là ứng dụng quản lý công việc hỗ trợ làm việc nhóm thời gian thực (Real-time Collaboration), được xây dựng theo kiến trúc SPA (Single Page Application) tách biệt hoàn toàn Backend và Frontend.

## 🚀 Mục tiêu dự án
Xây dựng hệ thống quản lý task đa người dùng, giải quyết bài toán đồng bộ dữ liệu tức thì (Real-time) và phân quyền chặt chẽ.

## 🛠 Tech Stack

### Backend (API)
- **Framework:** Laravel 10/11
- **Database:** MySQL
- **Auth:** Laravel Sanctum (Token-based)
- **Architecture:** Repository Pattern, Service Layer
- **Real-time:** Laravel Reverb / Pusher

### Frontend (Client)
- **Framework:** Vue 3 (Composition API)
- **Build Tool:** Vite
- **State Management:** Pinia
- **Styling:** Tailwind CSS
- **HTTP Client:** Axios

## 📦 Hướng dẫn cài đặt

### 1. Setup Backend
```bash
cd backend
composer install
cp .env.example .env
# Cấu hình DB trong file .env
php artisan key:generate
php artisan migrate
php artisan serve
```
### 2. Setup Frontend
```bash
cd frontend
npm install
npm run dev
```
Dev: Bình

Contact: Daylataikhoancuabinh@gmail.com