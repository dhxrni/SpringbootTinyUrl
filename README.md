# 🔗 Spring Boot Tiny URL Service

> A scalable URL shortening service built using Spring Boot that converts long URLs into compact, shareable links and redirects users efficiently.

---

## 🎯 Problem

Long URLs are hard to share, manage, and track. Platforms like Bitly solve this by generating short, unique links with redirection and analytics capabilities.

---

## 💡 Solution

This project implements a backend service that:
- Converts long URLs into short, unique identifiers
- Redirects users from short URLs to original URLs
- Tracks usage analytics (optional / if implemented)

---

## ⚙️ Features

- 🔗 Generate short URL from long URL  
- 🔁 Redirect short URL → original URL  
- 📊 (Optional) Track number of hits / usage  
- ⚡ Fast lookup using optimized storage  
- 🧩 Clean REST API design  

---

## 🏗️ Architecture

```text
Client → Controller → Service → Repository → Database
                     ↓
                Short Code Generator
