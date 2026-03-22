# Phân tích dữ liệu HCAHPS từ năm 2015-2023
## Các số liệu cần lưu ý:

## 1. Phân tích dữ liệu theo cấp quốc gia.
<p align=center>
  <img width="392" height="709" alt="image" src="https://github.com/user-attachments/assets/846c511e-7a44-426f-8af2-2f20e0dfc166" />
</p>
Biểu đồ này cho ta thấy sự biến động của đánh giá tích cực và đánh giá tiêu cực qua từng năm. Có thể thấy rằng với các đánh giá tích cực sẽ chiếm khoảng 70-72% và đánh giá tiêu cực chiếm khoảng 6-8% qua từng năm cho thấy trải nghiệm của bệnh nhân qua từng năm rất ổn định, không có biến động trong những năm từ 2013 đến 2022. Nhìn về mặt xu hướng, có sự biến động nhẹ trong báo cáo năm 2022 và năm 2023 điều này có thể là hệ quả do ảnh hưởng từ đại dịch COVID-19. Tóm lại biểu đồ thể hiện sự ổn định của y tế Mỹ nhưng đồng thời cũng cho thấy trong trải nghiệm không có cải thiện đáng kể.

<p align=center>  
  <img width="538" height="718" alt="image" src="https://github.com/user-attachments/assets/0b9c4da6-5f29-4856-b1e1-765b81d3d194" />
</p>
Với biểu đồ phân bố đánh giá, có thể thấy hầu hết đánh giá ở các khía cạnh tập trung vào phần đánh giá tích cực điều này phản ảnh bệnh nhân có trải nghiệm tốt. Trong các loại câu hỏi câu hỏi có một nhóm đặc biệt là nhóm thông tin xuất viện (H_COMP_6) không có các đánh giá ở mức trung lập vì đối với dạng câu hỏi này chỉ có hai câu trả lời. Ngoài ra nhìn vào tỉ lệ đánh giá tiêu cực có thể thấy nhóm trao đổi về thuốc (H_COMP_5) và nhóm thông tin xuất viện (H_COMP_6) là hai nhóm có tỉ lệ tiêu cực cao nhất tuy nhiên điều này chỉ đúng khi nhìn vào một khía cạnh đó là đánh giá tiêu cực, để có thể đánh giá trải nghiệm khách hàng thì không thể phụ thuộc vào duy nhất tỉ lệ đánh giá tiêu cực. Biểu đồ tiếp theo sẽ cho chúng ta một cái nhìn cụ thể hơn về trải nghiệm khách hàng.

<p align=center>
  <img width="385" height="717" alt="image" src="https://github.com/user-attachments/assets/27cb8099-e05f-4621-b65b-10d42b2f118f" />
</p>
Đây chính là bảng đánh giá trải nghiệm người dùng. Bảng này được tính dựa trên chỉ số đo lường Net Satisfaction được tính bằng công thức sau:
$ NSAT = %Tích cực - %Tiêu cực $
Khi tính bằng chỉ số này ta sẽ bỏ qua những lựa chọn trung lập, tập trung vào hai lựa chọn chính là tích cực và tiêu cực. Bằng cách này chúng ta sẽ có thể nhìn thấy trải nghiệm người dùng thông qua hai chỉ số mà không phiến diện từ một chỉ số tiêu cực duy nhất.
Có thế thấy rằng nếu so sánh dựa trên chỉ số NSAT thì khía cạnh có trải nghiệm tệ nhất là giao tiếp về thuốc (H_COMP_5) và xuất viện (H_COMP_7). Trong khi đó vấn đề về thông tin xuất viện (H_COMP_6) lại có chỉ số trải nghiệm đứng thứ 3, và đứng kế cuối nếu chỉ xét riêng đánh giá tiêu cực. Ngoài ra một khía cạnh cũng cho chỉ số trải nghiệm khoảng 50 đó chính là chỉ số tiếng ồn. Tuy vậy, điều này khá là hợp lý vì trong môi trường bệnh viện, tiếng ồn là thứ khó tránh khỏi.

**Kết luận:** Đánh giá tổng quan theo cấp quốc gia trải nghiệm của bệnh nhân có xu hướng ổn định qua từng năm. Gần như các đánh giá đều là đánh giá tích cực tuy nhiên nếu xét trên từng khía cạnh ta cần phải chú ý đến H_COMP_5 và H_COMP_7. Để có một cái nhìn cụ thế hơn ta cần phải đi tới so sánh trải nghiệm từng khía cạnh giữa các bang.

## 2. Phân tích dữ liệu theo cấp bang.
