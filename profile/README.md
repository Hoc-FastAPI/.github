<div align="center">

# ⚡ FASTAPI PYTHON ACADEMY

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.110+-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Pydantic](https://img.shields.io/badge/Pydantic-v2-E92063?style=for-the-badge&logo=pydantic&logoColor=white)](https://docs.pydantic.dev/)
[![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

**Không gian tài nguyên, bài giảng và đồ án thực chiến Backend API với FastAPI.**

[Tài Liệu Khóa Học](#-tài-nguyên-học-tập) • [Quy Chuẩn Nộp Bài](#-quy-chuẩn-thực-hành--nộp-bài) • [Cộng Đồng Hỗ Trợ](#-kênh-hỗ-trợ)

---

</div>

## 🎯 Mục Tiêu Môn Học

Tổ chức này được thành lập nhằm đồng bộ hóa toàn bộ học liệu, bài tập và dự án thực hành của môn học. Kết thúc chương trình, học viên nắm vững:

- **Asynchronous Architecture:** Cơ chế non-blocking I/O và tối ưu hiệu năng với `asyncio`.
- **API Design & Validation:** Xây dựng RESTful API chuẩn OpenAPI, serialize & validate dữ liệu với Pydantic v2.
- **Data Persistence:** Tương tác cơ sở dữ liệu bất đồng bộ qua SQLAlchemy 2.0 / AsyncPG, quản lý migration với Alembic.
- **Security & Production:** Xác thực phân quyền (OAuth2, JWT, hashing Passlib/Bcrypt), cấu hình CORS, Rate Limiting, Dockerize và CI/CD.

---

## 📚 Hệ Thống Repositories

| Repository | Loại | Trọng tâm |
| :--- | :---: | :--- |
| 📘 [`lectures-and-slides`](#) | Lý thuyết | Slide bài giảng, code snippet minh họa từng tuần |
| 📦 [`fastapi-boilerplate`](#) | Template | Khung dự án chuẩn (Clean Architecture, Docker, Settings) |
| 🧪 [`assignments-tracker`](#) | Thực hành | Đề bài Lab 01 → 06, checklist tiêu chí chấm điểm |
| 🚀 [`capstone-showcase`](#) | Đồ án | Nơi lưu trữ và giới thiệu đồ án cuối kỳ xuất sắc |

---

## 💻 Tech Stack Chuẩn

| Danh mục | Công nghệ & Thư viện sử dụng |
| :--- | :--- |
| **Core** | FastAPI, Pydantic v2, Starlette, Uvicorn |
| **Data** | PostgreSQL, SQLAlchemy 2.0 (Async), Alembic, Redis |
| **Test** | Pytest, HTTPX, Faker, Coverage |
| **DevOps** | Docker, Docker Compose, GitHub Actions |
---

## 📋 Quy Chuẩn Thực Hành & Nộp Bài

Mọi sinh viên/học viên thực hiện bài tập tuân thủ theo quy trình:

1. **Fork & Branching:**
   - Clone repo bài tập về local.
   - Tạo nhánh theo định dạng: `student/<ma_sinh_vien>-lab<so_thu_tu>`  
     *(Ví dụ: `student/2021001-lab03`)*

2. **Commit Message:** Tuân thủ Conventional Commits:
   - `feat:` Thêm tính năng/endpoint mới
   - `fix:` Sửa lỗi logic/database
   - `test:` Bổ sung unit test / integration test
   - `docs:` Cập nhật tài liệu API / README cá nhân

3. **Pull Request (PR):**
   - Đặt tiêu đề: `[Nộp bài] Lab <X> - <Họ và tên> - <MSSV>`
   - Đảm bảo toàn bộ test case và linter (`ruff` / `flake8`) chạy xanh trước khi tag Giảng viên review.

---

## 👤 Thông tin Tác giả

* **Email liên hệ:** ankhangbc.2021@gmail.com

<div align="center">
<sub>Xây dựng và phát triển vì mục tiêu học tập thực chiến. Chúc các bạn có kỳ học hiệu quả!</sub>
</div>