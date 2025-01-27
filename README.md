<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hướng Dẫn Multiboot từ ISO</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            margin: 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
            overflow: auto;
        }
    </style>
</head>
<body>
    <h1>Hướng Dẫn Multiboot từ ISO</h1>
    <p>Multiboot là quá trình cài đặt và sử dụng nhiều hệ điều hành trên cùng một máy tính. Dưới đây là các bước cơ bản để cài đặt multiboot từ file ISO:</p>

    <h2>1. Chuẩn Bị</h2>
    <p>Các bước cần thiết trước khi bắt đầu cài đặt multiboot:</p>
    <ul>
        <li>Tải các file ISO của các hệ điều hành bạn muốn cài đặt từ trang web chính thức.</li>
        <li>Tạo ổ USB multiboot từ các file ISO bằng cách sử dụng công cụ như YUMI hoặc Ventoy.</li>
        <li>Sao lưu dữ liệu quan trọng để tránh mất mát trong quá trình cài đặt.</li>
    </ul>

    <h2>2. Tạo USB Multiboot</h2>
    <p>Sử dụng YUMI hoặc Ventoy để tạo ổ USB multiboot từ các file ISO:</p>
    <pre>
        <code>
            1. Tải và cài đặt YUMI hoặc Ventoy từ trang web chính thức.
            2. Cắm USB vào máy tính.
            3. Mở YUMI hoặc Ventoy và chọn ổ USB của bạn.
            4. Chọn các file ISO của các hệ điều hành mà bạn muốn cài đặt.
            5. Nhấp "Start" để tạo USB multiboot.
        </code>
    </pre>

    <h2>3. Cài Đặt Các Hệ Điều Hành</h2>
    <p>Khởi động máy tính từ USB multiboot và cài đặt các hệ điều hành:</p>
    <pre>
        <code>
            1. Khởi động lại máy tính và vào BIOS/UEFI bằng cách nhấn phím tắt (thường là F2, F10, F12 hoặc Del).
            2. Chọn USB multiboot từ menu Boot.
            3. Theo các bước hướng dẫn trên màn hình để cài đặt từng hệ điều hành vào các phân vùng trống.
        </code>
    </pre>

    <h2>4. Cấu Hình Bootloader</h2>
    <p>Đảm bảo tất cả các hệ điều hành có thể khởi động từ bootloader:</p>
    <pre>
        <code>
            1. Sau khi cài đặt các hệ điều hành, khởi động lại máy tính.
            2. Nếu cần thiết, sử dụng công cụ như EasyBCD để cấu hình bootloader.
            3. Thêm mục khởi động cho tất cả các hệ điều hành vào bootloader.
        </code>
    </pre>

    <h2>Kết Luận</h2>
    <p>Sau khi hoàn tất các bước trên, bạn sẽ có nhiều hệ điều hành cài đặt trên cùng một máy tính và có thể chọn hệ điều hành mong muốn khi khởi động.</p>
</body>
</html>
