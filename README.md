# 📱 Sport Booking Mobile App

Ứng dụng mobile chính thức của nền tảng **Sport Booking** – cho phép người dùng đặt sân thể thao, theo dõi lịch chơi, nhận thông báo,...
Được phát triển bằng **React Native + Expo + TypeScript**.

---

![Expo](https://img.shields.io/badge/Expo-~53.0.17-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-✓-3178c6)
![CI/CD](https://github.com/trhgatu/sport-booking-app/actions/workflows/ci.yml/badge.svg)
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
- **CI/CD** với GitHub Actions (tự động lint & test build)
- **EAS Build** (Expo Application Services) – tạo APK nhanh chóng

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
npm run lint            # Kiểm tra lỗi lint
npm run format          # Format toàn bộ project
npm run format:check    # Kiểm tra vi phạm prettier
```

### 💥 Pre-commit Hook

> Đã tích hợp Husky + lint-staged → mỗi lần commit sẽ tự động format + lint.

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

> CI tự động lint + test build Android (expo export)

- `.github/workflows/ci.yml` đã cấu hình sẵn
- Có thể nâng cấp dùng `eas build` production (APK/AAB/IPA)
- Kết hợp EAS để dev mobile build APK dễ dàng

---

## 📦 Notes

- Sử dụng `expo-router` (giống Next.js routing)
- Tự động format và kiểm tra code khi commit
- Sẽ kết nối với hệ thống backend (đặt sân, thông báo, thanh toán,...)

---

## 🧙‍♂️ Contributors

- 🧙‍♂️[@trhgatu](https://github.com/trhgatu) – System Architect
- 📱 [@AnnKiz3110](https://github.com/AnnKiz3110) – Mobile Developer

---

## ❤️ Philosophy

> Code phải đẹp, sạch và có tổ chức – vì đây không chỉ là sản phẩm, mà còn là hệ sinh thái Sport Booking Platform.

---

## 📄 License

MIT – use, fork, and contribute freely!
