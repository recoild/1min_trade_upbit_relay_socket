
# 🚀 1min Trade Upbit Relay Socket

## 📝 개요
이 프로젝트는 업비트 거래소의 1분 거래 데이터를 소켓을 통해 중계하는 애플리케이션입니다. 🪙 실시간 데이터 중계, Docker 배포, Node.js 기반으로 동작합니다.

## 📁 파일 구조
- `Dockerfile`: 🐳 Docker 이미지를 생성하기 위한 설정 파일
- `package.json`: 📦 프로젝트의 종속성과 스크립트를 정의하는 파일
- `server.js`: 🖥️ 애플리케이션의 메인 서버 파일

## ⚙️ 설치 및 실행

### 🖥️ 요구 사항
- Node.js (최소 v14 이상) 🟢
- Docker (선택 사항) 🐳

### 📥 설치
1. 프로젝트를 클론합니다:
   ```bash
   git clone <repository-url>
   cd 1min_trade_upbit_relay_socket
   ```
2. 종속성을 설치합니다:
   ```bash
   npm install
   ```

### ▶️ 실행
1. 애플리케이션을 로컬에서 실행하려면:
   ```bash
   npm run dev
   # 또는
   npm run start
   ```
2. Docker를 사용하여 실행하려면:
   ```bash
   docker build -t upbit-relay-socket .
   docker run -p 3000:3000 upbit-relay-socket
   ```

## 💡 사용 방법
애플리케이션이 실행되면, 소켓을 통해 실시간으로 1분 거래 데이터를 받을 수 있습니다. 🔌 클라이언트는 소켓 연결을 통해 데이터를 구독할 수 있습니다.

## 🤝 기여
기여를 환영합니다! 🛠️ 버그를 발견하거나 기능 요청이 있다면 이슈를 생성해주세요.

## 📄 라이센스
이 프로젝트는 MIT 라이센스를 따릅니다.
