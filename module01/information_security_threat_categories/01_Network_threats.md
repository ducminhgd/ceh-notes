# Information gathering - Thu thập thông tin

This method is also called _human hacking_ or _non-IT hacking_. Information can be gathered from _human mistakes_, such as:
- Simple passwords base on personal information: birthday, phone numbers, address, or even favorite color of owners or their folks.
- Simple passwords from habits, such as: `admin`, `123456`, `12345678`, `password`, `admin@123`, etc.
- Any piece of paper, any email, any text message, any note a person writes, composes or stores.
- Public information of user on public sources on the Internet: forums, social networks or recruitment (work-market) website.
- Information of the system, of the company, of the organization that a person manages can be hacked via this method, too.

----

Phương pháp này còn gọi là kỹ thuật _hack con người_ hoặc _hack phi tin học_. Thông tin được thu thập từ _những sai lầm về mặt con người_, như là:
- Mật khẩu đơn giản dựa trên các thông tin cá nhân: ngày sinh, số điện thoại, địa chỉ, kể cả màu ưua thích của người đó hoặc người thân của họ.
- Mật khẩu đơn giản dựa trên thói quen người dùng, ví dụ: `admin`, `123456`, `12345678`, `password`, `admin@123`,...
- Bất cứ mẩu giấy, email, tin nhắn hay ghi chú nào từ người dùng.
- Thông tin được đăng tải ở nhiều nguồn trên Internet: diễn đàn, mạng xã hội và kể cả những trang tìm kiếm việc làm.
- Thông tin hệ thống, công ty hay tổ chức cũng có thể bị thu thập thông qua phương pháp này.

# Sniffing and eavesdropping

Sniffing is a process of monitoring and **capturing all data packets** passing through a given network using sniffing tools.

----

Sniffing là một phương pháp dùng các công cụ theo dõi và **bắt tất cả các gói tin** được chuyển trong mạng.

## Passive sniffing:

Passive sniffing means sniffing through a **hub**, on a hub the traffic is sent to all ports.

It involves only monitoring of packets sent by others without sending **any additional data packets** in the traffic network

In a network that use hubs to connect sytems, all **hosts on the network** can see all traffic therefore attacker can easily capture traffic going through the hub

Hub usage is out-dated today. Most modern networks use **switches**.

----

Sniffing bị động là sniff thông qua một **hub**, lưu lượng dữ liệu trong hub được gửi đến toàn bộ các cổng.

Theo dõi các gói tin được gửi bởi các thiết bị khác nhưng không gửi **bất kỳ gói dữ liệu thêm nào** trong một mạng dữ liệu.

Trong một mạng sử dụng hub, tất cả **các host trong mạng** có thể thấy được sự lưu thông dữ liệu do đó kẻ tấn công có thể bắt dữ liệu được truyền thông qua hub một các dễ dàng.

Hub là một loại thiết bị đã lỗi thời, các mạng dữ liệu hiệu tại đa số sử dụng **switch**.

## Active sniffing

**Active sniffing** is used to sniff **switch-based network**

Active sniffing involves **injecting address resolution packets (ARP)** into the network to flood the switch's Content Addressable Memory (CAM) table, CAM keeps track of which host is connected to which port.

_Please read more in Module 07 Sniffing_

----

Sniffing chủ động bao gồm cả việc **nhét các gói phân giải địa chỉ** vào trong mạng để gây quá tải bản Content Addressable Memory (CAM) của switch, CAM lưu trữ thông tin máy nào được kết nối vào port nào.

_Tham khảo thêm trong Module 07 Sniffing_

# Spoofing

# Session hijacking and Man-in-the-Middle attack

# DNS and ARP poisoning

# Password-based attacks

# Denial-of-Service attack

# Compromised-key attack

# Firewall and IDS attacks
