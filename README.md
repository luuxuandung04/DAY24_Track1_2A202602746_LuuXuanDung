# Day 24 – Track 1: ChấmNhanh

**Học viên:** Lưu Xuân Dũng – **2A202602746**. **Hình thức:** làm cá nhân, kiêm điều phối, tính số, phản biện và ghi chép. Ngày hoàn thiện file: 12/10/2026.

Bài dùng **Đề bài 2 – ChấmNhanh** trong `CS9_DeBai_GiaDinh.pdf`, trang 4–5. Phần A giữ nguyên tình huống **Trợ Lý Xanh**. Số sản phẩm, giá mô hình và tỷ giá đều được chép từ đề; chưa có phỏng vấn, log API, doanh thu hay vốn thật.

## File bàn giao

- [Excel để nộp](DAY24_Track1_2A202602746_LuuXuanDung.xlsx): tạo từ bản trống; đủ nhiệm vụ 0–4, các câu hỏi Phần A và bài mua/thuê máy chủ. Công thức gốc, ô vàng, bảo vệ sheet, danh sách chọn và các dòng ẩn của mẫu được giữ. Sheet 6 không áp dụng; ô điểm giảng viên không điền.
- [Ba slide trình bày](ChamNhanh_3slides.pptx): có lời nói và nguồn trong speaker notes; dùng để trình bày khoảng 3 phút, không thay file Excel.
- [Giải thích số và lời trình bày](Giai_thich_va_trinh_bay.md).
- [Phản biện và công khai hỗ trợ AI](AI_phan_bien.md).

## Kết quả chính

**Quyết định: Thử nghiệm nhỏ**, không triển khai toàn bộ chỉ vì LTV/CAC đẹp.

| Chỉ số | Kết quả |
| --- | ---: |
| Giá vốn / bài | 1.619,398 đồng |
| Giá sàn tham khảo / bài | 4.858,194 đồng |
| Phí trung tâm / tháng | 3.900.000 đồng, gồm 600 bài |
| Phí vượt | 5.500 đồng/bài |
| Doanh thu bình quân trước chia / khách / tháng | 6.512.500 đồng |
| Doanh thu bình quân giữ lại sau chia / khách / tháng | 5.210.000 đồng |
| Biên trước chia | 75,13% |
| Biên sau chia / doanh thu khách trả | 55,13% |
| Biên / doanh thu giữ lại (sheet 4) | 68,92% |
| LTV/CAC cơ sở | 11,40 lần |
| Hoàn vốn CAC cơ sở | 1,95 tháng |
| NPV 24 tháng cơ sở | +3,513 tỷ đồng |
| Hoàn vốn dự án cơ sở | Tháng 15 |
| NPV xấu; tháng hết tiền | −3,234 tỷ; tháng 17 |
| Biến nguy hiểm nhất | Doanh thu bình quân giảm |
| NPV nếu thay khách lớn bằng khách nhỏ | −57,7 triệu đồng |
| Trần chia đối tác hòa vốn, đổi một biến | 39,34% |

Ngưỡng sheet 5 đổi từng biến riêng, giữ các biến khác. 39,34% là trần hòa vốn, không phải tỷ lệ nên chấp nhận sát trần; nhiều cú sốc đồng thời có thể làm mô hình xấu hơn.
