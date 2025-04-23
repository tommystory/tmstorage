# tmstorage
# TMStorage 셀러 플랫폼

Clickmate를 벤치마킹한 셀러 전용 플랫폼입니다.  
판매자 상품 관리, 관리자 승인, 통계 기능까지 구현된 풀스택 프로젝트입니다.

## 🔧 기술 스택
- 프론트엔드: React, React Router, TailwindCSS
- 백엔드: Node.js, Express
- 데이터베이스: MongoDB (Mongoose)
- 인증: JWT
- 배포: (예정) Vercel + Render

## 📁 폴더 구조


tmstorage/ ┣ client/ 👉 프론트엔드 (React) ┃ ┣ src/pages/ 👉 페이지 구성 ┃ ┣ src/components/👉 공통 컴포넌트 ┃ ┗ src/services/ 👉 API 연동 ┣ server/ 👉 백엔드 (Express) ┃
┣ routes/ 👉 로그인, 상품, 유저 API ┃ ┣ models/ 👉 User, Product 모델 ┃ ┗ controllers/ 👉 비즈니스 로직 ┣ .env.example 👉 환경 변수 예시 ┗ README.md


## ✨ 기능 요약
- [x] 판매자 회원가입 / 로그인 (JWT)
- [x] 상품 등록 / 수정 / 삭제
- [x] 판매자 연락처, 정산 정보 관리
- [x] 관리자 기능 (셀러 승인 / 상품 목록 보기)
- [ ] 판매 통계 대시보드 (구현 예정)
- [ ] 이미지 업로드 (Cloudinary 연동 예정)

## 🚀 실행 방법
### 백엔드
```bash
cd server
npm install
npm run dev

##프론트엔드
cd client
npm install
npm start

## 환경 변수 설정 (.env)
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_secret_key
PORT=5000


### ✅ 3단계: 아래쪽으로 스크롤해서
- `"Commit changes"` 버튼이 있어
- 메시지는 그냥 두고
- **초록색 버튼 클릭**

cd client
npm install
npm start

cd server
npm install
npm run dev


