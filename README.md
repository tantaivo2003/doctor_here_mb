# 📱 HealthCare App (React Native + NodeJS + PostgreSQL)

Ứng dụng giúp bệnh nhân quản lý thông tin sức khỏe, đặt lịch khám với bác sĩ, theo dõi thuốc, và trò chuyện với bác sĩ qua nhắn tin/video call.

## 🚀 Tính năng chính

### 👤 Hồ sơ cá nhân
- Cập nhật thông tin cá nhân, bảo hiểm y tế, cài đặt tài khoản.
- Xem điều khoản sử dụng, chính sách bảo mật.

### 🗓️ Lịch hẹn
- Đặt lịch hẹn khám trực tiếp hoặc trực tuyến với bác sĩ.
- Quản lý lịch hẹn: sắp tới, đã hoàn thành, đã hủy.
- Nhắc nhở lịch khám và uống thuốc qua thông báo đẩy.

### 🧑‍⚕️ Tìm bác sĩ
- Tìm kiếm bác sĩ theo tên, chuyên khoa, bệnh viện.
- Bộ lọc và sắp xếp theo đánh giá, tên, chuyên ngành.
- Xem thông tin chi tiết bác sĩ, đánh giá và yêu thích.

### 💬 Nhắn tin & gọi video
- Nhắn tin văn bản, hình ảnh, file với bác sĩ.
- Gọi video trực tiếp giữa bác sĩ và bệnh nhân.
- Hệ thống trò chuyện thời gian thực (Stream.io).

### 💊 Quản lý thuốc & kết quả khám
- Xem đơn thuốc, lịch uống thuốc, chi tiết thuốc.
- Tra cứu kết quả khám bệnh, chẩn đoán.
- Đồng bộ chỉ số sức khỏe từ Health Connect (Android).

### 👨‍👩‍👧‍👦 Quản lý thành viên gia đình
- Thêm, chỉnh sửa và liên kết hồ sơ người thân.
- Đặt lịch hẹn thay mặt cho người thân.


## 🔧 Công nghệ sử dụng

### Frontend (React Native)
- **Expo** + **TypeScript**
- **React Navigation** (stack + tab navigation)
- **TailwindCSS (NativeWind)**
- **react-native-chart-kit** (hiển thị chỉ số)
- **AsyncStorage** (lưu trữ local)
- **Stream.io** (chat real-time + video call)
- **Health Connect API** (đồng bộ chỉ số Android)
- **Expo Push Notification**

### Backend (NodeJS)
- RESTful API
- Authentication: **JWT + Refresh Token**
- PostgreSQL
- Swagger API Docs (`/api-docs`)

### DevOps & CI/CD
- Docker (multi-service: backend, frontend, db, nginx)
- GitHub Actions (build & deploy)
- Digital Ocean, Nginx (reverse proxy)
- Firebase (Push notifycation)




