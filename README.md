# BÀI THỰC HÀNH 9
# XÂY DỰNG HỆ THỐNG TỔNG HỢP VÀ PHÂN TÍCH TÀI LIỆU NHIỀU NGUỒN

## I. GIAI ĐOẠN 1: TIẾP NHẬN VÀ PHÂN LOẠI TÀI LIỆU

### 1. Bảng phân loại và quản lý nguồn tài liệu

| Mã nguồn | Tên tài liệu | Định dạng | Số lượng | Nội dung chính |
|---|---|---|---:|---|
| TL01 | Quy định nhân sự 01 | PDF | Chưa xác định | Quy định chung về nhân sự |
| TL02 | Quy định nhân sự 02 | PDF | Chưa xác định | Chính sách và chế độ nhân viên |
| TL03 | Quy định nhân sự 03 | PDF | Chưa xác định | Các quy định liên quan khác |
| TL04 | Quy trình tuyển dụng | DOCX | 1 file | Các bước tuyển dụng |
| TL05 | Quy trình đánh giá nhân viên | DOCX | 1 file | Đánh giá hiệu suất |
| TL06 | Danh sách nhân sự | XLSX | 200 nhân viên | Dữ liệu nhân sự |
| TL07 | Báo cáo vấn đề vận hành | PDF | Chưa xác định | Các vấn đề phát sinh |

Tổng số tài liệu: 7 file, gồm 4 file PDF, 2 file DOCX và 1 file XLSX.

### 2. Phân loại theo chủ đề

| Nhóm tài liệu | Nguồn | Chủ đề cần khai thác |
|---|---|---|
| Chính sách nhân sự | TL01, TL02, TL03 | Quy định, quyền lợi, nghĩa vụ và chế độ |
| Tuyển dụng | TL04 | Tiếp nhận nhu cầu, đăng tuyển, phỏng vấn, tuyển chọn |
| Đánh giá nhân viên | TL05 | Tiêu chí, chu kỳ và kết quả đánh giá |
| Dữ liệu nhân sự | TL06 | Hồ sơ và thông tin quản lý nhân viên |
| Vấn đề vận hành | TL07 | Khó khăn, lỗi quy trình và nhu cầu cải tiến |

### 3. Xác định mức độ ưu tiên

| Mức độ | Nhóm tài liệu | Lý do |
|---|---|---|
| Cao | TL01, TL02, TL03 | Là căn cứ xác định các quy tắc quản lý nhân sự |
| Cao | TL04, TL05 | Mô tả trực tiếp các quy trình cần đưa vào phần mềm |
| Cao | TL07 | Giúp xác định vấn đề thực tế cần giải quyết |
| Trung bình | TL06 | Cung cấp dữ liệu để xác định cấu trúc hồ sơ và kiểm tra khả năng quản lý |

Mức độ ưu tiên trên chỉ phục vụ thứ tự phân tích, không có nghĩa tài liệu này có giá trị pháp lý cao hơn tài liệu khác.

### 4. Chiến lược phân đoạn tài liệu

Không xử lý toàn bộ tài liệu cùng lúc vì lượng thông tin lớn có thể khiến AI bỏ sót nội dung hoặc nhầm lẫn giữa các nguồn.

| Loại tài liệu | Cách phân đoạn | Cách xử lý |
|---|---|---|
| PDF quy định nhân sự | Chia theo chương, mục và khoảng 10–15 trang | Tóm tắt từng phần, trích xuất quy định |
| DOCX tuyển dụng | Chia theo từng bước của quy trình | Xác định đầu vào, người thực hiện và đầu ra |
| DOCX đánh giá | Chia theo chu kỳ, tiêu chí và kết quả | Trích xuất cách thức đánh giá |
| Excel nhân sự | Chia theo nhóm cột hoặc 40–50 dòng khi cần phân tích | Kiểm tra cấu trúc, kiểu dữ liệu và trường thông tin |
| PDF vấn đề vận hành | Chia theo từng nhóm vấn đề | Ghi nhận vấn đề, nguyên nhân được nêu và ảnh hưởng |

Đối với PDF 180 trang, nên đọc mục lục trước, sau đó chia theo chương và mục thay vì cắt trang một cách máy móc. Nếu một nội dung kéo dài qua nhiều trang, cần giữ nguyên phần liên quan để không mất ngữ cảnh.

## II. SƠ ĐỒ QUY TRÌNH XỬ LÝ TÀI LIỆU BẰNG AI

```text
              BẮT ĐẦU
                  |
                  v
       Tiếp nhận 7 tài liệu
                  |
                  v
        Kiểm tra định dạng
        và khả năng đọc file
                  |
                  v
       Phân loại theo chủ đề
                  |
                  v
       Chia nhỏ từng tài liệu
       theo trang / mục / dòng
                  |
                  v
       AI trích xuất thông tin
       theo cấu trúc thống nhất
                  |
                  v
       Lưu tóm tắt và nguồn gốc
       (Tên file + vị trí nguồn)
                  |
                  v
       Tổng hợp dữ liệu nhiều nguồn
                  |
                  v
       Đối chiếu và kiểm tra
       + Trùng lặp
       + Mâu thuẫn
       + Thiếu thông tin
                  |
                  v
        Kiểm chứng với tài liệu gốc
                  |
                  v
       Phân tích yêu cầu nghiệp vụ
                  |
                  v
       Phân loại yêu cầu hệ thống
       + Chức năng
       + Phi chức năng
                  |
                  v
       Đề xuất chức năng phần mềm
                  |
                  v
       Lập câu hỏi xác nhận
       với ban giám đốc
                  |
                  v
         HOÀN THÀNH BÁO CÁO
```

Quy trình được chia thành bốn giai đoạn chính. AI hỗ trợ xử lý thông tin nhưng người phân tích vẫn phải kiểm tra lại các nội dung quan trọng trước khi đưa vào báo cáo.

## III. GIAI ĐOẠN 2: TRÍCH XUẤT VÀ XỬ LÝ THÔNG TIN

### 1. Chuẩn hóa cấu trúc thông tin

Để dễ tổng hợp dữ liệu từ nhiều định dạng, sử dụng một cấu trúc chung:

| Trường thông tin | Ý nghĩa |
|---|---|
| ID | Mã định danh nội dung |
| Nhóm nghiệp vụ | Tuyển dụng, đánh giá, hồ sơ... |
| Nội dung | Thông tin được trích xuất |
| Đối tượng áp dụng | Nhân viên, quản lý, HR... |
| Điều kiện | Điều kiện thực hiện |
| Người phụ trách | Vai trò chịu trách nhiệm |
| Đầu vào | Thông tin cần có |
| Đầu ra | Kết quả sau khi thực hiện |
| Nguồn | Tên file |
| Vị trí | Trang, mục, bảng hoặc dòng |
| Trạng thái | Đã kiểm chứng, cần xác minh |

### 2. Bộ Prompt xử lý tài liệu

#### Prompt 1: Phân loại tài liệu

```text
Bạn là chuyên viên phân tích nghiệp vụ tại một công ty phần mềm.

Hãy đọc thông tin giới thiệu của tài liệu được cung cấp
và xác định:

1. Tên tài liệu.
2. Loại file.
3. Chủ đề chính.
4. Các nghiệp vụ liên quan.
5. Những thông tin quan trọng cần trích xuất.
6. Các tài liệu khác cần đối chiếu.

Không tự suy đoán nội dung chưa xuất hiện trong tài liệu.
Nếu không đủ thông tin, ghi "Chưa xác định".

Trả kết quả thành bảng có cấu trúc rõ ràng.
```

#### Prompt 2: Trích xuất quy định từ PDF

```text
Bạn là trợ lý phân tích tài liệu nhân sự.

Hãy phân tích phần tài liệu PDF được cung cấp,
chỉ xử lý nội dung trong phạm vi trang được chỉ định.

Trích xuất:
- Mã quy định (nếu có).
- Tên quy định.
- Nội dung chính.
- Đối tượng áp dụng.
- Điều kiện thực hiện.
- Trách nhiệm của các bên.
- Thời điểm hoặc chu kỳ áp dụng (nếu có).
- Tên file và số trang.

Yêu cầu:
Không tự viết thêm quy định.
Không thay đổi ý nghĩa nội dung gốc.
Nếu nội dung không rõ, đánh dấu "Cần xác minh".
Không kết luận quy định đã hết hiệu lực nếu tài liệu
không cung cấp căn cứ.
```

#### Prompt 3: Trích xuất quy trình từ DOCX

```text
Bạn là chuyên viên phân tích nghiệp vụ.

Hãy đọc phần quy trình trong tài liệu DOCX và chuyển
thành các bước nghiệp vụ có cấu trúc.

Với mỗi bước, xác định:
1. Tên bước.
2. Người thực hiện.
3. Điều kiện bắt đầu.
4. Dữ liệu đầu vào.
5. Hoạt động cần thực hiện.
6. Kết quả đầu ra.
7. Trường hợp ngoại lệ.
8. Vị trí nguồn trong tài liệu.

Không tự thêm bước chưa được mô tả.
Nếu thiếu thông tin về người phụ trách hoặc điều kiện,
hãy đánh dấu "Chưa được quy định rõ".
```

#### Prompt 4: Phân tích file Excel nhân sự

```text
Bạn là chuyên viên phân tích dữ liệu nhân sự.

Hãy kiểm tra cấu trúc file Excel chứa dữ liệu 200 nhân viên.

Thực hiện:
- Liệt kê tên các cột.
- Xác định kiểu dữ liệu từng cột.
- Thống kê số lượng bản ghi.
- Kiểm tra trường dữ liệu bị trống.
- Phát hiện mã nhân viên bị trùng.
- Kiểm tra dữ liệu không đúng định dạng.
- Xác định những trường có thể dùng để quản lý nhân sự.

Yêu cầu:
Không chỉnh sửa dữ liệu gốc.
Không tự điền thông tin còn thiếu.
Không hiển thị số điện thoại, địa chỉ, số định danh
hoặc thông tin cá nhân không cần thiết.
Sử dụng mã nhân viên hoặc mã thay thế để báo cáo.
Trình bày kết quả thành bảng.
```

#### Prompt 5: Phân tích vấn đề vận hành từ PDF

```text
Bạn là chuyên viên phân tích nghiệp vụ.

Hãy đọc nội dung báo cáo các vấn đề phát sinh
trong quá trình vận hành.

Với mỗi vấn đề, hãy trích xuất:
- Mã vấn đề.
- Mô tả vấn đề.
- Bộ phận liên quan.
- Quy trình bị ảnh hưởng.
- Tác động được ghi nhận.
- Nguyên nhân (chỉ khi tài liệu nêu rõ).
- Giải pháp đã được đề cập (nếu có).
- Tên file và số trang.

Phân biệt nguyên nhân được ghi nhận với nhận định
do người phân tích đưa ra.
Không tự tạo thêm nguyên nhân hoặc giải pháp.
```

#### Prompt 6: Tạo bản tóm tắt riêng cho từng tài liệu

```text
Hãy tạo bản tóm tắt cho tài liệu đã được xử lý.

Nội dung cần có:
1. Tên tài liệu.
2. Mục đích của tài liệu.
3. Các nội dung chính.
4. Các nghiệp vụ liên quan.
5. Những quy định hoặc quy trình quan trọng.
6. Thông tin còn thiếu hoặc chưa rõ.
7. Các nội dung cần đối chiếu với tài liệu khác.
8. Danh sách nguồn tham chiếu.

Giữ nguyên ý nghĩa tài liệu gốc.
Mỗi nhận định phải có nguồn cụ thể.
Không đưa ra kết luận vượt quá thông tin được cung cấp.
```

### 3. Quản lý nguồn tham chiếu

Mỗi nội dung trích xuất phải được lưu kèm nguồn để có thể tìm lại khi cần.

Ví dụ về cách ghi nguồn:

| ID | Nội dung | Nguồn | Vị trí |
|---|---|---|---|
| QD001 | Nội dung quy định nhân sự A | TL01.pdf | Trang 12–13 |
| QT001 | Các bước tuyển dụng | TL04.docx | Mục 2.1 |
| DG001 | Tiêu chí đánh giá | TL05.docx | Mục 3 |
| NS001 | Cấu trúc dữ liệu nhân viên | TL06.xlsx | Sheet 1, cột A–H |
| VH001 | Vấn đề trong quá trình vận hành | TL07.pdf | Trang 5 |

Các vị trí trên chỉ là ví dụ về cách ghi nguồn, chưa phải kết quả trích xuất từ tài liệu thật.

## IV. GIAI ĐOẠN 3: TỔNG HỢP VÀ ĐỐI CHIẾU

### 1. Prompt phát hiện nội dung trùng lặp

```text
Bạn là chuyên viên kiểm tra tính nhất quán tài liệu.

Hãy so sánh các nội dung được trích xuất từ nhiều
tài liệu khác nhau.

Xác định:
- Nội dung giống nhau hoàn toàn.
- Nội dung có ý nghĩa tương tự nhưng cách diễn đạt khác.
- Nội dung lặp lại nhưng có thêm điều kiện.
- Nội dung có thể liên quan nhưng không đủ căn cứ
  để kết luận là trùng lặp.

Với mỗi trường hợp, ghi rõ:
Tên file, vị trí nguồn và nội dung so sánh.

Không tự xóa hoặc gộp các quy định.
Hãy đề xuất nhóm nội dung cần xem xét.
```

### 2. Prompt phát hiện mâu thuẫn

```text
Bạn là chuyên viên phân tích nghiệp vụ.

Hãy đối chiếu các quy định và quy trình được trích xuất
từ các tài liệu nhân sự.

Tìm những trường hợp:
- Hai tài liệu quy định khác nhau về cùng một vấn đề.
- Quy trình mô tả không thống nhất với quy định.
- Có sự khác biệt về điều kiện thực hiện.
- Có sự khác biệt về người chịu trách nhiệm.
- Có thông tin chưa đủ căn cứ để xác định.

Lập bảng gồm:
1. Vấn đề cần đối chiếu.
2. Nội dung nguồn thứ nhất.
3. Nguồn thứ nhất và vị trí.
4. Nội dung nguồn thứ hai.
5. Nguồn thứ hai và vị trí.
6. Mức độ ảnh hưởng.
7. Câu hỏi cần xác nhận.

Không tự chọn một nội dung là đúng.
Không suy đoán tài liệu nào mới hơn đồng nghĩa với
việc tài liệu đó có giá trị thay thế tài liệu còn lại.
```

### 3. Prompt xác định thông tin còn thiếu

```text
Hãy rà soát các tài liệu đã được trích xuất
và xác định những thông tin còn thiếu để xây dựng
hệ thống quản lý nhân sự.

Tập trung vào:
- Vai trò và quyền hạn người dùng.
- Quy trình phê duyệt.
- Điều kiện tuyển dụng.
- Tiêu chí đánh giá nhân viên.
- Cách lưu trữ và cập nhật hồ sơ.
- Quy tắc bảo mật dữ liệu.
- Báo cáo và thống kê.
- Các trường hợp ngoại lệ.

Với mỗi nội dung còn thiếu, hãy ghi:
Mô tả, nghiệp vụ liên quan, mức độ ảnh hưởng
và câu hỏi cần gửi ban giám đốc.

Không tự bổ sung quy định thay cho doanh nghiệp.
```

### 4. Bảng tổng hợp nội dung trùng lặp và mâu thuẫn

Do chưa có tài liệu gốc, bảng dưới đây thể hiện các tình huống cần kiểm tra trong quá trình phân tích, không khẳng định đây là những mâu thuẫn đã xuất hiện thực tế.

| STT | Nội dung cần đối chiếu | Nguồn liên quan | Nội dung cần kiểm tra |
|---|---|---|---|
| 1 | Thông tin hồ sơ nhân viên | TL01, TL06 | Các trường thông tin có thống nhất không? |
| 2 | Điều kiện tuyển dụng | TL01, TL04 | Quy trình tuyển dụng có phù hợp quy định không? |
| 3 | Các bước phỏng vấn | TL04, TL07 | Có bước nào gây khó khăn khi vận hành không? |
| 4 | Tiêu chí đánh giá | TL02, TL05 | Tiêu chí trong hai tài liệu có giống nhau không? |
| 5 | Chu kỳ đánh giá | TL03, TL05 | Thời gian đánh giá có thống nhất không? |
| 6 | Quyền cập nhật hồ sơ | TL01, TL06 | Ai được phép thêm hoặc sửa thông tin? |
| 7 | Quy trình phê duyệt | TL02, TL04 | Có khác biệt về người phê duyệt không? |
| 8 | Lưu trữ thông tin | TL01, TL06, TL07 | Cách lưu trữ có đáp ứng nhu cầu vận hành không? |
| 9 | Báo cáo nhân sự | TL05, TL07 | Các báo cáo cần thiết đã được mô tả đầy đủ chưa? |
| 10 | Xử lý trường hợp ngoại lệ | TL01, TL04, TL05 | Các tình huống đặc biệt đã có hướng xử lý chưa? |

### 5. Phân loại mức độ xử lý

| Mức độ | Ý nghĩa | Cách xử lý |
|---|---|---|
| Cao | Mâu thuẫn có thể ảnh hưởng trực tiếp đến nghiệp vụ hoặc quyền lợi nhân viên | Yêu cầu ban giám đốc xác nhận trước khi thiết kế |
| Trung bình | Thông tin chưa thống nhất nhưng chưa ảnh hưởng trực tiếp đến chức năng chính | Đưa vào danh sách cần làm rõ |
| Thấp | Nội dung trùng lặp hoặc khác cách diễn đạt nhưng không làm thay đổi ý nghĩa | Ghi nhận và chuẩn hóa cách trình bày |

## V. GIAI ĐOẠN 4: PHÂN TÍCH YÊU CẦU NGHIỆP VỤ

### 1. Xác định các nhóm người dùng

| Vai trò | Nhu cầu chính |
|---|---|
| Ban giám đốc | Theo dõi tình hình nhân sự và xem báo cáo tổng hợp |
| Nhân viên nhân sự (HR) | Quản lý hồ sơ, tuyển dụng và đánh giá |
| Quản lý bộ phận | Theo dõi nhân viên và thực hiện đánh giá |
| Nhân viên | Xem thông tin cá nhân và kết quả đánh giá của mình |
| Quản trị hệ thống | Quản lý tài khoản, phân quyền và cấu hình hệ thống |

Đây là các vai trò đề xuất ban đầu, cần được xác nhận với doanh nghiệp.

### 2. Bảng tổng hợp yêu cầu chức năng

| Mã | Yêu cầu chức năng | Mô tả |
|---|---|---|
| FR01 | Đăng nhập | Người dùng đăng nhập bằng tài khoản được cấp |
| FR02 | Quản lý tài khoản | Tạo, khóa và quản lý tài khoản |
| FR03 | Phân quyền | Cấp quyền theo vai trò |
| FR04 | Quản lý hồ sơ nhân viên | Thêm, xem và cập nhật hồ sơ |
| FR05 | Tìm kiếm nhân viên | Tìm theo mã, tên hoặc bộ phận |
| FR06 | Quản lý tuyển dụng | Theo dõi các vị trí và ứng viên |
| FR07 | Theo dõi quy trình tuyển dụng | Quản lý trạng thái từng bước tuyển dụng |
| FR08 | Quản lý đánh giá | Tạo và theo dõi kỳ đánh giá |
| FR09 | Ghi nhận kết quả đánh giá | Lưu kết quả và nhận xét |
| FR10 | Quản lý phòng ban | Quản lý thông tin bộ phận |
| FR11 | Thống kê nhân sự | Tổng hợp số lượng và tình hình nhân sự |
| FR12 | Xuất báo cáo | Xuất báo cáo phục vụ quản lý |
| FR13 | Lưu lịch sử thay đổi | Theo dõi những thay đổi quan trọng |
| FR14 | Quản lý tài liệu | Lưu trữ tài liệu liên quan đến nhân sự |

Các chức năng trên là đề xuất phân tích ban đầu, chưa phải danh sách được ban giám đốc phê duyệt.

### 3. Bảng yêu cầu phi chức năng

| Mã | Nhóm yêu cầu | Nội dung |
|---|---|---|
| NFR01 | Bảo mật | Bảo vệ thông tin nhân viên khỏi truy cập trái phép |
| NFR02 | Phân quyền | Mỗi người dùng chỉ được truy cập chức năng phù hợp |
| NFR03 | Hiệu năng | Các thao tác tìm kiếm và truy xuất dữ liệu cần có thời gian phản hồi hợp lý |
| NFR04 | Tính toàn vẹn | Không tự ý thay đổi hoặc làm mất dữ liệu nhân sự |
| NFR05 | Khả năng sử dụng | Giao diện dễ hiểu, thuận tiện cho người dùng |
| NFR06 | Sao lưu | Có cơ chế sao lưu và phục hồi dữ liệu |
| NFR07 | Khả năng mở rộng | Có thể bổ sung chức năng khi doanh nghiệp phát triển |
| NFR08 | Nhật ký hệ thống | Ghi nhận các thao tác quan trọng |
| NFR09 | Quyền riêng tư | Hạn chế hiển thị dữ liệu cá nhân không cần thiết |
| NFR10 | Tính ổn định | Hệ thống hoạt động ổn định trong quá trình sử dụng |

Các yêu cầu về hiệu năng, thời gian phản hồi, thời gian lưu trữ và thời gian sao lưu cần được xác định bằng chỉ tiêu cụ thể sau khi trao đổi với doanh nghiệp.

### 4. Đề xuất danh sách chức năng cần xây dựng

#### Chức năng 1: Quản lý hồ sơ nhân viên

- Lưu mã nhân viên.
- Lưu họ tên và thông tin công việc cần thiết.
- Quản lý phòng ban và chức vụ.
- Cập nhật thông tin khi có thay đổi.
- Lưu lịch sử chỉnh sửa.

#### Chức năng 2: Quản lý tuyển dụng

- Tạo thông tin vị trí cần tuyển.
- Lưu thông tin ứng viên.
- Theo dõi hồ sơ ứng tuyển.
- Cập nhật trạng thái phỏng vấn.
- Ghi nhận kết quả tuyển chọn.

#### Chức năng 3: Quản lý đánh giá nhân viên

- Tạo kỳ đánh giá.
- Thiết lập tiêu chí đánh giá.
- Ghi nhận kết quả.
- Lưu nhận xét của người quản lý.
- Theo dõi lịch sử đánh giá.

#### Chức năng 4: Quản lý người dùng và phân quyền

- Tạo tài khoản.
- Phân quyền theo vai trò.
- Khóa tài khoản khi cần.
- Kiểm soát quyền truy cập dữ liệu.

#### Chức năng 5: Báo cáo và thống kê

- Thống kê số lượng nhân viên.
- Thống kê nhân viên theo phòng ban.
- Tổng hợp tình hình tuyển dụng.
- Tổng hợp kết quả đánh giá.
- Xuất báo cáo phục vụ ban giám đốc.

## VI. BÁO CÁO PHÂN TÍCH NGHIỆP VỤ

### 1. Tổng quan hệ thống

Qua việc xác định các nhóm tài liệu được cung cấp, có thể thấy hệ thống quản lý nhân sự cần hỗ trợ nhiều hoạt động khác nhau thay vì chỉ lưu trữ thông tin nhân viên. Các nghiệp vụ chính bao gồm quản lý hồ sơ, tuyển dụng, đánh giá nhân viên, phân quyền người dùng và tổng hợp báo cáo.

Hiện tại, thông tin phục vụ quản lý được phân bố trong nhiều loại tài liệu. Các quy định nằm trong PDF, quy trình được mô tả trong DOCX, dữ liệu nhân viên nằm trong Excel và các vấn đề thực tế được ghi nhận trong báo cáo vận hành. Việc phân tán thông tin như vậy khiến quá trình tìm kiếm, kiểm tra và đối chiếu có thể mất nhiều thời gian.

Vì vậy, hệ thống mới cần có khả năng tập trung dữ liệu và hỗ trợ các bộ phận thực hiện nghiệp vụ trên cùng một nền tảng.

### 2. Phân tích nghiệp vụ quản lý hồ sơ nhân viên

Quản lý hồ sơ là một trong những chức năng quan trọng nhất của hệ thống. Mỗi nhân viên cần có một mã định danh riêng để tránh nhầm lẫn giữa những người có họ tên giống nhau.

Thông tin hồ sơ có thể bao gồm mã nhân viên, họ tên, phòng ban, chức vụ, ngày bắt đầu làm việc và trạng thái làm việc. Các thông tin cá nhân nhạy cảm chỉ được lưu khi có mục đích nghiệp vụ phù hợp và phải được kiểm soát quyền truy cập.

Hệ thống nên cho phép bộ phận nhân sự thêm mới, cập nhật và tìm kiếm hồ sơ. Khi có thay đổi, hệ thống cần lưu lại lịch sử để có thể xác định nội dung nào đã được chỉnh sửa và ai thực hiện.

Một vấn đề cần quan tâm là dữ liệu Excel hiện có 200 nhân viên. Khi chuyển dữ liệu sang hệ thống mới, cần kiểm tra cấu trúc cột, mã nhân viên bị trùng, trường thông tin bị trống và dữ liệu không đúng định dạng. Quá trình nhập dữ liệu phải có bước kiểm tra trước khi chính thức sử dụng. Không được tự ý chỉnh sửa file Excel gốc để làm cho dữ liệu phù hợp với phần mềm.

### 3. Phân tích nghiệp vụ tuyển dụng

Quy trình tuyển dụng cần được xây dựng theo từng bước để bộ phận nhân sự dễ theo dõi.

Một quy trình dự kiến có thể gồm: tiếp nhận nhu cầu tuyển dụng, tạo thông tin vị trí, tiếp nhận hồ sơ ứng viên, sàng lọc hồ sơ, tổ chức phỏng vấn, ghi nhận kết quả và hoàn thành tuyển dụng.

Mỗi ứng viên cần có thông tin theo dõi riêng. Trạng thái ứng tuyển cần được cập nhật sau mỗi bước để nhân viên HR biết hồ sơ đang ở giai đoạn nào.

Hệ thống cũng nên hỗ trợ tìm kiếm ứng viên và lưu lịch sử trao đổi hoặc kết quả phỏng vấn. Tuy nhiên, các tiêu chí tuyển dụng, số vòng phỏng vấn và người có quyền phê duyệt cần được xác định theo tài liệu gốc và xác nhận của ban giám đốc.

### 4. Phân tích nghiệp vụ đánh giá nhân viên

Đánh giá nhân viên là nghiệp vụ cần có quy trình rõ ràng vì kết quả có thể được sử dụng trong các quyết định quản lý.

Hệ thống cần hỗ trợ tạo kỳ đánh giá, thiết lập tiêu chí, ghi nhận kết quả và lưu nhận xét của người phụ trách. Mỗi kết quả đánh giá phải gắn với đúng nhân viên và đúng kỳ đánh giá.

Ngoài ra, cần xác định ai là người có quyền đánh giá, ai được xem kết quả và có cần bước phê duyệt hay không.

Một điểm cần chú ý là không nên tự xây dựng thang điểm hoặc công thức đánh giá khi chưa có căn cứ từ tài liệu của doanh nghiệp. Những nội dung chưa rõ cần được đưa vào danh sách chờ xác nhận.

### 5. Phân tích vấn đề vận hành

Tài liệu ghi nhận vấn đề vận hành có vai trò quan trọng vì phản ánh những khó khăn trong quá trình thực hiện nghiệp vụ.

Khi xử lý tài liệu này, cần phân loại từng vấn đề theo quy trình liên quan, bộ phận bị ảnh hưởng và mức độ tác động được ghi nhận. Sau đó, đối chiếu với các tài liệu quy định và quy trình để xác định vấn đề xuất phát từ thiếu chức năng, thiếu thông tin hay quy trình chưa rõ ràng.

Chẳng hạn, nếu tài liệu thực tế ghi nhận việc mất nhiều thời gian tìm hồ sơ nhân viên, đây có thể là cơ sở để đề xuất chức năng tìm kiếm và lọc dữ liệu. Nếu có phản ánh về khó khăn khi theo dõi kết quả đánh giá, có thể xem xét chức năng quản lý lịch sử đánh giá.

Tuy nhiên, đây chỉ là ví dụ về cách chuyển vấn đề thành yêu cầu phần mềm. Không được khẳng định những vấn đề này đã thực sự xuất hiện nếu chưa kiểm tra báo cáo gốc.

### 6. Yêu cầu về bảo mật và quản lý dữ liệu

Hệ thống quản lý nhân sự sẽ xử lý nhiều thông tin cá nhân nên bảo mật cần được xem xét ngay từ giai đoạn phân tích.

Trước tiên, cần xây dựng cơ chế đăng nhập và phân quyền. Nhân viên HR có thể được cấp quyền quản lý hồ sơ, trong khi nhân viên thông thường chỉ nên xem những thông tin được phép liên quan đến bản thân.

Ban giám đốc cần có quyền xem báo cáo tổng hợp theo phạm vi được phê duyệt. Quản trị viên chịu trách nhiệm quản lý tài khoản và cấu hình hệ thống nhưng việc truy cập dữ liệu cá nhân cũng cần được kiểm soát.

Bên cạnh đó, hệ thống nên có nhật ký thao tác đối với những hoạt động quan trọng như cập nhật hồ sơ, thay đổi quyền truy cập và chỉnh sửa kết quả đánh giá.

Đối với dữ liệu được nhập từ Excel, cần giữ nguyên file gốc để phục vụ đối chiếu. Các bản dữ liệu dùng cho thử nghiệm hoặc phân tích nên được ẩn thông tin cá nhân không cần thiết.

### 7. Những vấn đề cần giải quyết trước khi triển khai

Có một số nội dung chưa thể kết luận nếu chưa đối chiếu đầy đủ các tài liệu:

- Chưa xác định được tài liệu nào là căn cứ cuối cùng khi các quy định khác nhau.
- Chưa có thông tin đầy đủ về vai trò và quyền phê duyệt.
- Chưa xác định rõ chu kỳ và tiêu chí đánh giá nhân viên.
- Chưa biết toàn bộ trường dữ liệu trong Excel có cần đưa vào hệ thống hay không.
- Chưa có chỉ tiêu cụ thể về hiệu năng và khả năng lưu trữ.
- Chưa xác định thời gian lưu hồ sơ và cách xử lý dữ liệu khi nhân viên nghỉ việc.

Những nội dung này cần được xác nhận trước khi chuyển sang thiết kế chi tiết.

### 8. Kết luận phân tích

Từ phạm vi bài toán, hệ thống quản lý nhân sự nên tập trung vào năm nhóm chức năng chính: quản lý hồ sơ nhân viên, quản lý tuyển dụng, quản lý đánh giá, quản lý tài khoản và phân quyền, báo cáo thống kê.

AI có thể hỗ trợ giảm thời gian đọc và tổng hợp tài liệu, nhưng không thể tự quyết định quy định nào được ưu tiên khi xuất hiện mâu thuẫn. Người phân tích phải kiểm tra nguồn, đối chiếu với tài liệu gốc và trao đổi với ban giám đốc trước khi đưa ra yêu cầu chính thức.

Do đó, báo cáo này được xem là cơ sở phân tích ban đầu để tiếp tục làm rõ nghiệp vụ và chuẩn bị cho giai đoạn thiết kế hệ thống.

## VII. CÂU HỎI CẦN BAN GIÁM ĐỐC XÁC NHẬN

| STT | Câu hỏi | Mục đích |
|---|---|---|
| 1 | Tài liệu nào được xác định là căn cứ chính khi có hai quy định khác nhau? | Xác định cách xử lý mâu thuẫn |
| 2 | Những vai trò nào được phép truy cập hệ thống? | Xác định nhóm người dùng |
| 3 | Nhân viên có được tự cập nhật hồ sơ cá nhân không? | Xác định quyền chỉnh sửa |
| 4 | Những thông tin nào bắt buộc phải lưu trong hồ sơ nhân viên? | Xác định cấu trúc dữ liệu |
| 5 | Quy trình tuyển dụng có bao nhiêu vòng và ai phê duyệt từng vòng? | Hoàn thiện nghiệp vụ tuyển dụng |
| 6 | Có cần lưu hồ sơ của những ứng viên không được tuyển không? | Xác định phạm vi lưu trữ |
| 7 | Chu kỳ đánh giá nhân viên được thực hiện như thế nào? | Xây dựng chức năng đánh giá |
| 8 | Ai có quyền xem và chỉnh sửa kết quả đánh giá? | Xác định phân quyền |
| 9 | Những tiêu chí nào được sử dụng để đánh giá nhân viên? | Xác định dữ liệu đánh giá |
| 10 | Có cần nhân viên xác nhận kết quả đánh giá của mình không? | Xác định bước xác nhận |
| 11 | Những báo cáo nào ban giám đốc cần theo dõi thường xuyên? | Xác định chức năng báo cáo |
| 12 | Dữ liệu nhân viên cần được lưu trữ trong thời gian bao lâu? | Xác định chính sách lưu trữ |
| 13 | Có cần tích hợp hệ thống với phần mềm chấm công hoặc tính lương không? | Xác định phạm vi tích hợp |
| 14 | Khi nhân viên nghỉ việc, tài khoản và hồ sơ sẽ được xử lý như thế nào? | Xác định nghiệp vụ nghỉ việc |
| 15 | Ai chịu trách nhiệm kiểm tra và phê duyệt dữ liệu khi nhập từ Excel? | Kiểm soát chất lượng dữ liệu |

## VIII. BẢNG KIỂM CHỨNG KẾT LUẬN VỚI NGUỒN GỐC

Bảng này được sử dụng để kiểm tra lại các nhận định trước khi đưa vào báo cáo chính thức.

| STT | Kết luận cần kiểm chứng | Nguồn cần đối chiếu | Vị trí cần kiểm tra | Trạng thái |
|---|---|---|---|---|
| 1 | Cấu trúc thông tin hồ sơ nhân viên | TL06 | Các cột trong Excel | Chưa kiểm chứng |
| 2 | Số lượng bản ghi nhân viên | TL06 | Toàn bộ dữ liệu | Chưa kiểm chứng |
| 3 | Các trường dữ liệu bắt buộc | TL01 | Các mục quy định hồ sơ | Chưa kiểm chứng |
| 4 | Quy định về cập nhật hồ sơ | TL02 | Mục quản lý thông tin | Chưa kiểm chứng |
| 5 | Các bước tuyển dụng | TL04 | Toàn bộ quy trình | Chưa kiểm chứng |
| 6 | Điều kiện tuyển dụng | TL01, TL04 | Mục tuyển dụng | Chưa kiểm chứng |
| 7 | Quyền phê duyệt tuyển dụng | TL04 | Mục phân công trách nhiệm | Chưa kiểm chứng |
| 8 | Chu kỳ đánh giá nhân viên | TL03, TL05 | Mục đánh giá | Chưa kiểm chứng |
| 9 | Tiêu chí đánh giá nhân viên | TL02, TL05 | Mục tiêu chí | Chưa kiểm chứng |
| 10 | Quyền truy cập kết quả đánh giá | TL01, TL05 | Mục bảo mật và đánh giá | Chưa kiểm chứng |
| 11 | Những khó khăn trong vận hành | TL07 | Các nội dung ghi nhận sự cố | Chưa kiểm chứng |
| 12 | Nhu cầu báo cáo và thống kê | TL05, TL07 | Các mục liên quan | Chưa kiểm chứng |

### Nguyên tắc kiểm chứng

- Chỉ chuyển trạng thái sang "Đã kiểm chứng" sau khi tìm được nội dung tương ứng trong tài liệu gốc.
- Ghi chính xác số trang đối với PDF.
- Ghi tên mục hoặc tiêu đề đối với DOCX.
- Ghi tên Sheet, cột và phạm vi dòng đối với Excel.
- Nếu không tìm thấy căn cứ, ghi "Chưa có nguồn xác nhận".
- Nếu hai nguồn không thống nhất, chuyển sang trạng thái "Chờ xác nhận", không tự lựa chọn.
