# Phần 1
Báo cáo phân tích (I/O)
-   Input (Văn bản thô): Các đoạn văn bản chứa cú pháp Markdown (` ```python`, ký hiệu bảng `|`, task list `- [ ]`, và ký tự thoát `\*`).
    
-   Output (Giao diện render trên StackEdit):
    
    -   Khối code Python hiển thị màu sắc cú pháp (Syntax Highlighting).
        
    -   Bảng so sánh hiển thị dạng lưới trực quan.
        
    -   Danh sách tác vụ hiển thị các hộp kiểm (checkbox).
        
    -   Ký tự đặc biệt hiển thị chính xác nhờ ký tự Escape (`\`).
   ## Source Code (`.md`)

Markdown

```
# Hướng dẫn cài đặt VS Code

## 1. Khai báo biến
Cấu hình biến `workspace_path` và `python_version`.

## 2. Mã nguồn Python
```python
import sys

def check_env():
    print(f"Python version: {sys.version}")

if __name__ == "__main__":
    check_env()
```
