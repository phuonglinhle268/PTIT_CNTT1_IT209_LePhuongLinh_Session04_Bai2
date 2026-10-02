# Du an Quan ly Phien ban
Phien ban: 1.0.0
Mo ta: He thong quan ly tai lieu ket hop Main va Feature Update.

---

## Bao cao Giai quyet Xung dot (Merge Conflict Report)

### 1. Cac buoc xu ly xung dot thu cong
- **Phat hien xung dot:** Sau lenh 'git merge feature-update', Git bao loi conflict tai dong mo ta trong file README.md.
- **Xoa dau phan cach:** Xoa bo hoan toan cac ky hieu Git chen vao: '<<<<<<< HEAD', '=======', va '>>>>>>> feature-update'.
- **Hop nhat noi dung:** Chinh sua lai dong noi dung phu hop de giu lai y nghia cua ca hai nhanh.
- **Luu va danh dau da xu ly:** Chay 'git add README.md' de dua file vao Staging Area.
- **Tao merge commit:** Chay 'git commit' de hoan tat qua trinh gop nhanh.

### 2. Giai thich co che gop 3 vung (3-Way Merge)
- Git su dung 3 commit de doi chieu:
  1. **Base Commit:** Commit to tien chung gan nhat giua 2 nhanh (Init commit).
  2. **Ours Commit (HEAD):** Commit moi nhat tren nhanh dang dung ('main').
  3. **Theirs Commit:** Commit moi nhat tren nhanh can gop vao ('feature-update').
- Khi ca 'Ours' va 'Theirs' deu sua cung mot dong so voi 'Base', Git khong the tu quyet dinh dong nao dung nen bat buoc nguoi dung phai giai quyet thu cong.
