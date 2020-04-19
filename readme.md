# I.Tải và Cài đặt bootstrap 4
## 1. Truy cập đường dẫn và tải source code bootstrap 4:

  ### Compiled CSS and JS
  https://getbootstrap.com/docs/4.0/getting-started/download/

## 2. Cài đặt (Link):
```
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <script src="js/bootstrap.min.js">
```
## 3. Các script đã sử dụng
  ### Script Jquery (Jquery.min.js): dùng để hỗ trợ các hiệu ứng lướt
  >https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js
  ### Script smoothScroll (smoothScroll.js): dùng dể hỗ trợ di chuyển mượt mà các liên kết trong trang web
  >https://www.w3schools.com/howto/howto_css_smooth_scroll.asp
  ### Script popper (popper.min.js): Hỗ trợ hiển thị popover 
  >https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js
  >
  Đoạn script sau: dùng để khai báo vào sử dụng các Popover
  ```
    <script>
        $(document).ready(function() {
            $('[data-toggle="popover"]').popover();
        });
    </script>
  ```
  Thứ tự nhúng script bắt buộc
  ```
    <!--1. jquery -->
    <script src="js/jquery.min.js"></script>
    <!--2. smooth scroll -->
    <script src="js/smoothScroll.js"></script>
    <!--3. popper -->
    <script src="js/popper.min.js"></script>
    <!--4. bootstrap -->
    <script src="js/bootstrap.js"></script>
  ```
  # II. Cấu trúc và bố cục trang web:
  ## Trang web Largo gồm 3 phần chính:
  > 1. Header
  > 2. Body
  > 3. Footer
  ### 1. HEADER: 
  (Gồm: logo, menu và nút liên hệ)

  ### 2. BODY:
  (Gồm: Banner, Nội thất phòng khách, nhà bếp, phòng ngủ, phòng tắm và thông tin về chúng tôi)

  ### 3. FOOTER:
  (Gồm: Logo, menu, thông tin mạng xã hội và copyright)