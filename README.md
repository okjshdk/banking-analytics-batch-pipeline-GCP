# banking-analytics-batch-pipeline-GCP

# Data Engineer Project | End-to-end Banking Analytics Batch Pipeline (GCP)

## 1. Tổng quan
  Dự án xây dựng hệ thống xử lý dữ liệu hàng ngày từ hệ thống core banking và crm banking rồi load vào Bigquery nhằm phục vụ mục đích BI Dashboard.
  
## 2. Điểm nổi bật

- Thiết kế kiến trúc batch pipeline theo mô hình Bronze - Silver - Gold.
- Sử dụng Datastream để CDC theo thời gian thực từ source sang Bigquery.
- Xây dựng quy trình xử lý dữ liệu và đặt lịch chạy tự động trên Bigquery bằng Dataform.
- Thiết kế 3 bảng Fact và 6 bảng Dim theo mô hình Star schema.
- Xây dựng cơ chế nạp dữ liệu tăng dần, tối ưu truy vấn SQL, kiểm tra chất lượng dữ liệu trên Dataform.
- Xử lý khoảng 10 triệu record mỗi ngày.
- Tự động refresh 3 dashboard trên Data Studio.



## 3. Kiến trúc hệ thống
<img width="1636" height="654" alt="system-architecture" src="https://github.com/okjshdk/telecom-network-monitoring/blob/main/architecture.png" />



## 4. Công nghệ sử dụng
  - Storage: Bigquery
  - CDC: Datastream
  - Processing & Orchestration: Bigquery, Datform
  - Dashboard: Data Studio
  - Infrastructure: GCP

## 5. Use Case
  ### Customer Value & Engagement Analysis Dashboard
  ### Customer Profile Dashboard
  ### Branch Transaction Performance Dashboard


