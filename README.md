🤖 Th07z Discord Bot

Một Discord bot đa chức năng được viết bằng Node.js, hỗ trợ AI, NSFW, Giveaway, Moderation và nhiều tiện ích khác.

---

🚀 Tính năng chính

🤖 AI

- Chat AI ("ask.js")
- Xử lý câu hỏi người dùng

🎉 Giveaway

- "gstart" – tạo giveaway
- "gend" – kết thúc giveaway
- "greroll" – quay lại người thắng
- "gdelete" – xoá giveaway
- "glist" – danh sách giveaway

🔞 NSFW

«⚠️ Chỉ hoạt động trong kênh NSFW»

- Ảnh/video: boobs, ass, hentai, neko, genshin, roblox...
- rule34 API
- tags NSFW

👉 Lưu ý: Một số API có thể đã bị bạn xoá → người dùng cần tự thêm lại API key.

---

📦 Tiện ích (Util)

- "afk" – chế độ AFK
- "userinfo", "serverinfo"
- "avatar", "banner"
- "stats"
- "prefix"

---

🛡️ Moderation

- "lock", "unlock", "lockall"
- "hide", "hideall"
- "role", "rrole"
- "nickname"
- "purgebots"
- quản lý channel & role

---

⚙️ Hệ thống khác

- AFK voice system ("afkVoice.json")
- Giveaway manager ("giveawayUtils.js")
- Guild data ("guilds.json")
- Emoji config ("emojis.json")
- Cluster support ("cluster.js")

---

📁 Cấu trúc thư mục

src/
 ├── commands/
 │    ├── 🤖 AI/
 │    ├── 🎉 Giveaway/
 │    ├── 🔞 Nsfw/
 │    ├── 📦 Util/
 │    └── 🛡️ Moderation/
 │
 ├── utils/
 ├── data/
 ├── Zay/
 ├── app.js
 └── cluster.js

---

⚙️ Cài đặt

1. Clone về

git clone <repo>
cd Th07z

2. Cài dependencies

npm install

3. Cấu hình ".env"

TOKEN=your_discord_bot_token
MONGO=your_mongodb_uri

👉 Nếu bạn đã xoá:

- API NSFW → người dùng tự thêm lại
- AI key → tự cấu hình lại (Gemini/OpenAI)

---

4. Config file

"src/config.json"

- prefix
- ownerID
- guildLogs
- link server hỗ trợ

👉 Nếu thiếu → tự tạo lại theo format.

---

▶️ Chạy bot

node src/app.js

Hoặc dùng cluster:

node src/cluster.js

---

❗ Lưu ý

- Một số file/API có thể đã bị xoá → bạn cần tự thêm lại:
  - API NSFW
  - API AI
  - MongoDB config
- Không có database → bot vẫn chạy nhưng sẽ mất dữ liệu
- NSFW cần bật kênh NSFW trong Discord

---

📌 TODO (gợi ý thêm)

- [ ] Thêm dashboard web
- [ ] Logging nâng cao
- [ ] Slash command
- [ ] Anti-spam / anti-raid

---

👤 Author

- Zay (custom build lại)

---

📜 License

Free to use, chỉnh sửa thoải mái 👍
