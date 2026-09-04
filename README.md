# 이하늘

**Unity Client Developer**  
2026 신입 게임 클라이언트 프로그래머 · 서울 / 경기 · 구직 중

게임 규칙을 코드 구조로 옮기는 일을 좋아합니다.  
데이터·입력·표현을 분리해, 나중에 바꿔도 무너지지 않는 시스템을 만듭니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=notion&logoColor=white)](https://determined-stay-89e.notion.site/Portfolio-3cf9e55d797480f0a9bbf420aacaf935)
[![STOVE](https://img.shields.io/badge/STOVE-출시작_플레이-FF5A00?style=flat-square)](https://store.onstove.com/ko/games/104973)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:skyee46@gmail.com)

---

## Selected Work

### 01 — 여보, 나 왔어

**3D 코믹 스텔스 어드벤처 · 개인 프로젝트 · 2026.05–2026.06**

<img src="./assets/gif/honey-im-home.gif" width="720" alt="사람의 발과 장애물을 피해 이동하는 여보, 나 왔어 플레이 화면">

만취한 아빠 개미가 아내의 메시지를 받으며 심부름을 마치고 집으로 돌아가는 게임입니다. 기획, 프로그래밍, 레벨 디자인을 단독으로 진행해 STOVE에 정식 출시했습니다.

- **게임 흐름** — 스토리·독백·미션 메시지가 하나의 큐에서 이어지는 메신저 기반 미션 시스템 구현
- **입력 설계** — `Player`와 `UI` Action Map을 분리해 컷씬 진입 시 별도 플래그 없이 플레이 입력을 차단
- **플레이어 액션** — 달리기·구르기·점프·앉기를 조합하는 회피 플레이 구현
- **문제 해결** — 작은 캐릭터가 메시 콜라이더를 관통하는 문제를 콜라이더 단순화, 물리 주기 조정, `Continuous` 충돌 감지 적용으로 개선

`Unity` `C#` `3D` `New Input System` `NavMesh`

[GitHub ↗](https://github.com/Devel-Rocket-ClassRoom/minigame-project-smflsmfqh) · [Play on STOVE ↗](https://store.onstove.com/ko/games/104973) · [Case Study ↗](https://determined-stay-89e.notion.site/Portfolio-3cf9e55d797480f0a9bbf420aacaf935)

### 02 — Tower And Dragon

**2D 아이소메트릭 디펜스 빌더 · 기업협약 팀 프로젝트 · 2026.07–2026.09**

<img src="./assets/gif/tower-and-dragon.gif" width="720" alt="그리드 위에 다중 셀 건물을 배치하는 Tower And Dragon 플레이 화면">

그리드·청크 기반 건물 배치와 영역 점령으로 네 개의 포탈을 봉인하는 디펜스 빌더입니다. 4인 팀에서 그리드, 건물 배치, 점령, 자원 노드, 새끼용, 튜토리얼과 전투 이펙트를 담당했습니다.

- **그리드 구조** — `GridMap`·`GridCell`·`Chunk` 데이터 구조와 배치·제거·재배치·회전 흐름 설계
- **건물 배치** — 건물의 점유 형태를 비트마스크로 정의한 Footprint 기반 다중 셀 판정 구현
- **점령 시스템** — 자원·인구 비용, 점령 후보 하이라이트, 경계선 렌더링과 불가 영역 가드 구현
- **성능 개선** — 매 프레임 계산하던 점령 하이라이트를 셀 상태가 변할 때만 갱신하는 이벤트 기반 구조로 전환
- **기여 범위** — 저장소 전체 1,265개 커밋 중 285개 커밋 참여

`Unity` `C#` `URP` `2D Isometric` `ScriptableObject`

[GitHub ↗](https://github.com/JoKangHyeon/TowerAndDragon) · [Case Study ↗](https://determined-stay-89e.notion.site/Portfolio-3cf9e55d797480f0a9bbf420aacaf935)

---

## Other Work

### 미니 메트로

노선을 그려 승객을 실어 나르는 미니멀 지하철 경영 시뮬레이션 클론입니다. 3인 팀에서 역·승객·자산 시스템과 씬·UI 흐름을 담당했습니다.

- 승객 스폰 책임을 중앙 매니저에서 각 역으로 옮겨 역별 동작을 독립적으로 관리
- 노선 삭제 시 사용 자산을 반환하도록 수정해 보유 수량과 실제 사용량의 정합성 확보

`Unity` `C#` · [GitHub ↗](https://github.com/Devel-Rocket-ClassRoom/toy-project-0-team-7)

---

## Stack

**Engine / Language** · Unity 6.3 LTS, C#  
**Unity** · URP, New Input System, NavMesh, Tilemap, ScriptableObject  
**Workflow** · Git, GitHub, Notion

프로젝트별 플레이 화면, 클래스 구조와 상세 트러블슈팅은 [포트폴리오](https://determined-stay-89e.notion.site/Portfolio-3cf9e55d797480f0a9bbf420aacaf935)에 정리했습니다.
