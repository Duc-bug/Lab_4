# Bài tập 4: Menu xử lý ảnh

**Yêu cầu:**  
- Tạo menu cho phép người dùng chọn các chức năng xử lý ảnh:
  - geometric_transformation
    - coordinate_mapping (lật ảnh)
    - Rotate (xoay ảnh)
    - Scale (phóng to/thu nhỏ)
    - Shift (tịnh tiến)
  - segment
    - Adaptive_thresholding
    - Binary_dilation
    - Binary_erosion
    - Otsu

- Người dùng có thể chọn 1 chức năng hoặc kết hợp 2 chức năng (1 từ mỗi nhóm).

**Hướng dẫn chạy:**  
1. Đảm bảo ảnh `dalat.jpg` nằm trong thư mục hiện tại.
2. Chạy file notebook `Baitap4.ipynb`.
3. Nhập lựa chọn theo hướng dẫn trên menu (vd: `1.2 2.1` để xoay rồi adaptive threshold).
4. Ảnh kết quả sẽ được lưu với tên `output_baitap4.jpg` và hiển thị trên màn hình.

**Lưu ý:**  
- Có thể thay đổi các phép biến đổi hoặc thông số cho phù hợp với nhu cầu.