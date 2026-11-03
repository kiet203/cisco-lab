# Mô phỏng mạng sử dụng cisco
## **Overview**

cấu trúc mạng được xây dựng trên phần mềm cisco packet tracer.Hệ thống bao gồm VLan,định tuyến OSPF,DHCP và NAT
## **Tóm tắt cấu hình**
- VLAN:Data(10),Server(20),VOICE(30),GUEST(40),ENG(50)
- OSPF area 1 giữa các Router
- NAT để truy cập Internet
- DHCP trên R2 cấp IP cho Vlan 30
  
## **FILE**

- campus_network.pkt-Sơ đồ cấu trúc mạng Packet Tracer hoàn chỉnh
- campus_topology.png-Sơ đồ trực quan
## **Kiểm chứng**

- Thực hiện ping thành công giữa các VLAN
- Xác nhận kết nối OSPF giữa tất cả các Router.
- Đã kiểm thử NAT cho mô phỏng Internet
- ACL chặn Vlan 10,20,30,các vlan khác được phép trên ISP
## **Bài học kinh nghiệm**
Đồ án này đã củng cố sự hiểu biết về OSPF, trunking, định tuyến VLAN trong các môi trường doanh nghiệp.
