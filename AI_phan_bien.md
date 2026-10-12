# AI phản biện và phạm vi hỗ trợ

Bài cá nhân của Lưu Xuân Dũng – 2A202602746, dùng Đề bài 2 ChấmNhanh. Codex hỗ trợ đọc đề, tính và điền Excel, phát hiện lỗi ô E29 trong mẫu, kiểm tra bằng Excel, viết quyết định và ba slide. Chưa có bằng chứng học viên đã tự tính độc lập trước khi dùng AI; không mô tả phản biện này như một buổi phỏng vấn khách hay phản biện của người thật. Không gọi API hay dùng dữ liệu học viên/khách hàng thật.

## Nhiệm vụ 0 – hai câu kiểm tra

1. Ai sử dụng điểm/nhận xét và ai ký trả phí: học viên, giáo viên hay trung tâm?
2. Một “việc” có kết thúc ở lần chấm điểm đầu tiên hay phải gồm nhận xét và xử lý bài sát ngưỡng/khiếu nại?

Quy ước dùng trong bài: trung tâm trả phí, giáo viên và học viên nhận giá trị; một việc là một bài có điểm bốn tiêu chí và nhận xét. Bài được chọn kiểm tra dùng chi phí kiểm tra riêng đã tính vào giá vốn.

## Phần A – chỗ dễ nhầm và hai câu tự soát

Khoản trả trước X, nghiệm thu Y và trả chậm AI dễ bị đưa nhầm kỳ khi nhìn tiền vào/ra. Gốc vay và mua tài sản cũng có thể bị ghi nhầm vào doanh thu/chi phí tháng.

1. Cuối tháng 1 trung tâm đã cung cấp bao nhiêu tháng dịch vụ cho X, và đã thu tiền những tháng nào?
2. Tháng 2 nghiệm thu Y nhưng chưa thu tiền; chi AI tháng 1 lúc này đã trả: mỗi khoản nằm ở tháng nào trong kết quả kinh doanh và dòng tiền?

Khi kiểm tra số đã điền, phát hiện E29 của file mẫu là −8 không khớp E27 − E28; thay bằng công thức trong ô vàng, không sửa cảnh báo.

## Nhiệm vụ 1 – tối đa ba khoản có thể ước thấp

1. **Kiểm tra 3 phút và tỷ lệ 10%:** bài khiếu nại có thể cần đọc lại toàn bộ hoặc trao đổi giáo viên. Đo trên 200 bài, ghi số bài cần sửa, phút xử lý trung vị và nhóm chậm; tách bài chọn kiểm tra khỏi mẫu đánh giá định kỳ để tránh tính trùng.
2. **Gọi lại 5%:** có thể chưa gồm đầu ra thiếu tiêu chí hoặc phản hồi bị trả lại. Ghi số lần gọi, token vào/ra và lý do gọi lại cho mỗi bài trong log; dùng tổng chi phí trên số bài hoàn thành.
3. **Hạ tầng 80, đánh giá 150 và khác 20 đồng/bài:** tách hóa đơn tăng theo lượt khỏi phí cố định; tính thời gian giáo viên chấm mẫu, lưu nhật ký và hỗ trợ khiếu nại. Đối chiếu chi theo tháng chia số bài hoàn thành, không tự thêm số để đạt mốc phần chìm.

Không đổi số của đề thành “đã đo”.

## Nhiệm vụ 2 – hai lý do khách từ chối hoặc mặc cả

1. Trung tâm nhỏ chỉ dùng 500 bài nhưng mua gói gồm 600, có thể muốn gói nhỏ hơn hoặc lo không sử dụng đủ. Đây là suy đoán; phỏng vấn người ký ngân sách về khối lượng theo mùa, mức chi hiện tại và điều kiện mua.
2. Trung tâm lớn trả 14,35 triệu/tháng, có thể so với giờ giáo viên sẵn có, chất lượng nhận xét và công sức xử lý khiếu nại. Hỏi số giáo viên chấm thực tế, giờ được tái sử dụng và mức chấp nhận phí vượt; không hạ dưới giá sàn chỉ để dễ bán.

Neo 25 triệu là giả định đề. Chưa có ý kiến khách thật hay bằng chứng giá có thể chấp nhận.

## Nhiệm vụ 3 – ba giả định cần bằng chứng nhất

1. **Tệp 75% nhỏ/25% lớn và mức dùng 500/2.500:** ít nhất bao nhiêu trung tâm lớn thực sự cam kết khối lượng này, và còn dùng trong hè không?
2. **10 khách mới đầu kỳ, tăng 5%/tháng và CAC 7 triệu:** pipeline, tỷ lệ ký, đào tạo, triển khai và chi phí đồng tiếp thị có hỗ trợ được tốc độ đó không?
3. **Churn 4,5% và kiểm tra 10%:** cohort qua mùa hè và mẫu chấm đối chiếu cho biết tỷ lệ ngừng dùng, bài phải sửa và thời gian xử lý ra sao?

LTV dùng lợi nhuận gộp sau chia, không dùng doanh thu. LTV/CAC 11,40 chưa loại trừ rủi ro hết tiền của công ty.

## Nhiệm vụ 4 – ba điểm đã đối chiếu

1. Giữ quyết định Thử nghiệm nhỏ vì cơ sở dương nhưng xấu hết tiền tháng 17; không đổi giả định để né số âm. Quy mô 8 trung tâm/8 tuần, trần 60 triệu và ngưỡng sửa điểm 10% trên 200 bài là đề xuất thêm, chưa thực hiện; không thay mô hình đề.
2. Phân biệt biên 55,13% trên doanh thu khách trả với 68,92% trên doanh thu giữ lại; trần chia 39,34% có trong mức tự tính. Biến nguy hiểm nhất và tình huống mất khách lớn khớp sheet 5.
3. Luật đủ chỉ số, ngưỡng 3,9504 triệu, hai tháng, mẫu đủ tám trung tâm, Dũng phụ trách, hành động dừng mở rộng/đàm phán và việc cấm hạ phí vượt dưới sàn. Mẫu thử nhỏ nên chưa đủ kiểm chứng churn dài hạn; tiếp tục theo cohort trước khi tuyển đầy đủ.

## Giới hạn kết quả

Đây là bài mô hình tài chính với đầu vào giả định. Chưa có khách ký, doanh thu thực, hợp đồng đối tác, log token hay kết quả pilot. Không xác nhận tỷ giá/giá mô hình hiện hành; chép nguồn đề ghi 04/10/2026. File đã chuẩn bị cục bộ, chưa gửi trên VLearn.
