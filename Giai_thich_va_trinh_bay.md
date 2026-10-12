# Giải thích và lời trình bày ChấmNhanh

Lưu Xuân Dũng – 2A202602746. Làm cá nhân. Đầu vào: Đề bài 2, PDF trang 4–5; các kết quả dưới đây là tính toán từ giả định bài tập.

## Phần A: tại sao có lãi chưa chắc có tiền?

Đơn vị phần này là triệu đồng. Doanh thu X chỉ ghi 20 mỗi tháng dù đã nhận 240 tháng 1. Dự án Y ghi 90 tháng 2 khi nghiệm thu dù đến tháng 4 mới thu. Chi phí AI ghi theo tháng phát sinh; tiền thanh toán chậm một tháng. Góp vốn 1.000 và vay 300 không phải doanh thu; mua máy chủ 360 là tài sản, khấu hao 10 mỗi tháng.

| Khoản | Tháng 1 | Tháng 2 | Tháng 3 | Tổng |
| --- | ---: | ---: | ---: | ---: |
| Doanh thu | 70 | 190 | 130 | 390 |
| Giá vốn | 25 | 35 | 45 | 105 |
| Lợi nhuận gộp | 45 | 155 | 85 | 285 |
| Hoạt động | 140 | 140 | 140 | 420 |
| EBITDA | −95 | 15 | −55 | −135 |
| Khấu hao | 10 | 10 | 10 | 30 |
| Lợi nhuận hoạt động | −105 | 5 | −65 | −165 |
| Lãi vay | 3 | 3 | 3 | 9 |
| Thuế | 0 | 0 | 0 | 0 |
| Lợi nhuận sau thuế | −108 | 2 | −68 | −174 |

Tháng 2 lãi 2, nhưng tiền giảm 88: thu 80, chi 15 AI của tháng 1 + 10 kiểm tra + 120 lương + 20 văn phòng + 3 lãi = 168. Không lấy lợi nhuận để thay cho thu/chi tiền.

Cuối tháng 3: tiền 921, phải thu 90, máy chủ 360, hao mòn −30 → tài sản 1.341. Nợ: phải trả 35 + doanh thu chưa thực hiện 180 + vay 300 = 515. Vốn: góp 1.000 + lỗ giữ lại −174 = 826. 515 + 826 = 1.341.

Dòng tiền kinh doanh = −174 + 30 − 90 + 35 + 180 = −19. Cộng đầu tư −360 và tài chính +1.300, tiền cuối kỳ 921. Tiền trả trước và công nợ giúp tiền giảm ít hơn lỗ, nhưng chưa phải hiệu quả bền vững.

Nếu từ tháng 4 giữ hoạt động tháng 3, thu 110 và chi 188 → đốt 78/tháng. 921/78 ≈ 11,8 tháng; thu thêm Y 90 đúng tháng 4 thì khoảng 13,0 tháng. Giả định không có vốn mới, không gia hạn X; bỏ qua tính nguyên tháng khi nói “khoảng”.

Mua/thuê: dùng PV với lãi tháng bằng lãi năm/12, chi cuối tháng. Ở 15%/năm, PV tiền thuê thấp hơn mua 360 nên chọn Thuê; ở 8%, PV cao hơn 360 nên chọn Mua. Không so đơn thuần 12 × 36 với 360.

## Giá vốn và giá bán

Chi phí AI = 2 × (3.000 × 2 + 800 × 10) / 1.000.000 × 26.170 × 1,05 = **769,398 đồng/bài**. Chi phí kiểm tra = 10% × 3/60 × 120.000 = **600 đồng/bài**. Các khoản khác = 80 + 150 + 20 = **250 đồng/bài**. Tổng **1.619,398**, phần chìm/AI **110,48%**; giá sàn 3 lần là **4.858,194**. Phí vượt 5.500 cao hơn sàn.

Khách thường trả 3,9 triệu, giá vốn 809.699 đồng/tháng; khách lớn trả 3,9 triệu + (2.500 − 600) × 5.500 = 14,35 triệu, giá vốn 4.048.495 đồng. Khách lớn trả 57,4% neo lương 25 triệu, chưa vượt 70%. “Còn dư địa” ở khách nhỏ chỉ là kết quả phép thử, không chứng minh họ muốn mua.

Gói không giới hạn 3,9 triệu: riêng khách lớn đã lỗ gộp 148.495 đồng trước chia; biên −3,81%. Chia đối tác 20% thì lỗ 928.495 đồng, biên −23,81% trên doanh thu khách trả. Do vậy không dùng gói này để cứu tỷ lệ neo lương.

Cột “Chi phí AI” ở sheet 2 thực tế nhân số bài với **toàn bộ giá vốn** của sheet 1, không chỉ token; giữ đúng công thức mẫu. Tỷ lệ khách lớn gói kết hợp khoảng 0,282; gói không giới hạn khoảng 1,038.

## Ba câu hỏi riêng của đề

1. **Mô hình đắt nhưng biên trên 70% vì sao?** Bình quân 1.000 bài/khách/tháng, doanh thu 6.512.500 đồng, giá vốn 1.619.398 đồng. Chênh lệch này cho biên trước chia 75,13%; đã tính người kiểm tra và vận hành. Chưa trừ CAC, đội cố định và xây dựng.
2. **Chia đối tác còn bao nhiêu?** Giữ 5.210.000 đồng, lợi nhuận gộp 3.590.602 đồng. Biên trên doanh thu khách trả = 55,13%, “ổn” theo mốc trên 50% của lớp. Sheet 4 chia cho doanh thu giữ lại nên là 68,92%. Trần chia tự tính để NPV 24 tháng bằng 0 là 39,34%; không coi đây là vùng an toàn khi các biến khác cũng xấu.
3. **Khách lớn bỏ đi thì sao?** 25% số khách mang lại 55,09% doanh thu; phí vượt chiếm 40,12% doanh thu cả tệp. Sheet 5 dòng 68 giả định thay toàn bộ khách lớn bằng khách nhỏ nhưng giữ số lượng và tốc độ khách: NPV −57,7 triệu, hoàn vốn danh nghĩa tháng 23, không hết tiền trong 24 tháng. Nếu mất khách mà chưa thay được, tình hình có thể xấu hơn; đây không phải cùng phép thử.

## Ngưỡng theo dõi

| Chỉ số | Hiện tại cơ sở | [TỰ TÍNH] NPV = 0 | Phía nguy |
| --- | ---: | ---: | --- |
| Doanh thu giữ lại/khách/tháng | 5.210.000 | 3.950.399,52 | Thấp hơn |
| Biên trên doanh thu giữ lại | 68,92% | 44,74% | Thấp hơn |
| CAC | 7.000.000 | 16.453.008,36 | Cao hơn |
| Khách mới tháng đầu | 10 | 5,26085 → ít nhất 6 | Thấp hơn |
| Cố định/tháng | 160.000.000 | 330.340.408,91 | Cao hơn |
| Chia đối tác | 20% | 39,34% | Cao hơn |

CAC tối đa tương ứng LTV/CAC khoảng **4,85 lần**, không phải mốc 3. “Đáng lo” đề xuất khi khoảng cách tới ngưỡng ≤10% tính tương đối; “nguy” khi qua ngưỡng về phía bất lợi. Đây là quy ước vận hành đề xuất, chưa phải số đo hay luật của đề. Dũng theo dõi mỗi tuần; chỉ số tháng dùng số lũy kế và chốt lại khi đủ tháng. Không dùng tăng trưởng “khách mới tháng 1” làm ngưỡng cứng cho mọi tháng sau.

## Kế hoạch thử đề xuất

8 trung tâm (6 nhỏ, 2 lớn), 8 tuần, trần chi 60 triệu. Đây là kế hoạch để đo giả định, **không thay đổi** mô hình 3 tỷ ngân sách, 600 triệu xây dựng, 160 triệu cố định của đề và chưa phải tiền đã chi. Dũng phụ trách tổng hợp; cần giáo viên trung tâm chấm đối chiếu 200 bài. Điều kiện mở rộng: doanh thu giữ lại đạt ngưỡng, tối đa 10% bài cần sửa điểm, và đủ người/nguồn lực kiểm tra. Hoãn tuyển đội 5 người trong khi chưa có bằng chứng. Nếu chạm trần 60 triệu trước đủ mẫu, dừng tuyển trung tâm mới và báo thiếu mẫu.

NẾU doanh thu giữ lại/khách dưới 3,9504 triệu/tháng TRONG 2 tháng liên tiếp trên cả 8 trung tâm THÌ Dũng dừng mở rộng, đàm phán lại gói và tỷ lệ chia; KHÔNG THÌ không giảm phí vượt dưới sàn 4.858 đồng/bài. Từ “KHÔNG THÌ” là việc cấm làm, không phải nhánh ngược lại.

## Mở rộng tùy chọn tại nhà

Giữ mọi giả định cơ sở, chỉ thay một biến:
- Gửi lô giảm 50% **giá token**, giữ tỷ lệ gọi lại, người kiểm tra và các khoản khác: giá vốn 1.234,699 đồng/bài; NPV +4,586 tỷ; biên sau chia/doanh thu khách trả 61,04%; hoàn vốn tháng 14.
- Đối tác lấy 30%: NPV +1,697 tỷ; biên sau chia/doanh thu khách trả 45,13%, “đáng lo” theo mốc lớp; hoàn vốn tháng 19.

Đây là tính độc lập bổ sung, không thay công thức hoặc đầu vào bản Excel nộp. Giá giảm 50% là giả định câu hỏi của đề; chưa xác minh nhà cung cấp có gói tương ứng.

## Lời trình bày khoảng 3 phút

**Slide 1 – khoảng 55 giây.** Tôi chọn thử nghiệm nhỏ ChấmNhanh, giữ gói 3,9 triệu đồng mỗi tháng gồm 600 bài, vượt thu 5.500 đồng mỗi bài. Khách trả tiền là trung tâm ngoại ngữ, bán qua đối tác chia 20%. Một việc là chấm bài viết 250–300 từ theo bốn tiêu chí và trả nhận xét trong 24 giờ. Toàn bộ đầu vào lấy từ Đề bài 2, chưa phải số đo thật. Giá vốn 1.619 đồng, gồm gọi mô hình 769 đồng, kiểm tra 600 đồng, các khoản khác 250 đồng. Biên trước chia 75,13%, sau chia trên doanh thu khách trả 55,13%. Tôi chưa coi điều này là bằng chứng khách chấp nhận giá.

**Slide 2 – khoảng 60 giây.** Cơ sở có NPV 3,513 tỷ và hoàn vốn dự án tháng 15; hoàn vốn CAC 1,95 tháng là chỉ tiêu khác. Lạc quan 15,025 tỷ, nhưng xấu âm 3,234 tỷ và hết tiền tháng 17. Churn xấu 7,2%, CAC 10,5 triệu, đủ sốc theo đề. Doanh thu bình quân giảm 20% làm NPV mất 2,906 tỷ, lớn nhất trong bảy biến thử. Chỉ 25% khách lớn mang lại 55,09% doanh thu. Nếu thay toàn bộ họ bằng khách nhỏ, NPV còn âm 57,7 triệu. Vì vậy chỉ số mỗi khách tốt chưa đủ để triển khai toàn bộ.

**Slide 3 – khoảng 60 giây.** Tôi đề xuất thử tám trung tâm trong tám tuần, trần chi 60 triệu, hoãn tuyển đội đầy đủ. Chỉ mở rộng khi doanh thu đạt ngưỡng và tối đa 10% bài phải sửa điểm trên 200 bài đối chiếu. Tôi theo dõi hằng tuần sáu mức hòa vốn. Nếu doanh thu giữ lại dưới 3,9504 triệu mỗi khách trong hai tháng liên tiếp trên đủ tám trung tâm, tôi dừng mở rộng và đàm phán lại gói, tỷ lệ chia. Việc cấm làm là hạ phí vượt dưới sàn. Trần chia 39,34% chỉ đúng khi các biến khác giữ nguyên, không nên đàm phán sát trần. Thử nghiệm là để đo, chưa được thực hiện.
