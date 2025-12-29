# Flex LIFF + Firebase

## การตั้งค่า

1. สร้าง Firebase Project
2. เปิด Firestore Database
3. สร้าง collection `appData` และ document `whitelistDoc` (document เดียว)
4. คัดลอก Firebase Config แล้ววางในไฟล์ `index.html` แทน `YOUR_API_KEY`, `YOUR_PROJECT_ID` ฯลฯ
5. เปิด LIFF App แล้วตั้ง LIFF ID ในไฟล์ `index.html`
6. Deploy ไป GitHub Pages หรือ Firebase Hosting

## วิธีใช้งาน

- Admin:
  - เพิ่ม/ลบ user ใน whitelist
  - แชร์ Flex ได้
- User:
  - แชร์ Flex ได้ถ้าอยู่ใน whitelist
  - กดปุ่มแอดไลน์แอดมิน หรือสแกน QR code
