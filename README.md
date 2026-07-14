# banking-analytics-batch-pipeline-GCP

# Data Engineer Project | End-to-end Banking Analytics Batch Pipeline (GCP)

## 1. Tổng quan
  Dự án xây dựng hệ thống xử lý dữ liệu hàng ngày từ hệ thống core banking và crm banking rồi load vào Bigquery nhằm phục vụ mục đích BI Dashboard.
  
## 2. Điểm nổi bật

- Thiết kế kiến trúc data pipeline theo mô hình Bronze – Silver – Gold trên Google Cloud Platform.
- Sử dụng Datastream để triển khai cơ chế CDC (Change Data Capture) đồng bộ dữ liệu gần thời gian thực từ source vào BigQuery.
- Xây dựng quy trình ELT workflow và tự động hóa lịch chạy bằng Dataform trên BigQuery.
- Thiết kế 3 Fact tables và 6 Dimension tables theo mô hình Star Schema.
- Xây dựng cơ chế incremental loading, tối ưu truy vấn SQL và triển khai kiểm tra chất lượng dữ liệu bằng Dataform assertions.
- Xử lý khoảng 10 triệu bản ghi/ngày và tối ưu hiệu suất pipeline.
- Tự động cập nhật dữ liệu cho 3 dashboard trên Looker Studio.



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


