# Project1-4Knights
Project1-4Knights created by GitHub Classroom

## Danh sách thành viên nhóm:
   * Phạm Khoa Nam | 1612408
   * Nguyễn Bữu Lộc | 1612343
   * Nguyễn Thanh Trí | 1612722
   * Phan Minh Sơn | 1612888
   * Nguyễn Thanh Tuấn | 1612774

## Ý tưởng của nhóm: Hệ thống tính tiền điện nước tự động và thanh toán nhanh tại kí túc xá Đại học Quốc gia

### Làm gì?
  Xây dựng một hệ thống tự động trong việc đo lường và tính toán tiền điện nước tại kí túc xá (KTX) ĐH Quốc gia
  sau đó gửi thông tin về cơ sở dữ liệu trung tâm để trưởng nhà và ban điều hành kí túc xá dễ dàng quản lí, cùng 
  với đó là một hệ thống thanh toán tiền ngay tại mỗi tòa nhà trong kí túc xá.

### Tại sao làm?
   * Hiện nay trong KTX, việc quản lí tiền điện nước sử dụng hàng tháng tại các phòng trong mỗi tòa nhà tốn rất nhiều
     thời gian và công sức. Trưởng nhà - người quản lí của mỗi tòa nhà phải dùng giấy bút đến từng phòng để ghi lại số
     đo trên đồng hồ điện nước, sau đó phải nhập lại vào máy tính để gửi về ban quản lí KTX.
   * Cùng với đó, việc thanh toán tiền lệ phí phòng ở cũng như tiền điện nước vì chỉ có một văn phòng chịu trách nhiệm
     thanh toán, vì vậy sinh viên thường phải xếp hàng đợi đến lượt mình đóng tiền. Ngoài ra, do không được nhắc nhở nên
     thường xảy ra những trường hợp sinh viên quên đóng tiền điện nước.
 
### Giải pháp chung
   * Lắp đặt một hệ thống bao gồm: thiết bị lấy số liệu điện nước, một chương trình tính phí điện nước, một cơ sở dữ liệu 
     đặt tại mỗi tòa nhà, thiết bị thanh toán tại tầng trệt mỗi tòa nhà (vd: máy quẹt thẻ ATM).
   * Xây dựng một app di động giúp sinh viên và trưởng nhà có thể tra cứu thông tin mọi lúc mọi nơi, nhắc nhở sinh viên mỗi
     khi đến hạn đóng tiền.
     
### Đối tượng hướng đến
   * Người quản lí và sinh viên đang sinh sống tại KTX ĐH Quốc Gia

### Các loại đối tượng người dùng của hệ thống và tác động của hệ thống đối với lợi ích của họ
 #### Sinh viên đang sinh sống tại KTX
   * Vì nhằm mục tiêu tự động hóa đến mức tối đa, hệ thống sẽ giúp cho công việc đóng phí điện nước của sinh viên trở nên đơn giản, tiện      lợi hơn, tiết kiệm nhiều thời gian, công sức.
   * Ngoài ra, nhờ một số tiện ích khác như theo dõi mức sử dụng điện nước qua các tháng kèm theo tiền lệ phí đã đóng hàng tháng, sinh        viên có thể dễ dàng lên kế hoạch sử dụng điện nước cho hợp lí.
 #### Ban quản lí KTX
   * Trưởng nhà: Giảm bớt gánh nặng công việc. Khi áp dụng hệ thống, trưởng nhà sẽ không còn phải đi đến từng phòng để lấy số liệu điện      nước nữa.
   * Nhân viên thu ngân: Do việc đóng và thu lệ phí đã được tự động hóa, những nhân viên này có thể sẽ mất công việc và được thuyên          chuyển qua làm công tác khác.
   * Ban lãnh đạo: Tốn chi phí ban đầu để lắp đặt hệ thống. Tuy nhiên, chi phí này nếu đem so sánh với khoảng thời gian, công sức, tiền      thuê nhân viên mà KTX tiết kiệm được trong khoảng thời gian lâu dài sử dụng hệ thống thì sẽ không đáng kể.

### Đối thủ?
   * Do đây là ý tưởng áp dụng trong quy mô nhỏ là khuôn viên KTX ĐH Quốc gia và từ trước tới nay chưa có hệ thống nào tương tự được sử      dụng trong phạm vi KTX nên có thể nói Project-4Knights hiện chưa có đối thủ cạnh tranh trực tiếp.

### Chi tiết kĩ thuật
 #### Những thiết bị cần chuẩn bị
  ##### Phần cứng:
    * Chip đo lượng điện, nước đã sử dụng. (Mỗi phòng sẽ có 2 chip để đo điện và nước).
    * Máy thanh toán (Ước tính trong khuôn viên KTX sẽ đặt khoảng 3-4 máy).
    * Hệ thống cáp dẫn để truyền dư liệu (Có thể thay thế bằng việc chuyển dữ liệu qua sóng điện từ).
    * Hệ thống máy chủ (tận dụng lại hệ thống cũ của KTX).
  ##### Phần mềm:
    * Website
    * App mobile
    * Thiết lập lại một cơ sở dữ liệu mới
    * Phần mềm điểu khiển chip đo
    * Phần mềm thanh toán 
 #### Sơ đồ chi tiết của hệ thống
    * Sau đây là sơ đồ chi tiết của hệ thống, cách lặp đặt hệ thống cũng có thể được rút ra từ sơ đồ này:
 
### Quy trình sử dụng hệ thống của người dùng
    * Do các phần việc của trường nhà và nhân viên thu ngân đã được tự động hóa hoàn toàn nên quy trình này chỉ để cập đến đối tượng           người dùng còn lại đó chính là sinh viên:
