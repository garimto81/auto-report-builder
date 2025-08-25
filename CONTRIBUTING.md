# 🤝 Auto Report Builder 기여 가이드

Auto Report Builder 프로젝트에 기여해주셔서 감사합니다! 

## 📋 목차
- [행동 강령](#행동-강령)
- [어떻게 기여할 수 있나요?](#어떻게-기여할-수-있나요)
- [개발 환경 설정](#개발-환경-설정)
- [Pull Request 프로세스](#pull-request-프로세스)
- [코딩 규칙](#코딩-규칙)
- [커밋 메시지 규칙](#커밋-메시지-규칙)

## 행동 강령

모든 기여자는 상호 존중하고 협력적인 환경을 유지해야 합니다.

## 어떻게 기여할 수 있나요?

### 버그 리포트
- GitHub Issues를 통해 버그를 신고해주세요
- 버그 재현 방법을 상세히 설명해주세요
- 환경 정보(OS, 브라우저 등)를 포함해주세요

### 기능 제안
- 먼저 Issues에서 논의를 시작해주세요
- 구체적인 사용 사례를 설명해주세요
- 가능하다면 목업이나 프로토타입을 제공해주세요

### 코드 기여
1. 이슈를 먼저 생성하거나 기존 이슈를 할당받으세요
2. Fork 후 feature 브랜치를 생성하세요
3. 코드를 작성하고 테스트를 추가하세요
4. Pull Request를 생성하세요

## 개발 환경 설정

```bash
# 저장소 클론
git clone https://github.com/yourusername/auto-report-builder.git
cd auto-report-builder

# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 테스트 실행
npm test
```

## Pull Request 프로세스

1. **브랜치 생성**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **코드 작성 및 테스트**
   - 모든 테스트가 통과해야 합니다
   - 새로운 기능은 테스트를 포함해야 합니다

3. **커밋**
   ```bash
   git commit -m "feat: 새로운 기능 추가"
   ```

4. **Push 및 PR 생성**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **코드 리뷰**
   - 최소 1명의 리뷰어 승인 필요
   - CI/CD 파이프라인 통과 필수

## 코딩 규칙

### TypeScript/JavaScript
- ESLint 규칙을 따릅니다
- Prettier로 포맷팅합니다
- 함수는 단일 책임 원칙을 따릅니다

### 네이밍 컨벤션
- 변수/함수: camelCase
- 클래스/타입: PascalCase
- 상수: UPPER_SNAKE_CASE
- 파일명: kebab-case

### 테스트
- 단위 테스트는 필수입니다
- 테스트 커버리지 80% 이상 유지
- E2E 테스트는 주요 플로우에 대해 작성

## 커밋 메시지 규칙

Conventional Commits 형식을 따릅니다:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Type
- `feat`: 새로운 기능
- `fix`: 버그 수정
- `docs`: 문서 수정
- `style`: 코드 포맷팅
- `refactor`: 리팩토링
- `test`: 테스트 추가/수정
- `chore`: 빌드, 설정 변경

### 예시
```
feat(auth): Google OAuth 로그인 추가

- Google OAuth 2.0 통합
- 사용자 프로필 자동 생성
- 세션 관리 개선

Closes #123
```

## 라이선스

기여하신 코드는 MIT 라이선스 하에 배포됩니다.

## 질문이 있으신가요?

- GitHub Discussions에서 질문해주세요
- Discord 커뮤니티에 참여하세요
- 이메일: contribute@autoreportbuilder.com

감사합니다! 🙏