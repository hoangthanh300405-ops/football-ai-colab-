# football-ai-colab
source: https://www.kaggle.com/datasets/excel4soccer/espn-soccer-data/data 
- Final_players_stats.csv là file có ranking và điểm (tấn công, phòng ngự) của cả team và từng người(đây là thử ko cần dựa trên) trọng số là tham khảo trên web và các cầu thủ được match với từng trận gòi(code : ranking_players.ipynb)
- players_data_light-2024_2025.csv là file stats của từng cầu thủ (code: Player_stat.ipynb )
- lineups.csv là file có cầu thủ nào đấu trận đấu nào( có chỉ số chung của cả mùa của từng cầu thủ) ko có điểm 
- Giải Thích
+ Player: Tên cầu thủ
+ Nation: Quốc tịch cầu thủ (ví dụ: POR, ENG, FRA)
+ Squad: Câu lạc bộ cầu thủ đang thi đấu
+ Comp: Giải đấu (ví dụ: Premier League)
+ Age :Tuổi cầu thủ (tính theo mùa giải)
+ MP (Matches Played) :Số trận đã ra sân
+ Min : Tổng số phút thi đấu
+ 90s Số trận quy đổi theo 90 phút( Min / 90)
+ Goals Số bàn thắng ghi được
+ Assists :Số kiến tạo
+ G+A: Tổng bàn thắng + kiến tạo
+ Shots: Tổng số cú sút
+ Shots_on_Target: Số cú sút trúng đích
+ xG (Expected Goals):Bàn thắng kỳ vọng
+ xA (Expected Assists):Kiến tạo kỳ vọng
+ Goals_per_90: Số bàn thắng trung bình mỗi 90 phút
+ Assists_per_90: Kiến tạo trung bình mỗi 90 phút
+ G+A_per_90: (Bàn thắng + kiến tạo) / 90 phút
+ Passes_Attempted: Tổng số đường chuyền
+ Passes_Completed: Số đường chuyền chính xác
+ Pass_Accuracy: Tỷ lệ chuyền chính xác (%)
+ Tackles :Số lần tắc bóng thành công
+ Interceptions: Số lần cắt bóng
+Blocks: Số lần chắn bóng
+Clearances: Số lần phá bóng

