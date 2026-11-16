prompt 1 zero-shot

bạn là nhân viên phân loại phản hồi khách hàng

hãy đọc từng phản hồi và phân loại thành 3 nhóm

tích cực: khách hàng hài lòng, khen ngợi

tiêu cực: khách hàng phàn nàn, không hài lòng

yêu cầu hỗ trợ: khách hàng cần giải quyết vấn đề cụ thể

trả kết quả thành bảng gồm STT, phản hồi, nhãn phân loại và lý do

prompt 2 few-shot

bạn là nhân viên phân loại phản hồi khách hàng

hãy phân loại phản hồi thành 3 nhóm tích cực, tiêu cực và yêu cầu hỗ trợ

ví dụ 1

phản hồi: sản phẩm rất đẹp, tôi rất thích

nhãn: tích cực

lý do: khách hàng khen sản phẩm

ví dụ 2

phản hồi: giao hàng quá chậm, tôi không hài lòng

nhãn: tiêu cực

lý do: khách hàng phàn nàn về giao hàng

ví dụ 3

phản hồi: sản phẩm bị lỗi, tôi muốn đổi hàng

nhãn: yêu cầu hỗ trợ

lý do: khách hàng cần giải quyết vấn đề

hãy dựa vào các ví dụ trên để phân loại phản hồi và xuất kết quả thành bảng

kết quả phân loại

| STT | Phản hồi | Nhãn phân loại | Lý do |
|---|---|---|---|
| 1 | Sản phẩm đẹp, giao hàng nhanh, rất hài lòng | Tích cực | Khách hàng hài lòng về sản phẩm và giao hàng |
| 2 | Tôi đã đặt hàng 5 ngày nhưng chưa nhận được | Tiêu cực | Khách hàng phàn nàn vì giao hàng chậm |
| 3 | Tai nghe không kết nối được Bluetooth | Yêu cầu hỗ trợ | Sản phẩm gặp lỗi cần được xử lý |
| 4 | Nhân viên tư vấn rất nhiệt tình | Tích cực | Khách hàng khen nhân viên |
| 5 | Tôi muốn hoàn tiền vì sản phẩm bị lỗi | Yêu cầu hỗ trợ | Khách hàng cần được hỗ trợ hoàn tiền |

so sánh kết quả

zero-shot phân loại nhanh nhưng có thể chưa thống nhất khi gặp phản hồi khó

few-shot có ví dụ mẫu nên kết quả rõ ràng và nhất quán hơn

kết luận

few-shot phù hợp hơn vì giúp AI phân loại chính xác và thống nhất hơn
