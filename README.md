# 📱 Sport Booking Mobile App

Ứng dụng mobile chính thức của nền tảng **Sport Booking** – cho phép người dùng đặt sân thể thao, theo dõi lịch chơi, nhận thông báo,...
Được phát triển bằng **React Native + Expo + TypeScript**.

---

![Expo](https://img.shields.io/badge/Expo-~53.0.17-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-✓-3178c6)
![CI/CD](https://github.com/InfinityDevTeam/sport-booking-app/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 👩‍💻 Developer

> 👤 [@AnnKiz3110](https://github.com/AnnKiz3110) – Mobile Engineer
> 📁 Repo được chia cấu trúc chuẩn, hỗ trợ CI/CD, ESLint, Prettier để đảm bảo clean code & dễ mở rộng.

---

## 🛠️ Tech Stack

- **Expo + React Native 0.79**
- **TypeScript**
- **expo-router** (App Router style)
- **React Navigation**
- **ESLint + Prettier**
- **CI/CD** với GitHub Actions (tự động build Android/iOS)

---

## 🧭 Folder Structure

```
src/
  ├── app/                  # expo-router pages
  ├── components/           # shared UI components
  ├── screens/              # legacy screen structure (nếu cần)
  ├── constants/            # app-wide constants
  ├── hooks/                # custom React hooks
  ├── services/             # API layer
  ├── store/                # redux / zustand state
  ├── utils/                # helper functions
  └── assets/               # fonts, icons, images
```

---

## 🚀 Getting Started

```bash
# Cài dependencies
npm install

# Chạy app trên Android hoặc Web
npm run android
npm run web

# iOS (cần macOS hoặc EAS Build)
npm run ios
```

---

## 🧹 Code Quality

### ✅ Lint & Format

```bash
# Kiểm tra lint
npm run lint

# Format toàn bộ project bằng Prettier
npm run format

# Kiểm tra vi phạm Prettier (CI sẽ fail nếu có)
npm run format:check
```

### 💥 Pre-commit Hook

> Đã tích hợp Husky + lint-staged → mỗi lần commit sẽ tự động chạy `eslint` và `prettier`.

---

## ⚙️ Scripts

```json
"scripts": {
  "start": "expo start",
  "android": "expo start --android",
  "ios": "expo start --ios",
  "web": "expo start --web",
  "lint": "expo lint",
  "format": "prettier --write .",
  "format:check": "prettier --check ."
}
```

---

## 🧪 CI/CD (GitHub Actions)

> CI sẽ tự động chạy lint + build app Android mỗi khi push vào `main`

- `.github/workflows/ci.yml` đã được cấu hình sẵn
- Nếu dùng Expo EAS Build → có thể tích hợp thêm EAS CLI (build APK/IPA thực tế)

---

## 📦 Notes

- Dự án dùng `expo-router` nên cấu trúc tương tự Next.js (app-based routing)
- Tương lai sẽ kết nối với **API backend** để sync tài khoản, đơn đặt sân, noti,...

---

## 🪄 Contributors

- 🧙‍♂️ Infinity – System Architect
- 📱 [@AnnKiz3110](https://github.com/AnnKiz3110) – Mobile Developer

---

## ❤️ Philosophy

> Code phải đẹp, sạch và có tổ chức – vì đây không chỉ là sản phẩm, mà còn là thanh kiếm thứ hai trong hệ sinh thái Sport Booking Platform.

---

## 📄 License

MIT – use, fork, and contribute freely!
