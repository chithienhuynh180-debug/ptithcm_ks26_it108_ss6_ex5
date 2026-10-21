## 1. sơ đồ ipo
- input. file trong downloads
- process. kiểm tra đuôi file
- output. ảnh vào media, code vào scripts, file tmp thì xóa

## 2. lệnh robot

```bash
cd ~/Downloads
mkdir -p media scripts
mv -n *.png *.jpg media/
mv -n *.py scripts/
rm -i *.tmp
```

nếu gặp thư mục trùng tên thì bỏ qua file đó để tránh lỗi.
