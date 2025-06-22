Dự báo nhiệt độ theo chuỗi thời gian bằng mô hình học máy timeseries
Giới thiệu
Dữ liệu được thu ở các trạm đo trên toàn thế giới với tổng là hơn 40GB. Vì yêu cầu dữ liệu trên 10GB nên nhóm đã cắt bớt số lượng trạm do từ hơn 5000 trạm xuống còn 1000 trạm (10GB). Bài toán trên là sẽ lấy dữ liệu trong 96h để dự đoán cho 24h tiếp theo. Cuối cùng mục tiêu dự án là nhằm xây dựng và đánh giá các mô hình dự báo nhiệt độ theo tập dữ liệu nhiệt độ của toàn thế giới. Chúng tôi sử dụng 3 mô hình chính:
+ LMST
+ Informer
+ LinearRegession

Dữ liệu gốc dược thu thập từ https://github.com/taohan10200/WEATHER-5K
Nguồn dataset:
+ Data Thô: https://hkustconnect-my.sharepoint.com/:u:/r/personal/thanad_connect_ust_hk/Documents/research_project/WEATHER_5k/OpenSourced/WEATHER-5K.zip?csf=1&web=1&e=U4THrm
+ Data clean: https://drive.google.com/drive/folders/1wP9DaqkY2BTB27QlRERZvGhvdGz9H3mE?usp=sharing

Cấu trúc thư mục:
/img/ # Hình ảnh, biểu đồ minh họa
/model/ # File mô hình huấn luyện  
/weight/ # File đã huấn luyện
/tiensuly/
README.md # Tài liệu hướng dẫn

Cảm ơn Thầy/Cô và các bạn!!!
