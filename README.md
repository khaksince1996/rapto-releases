# KhakiCollar — 배포

KhakiCollar 데스크탑 앱(macOS) 배포용 저장소입니다.
최신 버전은 **[Releases](https://github.com/khaksince1996/rapto-releases/releases)** 에서 내려받으세요.

## 어떤 파일을 받나요?

| 내 맥 | 받을 파일 |
|---|---|
| 애플 실리콘 (M1·M2·M3·M4) | `KhakiCollar-*-arm64.dmg` |
| 인텔 맥 | `KhakiCollar-*.dmg` |

> 내 맥 종류: 화면 왼쪽 위 사과 → "이 Mac에 관하여"에서 "칩"이 Apple이면 arm64.

## 설치 시 "손상되어 열 수 없음" 경고가 뜨면

아직 Apple 공증(notarization) 전 빌드라 macOS가 처음 실행을 막습니다. 아래 중 하나로 해제하세요.

- 앱을 응용 프로그램에 옮긴 뒤 **우클릭 → 열기** (더블클릭 말고)
- 또는 터미널에서:
  ```
  xattr -dr com.apple.quarantine ~/Downloads/KhakiCollar-*.dmg
  ```
