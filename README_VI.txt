BE VE & TO MAU - BO DU AN ANDROID

Chuc nang trong ban dau:
- Hoat dong ngoai tuyen, khong can quyen Internet.
- Thu vien 100 mau tranh (bo mau SVG lap lai theo nhom hinh minh hoa).
- Cham vao cac vung trong tranh de to mau.
- Hoan tac, luu tranh trong bo nho trinh duyet cua ung dung.
- Hoc ve theo tung buoc, sao thuong va huy hieu.
- Du lieu luu tren thiet bi, khong gui len may chu.

CACH XUAT APK BANG DIEN THOAI (CAN TAI KHOAN GITHUB):
1. Dang nhap GitHub tren Chrome: https://github.com
2. Tao repository moi ten BeVeToMau, chon Public (de de thao tac) va Create repository.
3. Tai file ZIP nay ve dien thoai, giai nen bang Files / Quan ly tep.
4. Trong repository GitHub, chon Add file > Upload files.
5. Tai len TOAN BO NOI DUNG ben trong thu muc BeVeToMau_Android (khong tai ca thu muc long ben ngoai). Phai thay README_VI.txt, app, build.gradle, settings.gradle, gradle.properties va .github.
6. Bam Commit changes.
7. Mo tab Actions cua repository. Workflow "Build Android APK" se tu chay.
8. Mo lan chay moi nhat, cho den khi co dau xanh (Success).
9. Keo xuong muc Artifacts, bam BeVeToMau-APK de tai file ZIP chua APK.
10. Giai nen ZIP, mo app-debug.apk va cho phep Chrome/Files cai ung dung tu nguon nay neu Android hoi.

NEU KHONG THAY ACTIONS:
- Vao Settings > Actions > General, cho phep actions, sau do vao Actions chay workflow.
- Co the vao Actions > Build Android APK > Run workflow.

LUU Y:
- APK debug de cai va thu nghiem, chua phai ban phat hanh Google Play.
- Khong chia se repository cong khai neu sau nay them du lieu rieng.
- Sao va tranh duoc luu trong du lieu ung dung tren dien thoai. Xoa du lieu/giai cai dat co the lam mat tranh.
- Bo tranh hien tai gom 100 muc thu vien dua tren 20 hinh mau vector lap lai theo ten/chu de; chua phai 100 tranh ve rieng biet.
