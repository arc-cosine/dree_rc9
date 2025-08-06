# 📘 Anonymous Community Board (Vanila.JS + Firebase)

익명 게시판 프로젝트입니다. Firebase Firestore, Authentication, Hosting을 기반으로 바닐라.JS 사용해 구현된 웹 커뮤니티 앱입니다.

## 🚀 Features

- ✅ 익명 글 작성 및 삭제
- ✅ 좋아요(추천) 기능
- ✅ 인기글 분류 (좋아요 기준)
- ✅ Firestore 기반 실시간 게시글 반영
- ✅ Firebase Authentication (익명 로그인)
- ✅ 반응형 UI

## 🛠️ Tech Stack

| Frontend | Backend (BaaS) | 기타 |
|----------|----------------|------|
| JavaScript | Firebase Hosting | Vercel (optional) |



## 🔧 Firebase 세팅 방법

1. [Firebase 콘솔](https://console.firebase.google.com/)에서 새 프로젝트 생성
2. Authentication > Sign-in method > 구글 로그인 활성화
3. Firestore Database > 보안 규칙 설정 (read, write 모두 가능)
4. Firebase Hosting 사용 시 배포 설정 가능

## 📦 설치 및 실행 방법

```bash
# 1. 레포 클론
git clone https://github.com/arc-cosine/dree_rc9.git

# 2. 디렉토리 이동
cd your-repo-name

# 3. 패키지 설치
npm install

# 4. 개발 서버 실행
npm start
```

## 💡 TODO

- [ ] 댓글 기능 추가
- [ ] 신고 기능 추가
- [ ] 관리자 페이지
- [ ] 유저 간 쪽지 기능
- [ ] 글 검색 기능

## 📝 License

MIT License

Made.by RC9 Studio.
Project 要雅所非
