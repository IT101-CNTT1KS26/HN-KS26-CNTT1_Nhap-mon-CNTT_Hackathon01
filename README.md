# BÀI LÀM – HACKATHON 01

- **Mã đề:** 14
- **Họ tên:**Văn Hữu Luân
- **Lớp:** CNTT1
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windown

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy
```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng

``` C:\Users\lenovo\Onedirve\Tailieu\starter\Nha KhoaWebSiteFinal get-childitem -recurse -force 
mv huong_dan_cham_soc.txt docs/
mv clinic.log logs/
cp bai_lam.md/he-thong-website


   

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------        10/27/2026   1:32 AM             65 .env
------        10/27/2026   1:32 AM           1079 Clini
                                                  c.log
------        10/27/2026   1:32 AM           6094 Dieu
                                                  Tri T
                                                  hang
                                                  4.xls
                                                  x
------        10/27/2026   1:32 AM             63 Huong
                                                   Dan
                                                  Cham
                                                  Soc.t
                                                  xt
------        10/27/2026   1:32 AM           5736 Logo
                                                  Nha K
                                                  hoa.P
                                                  NG
------        10/27/2026   1:32 AM             22 temp_
                                                  226.t
                                                  mp
```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
get-content clinic/ | slect-string "ERROR"


```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```
2026-04-28 09:51:29 [ERROR] Ket noi he thong ho so that bai
2026-04-28 10:07:29 [ERROR] Khong tim thay trang /bang-gia-dich-vu (404)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: 
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```
get-content clinic\ | slect-string "ERROR" | Measure-Object




```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```
5
```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```
C:\Users\lenovo\Onedirve\Tailieu\starter\Nha KhoaWebSiteFinal get-childitem -recurse -force 
mv huong_dan_cham_soc.txt docs/
mv clinic.log logs/
cp bai_lam.md/he-thong-website
get-content clinic\ | slect-string "ERROR"
get-content clinic\ | slect-string "ERROR" | Measure-Object


```

### Nội dung file logs/tong_hop.txt

```

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dieu_tri_thang_4.xlsx`, không cần ghi vào đây.
