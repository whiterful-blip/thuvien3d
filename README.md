# STL Drive

Website có riêng thư mục STL, upload nhiều file .stl và xem 3D trực tiếp bằng Three.js.

## Deploy Vercel
1. Upload repository lên GitHub hoặc dùng Vercel import.
2. Framework: Vite.
3. Build command: npm run build.
4. Output: dist.

## Lưu cloud
Tạo Supabase project, tạo Storage bucket tên `stl`, rồi thêm Environment Variables:
VITE_SUPABASE_URL
VITE_SUPABASE_ANON_KEY

Nếu chưa cấu hình Supabase, web chạy demo và file chỉ nằm trong trình duyệt.
