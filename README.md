# 단골창구 (dangol.org)

작은 가게의 문의 창구. 사장님은 가게 사진과 소개만 올리면 바로 열고, 손님은 QR만 찍으면 앱 없이 묻습니다.

- 서버: 가림 서버(Supabase qmwaraittiurkynszjts) — `baroka/sql/9_dangol_desk.sql`, `10_dangol_pay.sql`
- 같은 파일을 aliascall.com 과 함께 씁니다: `dangol.html`(손님) · `dangol_owner.html`(사장님) · `dangol_poster.html`(QR 포스터)
  — 주소(dangol.org)를 보고 로그인 화면 · 상품 번호 · QR 주소를 바꿉니다.
- 이 사이트만의 파일: `index.html`(첫 화면 · `?c=코드` → 손님 화면) · `login.html` · `terms.html` · `privacy.html` · `delete.html`
- 앱: 안드로이드 · 아이폰 `com.weaveapp.dangol` (사장님용), 결제 상품 구글 `dangol_1y` · 애플 `dangol_1y_nr` (1년 9,900원)
