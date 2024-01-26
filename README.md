# Study Spring MVC, Spring Framwork 4.3.x

web business
    - web: người dùng 
    - admin: quản trị 

web chúng ta không phải là 1 web quản lý 

- web quản lý
    - 1 giao diện : cho phần quản lý

- boostrap 3

- js nặng

- css nhẹ hơn js rất là nhiều

- 1 xài lại tất cả những thứ boostrap cung cấp
- 2 tự viết thêm những thứ boostrap không có nhưng chúng ta lại cần

- sitmesh decorator
- cách thức hoạt động dựa vào url

- filter
- nhận request -> /admin: apply giao diện admin
							/: apply giao diện web
- cơ chế: thay đổi content trong body thôi
- header và footer: cố định
- tái sử dụng 
- tạo ra 1 master layout: parent 
- mấy page kia là child extends parent

## JPA, Spring Data JPA
- 