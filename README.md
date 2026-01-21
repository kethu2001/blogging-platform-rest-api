# Blogging Platform REST API

A scalable and secure REST API for a multi-user content publishing platform.  
This backend system supports authentication, role-based access, CRUD operations, image uploads, and relational database design using modern backend practices.

> Built collaboratively to gain real-world industry exposure using GitHub workflows.

---

## 🚀 Project Overview

The **RESTful Content Platform API** enables users to:

- Sign up and log in securely
- Create, update, delete, and view posts
- Upload images for posts
- Comment on posts
- Manage content with role-based access (Admin / User)
- Maintain structured relationships using an ORM

This project focuses on **backend engineering best practices**, not frontend UI.

---

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- REST API architecture

### Database
- MySQL
- Sequelize ORM
- Migrations & Seeders

### Authentication & Security
- JWT (JSON Web Tokens)
- Input validation
- Protected routes

### Tools
- GitHub (branches, pull requests, code reviews)
- dotenv for environment configuration
- Multer for image uploads

---

## 👥 Team Collaboration

This project is developed by **two developers** following an industry-style workflow.

| Role | Responsibilities |
|-----|------------------|
| Backend Developer | API design, authentication, database logic |
| Backend Developer | Image uploads, validations, documentation |

### Collaboration Practices
- Feature-based branches
- Pull requests & reviews
- Clean, meaningful commits

---

## 🔌 API Features

### Authentication
- User registration
- User login
- JWT-based authorization

### Posts
- Create post
- Update post
- Delete post (soft delete)
- View all posts
- Pagination & search

### Comments
- Add comments to posts
- View post comments
- Comment moderation (Admin)

### Media
- Image upload for posts
- File validation

---

## 🔐 Role-Based Access

| Role | Permissions |
|----|------------|
| User | Create posts, comment, edit own posts |
| Admin | Manage all posts, comments, users |

---

## 🧠 Database Design

- Users
- Posts
- Comments
- Categories
- Tags

Includes:
- One-to-many relationships
- Audit fields (`createdAt`, `updatedAt`)
- Status-based records (draft / published)

---

## 🏗️ Setup Instructions

### Prerequisites
- Node.js (v16+)
- MySQL
- npm

### Installation
```bash
git clone https://github.com/kethu2001/blogging-platform-rest-api.git
cd restful-content-platform-api
npm install
