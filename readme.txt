**********Mục lục**********
---Project 2
   |
   --- 1. Note 
   | 
   --- 2. Báo cáo tiến độ (tuần 4)
   |
   --- 3. Demo (hiện vẫn chưa có)
   |
   --- 4. Setup môi trường
   |
   --- 5. Source code (đã được đẩy lên, 19/4/2023) 
   |
   --- 6. Research tham khảo (hiện vẫn chưa có)
**********Chức năng**********
+ 1. Note: Ghi lại chú ý sau mỗi buổi báo cáo.
+ 2. Báo cáo tiến độ: cập nhật tiến trình công việc.
+ 3. Demo: Video demo quá trình chạy thuật toán.
+ 4. Setup môi trường: Ghi lại hướng dẫn cài đặt các thư viện để sử dụng thuật toán phân cụm.
+ 5. Source code: Trong thư mục này có chứa toàn bộ code của nhóm em kèm theo đó là một vài bộ dataset dùng cho quá trình huấn luyện thuật toán.Nếu muốn sử dụng thuật toán, người dùng chỉ cần kích chuột phải vào folder Source, chọn Open with Code (với điều kiện là máy đã cài Visual Studio Code). Sau đó chạy file Clustering với các tham số sau đây:
	+ filename: tên tập dữ liệu mà người dùng muốn phân cụm
	+ lamda: giá trị ngưỡng để đánh giá thuộc tính của từng đối tượng
	+ eval: bao gồm 3 chỉ số để đánh giá đó là davies bouldin score, silhouette score và chỉ số IFV, để có thể sử dụng các chỉ số đánh giá này người dùng cần nhập eval = "davies_bouldin_score" cho chỉ số DB, "silhouette_score" cho chỉ số Silhouette, "IFV" cho chỉ số IFV, nếu không điền gì vào eval thì thuật toán sẽ không in ra bất kỳ chỉ số nào mà chỉ in ra số cụm được phân loại dựa vào giá trị lamda cho trước.
     Hiện tại có 2 file code đó là Clustering.py và trial.py. Clustering.py là file code thuật toán thầy Thảo yêu cầu, còn trial.py là file chạy thử thuật toán K-means và vẽ biểu đồ biển diễn của Elbow joint.
+ 6. Research tham khảo: những bài báo hay nội dung nhóm em dùng để xây dựng thuật toán