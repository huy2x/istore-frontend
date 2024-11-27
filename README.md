# iStore Frontend

## Giới thiệu
iStore Frontend là phần giao diện người dùng của dự án web thương mại điện tử chuyên về sản phẩm Apple. Được xây dựng bằng React và các công nghệ hiện đại.

## Công nghệ sử dụng
- React + Vite
- Tailwind CSS
- Shadcn/ui
- Redux Toolkit
- React Query
- React Router
- React Hook Form
- Axios

## Cấu trúc thư mục
```
src/
├── assets/
├── components/
│   ├── common/
│   │   ├── Button/
│   │   ├── Input/
│   │   └── Card/
│   └── layout/
│       ├── Header/
│       ├── Footer/
│       └── Sidebar/
├── config/
├── features/
│   ├── auth/
│   ├── products/
│   └── cart/
├── hooks/
├── lib/
├── pages/
├── services/
├── store/
├── styles/
├── types/
├── utils/
├── App.tsx
└── main.tsx
```

## Cài đặt và Chạy

### Yêu cầu hệ thống
- Node.js 16.x trở lên
- npm hoặc yarn

### Các bước cài đặt

1. Clone repository
```bash
git clone https://github.com/huy2x/istore-frontend.git
cd istore-frontend
```

2. Cài đặt dependencies
```bash
npm install
# hoặc
yarn
```

3. Cấu hình môi trường
- Tạo file `.env` từ `.env.example`
- Cập nhật các biến môi trường cần thiết

4. Chạy ứng dụng
```bash
npm run dev
# hoặc
yarn dev
```

Ứng dụng sẽ chạy tại `http://localhost:5173`

### Build production
```bash
npm run build
# hoặc
yarn build
```

## Tính năng chính
- [x] Authentication
- [x] Product listing
- [x] Shopping cart
- [x] User profile
- [ ] Payment integration
- [ ] Order tracking
- [ ] Reviews system

## Cấu trúc và Convention

### Component Structure
```
ComponentName/
├── index.tsx
├── ComponentName.tsx
├── ComponentName.types.ts
└── ComponentName.module.css (nếu cần)
```

### Naming Convention
- Components: PascalCase
- Files: PascalCase cho components, camelCase cho các file khác
- Functions: camelCase
- Constants: UPPER_SNAKE_CASE

## Contributing
1. Fork project
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

## License
[Apache-2.0 License](LICENSE)

## Tài liệu tham khảo
- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn/ui](https://ui.shadcn.com/)
