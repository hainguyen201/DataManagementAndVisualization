# Chạy hệ thống
```
docker-compose up -d
```
- Truy cập vào nifi: https://localhost:8443/nifi
    - username/pass: hainvadmin/hainvadmin@123
- Truy cập vào hadoop namenode: http://localhost:9870
- Truy cập vào pyspark
  ```
  Xem log
  docker logs -f pyspark-notebook
  ```
  Truy cập đường dẫn bắt đầu bởi: http://127.0.0.1:8888/
# File chạy các biểu đồ: 
  Truy cập file DataCovidAnalysis.ipynb
# Chạy nifi download dữ liệu trên internet
 - Truy cập nifi: https://localhost:8443/nifi
 - Upload file template PullDataTemplate.xml
 - Chạy từng group process tương ứng để tải dữ liệu về HDFS
   
