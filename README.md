# 🎬 TG Video Editor Simple

**Telegram Bot สำหรับตัดต่อวิดีโอแบบง่าย ๆ**

## ฟีเจอร์หลัก
- 🎬 Jump Cut (ตัดช่วงเงียบ)
- 🔇 Remove Air (ลบเสียงลมหายใจ/แอร์)
- ⚡ Full Auto

## วิธีใช้ใน Google Colab (แนะนำ)

```python
!git clone https://github.com/superkiatam12345-art/tg-video-editor-simple.git
%cd tg-video-editor-simple

!apt-get update -qq && apt-get install -y ffmpeg
!pip install -r requirements.txt

# รัน Bot
python bot.py
```

## วิธีตั้งค่า
1. สร้าง Bot ที่ @BotFather
2. เอา Token มาใส่ใน `config.py`

---

**พร้อมใช้งานทันทีใน Colab**