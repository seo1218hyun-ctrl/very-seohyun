# 나의 첫 배포

연세대학교 창업학회 VERY의 개발 특강 실습용 템플릿입니다. 설치도, 터미널도, 코드 작성도 필요 없습니다. 브라우저만 있으면 이 페이지를 내 계정으로 가져와 인터넷에 올릴 수 있습니다.

## 시작하기 전에

세 곳에 가입해 둡니다. 모두 무료입니다.

1. [GitHub](https://github.com) 가입
2. [Vercel](https://vercel.com) 가입. `Continue with GitHub`를 눌러 방금 만든 GitHub 계정으로 들어갑니다
3. [Claude](https://claude.ai) 가입. 쓰던 AI 채팅이 있으면 그것을 써도 됩니다

## 걸음 1. 내 주소 받기

아래 버튼을 누릅니다.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYONSEIVERY%2Ffirst-deploy&repository-name=very-myname)

1. 저장소 이름 칸의 `very-myname`에서 `myname`을 내 영문 이름으로 바꿉니다. 예: `very-minseo`
2. `Create`를 누르고 1분쯤 기다립니다
3. 축하 화면이 뜨면 끝입니다. `very-내이름`으로 시작하는 주소가 생겼습니다. 같은 이름을 누가 먼저 썼다면 뒤에 글자가 더 붙는데, 정상입니다. 휴대폰으로도 열어 보세요

방금 일어난 일: 이 템플릿이 내 GitHub 계정에 복제됐고, Vercel이 그것을 인터넷에 올렸습니다.

## 걸음 2. 고쳐서 다시 배포하기

1. [github.com](https://github.com)에서 방금 생긴 내 저장소(`very-내이름`)를 엽니다
2. `index.html`을 누르고 오른쪽 위 연필 아이콘을 누릅니다
3. `홍길동`을 내 이름으로 바꿉니다
4. 오른쪽 위 `Commit changes...`를 누르고, 한 번 더 `Commit changes`를 누릅니다
5. 1분 뒤 내 주소를 새로고침합니다. 이름이 바뀌어 있습니다

방금 일어난 일: 저장(커밋)을 했더니 Vercel이 알아서 다시 올렸습니다. 개발자들이 매일 하는 일이 이것입니다.

## 걸음 3. AI로 내 아이디어 페이지 만들기

1. `index.html` 내용을 전부 복사합니다
2. Claude에 붙여넣고 이렇게 부탁합니다

   > 이 페이지를 내 해커톤 아이디어 소개 페이지로 바꿔 줘. 아이디어는 (한 줄 설명)이야. 대상은 (누구)이고, 사전 신청 버튼이 하나 있으면 좋겠어. HTML 파일 하나로, 외부 파일 없이 만들어 줘.

3. 받은 코드를 전부 복사해 GitHub의 `index.html`에 덮어씁니다(연필 → 전체 선택 → 붙여넣기)
4. `Commit changes`를 누르고 1분 뒤 새로고침합니다

마음에 안 들면 Claude에게 "제목을 더 크게", "휴대폰에서 더 보기 좋게"처럼 한 가지씩 다시 부탁하고 같은 방법으로 덮어씁니다.

## 더 해 보기

- [Tally](https://tally.so)로 신청 폼을 만들어 페이지의 버튼에 연결하기
- 걸음 3을 하기 전이라면 `style.css` 맨 위의 색 다섯 줄을 바꿔 내 색으로 만들기. 걸음 3을 마쳤다면 Claude에게 색을 바꿔 달라고 부탁하기
- [Microsoft Clarity](https://clarity.microsoft.com)를 붙여 사람들이 어디를 누르는지 보기

## 막혔을 때

- 걸음 1에서 GitHub 연결 화면이 나오면 `Install`을 눌러 허용합니다
- 주소를 열었는데 예전 화면이면 1분 더 기다렸다가 새로고침합니다
- 망쳤다 싶으면 걱정하지 않아도 됩니다. GitHub는 모든 저장을 기억하고 있어서 `index.html`의 `History`에서 예전 내용을 볼 수 있습니다

## 이 저장소에 들어 있는 것

| 파일 | 하는 일 |
|---|---|
| `index.html` | 페이지의 내용. 여기를 고칩니다 |
| `style.css` | 페이지의 생김새. 색과 글자 크기가 들어 있습니다 |
| `README.md` | 지금 읽고 있는 안내문 |
