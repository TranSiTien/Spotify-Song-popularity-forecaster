
# DỰ ĐOÁN ĐỘ PHỔ BIẾN CỦA BÀI HÁT K-POP TRÊN SPOTIFY

## 1. Tổng quan đề tài
- Giới thiệu đề tài: Dự đoán độ phổ biến của 1 bài hát K-pop dựa trên các yếu tố khác nhau (thời lượng, thời gian phát hành, nghệ sĩ,...) trên nền tảng Spotify
- Input: Dữ liệu chi tiết các bài hát K-pop trên trang web spotify.com
- Rút ra kết luận về mối tương quan giữa các thuộc tính
## 2. Cấu trúc thư mục
- raw_data.csv: File dữ liệu sau khi crawl
- clean_data.csv: File dữ liệu sau khi clean data
- crawl_data.ipynb: File notebook chứa mã nguồn crawl raw_data
- clean_data.ipynb: File notebook chứa mã nguồn clean raw_data
- visualization.ipynb: File notebook chứa mã nguồn trực quan hóa dữ liệu
- kpop.ipynb: File notebook tổng hợp
## 3. Hưỡng dẫn chạy chương trình
- Cài đặt các thư viện cần cho mã nguồn
- Chạy các file: crawl_data.ipynb, clean_data.ipynb, visualization.ipynb 
- Chạy file kpop.ipynb để thay thế cho 3 file trên
