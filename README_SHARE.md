# Rumble Dodgeball 공유 방법

이 시뮬레이터는 `index.html` 하나로 실행됩니다.

## 같은 와이파이/사내망에서 URL로 공유

1. 이 폴더에서 서버를 실행합니다.

```powershell
node .\share-server.js
```

2. 터미널에 표시되는 `Network` 주소를 팀원에게 공유합니다.

예시:

```text
http://172.21.1.35:8765/
```

팀원은 같은 네트워크에 있어야 합니다. Windows 방화벽 알림이 뜨면 Private network 허용이 필요할 수 있습니다.

## 네트워크가 다를 때

파일 하나만 보내려면 `index.html`을 전달하면 됩니다. 팀원은 파일을 더블클릭해서 브라우저로 열 수 있습니다.

외부 팀원이 URL로 접속해야 한다면 GitHub Pages, Netlify, Vercel 같은 정적 호스팅에 `index.html`을 올리면 됩니다.
