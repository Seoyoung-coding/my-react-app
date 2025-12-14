my-react-app/
├── node_modules/     # 설치된 패키지
├── public/           # 정적 파일
├── src/
│   ├── assets/       # 이미지, 폰트 등
│   ├── App.css       # App 스타일
│   ├── App.jsx       # 메인 컴포넌트
│   ├── index.css     # 전역 스타일
│   └── main.jsx      # 진입점
├── index.html        # HTML 템플릿
├── package.json      # 프로젝트 설정
└── vite.config.js    # Vite 설정


## 지금 구조

VS Code = 코드 작성/수정하는 곳

브라우저 (http://localhost:5173) = 결과 화면 보는 곳

npm run dev = VS Code 코드 ↔ 브라우저를 연결해주는 개발 서버 실행 명령







## 1단계
```
function Welcome() {
  return <h1>안녕하세요, React입니다!</h1>;
}

function App() {
  return (
    <div>
      <Welcome />
    </div>
  );
}

export default App;
```
