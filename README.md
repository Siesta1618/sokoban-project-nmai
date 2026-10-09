# Sokoban + AI

Game Sokoban chạy trong Jupyter Notebook, có AI tự đăng nhập và chơi bằng thuật toán tìm kiếm.

## Cài đặt

```bash
python -m venv .venv
.venv\Scripts\activate          # Windows
pip install -r requirements.txt
```

Mở `sokoban_ai.ipynb`, chọn kernel `.venv` rồi chạy **Run All**.

## Nội dung notebook

| Mục | Nội dung |
|---|---|
| §1 | Cài đặt & import |
| §2 | Level (định dạng XSB) |
| §3 | Game engine: `Level`, `SokobanGame` |
| §4 | Hiển thị: vẽ bàn chơi, phát lại, xuất GIF vào `outputs/` |
| §5 | Người chơi thật (nút bấm ipywidgets) |
| §6 – §10 | AI: giao thức đăng nhập, BFS/DFS/UCS/A*, demo, thực nghiệm *(đang làm)* |

> Trước khi nộp: **Restart & Run All** để lưu toàn bộ output (hình, GIF) vào file `.ipynb`.
