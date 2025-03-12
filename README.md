# Dự án website quản lý công việc TM 🚀

> TM là một ứng dụng quản lý công việc giúp người dùng theo dõi tiến độ, phân công nhiệm vụ và tối ưu hóa quy trình làm việc..

## ✨ Tính năng

- ✅ Quản lý danh sách công việc theo trạng thái: To Do, In Progress, Review, Done.
- ✅ Quản lý thành viên, đội nhóm.
- ✅ Kéo thả (Drag & Drop) để thay đổi thứ tự ưu tiên công việc.
- ✅ Tìm kiếm, lọc và sắp xếp công việc.
- ✅ Phân quyền người dùng.
- ✅ Nhắn tin, gọi video thời gian thực với socket và zegocloud.
- ✅ Giao diện trực quan dễ sử dụng.

## 🔧 Công nghệ sử dụng

- 🔥 **Frontend**: ReactJS, Vite, Tailwind, Redux Toolkit, Formik, Frame Motion, Yup, Ant Design, DnD Kit
- ⚡ **Backend**: Node.js, Express, Socket, MongoDB, Mongoose, Redis
- 🔗 **Authentication**: JWT
- 🛢 **Hosting**: Vercel (Frontend), Render (Backend)

## 📎 Link github

#### 🌐 **Frontend**

- [github.com/phucngdev/TM-FE.git](https://github.com/phucngdev/TM-FE.git)

#### 💻 **Backend**

- [github.com/phucngdev/TM-BE.git](https://github.com/phucngdev/TM-BE.git)

### 1️⃣ **Yêu cầu**

- Node.js >= 16
- Database
- Other necessary dependencies

### 2️⃣ **Clone the repository**

```sh
git clone https://github.com/phucngdev/TM-FE.git
git clone https://github.com/phucngdev/TM-BE.git
cd repository
```

### 3️⃣ **Install dependencies**

```sh
npm install
```

### 4️⃣ **Setup environment variables**

Create a `.env` file and configure:

#### 🌐 **Frontend**

```
VITE_APP_ID=yourappid (zegocloud)
VITE_SECRET=yourkey
VITE_API_URL=yourlinkapi
VITE_SECRET_KEY=yourkey
```

#### 💻 **Backend**

```
MONGODB_URL=yoururldatabase
JWT_ACC_SECRET=yourkey
JWT_REF_SECRET=yourkey
VITE_SECRET_KEY=yourkey
```

### 5️⃣ **Chạy dự án**

#### 🌐 **Frontend**

```sh
npm run dev
```

#### 💻 **Backend**

```sh
npm start
```

## 📌 Danh sách API Endpoints (sẽ bổ sung sau)

| Method | Endpoint            | Mô tả                                    | Request Body (JSON) | Token  |
| ------ | ------------------- | ---------------------------------------- | ------------------- | ------ |
| `GET`  | `/api/v1/tasks`     | Lấy danh sách tất cả công việc           | ❌ Không cần        | ✅ Cần |
| `GET`  | `/api/v1/tasks/:id` | Lấy thông tin chi tiết của một công việc | ❌ Không cần        | ✅ Cần |

---

## 📩 Contact

- 📧 Email: phucnguyen09022003@gmail.com
- 📌 Portfolio: [nguyenminhphuc.vercel.app](https://nguyenminhphuc.vercel.app)
- 🔗 Github: [github.com/phucngdev](https://github.com/phucngdev)
