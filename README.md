# proletarian-wizard
[proletarian-wizard](https://www.obsidianstats.com/plugins/proletarian-wizard)
Plugin Proletarian Wizard Task Manager tạo ra một lối đi riêng trong hệ sinh thái quản lý công việc của Obsidian bằng cách tập trung vào sự đơn giản, trực quan và tích hợp chặt chẽ với ghi chú hàng ngày. Điểm khác biệt lớn nhất của nó so với các plugin mạnh mẽ khác như Tasks, Todoist Sync hay Task Board nằm ở triết lý hoạt động và đối tượng người dùng mà nó hướng tới.

Về cơ bản, Proletarian Wizard biến các công việc (task) mà bạn ghi chép tự nhiên trong các ghi chú thành một bảng điều khiển (dashboard) tương tác. Thay vì yêu cầu người dùng học một ngôn ngữ truy vấn phức tạp hay phải tích hợp với một dịch vụ bên ngoài, plugin này tự động nhận diện và hiển thị công việc trên một giao diện thống nhất, nơi bạn có thể dễ dàng lên kế hoạch cho ngày hôm nay, ngày mai hoặc tương lai.


Tôi sử dụng plugin proletarian-wizard giúp nhìn và chuyển todo trong quá trình viết journal theo bullet journal methon được dễ dàng hơn.
Nhưng do plugin khá đơn giản
- sắp xếp các task ngược với thứ tự tôi viết
- không hỗ trợ hiển thị link tới note trong task
- không hỗ trợ tốt mobile\
- Load toàn bộ note trong vault để lấy tasks => dẫn đến quá dư thừa
- Có exclude folder nhưng chạy chưa đúng

  Nên tôi chỉnh lại cho phù hợp với nhu cầu của bản thân
  - Thêm các tác vụ để mobile cũng có thể dùng dễ dàng
    - Chỉnh lại giao diện cho mobile sẽ hiển thị dạng list và ưu tiên In Progress lên
  - Thay đổi click sẽ hiện model context menu chứ không bay thẳng tới note file chứa task => giúp hoạt động thống nhất trên desktop và mobile
  - khi tới notes luôn check có dang mở chưa, nếu rồi thì chỉ active tab note đó lên không mở mới
  - Contex Menu:
    - Thêm tính năng đi tới chi tiết note
    - Thêm tính năng chuyển task Todo -> InProgress -> Done ( bản cũ chỉ có thể kéo qua, vì vậy không chạy tốt trên mobile)
