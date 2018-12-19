# B1: tải ảnh bản thiết kế có sẵn (design)
# B2: tạo thư mục Source Code
## 2.1:
		npm install -g expo-cli (nếu đã có expo bỏ qua bước này)
## 2.2: tạo dự án với tên: CVSPharmacy.
		expo init CVSPharmacy ( dùng phím lên xuống để chọn tabs đã build sẵn)
		cd CVSPharmacy
		expo start
## 2.3: Khởi động máy ảo(Genymotion)
## 2.4: Nhấn a để chạy project.
# B3:Cấu trúc lại các màn hình(screen) có sẵn	vào trong thư mục (vd:trong screens có screen1 screen2 ...; trong screens1 có: screen1.js; styles.js)

# B4: commit source đến github
## cần tạo một repository trên website github trước.
		- Chọn Your repository (góc trên bên phải)
		- Chọn New 
		- Gõ tên của repos đó: CVSPharmacy
## Đi đến thư mục gốc cần commit (cd..[lùi])
		git init
		git add .
		git commit -m "comment first code"
		git remote add origin https://github.com/phuthetran/CVSPharmacy.git
		git push -u origin master
## Đi đến website theo link để ktra thông tin đã commit
