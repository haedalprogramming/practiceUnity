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
| **1. 환경 구축 & GitHub 세팅**    | • [Unity Hub 설치, LTS 버전 선택](./1-1.UnityHub설치LTS버전선택.md)<br>• [에디터 UI 투어(Scene, Game, Inspector)](./1-2.Unity에디터UI투어–SceneGameInspector창이해하기.md)<br>•[Unity 에디터 창 기능별 역할 설명](./1-2-1.Unity에디터창기능별역할설명.md)<br>• [Git & GitHub 기본 흐름](./1-3.Git&GitHub기본흐름.md)  | • [.gitignore(Unity) 설정, Remote 연결](./1-4.gitignore(Unity)설정Remote연결.md)<br>• [Notion 스페이스·Velog 블로그 개설](./1-5.Notion스페이스·Velog블로그개설.md)<br>• [Notion 개별 포트폴리오 작성 가이드](./1-5-1.Notion으로개별포트폴리오작성하기.md)  | • [개인 레포 + Org 팀 Repo 생성, README/Issue Template 작성](./1-6.개인레포+Org팀Repo생성READMEIssueTemplate작성.md)<br>• [Issue 라벨 및 Project Board 실습](./1-7.Issue라벨및ProjectBoard실습.md)        | ✔ Repo·Project 보드 생성<br>✔ Unity Sample Scene 커밋 |
| **2. C# 기초 & 스크립트 작성 ①**    | • [C# 문법(변수, 흐름제어, 클래스) 리뷰](./2-1.C샵문법리뷰.md)<br>• [조건문·반복문 구조별 실습 예시](./2-1-1.조건문·반복문구조별실습예시.md)<br>• [C# 메서드·클래스 설계 연습](./2-1-2.C샵메서드·클래스설계연습.md) | • [MonoBehaviour 생명주기(Start, Update)](./2-2.MonoBehaviour생명주기.md)<br>• [Input System 설정](./2-3.InputSystem설정하기.md)<br>• [사용자 입력 처리 다양화](./2-3-1.사용자입력처리다양화.md)        | • [Mini Task: “PlayerController.cs” → 이동·점프 구현](./2-4.MiniTask:`PlayerController.cs`–이동과점프구현.md)<br>• [점프 쿨타임/속도 제한 구현](./2-5.점프쿨타임속도제한구현.md)         | ✔ 캐릭터 이동 기능 PR + 코드리뷰                           |
| **3. 2D 게임 시스템**            | • [Sprite·Tilemap·Collider 2D](./3-1.SpriteTilemapCollider2D.md)<br>• [타일맵으로 레벨 구성하는 실습](./3-1-1.타일맵으로레벨구성하는실습.md)                                                | • [Rigidbody2D·Physics Materials·레이어](./3-2.Rigidbody2D·PhysicsMaterials·레이어.md)<br>• [Physics Material 설정 실험](./3-2-1.PhysicsMaterial설정실험.md)                             | • [Parallax Background, UI (Health, Score)](./3-3.ParallaxBackground&UI구현(HealthScore).md)<br>• [2D 미션 맵에 UI 반영 실습](./3-4.2D미션맵에UI반영실습.md)             | ✔ 2D Level 1 완성 & Prefab 정리                     |
| **4. 2D 게임 Polish & Build** | • [애니메이션(State Machine)·사운드 추가](4-1.애니메이션(StateMachine)·사운드추가.md)<br>• [Transition/Trigger 실습](4-1-1.TransitionTrigger실습.md)                                              | • [Post-processing(URP), 파티클 이펙트](4-2.Post-processing(URP)·파티클이펙트.md)<br>• [효과 사운드 동기화 처리](4-2-1.효과사운드동기화처리.md)                                | • [WebGL 빌드 → GitHub Pages 배포](4-3.WebGL빌드→GitHubPages배포.md)<br>• [빌드 경량화 설정 연습](4-3-1.빌드경량화설정연습.md)                         | ✔ 2D 횡스크롤 게임<br>✔ Velog Devlog 1편              |
| **5. 3D 기초 & 씬 제작**         | • [3D 좌표계·프리팹·Hierarchy 구성]()                                                                | • [Lights(포인트·스팟), Materials(PBR)]()                                | • [Mini Task: “3D Playground” 씬 + Basic FPS Controller]() | ✔ 3D 씬 스크린샷 PR                                  |
| **6. 3D 게임플레이 & UI**        | • [Physics (캐릭터 컨트롤러 vs Rigidbody)]()                                                        | • [카메라 시스템(Cinemachine), 트리거·이벤트]()                                 | • [UI Toolkit / Canvas, 게임 루프 완성]()                       | ✔ 3D 미션 2개 클리어 가능                               |
| **7. 성능 최적화 & 포트폴리오 정리**    | • [프로파일러, 메모리·Draw Call 관리]()                                                                | • [Addressables·빌드 플랫폼(Android/PC)]()                               | • [Notion Case Study · Velog 회고 작성]()                     | ✔ 빌드 사이즈 < 100 MB<br>✔ 포트폴리오 초안                 |
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
