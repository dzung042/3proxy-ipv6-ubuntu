# 3proxy-ipv6-ubuntu
Create Ipv6 sock proxy, http proxy use 3proxy on ubuntu

# Tự động cài đặt proxy trên Ubuntu (18.04/20.04/22.04)
# Tính năng:
#  - Tự động phát hiện IPv4 và cổng mạng
#  - Tự động phát hiện IPv6 /64 prefix  hoặc nhập thủ công
#  - Tạo  IPv6 từ prefix đã phát hiện hoặc có thể nhập thủ công
#  - Cấu hình 3proxy  1 port / 1 IPv6
#  - Hỗ trợ HTTP và SOCKS5 
#  - Tạo user/pass cho mỗi proxy
#  - Tối ưu cho tải cao
#  - Tự động boot script để khởi động lại IPv6 khi reboot
#  - Tự động mở port firewall
# Để cài đặt chạy lệnh sau
```sh
curl -Lso- https://raw.githubusercontent.com/dzung042/3proxy-ipv6-ubuntu/refs/heads/main/ubuntu-proxy.sh | bash
```
