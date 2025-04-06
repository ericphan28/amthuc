# Tài liệu Triển khai

## Hướng dẫn triển khai

### Chọn nhà cung cấp hosting
- **Hosting**: Heroku, Netlify, AWS

### Triển khai ứng dụng
1. **Triển khai frontend**:
   - Đưa mã nguồn React.js lên Netlify hoặc Vercel
   - Cấu hình build và deploy

2. **Triển khai backend**:
   - Đưa mã nguồn Node.js/Express lên Heroku hoặc AWS
   - Cấu hình môi trường và biến môi trường

3. **Triển khai cơ sở dữ liệu**:
   - Sử dụng MongoDB Atlas hoặc cài đặt MongoDB trên AWS
   - Cấu hình kết nối đến cơ sở dữ liệu

### Cấu hình CI/CD
- Sử dụng GitHub Actions để tự động hóa quy trình build và deploy
- Cấu hình pipeline để kiểm thử và deploy tự động