# Phân tích dữ liệu HCAHPS từ năm 2015-2023
## Các số liệu cần lưu ý:

## 1. Phân tích dữ liệu theo cấp quốc gia.
<p align=center>
  <img width="392" height="709" alt="image" src="https://github.com/user-attachments/assets/846c511e-7a44-426f-8af2-2f20e0dfc166" />
</p>
Biểu đồ thể hiện xu hướng đánh giá trải nghiệm bệnh nhân tại các bệnh viện Hoa Kỳ theo từng năm. Kết quả cho thấy tỷ lệ đánh giá tích cực duy trì ở mức cao và khá ổn định, dao động khoảng 70–72% trong giai đoạn 2015–2021. Trong khi đó, tỷ lệ đánh giá tiêu cực chỉ chiếm khoảng 7–9%. Khoảng cách lớn giữa tỷ lệ đánh giá tích cực và tiêu cực cho thấy phần lớn bệnh nhân có trải nghiệm tốt với dịch vụ bệnh viện tại Hoa Kỳ.
Tuy nhiên, từ năm 2022 đến 2023 có thể quan sát thấy một sự thay đổi nhẹ: tỷ lệ đánh giá tích cực giảm trong khi đánh giá tiêu cực tăng lên. Sự thay đổi này có thể liên quan đến những tác động kéo dài của đại dịch COVID-19 đối với hệ thống y tế, bao gồm áp lực quá tải bệnh viện và chất lượng dịch vụ bị ảnh hưởng.
Nhìn chung, kết quả cho thấy trải nghiệm bệnh nhân tại các bệnh viện Hoa Kỳ tương đối ổn định trong nhiều năm, tuy nhiên xu hướng gần đây cho thấy dấu hiệu suy giảm nhẹ về mức độ hài lòng của bệnh nhân.

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
### 2.1. So sánh giữa các bang.
Vì bộ dữ liệu không đi sâu vào từng câu hỏi một vì vậy chúng ta sẽ đi sâu vào việc phân tích và so sánh giữa các bang với nhau. 
<div align=center>
  <img width="504" height="830" alt="image" src="https://github.com/user-attachments/assets/8b06a7b9-9c2b-43e0-9f87-1a7e3a632216" />
  <img width="499" height="831" alt="image" src="https://github.com/user-attachments/assets/a21e575b-36e0-41b5-a745-fd41ec4f4950" />
</div>

Trước hết xem xét về tổng quan ta có thể thấy trong biểu đồ nhiệt, nổi bật nhất chính là District of Columbia có màu đỏ nhất và kéo dài qua từng năm. Điều này thể hiện trải nghiệm tệ của bang này qua từng năm và không có sự cải thiện. Ngoài ra còn có nhiều bang khác cũng có tình trạng kéo dài tương tự ví dụ như NJ, NY, NV,... Nhìn vào mặt khác các bang có trải nghiệm tốt cũng luôn giữ vững trải nghiệm qua các năm và không có sự biến động lớn. Để có một cái nhìn rõ ràng hơn về sự thay đổi trải nghiệm chăm sóc sức khỏe theo thời gian, ta sẽ tới với biểu đồ tiếp theo.

<div>
  <img width="459" height="345" alt="image" src="https://github.com/user-attachments/assets/f6115bc7-2ebf-46c3-9d88-2af52f5b0b47" />
  <img width="451" height="367" alt="image" src="https://github.com/user-attachments/assets/e8cc0ab9-69d8-44ae-afd6-2ee7128b409e" />
</div>

Kết quả cho thấy sự khác biệt rõ rệt về trải nghiệm bệnh nhân giữa các bang. Nhóm các bang có mức Net Satisfaction cao nhất duy trì giá trị khoảng 68–73, trong khi nhóm thấp nhất chỉ đạt khoảng 45–60, tạo ra khoảng cách trung bình khoảng 20–25 điểm.

Các bang có trải nghiệm tốt nhất có xu hướng tăng nhẹ từ 2015 đến khoảng 2020–2021 trước khi giảm nhẹ trong giai đoạn 2022–2023, nhưng nhìn chung mức độ biến động tương đối nhỏ. Ngược lại, nhóm bang có trải nghiệm thấp duy trì mức hài lòng thấp hơn đáng kể trong toàn bộ giai đoạn nghiên cứu, trong đó District of Columbia thường xuyên là bang có giá trị thấp nhất.

Ngoài ra, cả hai nhóm đều cho thấy xu hướng giảm nhẹ trong giai đoạn 2022–2023, cho thấy có thể tồn tại các yếu tố hệ thống ảnh hưởng đến trải nghiệm bệnh nhân trên toàn quốc.
<div>
  <img width="381" height="324" alt="image" src="https://github.com/user-attachments/assets/d2175613-ace8-4dfd-b509-dfdaa4cda070" />
  <img width="383" height="322" alt="image" src="https://github.com/user-attachments/assets/37e8bb10-27c8-4fa7-98aa-02f167e9e44a" />
</div>

Hai biểu đồ thể hiện 10 bang có mức độ hài lòng cao nhất và thấp nhất dựa trên chỉ số Net Satisfaction. Kết quả cho thấy các bang có mức hài lòng cao nhất chủ yếu thuộc khu vực Trung Tây như Nebraska, South Dakota, Minnesota và Iowa với chỉ số khoảng 65–72. Ngược lại, các bang có mức hài lòng thấp nhất bao gồm California, New York, New Jersey và District of Columbia với chỉ số chỉ khoảng 48–60.

Sự khác biệt này có thể phản ánh tác động của mật độ dân số và áp lực lên hệ thống bệnh viện. Các bang đông dân thường phải đối mặt với tình trạng quá tải bệnh viện, thời gian chờ lâu và nguồn lực y tế hạn chế, từ đó ảnh hưởng đến trải nghiệm của bệnh nhân. Khoảng cách khoảng 10–15 điểm giữa hai nhóm cho thấy sự chênh lệch đáng kể về chất lượng trải nghiệm chăm sóc y tế giữa các bang.
