### build Kernel GKI + patch sẵn SUSFS!

> Cập nhật mới:
> - Đã sửa lại lỗi không nhận KSU Manager của KernelSU Next, nếu vẫn còn lỗi này, xin hãy tải xuống gói KernelSU Next Manager này [KSU_Next_v1.0.9_12797](https://github.com/KernelSU-Next/KernelSU-Next/releases/download/v1.0.9/KernelSU_Next_v1.0.9_12797-release.apk)!

### Mẹo nhỏ
1. Về bản vá bảo mật
- Thời gian bản vá bảo mật trong cài đặt điện thoại không liên quan gì đến thời gian bản vá bảo mật của hạt nhân GKI, vui lòng bỏ qua.
2. Về phiên bản Android
- Phiên bản Android của hệ thống điện thoại không liên quan gì đến phiên bản Android của hạt nhân GKI, và nên được so sánh với phiên bản **android** của phiên bản hạt nhân điện thoại.
- Giả sử phiên bản hạt nhân do điện thoại đặt là 5.10.66-**android12**-9-00001-g41ff3fa8fop9-ab8161528.
- Sau đó, bạn cần flash tệp **android12**-5.10.66-2022-01-AnyKernel3.zip đã tải xuống [tại đây](https://github.com/nguyensu66/GKI_KernelSU_SUSFS/releases)

### Hỗ trợ
| Chức năng | Mô tả |
| --- | --- |
| [KernelSU](https://kernelsu.org/zh_CN/) | Bao gồm **Official, MKSU, SUKISU, NEXT** |
| [SUSFS4](https://gitlab.com/simonpunk/susfs4ksu) | Hỗ trợ các bản vá chức năng ẩn KSU ở cấp độ kernel |
| [BBR](https://blog.thinkin.top/archives/ke-pu-bbrdao-di-shi-shi-me) | Thuật toán kiểm soát TCP |
| [Wireguard](https://zh.wikipedia.org/wiki/WireGuard) | Tham khảo liên kết wiki bên trái |
| [LZ4KD](https://github.com/ShirkNeko/SukiSU_patch/tree/main/other) | Thuật toán ZRAM từ nguồn HUAWEI, bản vá được chuyển bởi [雲雲之枫](http://www.coolapk.com/u/24963680)

> ### Hướng dẫn chọn phiên bản kernel

> Tất nhiên rằng tôi rất khuyến khích bạn sử dụng phiên bản kernel cùng với kernel của thiết bị, nhưng nếu bạn không thể tìm thấy phiên bản của mình, bạn có thể thử cách dưới đây
> 1. Khi phiên bản chính GKI của điện thoại là 5.10.x (chẳng hạn như 5.10.168), bạn có thể flash kernel với phiên bản phụ cao hơn của cùng phiên bản chính (chẳng hạn như 5.10.198).
> 2. 
