```mermaid
graph TD;
  A[Khách hàng đặt hàng] -->|Xác nhận đơn| B[Hệ thống tiếp nhận đơn hàng];
  B --> C[Nhà hàng chuẩn bị món ăn];
  C --> D[Kiểm tra và đóng gói];
  D --> E[Nhân viên giao hàng nhận đơn];
  E --> F[Giao hàng đến khách hàng];
  F -->|Xác nhận nhận hàng| G[Hoàn tất đơn hàng];
  F -->|Khách hàng đánh giá| H[Hệ thống ghi nhận phản hồi];
