Bài 7: Thiết kế Quy trình Che mờ (Data Masking) Khách VIP

Phần A: Bảng Che Mờ PII

| Thông tin PII                   | Nhãn che mờ Placeholder | Loại dữ liệu       |
| ------------------------------- | ----------------------- | ------------------ |
| Phạm Minh C                     | \[Tên\_khách\_VIP]      | Tên khách hàng VIP |
| 0988.111.222                    | \[SĐT\_ẨN]              | Số điện thoại      |
| minhc@gmail.com                 | \[EMAIL\_ADDRESS]       | Thư điện tử        |
| Căn hộ 502 Chung cư Sunrise, Q7 | \[ADDRESS]              | Địa chỉ nhà        |



Phần B: viết lại Văn Bản Đã Che Mờ (Masked Input)

"Tôi là \[Tên\_khách\_VIP] (SĐT: \[SĐT\_ẨN] Email: \[EMAIL\_ADDRESS], ở \[ADDRESS]). Ngày 20/09 tôi mua 2kg thịt bò Wagyu giá 4.500.000 VNĐ tại MartX District 7 nhưng bị giao chậm 3 tiếng làm hỏng tiệc gia đình. Tôi yêu cầu bồi thường 100%!"



Phần C: Prompt Gửi AI (Prompt gửi AI công cộng)

Hãy đóng vai là Trưởng bộ phận Chăm sóc Khách hàng của hệ thống bán lẻ MartX, và bạn gặp một đơn khiếu nại từ khách hàng VIP, hãy viết đơn xin lỗi chân thành, chuyên nghiệp và lịch sự

Nội dung khiếu nại (Masked Input) của khách hàng:"Tôi là \[Tên\_khách\_VIP] (SĐT: \[SĐT\_ẨN] Email: \[EMAIL\_ADDRESS], ở \[ADDRESS]). Ngày 20/09 tôi mua 2kg thịt bò Wagyu giá 4.500.000 VNĐ tại MartX District 7 nhưng bị giao chậm 3 tiếng làm hỏng tiệc gia đình. Tôi yêu cầu bồi thường 100%!"

Yêu cầu đối với thư phản hồi:

1\.Thừa nhận thiếu sót về việc giao hàng chậm trễ gây ảnh hưởng đến tiệc của khách hàng.

2\. Đưa ra phương án giải quyết thỏa đáng (chấp nhận bồi thường 100% giá trị đơn hàng kèm theo voucher ưu đãi cho lần mua sắm tiếp theo tại MartX District 7).

3. Giữ giọng văn cầu thị, lịch sự và tôn trọng xưng hô với khách VIP.



Phần D (Văn bản De-mask):Trình bày kết quả thư xin lỗi cuối cùng sau khi thay lại thông tin thật:

Phản hồi khiếu nại: Thư xin lỗi chân thành từ MartX gửi đến Quý khách Phạm Minh C

Kính gửi Quý khách Phạm Minh C,

Lời đầu tiên, MarkX xin gửi lời xin lỗi chân thành và sâu sắc nhất đến Quý khách vì sự cố giao hàng chậm trễ 3 tiếng trong ngày 20/09 vừa qua tại cửa hàng MartX District 7.

Chúng tôi hoàn toàn thấu hiểu rằng sự chậm trễ này đã và tổn thất ảnh hưởng nghiêm trọng đến tiệc gia đình quan trọng của gia đình Quý khách,với đơn hàng 2kg thịt bò Wagyu có giá trị 4.500.000 VNĐ bị giao trễ. Đây là một thiếu sót lớn trong quy trình vận vận chuyển và điều phối đơn hàng của chúng tôi.

Nhằm bồi thường cho khách hàng,chúng tôi chấp nhận yêu cầu bồi thường 100% giá trị đơn hàng (4.500.000 VNĐ) của khách hàng và  gửi số tiền bồi thường vào lại tài khoản của Quý khách, kèm một voucher đặc quyền dành riêng cho khách hàng VIP của chúng tôi

Nhân viên phụ trách sẽ liên hệ trực tiếp qua số điện thoại 0988.111.222 hoặc email minhc@gmail.com của Quý khách trong thời gian sớm nhất để hoàn tất thủ tục bồi thường.

