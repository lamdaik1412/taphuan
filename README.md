## ------------------------------------------------------------

git init // tạo repo mới trên máy
git clone + link // chép code từ link về máy

git add + tên file // hoặc
git add . // để thêm tất cả vào chỉ mục
git commit -m "nội dung commit" // đưa các file đã add vào head.

git push origin + tên nhánh // đẩy code lên
git remote add origin link // map code trên máy và link trên github

## -------------------------------------------------------------

git pull // update code về á

git checkout -b + tên nhánh // tạo nhánh mới
git checkout + tên nhánh // chuyển nhánh
git checkout -d tên nhánh // xóa nhánh
git push origin + tên nhánh // đẩy nhánh
git merge + tên nhánh // merge code từ các nhánh đang hoạt động vào tên nhánh

git fetch origin
git reset --hard origin/master

https://rogerdudler.github.io/git-guide/index.vi.html
