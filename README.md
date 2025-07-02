# practiceUnity
유니티로 배우는 게임엔진 기초

## 2025 여름 경북소프트웨어마이스터고 기술교육

**교과목 2 (유니티 게임엔진 기초)** ― 총 8 일, 하루 9 시간 (09:00 – 18:00 / 점심 12:00 – 13:00)

> **학습 목표**
>
> 1. Unity Hub ‧ 에디터 구조와 워크플로를 이해하고 능숙하게 탐색한다.
> 2. C# 스크립팅(클래스 · 메쏘드 · 이벤트 · 코루틴)을 사용해 **2D 플랫포머 → 3D 미니게임**을 완성한다.
> 3. GitHub Flow(Branch → PR → Review → Merge)로 팀 협업하며, Issue·Project 보드로 작업을 추적한다.
> 4. Notion·Velog를 활용해 개발 일지와 포트폴리오를 체계적으로 관리한다.
> 5. 최종 Demo Day에서 **실행 파일(또는 WebGL) + 개발 스토리**를 발표한다.

---

## 목차 & 세부 커리큘럼

| Day                         | 오전 세션 (09 – 12)                                                                          | 오후 세션 (13 – 15:30)                                              | 심화/실습 (15:30 – 18)                                    | 일일 산출물 · 점검                                     |
| --------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------- | ----------------------------------------------- |
| **1. 환경 구축 & GitHub 세팅**    | • [Unity Hub 설치, LTS 버전 선택](https://github.com/isp829/practiceUnity/blob/patch-2/1-1.Unity%20Hub%20%EC%84%A4%EC%B9%98%2C%20LTS%20%EB%B2%84%EC%A0%84%20%EC%84%A0%ED%83%9D.md)<br>• [에디터 UI 투어(Scene, Game, Inspector)](https://github.com/isp829/practiceUnity/blob/patch-2/1-2%20Unity%20%EC%97%90%EB%94%94%ED%84%B0%20UI%20%ED%88%AC%EC%96%B4%20%E2%80%93%20Scene%2C%20Game%2C%20Inspector%20%EC%B0%BD%20%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0.md)<br>• [Git & GitHub 기본 흐름](https://github.com/isp829/practiceUnity/blob/patch-2/1-3.%20Git%20%26%20GitHub%20%EA%B8%B0%EB%B3%B8%20%ED%9D%90%EB%A6%84.md)<br>•[Unity 에디터 창 기능별 역할 설명](https://github.com/isp829/practiceUnity/blob/patch-2/1-4.5.%20Unity%20%EC%97%90%EB%94%94%ED%84%B0%20%EC%B0%BD%20%EA%B8%B0%EB%8A%A5%EB%B3%84%20%EC%97%AD%ED%95%A0%20%EC%84%A4%EB%AA%85.md)  | • [.gitignore(Unity) 설정, Remote 연결](https://github.com/isp829/practiceUnity/blob/patch-2/1-4.gitignore(Unity)%20%EC%84%A4%EC%A0%95%2C%20Remote%20%EC%97%B0%EA%B2%B0.md)<br>• [Notion 스페이스·Velog 블로그 개설](https://github.com/isp829/practiceUnity/blob/patch-2/1-5.%20Notion%20%EC%8A%A4%ED%8E%98%EC%9D%B4%EC%8A%A4%C2%B7Velog%20%EB%B8%94%EB%A1%9C%EA%B7%B8%20%EA%B0%9C%EC%84%A4.md)<br>• Notion 협업 템플릿 구조 설명  | • [개인 레포 + Org 팀 Repo 생성, README/Issue Template 작성](https://github.com/isp829/practiceUnity/blob/patch-2/1-6.%20%EA%B0%9C%EC%9D%B8%20%EB%A0%88%ED%8F%AC%20%2B%20Org%20%ED%8C%80%20Repo%20%EC%83%9D%EC%84%B1%2C%20README%2CIssue%20Template%20%EC%9E%91%EC%84%B1.md)<br>• Issue 라벨 및 Project Board 실습        | ✔ Repo·Project 보드 생성<br>✔ Unity Sample Scene 커밋 |
| **2. C# 기초 & 스크립트 작성 ①**    | • [C# 문법(변수, 흐름제어, 클래스) 리뷰](https://github.com/isp829/practiceUnity/blob/patch-2/2-1.%20C%23%20%EB%AC%B8%EB%B2%95%20%EB%A6%AC%EB%B7%B0.md)<br>• 조건문·반복문 구조별 실습 예시<br>• C# 메서드·클래스 설계 연습 | • [MonoBehaviour 생명주기(Start, Update)](https://github.com/isp829/practiceUnity/blob/patch-2/2-2.%20MonoBehaviour%20%EC%83%9D%EB%AA%85%EC%A3%BC%EA%B8%B0.md)<br>• [Input System 설정](https://github.com/isp829/practiceUnity/blob/patch-2/2-3.%20Input%20System%20%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0.md)<br>• 사용자 입력 처리 다양화        | • [Mini Task: “PlayerController.cs” → 이동·점프 구현](https://github.com/isp829/practiceUnity/blob/patch-2/2-4.%20Mini%20Task%3A%20%60PlayerController.cs%60%20%E2%80%93%20%EC%9D%B4%EB%8F%99%EA%B3%BC%20%EC%A0%90%ED%94%84%20%EA%B5%AC%ED%98%84.md)<br>• 점프 쿨타임/속도 제한 구현         | ✔ 캐릭터 이동 기능 PR + 코드리뷰                           |
| **3. 2D 게임 시스템**            | • [Sprite·Tilemap·Collider 2D](https://github.com/isp829/practiceUnity/blob/patch-2/3-1.%20Sprite%20%C2%B7%20Tilemap%20%C2%B7%20Collider%202D.md)<br>• 타일맵으로 레벨 구성하는 실습                                                | • [Rigidbody2D·Physics Materials·레이어](https://github.com/isp829/practiceUnity/blob/patch-2/3-2.Rigidbody2D%20%C2%B7%20Physics%20Materials%20%C2%B7%20%EB%A0%88%EC%9D%B4%EC%96%B4.md)<br>• Physics Material 설정 실험                             | • [Parallax Background, UI (Health, Score)](https://github.com/isp829/practiceUnity/blob/patch-2/3-3.Parallax%20Background%20%26%20UI%20%EA%B5%AC%ED%98%84%20(Health%2C%20Score).md)<br>• 2D 미션 맵에 UI 반영 실습             | ✔ 2D Level 1 완성 & Prefab 정리                     |
| **4. 2D 게임 Polish & Build** | • [애니메이션(State Machine)·사운드 추가](https://github.com/isp829/practiceUnity/blob/patch-2/4-1.%20%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98(State%20Machine)%20%C2%B7%20%EC%82%AC%EC%9A%B4%EB%93%9C%20%EC%B6%94%EA%B0%80.md)<br>• Transition/Trigger 실습                                              | • [Post-processing(URP), 파티클 이펙트](https://github.com/isp829/practiceUnity/blob/patch-2/4-2.%20Post-processing(URP)%20%C2%B7%20%ED%8C%8C%ED%8B%B0%ED%81%B4%20%EC%9D%B4%ED%8E%99%ED%8A%B8.md)<br>• 효과 사운드 동기화 처리                                | • [WebGL 빌드 → GitHub Pages 배포](https://github.com/isp829/practiceUnity/blob/patch-2/4-3.%20WebGL%20%EB%B9%8C%EB%93%9C%20%E2%86%92%20GitHub%20Pages%20%EB%B0%B0%ED%8F%AC.md)<br>• 빌드 경량화 설정 연습                         | ✔ 2D WebGL 링크<br>✔ Velog Devlog 1편              |
| **5. 3D 기초 & 씬 제작**         | • [3D 좌표계·프리팹·Hierarchy 구성](https://github.com/isp829/practiceUnity/blob/patch-2/5-1.%203D%20%EC%A2%8C%ED%91%9C%EA%B3%84%C2%B7%ED%94%84%EB%A6%AC%ED%8C%B9%C2%B7Hierarchy%20%EA%B5%AC%EC%84%B1.md)                                                                | • [Lights(포인트·스팟), Materials(PBR)](https://github.com/isp829/practiceUnity/blob/patch-2/5-2.%20Lights(%ED%8F%AC%EC%9D%B8%ED%8A%B8%C2%B7%EC%8A%A4%ED%8C%9F)%2C%20Materials(PBR).md)                                | • [Mini Task: “3D Playground” 씬 + Basic FPS Controller](https://github.com/isp829/practiceUnity/blob/patch-2/5-3.%20Mini%20Task%3A%20%E2%80%9C3D%20Playground%E2%80%9D%20%EC%94%AC%20%2B%20Basic%20FPS%20Controller.md) | ✔ 3D 씬 스크린샷 PR                                  |
| **6. 3D 게임플레이 & UI**        | • [Physics (캐릭터 컨트롤러 vs Rigidbody)](https://github.com/isp829/practiceUnity/blob/patch-2/6-1.%20Physics%20(%EC%BA%90%EB%A6%AD%ED%84%B0%20%EC%BB%A8%ED%8A%B8%EB%A1%A4%EB%9F%AC%20vs%20Rigidbody).md)                                                        | • [카메라 시스템(Cinemachine), 트리거·이벤트](https://github.com/isp829/practiceUnity/blob/patch-2/6-2.%20%EC%B9%B4%EB%A9%94%EB%9D%BC%20%EC%8B%9C%EC%8A%A4%ED%85%9C(Cinemachine),%20%ED%8A%B8%EB%A6%AC%EA%B1%B0%C2%B7%EC%9D%B4%EB%B2%A4%ED%8A%B8.md)                                 | • [UI Toolkit / Canvas, 게임 루프 완성](https://github.com/isp829/practiceUnity/blob/patch-2/6-3.%20UI%20Toolkit%20%2CCanvas%2C%20%EA%B2%8C%EC%9E%84%20%EB%A3%A8%ED%94%84%20%EC%99%84%EC%84%B1.md)                       | ✔ 3D 미션 2개 클리어 가능                               |
| **7. 성능 최적화 & 포트폴리오 정리**    | • [프로파일러, 메모리·Draw Call 관리](https://github.com/isp829/practiceUnity/blob/patch-2/7-1.%20%ED%94%84%EB%A1%9C%ED%8C%8C%EC%9D%BC%EB%9F%AC,%20%EB%A9%94%EB%AA%A8%EB%A6%AC%C2%B7Draw%20Call%20%EA%B4%80%EB%A6%AC.md)                                                                | • [Addressables·빌드 플랫폼(Android/PC)](https://github.com/isp829/practiceUnity/blob/patch-2/7-2.%20Addressables%C2%B7%EB%B9%8C%EB%93%9C%20%ED%94%8C%EB%9E%AB%ED%8F%BC(Android%2CPC).md)                               | • [Notion Case Study · Velog 회고 작성](https://github.com/isp829/practiceUnity/blob/patch-2/7-3.%20Notion%20Case%20Study%20%C2%B7%20Velog%20%ED%9A%8C%EA%B3%A0%20%EC%9E%91%EC%84%B1.md)                     | ✔ 빌드 사이즈 < 100 MB<br>✔ 포트폴리오 초안                 |
| **8. Demo Day & 회고**        | • 발표 흐름(기획→기술→결과), 리허설                                                                   | • 팀별 시연 & Q·A (15 min/team)                                     | • 360° 피드백 · 레트로스펙티브                                  | ✔ 최종 Tag v1.0<br>✔ 수료증 & 포트폴리오 완료               |

---

### 평가 방법 (총 100 점)

| 항목                  | 비율   | 평가지표                        |
| ------------------- | ---- | --------------------------- |
| 최종 게임 결과물(2D + 3D)  | 40 점 | 플레이 완성도, 아트·사운드 통일감, 빌드 안정성 |
| 코드 품질 & GitHub 협업   | 20 점 | 커밋 메시지, PR 리뷰, Branch 전략    |
| 기술 구현 & 최적화         | 15 점 | FPS ≥ 60, 프로파일링 개선, 메모리 관리  |
| 포트폴리오(Notion·Velog) | 15 점 | 과정 기록, 아카이빙 품질, 가독성         |
| 발표 & 커뮤니케이션         | 10 점 | 구조적 스토리텔링, 질의응답 대응          |

---

### 운영 포인트

* **Daily Stand-up (09:00) / Retrospective (17:45)**: GitHub Issue 상태 업데이트
* **Mentor Clinic** (매일 14:30 – 15:30): 코드·아트·버그 헬프
* **Checkpoint Quiz** (2 · 4 · 6일 오전): Kahoot! 10문항으로 핵심 개념 리마인드
* **리소스 팩**: 무료 애셋·사운드·폰트 모음, .gitignore·Unity URP 템플릿, 기본 Cinemachine 세팅 파일

---

본 커리큘럼은 **“기획 → 개발 → 빌드 → 배포”** 전 과정을 8 일 안에 체험하도록 설계했습니다.
