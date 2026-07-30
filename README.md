## Gợi ý, truy cập nguồn [```HistData.com```](https://www.histdata.com/) để tải các loại dữ liệu cặp tiền mới nhất.
- Các hệ thống khung M15.
  - Hệ thống tín hiệu giao dịch BTC/USD, khung 15m. [```Link repo.```](https://github.com/phucoding286/btc-trade-signal-15m-algo) (Hổ trợ bot OKX) (Tối ưu cho sàn crypto) (Tạm ngừng phát triển và bảo trì, do nghị định 284/2026 NĐ-CP)
  - Hệ thống tín hiệu giao dịch XAU/USD, khung 15m [```Link repo```](https://github.com/phucoding286/xau-trading-signal-15m-algo) (Hổ trợ bot OKX) (Tối ưu cho sàn crypto)
  - Hệ thống tín hiệu giao dịch XAU/USD, khung 15m [```Link repo```](https://github.com/phucoding286/xau-trading-signal-15m-algo-fx) (Tối ưu cho sàn FX)
  - Hệ thống tín hiệu giao dịch EUR/USD, khung 15m [```Link repo```](https://github.com/phucoding286/eur-trading-signal-15m-algo-fx) (Tối ưu cho sàn FX)
  - Hệ thống tín hiệu giao dịch USD/JPY, khung 15m [```Link repo```](https://github.com/phucoding286/usd-jpy-trading-signal-15m-algo-fx) (Tối ưu cho sàn FX)
- Các hệ thống khung M5.
  - Hệ thống tín hiệu giao dịch EUR/USD, khung 5m [```Link repo```](https://github.com/phucoding286/eur-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
  - Hệ thống tín hiệu giao dịch USD/JPY, khung 5m [```Link repo```](https://github.com/phucoding286/usd-jpy-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
  - Hệ thống tín hiệu giao dịch XAU/USD, khung 5m [```Link repo```](https://github.com/phucoding286/xau-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
   
## Các công cụ, bot trade, giúp hổ trợ tự động trade.
1. [Bot trade OKX, tự động mở lệnh theo tín hiệu.](https://github.com/phucoding286/okx-bot-trade) (Created by Phu) (Project đã bị hỏng, không nên dùng!)
2. [Bot gửi tín hiệu qua Telegram.](https://github.com/phucoding286/telegram-trading-signal-bot) (Chỉ hổ trợ cho các Hệ thống tối ưu cho sàn FX) (Created by Phu)

## Lưu ý quan trọng.
1. Tránh dùng các tín hiệu xuyên qua cuối tuần, ví dụ hôm thứ sáu bạn quyết định dừng trade và đợi qua cuối tuần, nhưng hệ thống báo một tín hiệu LONG hoặc SHORT gì đó, bạn bỏ qua do cuối tuần không trade, sang thứ hai nó vẫn giữ tín hiệu đấy thì không nên vào lệnh ngay, hãy đợi tín hiệu mới để trade.
2. Đường dẫn ```C:\SIGNAL_LOG``` chính là folder chứa các file cache tín hiệu của tất cả thuật toán định lượng ở trên, nếu sau này có lỗi hay vấn đề gì có thể xóa folder này để reset lại.
3. Các thuật toán cho chart 15m đợi tín hiệu khá lâu, và không có tín hiệu vào lệnh nhiều và vì khoảng giá rộng hơn nên khiến sl và tp xa hơn bạn có thể phải đợi lâu hơn để tp, khiến lệnh dễ bị sl hơn do giá quay ngược, bạn có thể không nên dùng 15m nếu không muốn đợi quá nhiều hoặc tài khoản còn nhỏ, ưu tiên dùng các thuật toán tối ưu cho 5m.
