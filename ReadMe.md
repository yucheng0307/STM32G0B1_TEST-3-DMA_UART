TEST-3-UART to 電腦
===
UART與電腦互相通訊
---
# 內容
- 開發板連結至電腦之UART，使用此UART與電腦進行通訊。
- 與TEST-2使用中斷方式不同，此練習使用DMA方式進行接收、中斷方式進行傳輸，比TEST-2更加實用。
---
## 描述
- 練習STM32如何使用UART並與電腦連接，互相通訊。
- 電腦傳送4 bytes data給MCU。
- MCU利用DMA-UART收到4 bytes data，透過中斷傳輸"hello world"給電腦。
- 於MCU debug模式確認是否有接收到data。
- 於電腦確認是否收到MCU回傳"hello world"。
---