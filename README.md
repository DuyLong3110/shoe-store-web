# shoe-store-web
Online shoe store built with React, Node.js, Express and MongoDB.

1. Biểu Đồ Use Case
 <img width="1032" height="1217" alt="image" src="https://github.com/user-attachments/assets/af12d3b8-d872-467d-b7b8-8191e127a282" />
<img width="863" height="696" alt="image" src="https://github.com/user-attachments/assets/7a63d697-913e-4e64-8ab2-3e274f4f494d" />


## 👤 Danh sách Actor

| STT | Actor     | Mô tả |
|-----|----------|------|
| 1 | Guest | Người dùng chưa đăng nhập, có thể xem và tìm kiếm sản phẩm |
| 2 | Customer | Người dùng đã đăng ký, có thể mua hàng |
| 3 | Admin | Quản trị hệ thống |

---

## 📋 Danh sách Use Case (Guest / Customer)

| STT | Use Case | Actor |
|-----|---------|------|
| 1 | Đăng ký | Guest |
| 2 | Đăng nhập | Guest, Customer |
| 3 | Đăng xuất | Customer |
| 4 | Quên mật khẩu | Guest, Customer |
| 5 | Xem & tìm kiếm sản phẩm | Guest, Customer |
| 6 | Lọc & sắp xếp sản phẩm | Guest, Customer |
| 7 | Xem chi tiết sản phẩm | Guest, Customer |
| 8 | Thêm vào giỏ hàng | Customer |
| 9 | Quản lý giỏ hàng | Customer |
| 10 | Đặt hàng | Customer |
| 11 | Thanh toán MoMo | Customer |
| 12 | Xác nhận đơn hàng | Customer |
| 13 | Xem lịch sử đơn hàng | Customer |
| 14 | Theo dõi trạng thái đơn hàng | Customer |
| 15 | Hủy đơn hàng | Customer |
| 16 | Viết đánh giá | Customer |
| 17 | Xem đánh giá | Guest, Customer |
| 18 | Quản lý hồ sơ cá nhân | Customer |

---

## 📋 Danh sách Use Case (Admin)

| STT | Use Case | Actor |
|-----|---------|------|
| 19 | Đăng nhập Admin | Admin |
| 20 | Xem Dashboard | Admin |
| 21 | Quản lý sản phẩm | Admin |
| 22 | Quản lý danh mục | Admin |
| 23 | Quản lý đơn hàng | Admin |
| 24 | Cập nhật trạng thái đơn hàng | Admin |
| 25 | Quản lý người dùng | Admin |
| 26 | Xem thống kê doanh thu | Admin |

---

## 🔗 Quan hệ «include»

| Use Case A | Use Case B |
|-----------|-----------|
| Đăng nhập Admin | Xem Dashboard |
| Quản lý đơn hàng | Cập nhật trạng thái đơn hàng |
| Đặt hàng | Xác nhận đơn hàng |

---

## 🔄 Quan hệ «extend»

| Use Case A | Use Case B |
|-----------|-----------|
| Lọc & sắp xếp sản phẩm | Xem & tìm kiếm sản phẩm |
| Xem chi tiết sản phẩm | Xem & tìm kiếm sản phẩm |
| Thêm vào giỏ hàng | Xem chi tiết sản phẩm |
| Quản lý giỏ hàng | Thêm vào giỏ hàng |
| Đặt hàng | Quản lý giỏ hàng |
| Thanh toán MoMo | Đặt hàng |
| Theo dõi trạng thái đơn hàng | Xem lịch sử đơn hàng |
| Hủy đơn hàng | Xem lịch sử đơn hàng |
| Xem đánh giá | Xem chi tiết sản phẩm |
| Quản lý danh mục | Quản lý sản phẩm |

---

## 🛠️ Công nghệ

- ReactJS  
- NodeJS (Express)  
- MongoDB  
