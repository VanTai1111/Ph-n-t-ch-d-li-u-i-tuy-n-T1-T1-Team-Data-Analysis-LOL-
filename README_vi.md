# 📊 Phân Tích Dữ Liệu Đội Tuyển T1 | T1 Esports Data Analysis

### 1. Giới thiệu
Dự án này thực hiện thu thập, xử lý và phân tích dữ liệu thi đấu của đội tuyển **T1** trong các giải đấu.  
Quy trình gồm:
1. **Crawl dữ liệu** từ trang [T1 Match History on LoL Fandom](https://lol.fandom.com/wiki/T1/Match_History) từ 01/2022 - 08/2025 (các cột: `Date`, `Tournament`, `P`, `W/L`, `Side`, `Vs`, `Bans`, `Bans Vs`, `Picks`, `Picks Vs`, `Players`, `SB`, `VOD`).
2. **Tiền xử lý dữ liệu** bằng Python và Power Bi: gộp file, xóa trùng lặp, chuẩn hóa tên cột(Tournament, Vs), tạo các measure.
3. **Trực quan hóa** bằng Power BI: tạo dashboard phân tích kết quả, hiệu suất, và so sánh...

---

### 2. Công cụ sử dụng
- **Python**: BeautifulSoup(bs4), requests, pandas
- **Power BI**: tạo báo cáo 
- **Nguồn dữ liệu**: dữ liệu công khai từ trang [T1 Match History on LoL Fandom](https://lol.fandom.com/wiki/T1/Match_History)

**Tác giả:** Tai Pham
