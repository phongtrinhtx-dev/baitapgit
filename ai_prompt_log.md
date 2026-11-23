hãy cho biết sự khác nhau giữa thẻ ul và li

Trong HTML, thẻ <ul> và <li> luôn đi cùng nhau để tạo danh sách, nhưng vai trò và bản chất của chúng hoàn toàn khác nhau:

1. Bảng so sánh nhanh
Đặc điểm	Thẻ <ul>	Thẻ <li>
Tên viết tắt	Unordered List	List Item
Ý nghĩa	Danh sách không có thứ tự	Từng mục/phần tử trong danh sách
Vai trò	Thẻ cha (Container): Bao bọc toàn bộ danh sách	Thẻ con: Chứa nội dung của từng dòng/mục
Cách dùng	Chứa trực tiếp các thẻ <li> bên trong	Phải nằm bên trong <ul>, <ol> hoặc <menu>
Hiển thị mặc định	Tạo khối có thụt lề (padding lề trái)	Hiển thị dạng list-item với dấu chấm tròn (bullet point) ở đầu dòng
2. Ví dụ trực quan
html
<ul>  <!-- Thẻ cha: xác định đây là một danh sách không thứ tự -->
  <li>HTML</li>  <!-- Thẻ con: mục thứ nhất -->
  <li>CSS</li>   <!-- Thẻ con: mục thứ hai -->
  <li>JavaScript</li> <!-- Thẻ con: mục thứ ba -->
</ul>

Kết quả hiển thị trên trình duyệt:


  
HTML

  
CSS

  
JavaScript

  
3. Những lưu ý quan trọng

  
Tính ngữ nghĩa (Semantic HTML):
  
  

  
Không đặt nội dung văn bản trực tiếp trong <ul> mà không qua <li> (ví dụ viết <ul>Xin chào</ul> là sai cú pháp).

  
Không dùng <li> đứng độc lập một mình ngoài thẻ cha (<ul> hoặc <ol>).

  

  
Sự linh hoạt của <li>: Thẻ <li> còn có thể dùng trong thẻ <ol> (Ordered List - danh sách đánh số thứ tự 1, 2, 3...), còn <ul> chỉ dùng khi các mục không phân biệt thứ hạng hay thứ tự trước sau.

  
