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
   
Chắc chắn rồi, đây là nội dung đã được chuyển thành bảng Markdown:

| Tính năng | Proletarian Wizard Task Manager | Plugin Tasks | Plugin Todoist Sync | Plugin Task Board |
| :--- | :--- | :--- | :--- | :--- |
| **Triết lý cốt lõi** | Trực quan & Tự động: Tự động tổng hợp task từ ghi chú vào một bảng điều khiển tương tác để lên kế hoạch. | Mạnh mẽ & Linh hoạt: Quản lý task bằng ngôn ngữ truy vấn (query) mạnh mẽ, tùy biến cao. | Tích hợp & Đa nền tảng: Đồng bộ hóa task giữa Obsidian và dịch vụ Todoist bên ngoài. | Kanban chuyên dụng: Tạo ra một bảng Kanban để quản lý toàn bộ task trong vault. |
| **Giao diện chính** | Bảng điều khiển tương tác với các cột như "Hôm nay", "Kế hoạch", "Quá hạn". | Dựa trên các khối mã truy vấn (query blocks) được nhúng vào bất kỳ ghi chú nào. | Hiển thị danh sách task từ Todoist thông qua các truy vấn trong ghi chú. | Một bảng Kanban trực quan, có thể kéo-thả, chuyên biệt cho việc quản lý task. |
| **Cách tạo & quản lý Task** | Ghi task ở bất kỳ đâu trong ghi chú, plugin sẽ tự động nhận diện và hiển thị. Thay đổi trên bảng sẽ cập nhật lại ghi chú và ngược lại. | Sử dụng cú pháp markdown đặc biệt để thêm ngày tháng, mức độ ưu tiên, v.v. Quản lý chủ yếu qua truy vấn. | Tạo task trong Obsidian để gửi lên Todoist hoặc ngược lại. Phụ thuộc vào nền tảng Todoist. | Tự động quét toàn bộ vault để tìm task và hiển thị trên bảng. Có thể chỉnh sửa, thêm ghi chú, sub-task ngay trên thẻ. |
| **Điểm mạnh nổi bật** | - Dễ sử dụng: Không cần học cú pháp phức tạp, phù hợp cho người mới bắt đầu.\<br\>- Đồng bộ hai chiều: Thay đổi ở bất kỳ đâu đều được cập nhật.\<br\>- Lên kế hoạch trực quan: Dễ dàng kéo-thả task vào các cột kế hoạch.\<br\>- Báo cáo đơn giản: Tích hợp tính năng tổng kết công việc đã hoàn thành. | - Tùy biến cực cao: Có thể tạo ra mọi loại dashboard với hệ thống truy vấn chi tiết.\<br\>- Tính năng nâng cao: Hỗ trợ task lặp lại, phụ thuộc, và nhiều thuộc tính khác.\<br\>- Hệ sinh thái lớn: Tích hợp tốt với nhiều plugin khác như Dataview, Calendar. | - Đa nền tảng: Quản lý task trên điện thoại, web thông qua ứng dụng Todoist.\<br\>- Thông báo & Nhắc nhở: Tận dụng hệ thống thông báo mạnh mẽ của Todoist.\<br\>- Cộng tác: Dễ dàng chia sẻ và giao việc nếu dùng Todoist Pro. | - Giao diện Kanban mạnh mẽ: Cung cấp trải nghiệm giống Trello hay Jira ngay trong Obsidian.\<br\>- Tương tác cao: Hỗ trợ kéo-thả, thêm bình luận, sub-task trực tiếp trên thẻ task.\<br\>- Tự động hóa: Có thể thiết lập quy tắc tự động thay đổi trạng thái task. |
| **Phù hợp với ai?** | Người dùng muốn một giải pháp quản lý công việc đơn giản, tích hợp ngay trong ghi chú mà không cần cấu hình phức tạp. Người thích lên kế hoạch hàng ngày một cách trực quan. | Người dùng thành thạo (power users) muốn xây dựng một hệ thống quản lý công việc tùy chỉnh, chi tiết và không ngại học ngôn ngữ truy vấn. | Người dùng đã hoặc đang sử dụng Todoist và muốn kết nối quy trình làm việc của mình với Obsidian. Người cần truy cập task mọi lúc, mọi nơi. | Người dùng yêu thích phương pháp Kanban, muốn có một cái nhìn tổng quan về quy trình công việc và quản lý dự án theo các giai đoạn. |

<img width="1842" height="969" alt="image" src="https://github.com/user-attachments/assets/9fe52aba-fef3-4997-a6d8-e6ee07dd9a60" />


