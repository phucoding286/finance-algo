## Gợi ý, truy cập nguồn [```HistData.com```](https://www.histdata.com/) để tải các loại dữ liệu cặp tiền mới nhất.
- Hệ thống tín hiệu giao dịch EUR/USD, khung 5m [```Link repo```](https://github.com/phucoding286/eur-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
- Hệ thống tín hiệu giao dịch USD/JPY, khung 5m [```Link repo```](https://github.com/phucoding286/usd-jpy-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
- Hệ thống tín hiệu giao dịch GBP/CHF, khung 5m [```Link repo```](https://github.com/phucoding286/gbp-chf-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
- Hệ thống tín hiệu giao dịch AUD/NZD, khung 5m [```Link repo```](https://github.com/phucoding286/aud-nzd-trading-signal-5m-algo-fx) (Tối ưu cho sàn FX)
   
## Các công cụ, bot trade, giúp hổ trợ tự động trade.
1. [Bot gửi tín hiệu qua Telegram.](https://github.com/phucoding286/telegram-trading-signal-bot) (Chỉ hổ trợ cho các Hệ thống tối ưu cho sàn FX) (Created by Phu)

## Hướng dẫn sử dụng chi tiết và các lưu ý.
1. Đường dẫn ```C:\SIGNAL_LOG``` chính là folder chứa các file cache tín hiệu của tất cả thuật toán định lượng ở trên, nếu sau này có lỗi hay vấn đề gì có thể xóa folder này để reset lại.
2. Tăng trưởng vốn nhanh bằng lãi suất kép, ví dụ bạn có 400 đô, hãy đi với rủi ro là 5-10% vốn (tùy thuộc vào khẩu vị rủi ro) và reward nhận lại có thể là xấp xỉ rủi ro, ví dụ bạn có 400 đô, đi 5% risk là 20 đô, reward nhận lại là 20 đô, sau 1 tháng, bạn đi 10 lệnh, và hệ thống có 70% winrate, thì giả định bạn win 7/10 lệnh, thì bạn có thể nhận về 140 đô lãi, dùng công thức tính ```(10 * 20) - (20 * (10 - 7))```, sau cùng bạn được 540 đô, thay vì đi 20 đô ban đầu, tháng sau bạn có thể đi 25-27 đô, vì 5% của 540 đô lúc đó không còn là 20 đô nữa.
