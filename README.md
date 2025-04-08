#  🐱 FlappyCat – The Impossible Meow
**FlappyCat** là một mini game 2D vui nhộn, phát triển bằng ngôn ngữ **C++** kết hợp với thư viện **SDL2**. Cảm hứng từ Flappy Bird huyền thoại, trong game này bạn sẽ điều khiển một chú mèo bay lượn giữa những cột ống xanh trên hành trình chống lại trọng lực và sự nống nảy.

---

## ✨ Tính năng nổi bật

- 🐾 Nhấn phím để mèo bay, thảo tay là mèo rơi.
- 👽 Tránh va chạm với ống nước và mặt đất.
- 🌟 Tính điểm khi vượt qua ống, lưu điểm cao nhất vào file.
- ⏸️ Tạm dừng / Tiếp tục / Replay.
- 🎶 Hiệu ứng âm thanh sinh động.
- 🎨 Đồ họa pixel art đơn giản, trí tuệ.

---

## 🎮 Cách chơi

- **Space / Click chuột**: Mèo nhảy lên.
- Tránh va chạm ống hoặc rơi xuống đất.
- Mỗi cặp ống vượt qua: +1 điểm.
- Game Over khi va chạm. Chọn replay để bày tiếp!

---

## 📁 Cài đặt

### Yêu cầu:

- C++ Compiler (g++, Code::Blocks...)
- SDL2, SDL2\_image, SDL2\_mixer, SDL2\_ttf

### Build (Linux/macOS):

```bash
g++ -o flappycat main.cpp game.cpp cat.cpp pipe.cpp land.cpp lib.cpp sound.cpp \
    -lSDL2 -lSDL2_image -lSDL2_mixer -lSDL2_ttf
./flappycat
```

### Code::Blocks (Windows):

- Mở `flappycat.cbp`
- Build & Run
- Copy các DLL và folder `res/` đến chung thư mục với .exe

---

## 📂 Cấu trúc dự án

```
flappycat/
├── main.cpp            # Chính game loop
├── game.*              # Quản lý trạng thái game
├── cat.*               # Logic nhân vật chính
├── pipe.*              # Sinh và di chuyển ống
├── land.*              # Đất trượt
├── lib.*               # Load texture, vẽ text, số...
├── sound.*             # Xử lý âm thanh
├── res/                # Tài nguyên hình, âm, data
```

---

## 🌟 Mục tiêu dự án

- Học SDL2 & C++ thực tiễn.
- Tài liệu tham khảo cho beginner.
- Cái cớ vững chắc cho ai muốn làm game nghiêm tụ.

---

## 🚀 Tính năng đề xuất tương lai

-

---

## 💼 Giấy phép

Dự án này chệ yêu cầu phi thương mại và học tập, có thể sử dụng tự do.

---

## 🙋 Liên hệ

> Yêu thích FlappyCat? Muốn tham gia cùng làm game? Gửi **meo** cho chúng tôi!

---

***Hãy giúp chú mèo bay cao, tránh xa cái ống xanh và chế nâu!***

Những người làm game này:

Nhóm 3: Trần Bá Lực - 23021418

               Vũ Đình Huy - 23021408

              Trần Tuấn Minh - 23021422

From K68-SAE
