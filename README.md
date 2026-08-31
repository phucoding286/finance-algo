## Gợi ý, truy cập nguồn [```HistData.com```](https://www.histdata.com/) để tải các loại dữ liệu cặp tiền mới nhất.

1. Các thuật toán giao dịch thuộc mô hình MA Heads và R/S Detector.
   - Các thuật toán cho khung M5.
       - Mô hình MA Heads đã optimized cho EUR/USD, khung M5 [```Link repo```](https://github.com/phucoding286/eur-trading-signal-5m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads đã optimized cho CAD/JPY, khung M5 [```Link repo```](https://github.com/phucoding286/cad-jpy-trading-signal-5m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads đã optimized cho GBP/CHF, khung M5 [```Link repo```](https://github.com/phucoding286/gbp-chf-trading-signal-5m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads đã optimized cho AUD/NZD, khung M5 [```Link repo```](https://github.com/phucoding286/aud-nzd-trading-signal-5m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
   - Các thuật toán cho khung M1.
       - Mô hình MA Heads đã optimized cho XAU/USD, khung M1 [```Link repo```](https://github.com/phucoding286/xau-trading-signal-1m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads đã optimized cho USTEC, khung M1 [```Link repo```](https://github.com/phucoding286/ustec-trading-signal-1m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads đã optimized cho UK100, khung M1 [```Link repo```](https://github.com/phucoding286/uk100-trading-signal-1m-MaHeads-algo-fx) (Tối ưu cho sàn FX)
         
2. Các thuật toán giao dịch thuộc mô hình Market Structure Validate và R/S Detector (MSV).
   - Các thuật toán cho khung M1.
       - Mô hình MSV đã optimized cho XAU/USD, khung M1 [```Link repo```](https://github.com/phucoding286/xau-m1-trading-MSV-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MSV đã optimized cho USTEC, khung M1 [```Link repo```](https://github.com/phucoding286/ustec-trading-signal-1m-MSV-algo-fx) (Tối ưu cho sàn FX)
       - Mô hình MSV đã optimized cho UK100, khung M1 [```Link repo```](https://github.com/phucoding286/uk100-trading-signal-1m-MSV-algo-fx) (Tối ưu cho sàn FX)
    
3. Nhánh các thuật toán thích nghi nhanh liên tục với thị trường (liên tục tối ưu hóa trong thời gian ngắn, vẫn sử dụng các kiến trúc trên.)
   - Các thuật toán cho khung M1.
       - Mô hình MA Heads fast-adaptive cho XAU/USD, khung M1 [```Link repo```](https://github.com/phucoding286/xau-m1-trading-MaHeads-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads fast-adaptive cho USTEC, khung M1 [```Link repo```](https://github.com/phucoding286/ustec-m1-trading-MaHeads-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MA Heads fast-adaptive cho UK100, khung M1 [```Link repo```](https://github.com/phucoding286/uk100-m1-trading-MaHeads-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MSV fast-adaptive cho XAUUSD, khung M1 [```Link repo```](https://github.com/phucoding286/xau-m1-trading-MSV-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MSV fast-adaptive cho USTEC, khung M1 [```Link repo```](https://github.com/phucoding286/ustec-m1-trading-MSV-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
       - Mô hình MSV fast-adaptive cho UK100, khung M1 [```Link repo```](https://github.com/phucoding286/uk100-m1-trading-MSV-fast-adaptive-algorithm-fx) (Tối ưu cho sàn FX)
    
## Lưu ý khi chạy nhiều mô hình song song.
1. Nên đặt lot theo risk là số tiền risk cho cho tổng số thuật toán bạn muốn chạy trên mỗi lệnh của mỗi thuật toán mà bạn chấp nhận, điều này giúp phân phối toán học chính xác hơn.
2. Giả sử bạn có vốn 100 đô, bạn chấp nhận tối đa mỗi lệnh chỉ mất 5 đô, nhưng bạn lại chạy 2 hệ thống song song, thì nên đặt risk cho mỗi lệnh là 2.5 đô.
   
## Các công cụ, bot trade, giúp hổ trợ tự động trade.
1. [Bot gửi tín hiệu qua Telegram.](https://github.com/phucoding286/telegram-trading-signal-bot) (Chỉ hổ trợ MA Heads algorithm) (Created by Phu)
2. [Bot tự động trade, MT5/Exness.](https://github.com/phucoding286/exness-bot-trade) (Hổ trợ tất cả thuật toán trên)
3. [Tool backtest các thuật toán trong danh mục và thống kê hiệu suất tổng thể.](https://github.com/phucoding286/portfolio-backtest) (Hổ trợ tất cả thuật toán trên)

## Hướng dẫn sử dụng chi tiết và các lưu ý.
1. Đường dẫn ```C:\SIGNAL_LOG``` chính là folder chứa các file cache tín hiệu của tất cả thuật toán định lượng ở trên, nếu sau này có lỗi hay vấn đề gì có thể xóa folder này để reset lại.
2. Tăng trưởng vốn nhanh bằng lãi suất kép, ví dụ bạn có 400 đô, hãy đi với rủi ro là 5-10% vốn (tùy thuộc vào khẩu vị rủi ro) và reward nhận lại có thể là xấp xỉ rủi ro, ví dụ bạn có 400 đô, đi 5% risk là 20 đô, reward nhận lại là 20 đô, sau 1 tháng, bạn đi 10 lệnh, và hệ thống có 70% winrate, thì giả định bạn win 7/10 lệnh, thì bạn có thể nhận về 140 đô lãi, dùng công thức tính ```(10 * 20) - (20 * (10 - 7))```, sau cùng bạn được 540 đô, thay vì đi 20 đô ban đầu, tháng sau bạn có thể đi 25-27 đô, vì 5% của 540 đô lúc đó không còn là 20 đô nữa.
