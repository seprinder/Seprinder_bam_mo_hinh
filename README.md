# Hướng dẫn xuất Profile từ Cura để dùng trên Seprinder.com

Seprinder dùng **Cura Engine** để slice và gửi G-code trực tiếp tới máy in.  
Bạn có thể sử dụng cài đặt từ **Ultimaker Cura** với Seprinder theo các bước dưới đây.

---

## Bước 1: Lấy profile từ Cura

Mở **Ultimaker Cura** trên máy tính.

<p align="center">
  <img src="https://github.com/seprinder/Seprinder_bam_mo_hinh/blob/main/Image/xuat_profile_tu_cura.png" alt="Hướng dẫn lấy profile" width="800">
</p>

1. Vào **Preferences → Configure Cura...**  

2. Chọn **Profiles**  

3. Chọn profile cần xuất  

4. Bấm biểu tượng **ba gạch** của profile  

5. Chọn **Export** và lưu file `.curaprofile`

---

## Bước 2: Tải profile lên Seprinder

1. Mở [seprinder.com](seprinder.com)  

2. **Đăng nhập** vào tài khoản đã thêm máy in  

3. Vào **Vận hành →** chọn máy in cần chỉnh  

4. Kéo thả hoặc chọn file `.curaprofile` vào ô **Cấu hình**  

5. Lần slice sau sẽ dùng cài đặt bạn vừa tải lên

---

## Bước 3: Chỉnh sửa profile trên Seprinder.com

<p align="center">
  <img src="https://github.com/seprinder/Seprinder_bam_mo_hinh/blob/main/Image/huong_dan_de_profile.png" alt="Hướng dẫn để profile" width="800">
</p>

1. Ở **ô Cấu hình**, có thể chọn hoặc kéo thả lại file `.curaprofile` khi cần cập nhật  

2. Các thông số trong profile sẽ hiện ra để bạn xem và chỉnh  

3. Có thể sửa **Start/End G-code** trực tiếp  

4. Một số thông số cho phép chỉnh nhanh để tối ưu bản in

5. Kích thước in và giá 

---

## Lưu ý

Hiện tại **infill** và **nhiệt độ** phải nhập thêm ở ô **cấu hình tùy chỉnh**;  
nếu không, Cura Engine sẽ sử dụng giá trị mặc định: **215 °C / 60 °C, 30% infill**.

Các thông số **infill** và **nhiệt độ**:

<p align="center">
  <img src="https://github.com/seprinder/Seprinder_bam_mo_hinh/blob/main/Image/thong_so_infill.png" alt="Thông số infill" width="800">
</p>

infill_line_distance # sử dụng khoảng cách đường infill (có thể thay cho % infill)


material_bed_temperature # nhiệt độ bàn in

material_bed_temperature_layer_0 # nhiệt độ bàn in lớp đầu

material_print_temperature # nhiệt độ hotend

material_print_temperature_layer_0 # nhiệt độ hotend lớp đầu

center_object = true/false #đặt vật in ở giữa (true để vật ở giữa, false để đặt vật ở tọa độ 0;0. mặc định false)




