# KPDL · Phòng giải đề

Web tĩnh tiếng Việt, chạy trực tiếp bằng cách mở `dist/index.html`. Không cần cài thư viện hoặc API key.

- Tích hợp dữ liệu và ảnh gốc của cả 5 đề.
- Thống kê, boxplot SVG, chuẩn hóa, phân thùng và Pearson; cấu hình riêng theo đề.
- K-means: bảng khoảng cách, cập nhật tâm và biểu đồ; đề 3 dùng Manhattan.
- Apriori và luật kết hợp; ID3 và FP-Growth từ notebook.
- Lưu dữ liệu câu 1 và dàn ý bài tập lớn trong localStorage; in hoặc lưu PDF.

Kiểm tra: `node check.cjs`.

Quy ước: độ lệch chuẩn tổng thể (chia n); tứ phân vị theo trung vị hai nửa; equal-width đóng bên phải, bin đầu đóng hai đầu; hòa biên chọn dưới; K-means cập nhật trung bình cộng kể cả khoảng cách Manhattan như notebook. Câu 3 cần nội dung bài tập lớn thật của sinh viên.
