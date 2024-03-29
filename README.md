# git_tutorial
Dưới đây là tài liệu hướng dẫn sử dụng Git viết bằng ngôn ngữ Markdown:
![](/images/1648470569696.png)
# Hướng dẫn sử dụng Git

## Giới thiệu về Git

Git là một hệ thống quản lý phiên bản mã nguồn mở, được thiết kế để theo dõi các thay đổi trong mã nguồn của một dự án phần mềm và quản lý các phiên bản khác nhau của mã nguồn đó. Nó cho phép các nhà phát triển làm việc cùng nhau trên cùng một dự án một cách hiệu quả bằng cách theo dõi và ghi lại lịch sử các thay đổi, cho phép họ hợp nhất các thay đổi từ nhiều nguồn khác nhau một cách an toàn và dễ dàng. Git là một trong những công cụ quản lý phiên bản phổ biến nhất và được sử dụng rộng rãi trong cộng đồng phát triển phần mềm.

## Kiến trúc của Git

Kiến trúc của Git là cách mà Git tổ chức và quản lý dữ liệu của một dự án phần mềm. Điều này bao gồm cách Git lưu trữ lịch sử thay đổi, quản lý các nhánh, và làm việc với các kho chứa từ xa. 

Một phần quan trọng của kiến trúc của Git là sự phân tán, cho phép nhiều máy tính làm việc đồng thời trên cùng một dự án mà không cần một máy chủ trung tâm. Mỗi máy tính có thể chứa một bản sao của toàn bộ kho chứa, bao gồm lịch sử commit và tất cả các nhánh. Điều này cho phép các nhà phát triển làm việc độc lập và đồng bộ hóa các thay đổi của họ với nhau thông qua các thao tác như pull và push.

Ngoài ra, kiến trúc của Git cũng bao gồm cách mà dữ liệu được tổ chức bên trong một kho chứa, bao gồm cây thư mục và các commit, cũng như cách mà các nhánh và thẻ được quản lý và hợp nhất với nhau.

Tóm lại, kiến trúc của Git cung cấp một cách linh hoạt và hiệu quả để quản lý mã nguồn và làm việc cùng nhau trên dự án phần mềm.

## Các thuật ngữ

- **Repository (Kho chứa)**: Nơi lưu trữ toàn bộ dữ liệu và lịch sử thay đổi của dự án.
- **Commit**: Hành động ghi lại một bản sao của dự án tại một thời điểm cụ thể.
- **Branch (Nhánh)**: Phiên bản riêng biệt của dự án, cho phép phát triển độc lập mà không ảnh hưởng đến phiên bản chính.

## Các lệnh cơ bản

1. `git init`: Khởi tạo một kho chứa Git mới.
2. `git clone <url>`: Sao chép một kho chứa từ xa vào máy tính cục bộ.
3. `git add <file>`: Thêm các tệp tin đã sửa đổi vào chỉ mục để chuẩn bị cho việc commit.
4. `git commit -m "<message>"`: Ghi lại các thay đổi đã thêm vào chỉ mục với một thông điệp mô tả.
5. `git push`: Đẩy các commit cục bộ lên kho chứa từ xa.
6. `git pull`: Cập nhật thay đổi từ kho chứa từ xa về máy tính cục bộ.
7. `git branch`: Liệt kê tất cả các nhánh hiện có trong kho chứa.
8. `git checkout <branch>`: Chuyển đổi sang một nhánh khác.

## Demo

Dưới đây là một ví dụ về cách sử dụng Git để quản lý dự án:

1. Khởi tạo một kho chứa Git mới:
   ```
   git init
   ```

2. Thêm tệp tin vào chỉ mục:
   ```
   git add <file>
   ```

3. Ghi lại các thay đổi:
   ```
   git commit -m "Initial commit"
   ```

4. Đẩy commit lên kho chứa từ xa:
   ```
   git push origin master
   ```

5. Sao chép một kho chứa từ xa vào máy tính cục bộ:
   ```
   git clone <url>
   ```

Với những bước trên, bạn đã có thể sử dụng Git để quản lý dự án của mình một cách hiệu quả.
test