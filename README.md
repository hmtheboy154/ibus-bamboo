IBus Bamboo - Bộ gõ tiếng Việt cho Linux
===================================
[![GitHub release](https://img.shields.io/github/release/BambooEngine/ibus-bamboo.svg)](https://github.com/BambooEngine/ibus-bamboo/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://opensource.org/licenses/GPL-3.0)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/BambooEngine/ibus-bamboo)

## Mục lục

- [Sơ lược tính năng](#sơ-lược-tính-năng)
- [Hướng dẫn cài đặt](#hướng-dẫn-cài-đặt)
	- [Mageia](#Mageia)
- [Hướng dẫn sử dụng](#hướng-dẫn-sử-dụng)
- [Báo lỗi](#báo-lỗi)
- [Giấy phép](#giấy-phép)

## Sơ lược tính năng
* Hỗ trợ tất cả các bảng mã phổ biến:
  * Unicode, TCVN (ABC)
  * VIQR, VNI, VPS, VISCII, BK HCM1, BK HCM2,…
  * Unicode UTF-8, Unicode NCR - for Web editors.
* Các kiểu gõ thông dụng:
  * Telex, Telex W, Telex 2, Telex + VNI + VIQR
  * VNI, VIQR, Microsoft layout
* Nhiều tính năng hữu ích, dễ dàng tùy chỉnh:
  * Kiểm tra chính tả (sử dụng từ điển/luật ghép vần)
  * Dấu thanh chuẩn và dấu thanh kiểu mới
  * Bỏ dấu tự do, Gõ tắt,...
  * 2666 emojis từ [emojiOne](https://github.com/joypixels/emojione)
* Sử dụng phím tắt <kbd>Shift</kbd>+<kbd>~</kbd> để loại trừ ứng dụng không dùng bộ gõ, chuyển qua lại giữa các chế độ gõ:
  	* Pre-edit (default)
  	* Surrounding text, IBus ForwardKeyEvent,...
   ![ibus-bamboo](https://github.com/BambooEngine/ibus-bamboo/raw/gh-resources/demo.gif)

## Hướng dẫn cài đặt
### Mageia
Kiểm tra tab Releases

## Hướng dẫn sử dụng
Điểm khác biệt giữa `ibus-bamboo` và các bộ gõ khác là `ibus-bamboo` cung cấp nhiều chế độ gõ khác nhau (1 chế độ gõ có gạch chân và 5 chế độ gõ không gạch chân; tránh nhầm lẫn **chế độ gõ** với **kiểu gõ**, các kiểu gõ bao gồm `telex`, `vni`, ...).

Để chuyển đổi giữa các chế độ gõ, chỉ cần nhấn vào một khung nhập liệu (một cái hộp để nhập văn bản) nào đó, sau đó nhấn tổ hợp <kbd>Shift</kbd>+<kbd>~</kbd>, một bảng với những chế độ gõ hiện có sẽ xuất hiện, bạn chỉ cần nhấn phím số tương ứng để lựa chọn.

**Một số lưu ý:**
- Một ứng dụng có thể hoạt động tốt với chế độ gõ này trong khi không hoạt động tốt với chế độ gõ khác.
- Các chế độ gõ được lưu riêng biệt cho mỗi phần mềm (`firefox` có thể đang dùng chế độ 3, trong khi `libreoffice` thì lại dùng chế độ 2).
- Bạn có thể dùng chế độ `Thêm vào danh sách loại trừ` để không gõ tiếng Việt trong một chương trình nào đó.
- Để gõ ký tự `~` hãy nhấn tổ hợp <kbd>Shift</kbd>+<kbd>~</kbd> 2 lần.

## Báo lỗi
Trước khi báo lỗi vui lòng đọc [những vấn đề thường gặp](https://github.com/BambooEngine/ibus-bamboo/wiki/C%C3%A1c-v%E1%BA%A5n-%C4%91%E1%BB%81-th%C6%B0%E1%BB%9Dng-g%E1%BA%B7p) và tìm vấn đề của mình ở trong đó.

Nếu trang phía trên không giải quyết vấn đề của bạn, vui lòng [báo lỗi tại đây](https://github.com/BambooEngine/ibus-bamboo/issues)

## Giấy phép
ibus-bamboo là phần mềm tự do nguồn mở. Toàn bộ mã nguồn của ibus-bamboo được phát hành dưới các quy định ghi trong Giấy phép Công cộng GNU (GNU General Public License v3.0).

*Từ phiên bản v0.5.3, ibus-bamboo được viết lại và phát triển độc lập với ibus-teni.*
