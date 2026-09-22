# doanCNPM
Thuyết minh tự động đa ngôn ngữ — Mục 3: BE Services

Đồ án môn Công nghệ phần mềm — mục 3: xây dựng các backend service giao tiếp với nhau (Location, Geofence, Explanation, Translation, TTS), có REST API và CD/CI, phục vụ tính năng thuyết minh tự động theo vị trí GPS, hỗ trợ đa ngôn ngữ.

Ý tưởng

Người dùng di chuyển (trên web/mobile) → ứng dụng gửi vị trí GPS lên server → server kiểm tra xem người dùng có đang ở gần 1 điểm tham quan (POI) nào không → nếu có, tự động trả về nội dung thuyết minh (kèm audio) bằng đúng ngôn ngữ người dùng chọn.
