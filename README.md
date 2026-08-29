# FallGuys

Unity로 제작한 Fall Guys 스타일 멀티플레이 파티 게임 프로젝트입니다.

## 개발 환경

- Unity 2022.3.58f1
- URP (Universal Render Pipeline)
- TCP 기반 자체 네트워킹 (Protobuf 직렬화)

## 주요 기능

- 실시간 멀티플레이 (TCP 서버-클라이언트 통신)
- 레이스 / 탈락(elimination) / 관전(spectator) 시스템
- Cinemachine 기반 카메라 연출
- DOTween을 활용한 UI/오브젝트 애니메이션

## 시작하기

1. Unity Hub에서 `2022.3.58f1` 버전으로 프로젝트를 엽니다.
2. `Packages/manifest.json`에 정의된 패키지가 자동으로 복원됩니다.
3. `Assets` 폴더의 메인 씬을 열어 실행합니다.

## 프로젝트 구조

```
Assets/
  Scripts/
    GoTCP/        # TCP 네트워크 통신 모듈
  Resources/      # 폰트, 캐릭터, 설정 리소스
  Settings/       # URP 렌더링 설정
ProjectSettings/  # Unity 프로젝트 설정
Packages/         # 패키지 의존성 목록
```
