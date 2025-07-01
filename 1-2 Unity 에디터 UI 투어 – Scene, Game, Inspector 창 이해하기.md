# 🖥️ Unity 에디터 UI 투어 – Scene, Game, Inspector 창 이해하기

Unity 에디터는 다양한 창(Panels)으로 구성되어 있으며, 각 창의 기능을 이해하면 프로젝트 탐색과 개발 속도가 크게 향상됩니다.

---

## 🧭 1. Scene 뷰 – **게임 월드를 디자인하는 공간**

Scene 뷰는 Unity에서 게임 오브젝트를 **배치·편집·설계**하는 작업 공간입니다.

- 3D/2D 객체를 직접 선택하고 이동, 회전, 스케일 등을 조절 가능
- **카메라 시점과 다르게 자유롭게 탐색**할 수 있음
- 게임오브젝트의 위치(Vector3), 구조(Hierarchy) 등을 시각적으로 이해할 수 있음

🔧 단축키:
- `W`: 이동
- `E`: 회전
- `R`: 크기 조절
- `F`: 선택한 오브젝트로 포커스

<!-- 이미지: Scene 뷰 전체 인터페이스 -->
<!-- ![Scene View](images/unity_scene_view.png) -->

---

## 🎮 2. Game 뷰 – **플레이어가 실제로 보는 화면**

Game 뷰는 **카메라를 통해 보이는 시점**으로, 게임을 실행했을 때 플레이어가 보게 될 최종 화면입니다.

- Scene 뷰에서 설정한 오브젝트들이 실제로 어떻게 보일지 확인
- **Play 버튼(▶️)** 을 누르면 Game 뷰에서 실시간 테스트 가능
- **해상도**나 **비율**도 설정 가능 (e.g. 16:9, 1080p, Free Aspect 등)

🔧 주의: Play 모드에서 변경한 내용은 저장되지 않음!

<!-- 이미지: Game 뷰 예시 화면 -->
<!-- ![Game View](images/unity_game_view.png) -->

---

## 🧩 3. Inspector – **선택한 오브젝트의 세부 설정창**

Inspector는 선택한 오브젝트의 **속성, 컴포넌트, 스크립트 등 세부 정보를 수정**하는 창입니다.

- Transform(위치, 회전, 크기) 기본값
- Rigidbody, Collider, AudioSource 등 다양한 컴포넌트 추가/제거
- C# 스크립트를 붙여서 동작 설정

> 🎯 핵심: Unity에서 오브젝트 동작을 제어하려면 Inspector에서 컴포넌트를 조절하는 게 기본!

<!-- 이미지: Inspector 창 예시 -->
<!-- ![Inspector](images/unity_inspector_panel.png) -->

---

## ✨ 기타 주요 창 소개 (요약)

| 창 이름 | 역할 |
|--------|------|
| **Hierarchy** | 씬 안에 있는 모든 오브젝트 리스트 |
| **Project** | 프로젝트 내 에셋 폴더 구조 |
| **Console** | 로그, 에러, 디버깅 메시지 확인 |
| **Toolbar** | 실행(▶️), 일시정지, 조작 도구 선택 |

---

## ✅ 실습 미션

✔ Unity Sample Project를 실행한 뒤, 다음을 해보세요:

- Scene 뷰에서 `Main Camera`와 `Directional Light` 선택 후 이동시켜 보기
- Game 뷰에서 해상도 설정 변경해 보기
- Cube를 생성하고 Inspector에서 색상(Material) 바꿔 보기

---

## 🧠 정리

| 항목 | 설명 |
|------|------|
| **Scene** | 개발자용 디자인 공간 |
| **Game** | 플레이어 시점의 결과 화면 |
| **Inspector** | 오브젝트 속성 설정 창 |

---

## 📎 참고 링크

- [Unity Editor 기본 구조 – 공식 문서](https://docs.unity3d.com/Manual/unity-editor.html)
- [Unity Hotkeys (단축키) 공식 리스트](https://docs.unity3d.com/Manual/UnityHotkeys.html)
