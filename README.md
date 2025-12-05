# workout-sns-app
React Native app for Workout SNS

## 기술 스택

- React Native 0.73.x
- TypeScript
- Zustand (상태관리)
- React Query (서버 상태)
- React Navigation

## 로컬 실행

### 1. 환경변수 설정
```bash
cp .env.example .env
# .env 파일 열어서 API_URL 등 설정
```

### 2. 의존성 설치
```bash
npm install
```

### 3. Android 실행
```bash
npm run android
```

## 주요 기능

- 회원가입/ 로그인 (JWT + 카카오)
- 게시글 작성/조회 (이미지 포함)
- 좋아요/댓글
- 푸시 알림
- 카카오톡 공유

## 관련 저장소
- [백엔드 (Spring Boot)](https://github.com/jayhug2/workout-sns-api)
