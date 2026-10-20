<!-- NAVIGATION -->
<p align="center">
  <a href="#introduction">
    <img src="https://img.shields.io/badge/🏠_Introduction-161B22?style=for-the-badge&labelColor=161B22" alt="Introduction" />
  </a>
  <a href="#technology-stack">
    <img src="https://img.shields.io/badge/🛠️_Technology_Stack-161B22?style=for-the-badge&labelColor=161B22" alt="Technology Stack" />
  </a>
  <a href="#project-features">
    <img src="https://img.shields.io/badge/📌_Project_Features-161B22?style=for-the-badge&labelColor=161B22" alt="Project Features" />
  </a>
  <a href="#git-commit-convention">
    <img src="https://img.shields.io/badge/📝_Git_Commit_Convention-161B22?style=for-the-badge&labelColor=161B22" alt="Git Commit Convention" />
  </a>
  <a href="#document">
    <img src="https://img.shields.io/badge/📚_Document-161B22?style=for-the-badge&labelColor=161B22" alt="Document" />
  </a>
  <a href="#project-status">
    <img src="https://img.shields.io/badge/📊_Project_Status-161B22?style=for-the-badge&labelColor=161B22" alt="Project Status" />
  </a>
</p>

---



# LinkJob

<p align="center">
  <img src="https://img.shields.io/badge/LinkJob-Job%20Search-2563EB?style=flat-square" alt="LinkJob" />
  <img src="https://img.shields.io/badge/Status-In%20Development-F59E0B?style=flat-square" alt="Project Status" />
</p>

<p align="center">
  <strong>Kết nối cơ hội – Kiến tạo tương lai.</strong>
  <br />
  Nền tảng tìm kiếm việc làm và kết nối ứng viên với nhà tuyển dụng.
</p>

---

## 📑 Table of Contents

- [1. Introduction](#1-introduction)
- [2. Technology Stack](#2-technology-stack)
- [3. Project Features](#3-project-features)
- [4. Git Commit Convention](#4-git-commit-convention)
- [5. Document](#5-document)
- [6. Project Status](#6-project-status)

---
<a id="introduction"></a>
## 🏠 1. Introduction

### About LinkJob

**LinkJob** là dự án website tìm kiếm việc làm, hướng đến việc kết nối ứng viên với nhà tuyển dụng thông qua một nền tảng trực tuyến thuận tiện và dễ sử dụng.

Dự án được xây dựng nhằm áp dụng kiến thức về phát triển web, thiết kế API, quản lý cơ sở dữ liệu và triển khai ứng dụng.

### Project Objectives

- Cung cấp chức năng tìm kiếm và lọc việc làm theo nhu cầu.
- Hỗ trợ ứng viên quản lý hồ sơ cá nhân và ứng tuyển trực tuyến.
- Hỗ trợ nhà tuyển dụng đăng tin và quản lý hồ sơ ứng tuyển.
- Cung cấp công cụ quản trị để quản lý người dùng và nội dung.
- Thực hành quy trình phát triển phần mềm, quản lý mã nguồn và triển khai ứng dụng.

### Project Information

| Item | Description |
|---|---|
| Project Name | LinkJob |
| Project Type | Job Search & Recruitment Platform |
| Frontend | React |
| Backend | ASP.NET Core Web API (C#) |
| Primary Database | Microsoft SQL Server |
| Containerization | Docker |
| Deployment | Render |
| Optional Database | MongoDB |
| Project Status | In Development |

---

<a id="technology-stack"></a>
## 🛠️ 2. Technology Stack

Các công nghệ dưới đây là định hướng kỹ thuật dự kiến. Công nghệ có thể được điều chỉnh trong quá trình phát triển.

### Frontend

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

- **React:** Xây dựng giao diện người dùng theo component.
- **HTML5, CSS3, JavaScript:** Xây dựng cấu trúc, giao diện và xử lý tương tác.

### Backend

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C Sharp" />
  <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
</p>

- **C#:** Ngôn ngữ lập trình chính cho phía máy chủ.
- **ASP.NET Core Web API:** Xây dựng RESTful API phục vụ giao tiếp giữa frontend và backend.
- **Entity Framework Core:** Công cụ ORM dự kiến sử dụng để làm việc với cơ sở dữ liệu.

### Database

<p>
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="Microsoft SQL Server" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
</p>

- **Microsoft SQL Server:** Cơ sở dữ liệu chính dự kiến sử dụng để lưu trữ tài khoản, công ty, tin tuyển dụng và hồ sơ ứng tuyển.
- **MongoDB (Optional):** Có thể được bổ sung trong tương lai nếu xuất hiện nhu cầu lưu trữ dữ liệu dạng tài liệu phù hợp.

### Deployment & DevOps

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" alt="Render" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</p>

- **Docker:** Đóng gói ứng dụng thành container để hỗ trợ môi trường phát triển và triển khai nhất quán.
- **Render:** Nền tảng dự kiến sử dụng để triển khai ứng dụng.
- **Git & GitHub:** Quản lý mã nguồn, theo dõi lịch sử thay đổi và cộng tác phát triển.

---

<a id="project-features"></a>
## 📌 3. Project Features

Các chức năng dự kiến phát triển:

| Module | Planned Features |
|---|---|
| Authentication | Đăng ký, đăng nhập, đăng xuất |
| Job Search | Tìm kiếm, lọc và phân trang việc làm |
| Candidate Profile | Quản lý hồ sơ cá nhân và CV |
| Job Application | Ứng tuyển và theo dõi trạng thái hồ sơ |
| Employer | Quản lý thông tin công ty và tin tuyển dụng |
| Administration | Quản lý người dùng, doanh nghiệp và tin đăng |

*Danh sách trên là phạm vi dự kiến, không có nghĩa các chức năng đã hoàn thành.*

---

<a id="git-commit-convention"></a>
## 📝 4. Git Commit Convention

LinkJob sử dụng quy ước commit nhất quán nhằm giúp lịch sử Git dễ đọc, dễ tìm kiếm và thuận tiện cho việc bảo trì mã nguồn.

### 4.1. Commit Message Structure

```text
<type>(<scope>): <short description> | <revision>
```

- `type`: Mục đích của thay đổi.
- `scope`: Module hoặc khu vực bị ảnh hưởng, có thể bỏ qua.
- `short description`: Mô tả ngắn gọn nội dung thay đổi.
- `revision`: Ký hiệu lần triển khai hoặc cập nhật của tính năng, theo quy tắc tại mục 4.6.

### 4.2. Commit Types

| Type | Description | Usage |
|---|---|---|
| `feat` | New feature | Thêm chức năng |
| `fix` | Bug fix | Sửa lỗi |
| `docs` | Documentation | Cập nhật tài liệu |
| `style` | Code formatting | Định dạng code, không đổi logic |
| `refactor` | Code refactoring | Cải thiện cấu trúc code |
| `perf` | Performance improvement | Tối ưu hiệu năng |
| `test` | Tests | Thêm hoặc sửa kiểm thử |
| `build` | Build system | Cập nhật dependencies hoặc cấu hình build |
| `ci` | Continuous integration | Cập nhật CI/CD |
| `chore` | Maintenance | Công việc bảo trì |
| `revert` | Revert changes | Hoàn tác commit |

### 4.3. Common Scopes

| Scope | Description |
|---|---|
| `ui` | Giao diện người dùng |
| `frontend` | Ứng dụng phía client |
| `backend` | Xử lý phía máy chủ |
| `api` | API endpoints |
| `auth` | Xác thực và phân quyền |
| `user` | Tài khoản và hồ sơ người dùng |
| `job` | Tin tuyển dụng và tìm kiếm việc làm |
| `company` | Thông tin doanh nghiệp |
| `application` | Hồ sơ ứng tuyển |
| `database` | Cơ sở dữ liệu |
| `admin` | Chức năng quản trị |
| `config` | Cấu hình ứng dụng |
| `readme` | Tài liệu README |
| `docker` | Cấu hình Docker |

### 4.4. Commit Examples

```bash
# Add a feature
git commit -m "feat(job): add job search functionality"

# Fix a bug
git commit -m "fix(auth): fix login validation"

# Update the user interface
git commit -m "feat(ui): add responsive navigation"

# Improve existing code
git commit -m "refactor(api): simplify job service"

# Update documentation
git commit -m "docs(readme): update project introduction"

# Optimize a database query
git commit -m "perf(database): optimize job search query"
```

### 4.5. Commit Rules

1. Ưu tiên sử dụng tiếng Anh cho commit message.
2. Mỗi commit tập trung vào một mục đích chính.
3. Mô tả cụ thể, ngắn gọn và phản ánh đúng nội dung thay đổi.
4. Tránh các thông điệp chung chung như `update code`, `fix bug` hoặc `final`.
5. Kiểm tra các thay đổi trước khi commit.
6. Không commit mật khẩu, API key hoặc thông tin xác thực nhạy cảm.

---

### 4.6. Feature Revision Convention

LinkJob sử dụng ký hiệu revision để theo dõi lịch sử triển khai và cập nhật của từng tính năng.

**Revision Rules**

| Ký hiệu | Ý nghĩa |
|---|---|
| `init` | Lần triển khai đầu tiên của tính năng |
| `H2` | Lần cập nhật thứ hai |
| `H3` | Lần cập nhật thứ ba |
| `H4` | Lần cập nhật thứ tư |
| `HN` | Các lần cập nhật tiếp theo, với `N` là số thứ tự |

**Examples**

```bash
# Initial implementation of login
git commit -m "feat(auth): implement login | init"

# Second revision of login
git commit -m "fix(auth): fix login validation | H2"

# Third revision of login
git commit -m "refactor(auth): improve login logic | H3"

# Initial implementation of job search
git commit -m "feat(job): implement job search | init"

# Second revision of job search
git commit -m "feat(job): add job filters | H2"
```

**Revision Guidelines**

1. Sử dụng `init` cho lần triển khai đầu tiên của một tính năng.
2. Bắt đầu từ `H2` cho lần cập nhật thứ hai, sau đó tăng tuần tự `H3`, `H4`, `H5`, ...
3. Mỗi tính năng hoặc `scope` có chuỗi revision độc lập.
4. Khi quay lại chỉnh sửa một tính năng đã có, tiếp tục số revision trước đó, không đặt lại từ `init`.
5. Chỉ tăng revision khi có một thay đổi cần được theo dõi như một lần cập nhật riêng; không bắt buộc mọi commit nhỏ đều phải tăng số.
6. Revision là quy ước nội bộ của dự án, không thay thế phiên bản phát hành chính thức của ứng dụng.

**Note:** Git không tự quản lý hoặc xác minh các ký hiệu revision trong commit message. Nhóm cần thống nhất số tiếp theo cho từng tính năng để tránh trùng lặp.


<a id="document"></a>
## 📚 5. Document

Khu vực lưu trữ các tài liệu kỹ thuật, hướng dẫn sử dụng và thông tin phục vụ quá trình phát triển LinkJob.

| Document | Description | Status |
|---|---|---|
| README.md | Tổng quan dự án và hướng dẫn cơ bản | In Progress |
| System Design | Kiến trúc hệ thống | Planned |
| Database Design | Thiết kế cơ sở dữ liệu | Planned |
| API Documentation | Tài liệu API | Planned |
| Installation Guide | Hướng dẫn cài đặt và chạy dự án | Planned |
| Deployment Guide | Hướng dẫn triển khai | Planned |

Khi các tài liệu được tạo, có thể đặt chúng trong thư mục `docs/` và bổ sung liên kết tương ứng tại đây.

---

<a id="project-status"></a>
## 📊 6. Project Status

LinkJob hiện đang trong giai đoạn lên kế hoạch và phát triển.

Các công nghệ, kiến trúc và chức năng được mô tả trong README thể hiện định hướng ban đầu của dự án. Nội dung sẽ được cập nhật theo tiến độ triển khai thực tế.

---

<p align="center">
  <strong>LinkJob</strong>
  <br />
  Connecting People with Opportunities.
</p>
