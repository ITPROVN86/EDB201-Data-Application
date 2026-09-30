# EDB201 – Data Application | Ứng dụng dữ liệu

EDB201 giúp sinh viên dùng dữ liệu thương mại điện tử để trả lời câu hỏi kinh doanh, kiểm tra độ tin cậy của kết quả và đề xuất hành động có thể đo lường. Tình huống xuyên suốt gồm khách hàng, đơn hàng, dòng hàng, sản phẩm và danh mục sản phẩm có thuộc tính thay đổi theo ngành hàng. Không yêu cầu kiến thức lập trình trước môn học; nên biết thao tác bảng tính và kiến thức thương mại điện tử cơ bản.

## Kết quả học tập

Sau môn học, sinh viên có thể:

1. Giải thích nguồn dữ liệu, quan hệ giữa các bảng và cấu trúc document; chọn cách biểu diễn dữ liệu phù hợp với nhu cầu kinh doanh.
2. Dùng SQL để lọc, tổng hợp và nối dữ liệu; tính KPI bán hàng, khách hàng và kiểm tra kết quả.
3. Đọc và truy vấn document sản phẩm trong MongoDB bằng bộ lọc và phép chọn trường cơ bản; giải thích khi nào mô hình document hữu ích.
4. Phát hiện và xử lý dữ liệu thiếu, trùng hoặc không nhất quán; ghi lại tác động đến KPI.
5. Diễn giải kết quả đã kiểm chứng, nêu giới hạn và đề xuất hành động khả thi với KPI theo dõi.
6. Nếu dùng AI để soạn hoặc sửa truy vấn, ghi nhận cách sử dụng và tự kiểm tra kết quả độc lập.

## Công cụ và phạm vi

| Công cụ | Mục đích |
|---|---|
| PostgreSQL và DBeaver | Truy vấn các bảng giao dịch, kiểm tra số bản ghi và KPI |
| Excel hoặc Google Sheets | Đối chiếu mẫu dữ liệu, ghi nhật ký chất lượng và trình bày kết quả |
| MongoDB Compass | Nhập collection đã chuẩn bị, lọc và chọn trường của document JSON |
| Nền tảng chia sẻ tệp được phê duyệt | Nộp truy vấn, bằng chứng kiểm tra và báo cáo |

Giảng viên cung cấp bộ dữ liệu, data dictionary, định nghĩa KPI, hướng dẫn thiết lập và số bản ghi đối chiếu. Search engine, cache, warehouse/lakehouse, Power BI, machine learning và RAG không phải nội dung triển khai hay tiêu chí chấm điểm bắt buộc.

## Lộ trình 20 buổi

| Buổi | Nội dung và sản phẩm thực hành |
|---:|---|
| 1 | Tình huống kinh doanh, nguồn dữ liệu, câu hỏi và KPI |
| 2 | Bảng, khóa, quan hệ; theo dõi một đơn hàng và nhận diện nguy cơ đếm trùng |
| 3 | Kết nối PostgreSQL bằng DBeaver, nhập CSV, kiểm tra cấu trúc và số bản ghi |
| 4 | SQL cơ bản: `SELECT`, `WHERE`, `ORDER BY`, lọc ngày và trạng thái |
| 5 | Chất lượng dữ liệu: giá trị thiếu, bản ghi trùng, trạng thái không hợp lệ; quy tắc xử lý |
| 6 | `GROUP BY`, `HAVING`; doanh thu, số đơn và giá trị đơn hàng trung bình (AOV) |
| 7 | `INNER JOIN`, `LEFT JOIN`; đối chiếu số dòng và doanh thu sau khi nối bảng |
| 8 | Tình huống SQL: kết quả theo nhóm hàng và khách hàng; giao Assignment 1 |
| 9 | **Progress Test 1 (Quiz)** và thực hành báo cáo SQL |
| 10 | Assignment 1; nộp truy vấn, kiểm tra KPI và đề xuất kinh doanh |
| 11 | JSON và thuộc tính sản phẩm khác nhau giữa các ngành hàng |
| 12 | MongoDB Compass: nhập collection, lọc và chọn trường sản phẩm |
| 13 | Chọn SQL hay document theo nhu cầu; giao Assignment 2 |
| 14 | Truy vấn MongoDB cơ bản và diễn giải kết quả cho danh mục sản phẩm |
| 15 | Kết hợp KPI bán hàng từ SQL với thuộc tính danh mục qua mã sản phẩm được cung cấp |
| 16 | Assignment 2; nộp bằng chứng MongoDB và lập luận lựa chọn mô hình dữ liệu |
| 17 | **Progress Test 2 (Quiz)** và ôn tập chất lượng dữ liệu, NoSQL |
| 18 | Dùng AI hỗ trợ truy vấn có kiểm chứng: kiểm tra lược đồ, mẫu và tổng đối chiếu |
| 19 | Diễn tập Final Project: bằng chứng, giới hạn, hành động và câu hỏi bảo vệ |
| 20 | **Final Project:** trình bày theo nhóm và trả lời câu hỏi cá nhân |

## Đánh giá

| Thành phần | Tỷ trọng | Yêu cầu chính |
|---|---:|---|
| Progress Test 1 (Quiz) | 10% | Cá nhân, 30 phút; dữ liệu quan hệ, SQL cơ bản, chất lượng dữ liệu và KPI từ buổi 1–8 |
| Progress Test 2 (Quiz) | 10% | Cá nhân, 30 phút; JSON, MongoDB cơ bản, lựa chọn SQL/document và diễn giải dữ liệu từ buổi 10–16 |
| Assignment 1 – E-commerce Sales Evidence | 20% | Nhóm; truy vấn SQL chạy lại được, nhật ký kiểm tra, KPI và khuyến nghị ngắn |
| Assignment 2 – Product Catalogue Decision | 20% | Nhóm; bằng chứng truy vấn MongoDB cơ bản, quyết định mô hình dữ liệu và đề xuất có KPI |
| Final Project – Presentation and Defense | 40% | Nhóm trình bày một vấn đề thương mại điện tử; mỗi thành viên trả lời câu hỏi cá nhân; điểm thành phần tối thiểu **4,0/10** |

Final Project cần có KPI SQL đã đối chiếu, một ví dụ document sản phẩm và truy vấn MongoDB cơ bản, bằng chứng chất lượng dữ liệu, lý do chọn cách biểu diễn dữ liệu, khuyến nghị khả thi và cách đo hiệu quả. Không yêu cầu xây dựng hệ thống SQL–NoSQL hoàn chỉnh hoặc triển khai search/cache. Điểm cá nhân có thể khác nhau theo phần đóng góp và câu trả lời bảo vệ.

## Quy cách bài nộp

Mỗi bài nộp cần có dữ liệu đầu vào hoặc tham chiếu tới bộ dữ liệu được cấp; truy vấn có thể chạy lại; kết quả và cách kiểm tra; định nghĩa KPI; nhận định dựa trên bằng chứng; phần việc của từng thành viên. Nếu sử dụng AI, ghi công cụ, mục đích, phần đã sửa và phép kiểm tra độc lập. Không đưa dữ liệu cá nhân thật hoặc thông tin nhạy cảm vào công cụ AI công cộng.

## Học liệu

### Tài liệu chính

1. Kenneth C. Laudon và Carol Guercio Traver, *E-Commerce 2023–2024: Business, Technology, Society*, Global Edition, 18th Edition, Pearson, 2023. Đọc các phần được chỉ định để hiểu bối cảnh kinh doanh, khách hàng, sản phẩm và hoạt động thương mại điện tử.
2. Anthony DeBarros, *Practical SQL, 2nd Edition: A Beginner's Guide to Storytelling with Data*, No Starch Press, 2022. Đọc các phần được chỉ định về PostgreSQL, truy vấn, nối bảng, tổng hợp và kiểm tra dữ liệu. Window functions, stored procedures và phân tích không gian không thuộc yêu cầu cốt lõi.

### Tài liệu tham khảo có chọn lọc

- Carlos Coronel và Steven Morris, *Database Systems: Design, Implementation, & Management*, 14th Edition, Cengage, 2023: khóa, quan hệ và thiết kế dữ liệu nền tảng.
- Joe Reis và Matt Housley, *Fundamentals of Data Engineering*, O'Reilly Media, 2022: nguồn, chất lượng và dòng dữ liệu; không yêu cầu triển khai pipeline.
- Martin Kleppmann và Chris Riccomini, *Designing Data-Intensive Applications*, 2nd Edition, O'Reilly Media, 2026: tài liệu tham khảo cho giảng viên về lựa chọn kiến trúc.
- [MongoDB Documentation](https://www.mongodb.com/docs/): document, truy vấn cơ bản và MongoDB Compass. Giảng viên chỉ định các trang cần đọc cho buổi 11–14.

Lộ trình thực hành: **câu hỏi kinh doanh → nguồn và chất lượng dữ liệu → truy vấn và kiểm tra KPI → diễn giải → hành động có thể đo lường**.
