# Manual Testing (Part 1)
## Định nghĩa kiểm thử
Kiểm thử là quá trình đánh giá chất lượng phần mềm hoặc hệ thống để xác định tính đúng đắn, tính hoạt động và tính đầy đủ của chúng. Kiểm thử giúp đảm bảo rằng phần mềm hoặc hệ thống đáp ứng được các yêu cầu và mong đợi của người sử dụng cuối.

### Mục đích của kiểm thử phần mềm

Mục đích của kiểm thử phần mềm là đảm bảo tính đúng đắn, tính hoạt động và tính đầy đủ của phần mềm. Kiểm thử phần mềm cũng nhằm đảm bảo rằng phần mềm được phát triển đúng theo các yêu cầu của khách hàng, đáp ứng các tiêu chuẩn chất lượng và cải thiện hiệu suất của phần mềm.

Ngoài ra, kiểm thử phần mềm cũng giúp giảm thiểu các rủi ro và chi phí trong quá trình phát triển phần mềm bằng cách phát hiện các lỗi sớm và sửa chữa chúng trước khi phần mềm được triển khai.

### Tầm quan trọng của kiểm thử phần mềm

Tầm quan trọng của kiểm thử phần mềm không chỉ nằm ở việc đảm bảo tính đúng đắn, tính hoạt động và tính đầy đủ của phần mềm, mà còn ở việc giúp tăng cường sự tin tưởng của khách hàng đối với sản phẩm phần mềm.

Các sản phẩm phần mềm được kiểm thử kỹ lưỡng cũng giúp tăng cường uy tín của công ty và tăng khả năng cạnh tranh trên thị trường.

Bên cạnh đó, việc áp dụng kiểm thử phần mềm giúp tối ưu hóa quá trình phát triển phần mềm, giảm thiểu rủi ro và chi phí phát sinh trong quá trình triển khai sản phẩm.

### Các định nghĩa cơ bản trong kiểm thử phần mềm:

- Test case: là một bộ sưu tập các bước thực hiện kiểm thử nhằm kiểm tra tính năng hoặc tính năng của phần mềm. Một test case cần phải mô tả rõ ràng các bước thực hiện, dữ liệu đầu vào, kỳ vọng đầu ra, và các điều kiện tiên quyết để có thể kiểm tra tính chính xác và đầy đủ của phần mềm.

- Test plan: là một tài liệu mô tả chi tiết các hoạt động kiểm thử sẽ được thực hiện để đảm bảo rằng phần mềm đáp ứng được các yêu cầu chức năng và phi chức năng. Test plan cần phải được xây dựng trước khi bắt đầu quá trình kiểm thử và bao gồm các phần như mục đích, phạm vi, tiêu chuẩn kiểm thử, kế hoạch kiểm thử, tài nguyên, lịch trình, đánh giá kết quả kiểm thử.

- Test suite: là một tập hợp các test case liên quan đến nhau và được tổ chức để kiểm tra một chức năng hoặc một tính năng cụ thể của phần mềm.

- Test environment: là môi trường phần mềm được cài đặt để thực hiện các hoạt động kiểm thử, bao gồm phần mềm kiểm thử, cơ sở dữ liệu, phần cứng và các thành phần khác.

- Traceability matrix: là một tài liệu thể hiện mối quan hệ giữa các yêu cầu chức năng và phi chức năng, các test case và các kết quả kiểm thử. Traceability matrix giúp kiểm tra tính đầy đủ của các test case, đảm bảo rằng tất cả các yêu cầu đã được kiểm tra và đánh giá hiệu quả của các hoạt động kiểm thử.

## Các phương pháp kiểm thử
### Có nhiều phương pháp kiểm thử, bao gồm:

- Kiểm thử đơn vị (Unit testing): kiểm thử các đơn vị code riêng lẻ của phần mềm để xác định tính đúng đắn và chức năng của chúng.

- Kiểm thử tích hợp (Integration testing): kiểm thử sự tương tác giữa các phần của phần mềm hoặc hệ thống để đảm bảo tính tương thích và tính đầy đủ của chúng.

- Kiểm thử hệ thống (System testing): kiểm thử toàn bộ hệ thống phần mềm để đảm bảo rằng nó đáp ứng các yêu cầu chức năng và phi chức năng.

- Kiểm thử chấp nhận (Acceptance testing): kiểm thử bởi người sử dụng hoặc khách hàng để đảm bảo rằng phần mềm hoặc hệ thống đáp ứng được các yêu cầu và mong đợi của họ.

## Quy trình kiểm thử
### Quy trình kiểm thử bao gồm các bước sau:

- Xác định các yêu cầu và mong đợi của khách hàng và người sử dụng cuối.

- Lập kế hoạch và thiết kế kiểm thử, bao gồm việc xác định các phương pháp, tài nguyên và thời gian cần thiết.

- Thực hiện các test case, ghi lại kết quả kiểm thử và báo cáo các lỗi và vấn đề.

- Sửa chữa các lỗi và vấn đề đã phát hiện.

- Lặp lại các bước trên cho đến khi phần mềm hoặc hệ thống đáp ứng được các yêu cầu và mong đợi của khách hàng và người sử dụng cuối.

## Chuẩn bị và thiết kế kiểm thử
### Chuẩn bị và thiết kế kiểm thử bao gồm các bước sau:
- Xác định các yêu cầu và mong đợi của khách hàng và người sử dụng cuối.

- Thiết kế kế hoạch kiểm thử, bao gồm các mục đích, phạm vi, tiêu chuẩn kiểm thử, tài nguyên, lịch trình và kế hoạch đánh giá kết quả kiểm thử.

- Thiết kế test case dựa trên các yêu cầu và mong đợi của khách hàng và người sử dụng cuối. Test case nên được thiết kế sao cho đủ để kiểm tra tính chính xác, tính đầy đủ và tính hoạt động của phần mềm.

- Xác định các tiêu chuẩn và các trường hợp kiểm thử. Tiêu chuẩn kiểm thử nên được thiết kế để đảm bảo rằng phần mềm đáp ứng các tiêu chuẩn chất lượng cần thiết. Các trường hợp kiểm thử nên bao gồm các tình huống và kịch bản khác nhau để đảm bảo tính đầy đủ của kiểm thử.

- Xây dựng môi trường kiểm thử. Môi trường kiểm thử nên được xây dựng để phù hợp với yêu cầu của kiểm thử và đảm bảo rằng phần mềm được kiểm thử trong môi trường giống với môi trường thực tế nhất có thể.

- Thực hiện kiểm thử bằng các test case và phương pháp kiểm thử đã được thiết kế.

- Theo dõi, đánh giá và báo cáo kết quả kiểm thử. Kết quả kiểm thử nên được đánh giá và báo cáo đầy đủ để có thể cải thiện quá trình kiểm thử và phát triển phần mềm trong tương lai.
