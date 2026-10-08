# Winter Stove — 정창우 작성 코드

> Meta Quest VR 생활 · 미니게임 · 팀 3인 · 2026.06  
> Unity 6 · C# · XR Interaction Toolkit · Final IK  
> 내 커밋 기간: 2026-06-09 – 2026-06-19

Unity 프로젝트 전체가 아니라, **정창우(jcw3421)가 실제로 커밋해서 만들거나 수정한 코드 파일만** 모아 둔 레포입니다.
아트 · 사운드 · 씬 · 프리팹 · 에셋스토어 패키지 · 서드파티 코드는 모두 빠져 있어서 이 레포만으로는 빌드되지 않습니다.

## 추출 기준

- 원본: 디벨로켓 부트캠프 조직(`Devel-Rocket-ClassRoom`)의 프로젝트 레포 — 모든 브랜치의 커밋을 조사
- 커밋 작성자가 `jcw3421 <gatecrow@naver.com>` 또는 `정창우 <jcw3421@gmail.com>` 인 커밋에서 추가 · 수정된 코드 파일 (`.cs` `.shader` `.hlsl` 등)
- 직접 만든 파일은 전부 포함, 남이 만든 파일은 현재 버전에 내가 쓴 줄이 5줄 이상 남아 있을 때만 포함
- 파일 내용은 기본 브랜치의 최신 버전 (기본 브랜치에 없으면 해당 파일이 있는 가장 최근 커밋)
- `내 줄 / 전체` 는 `git blame -w` 기준으로 지금 남아 있는 줄 중 내가 쓴 줄 수. 팀 프로젝트라 수정한 파일에는 팀원이 쓴 코드도 함께 들어 있습니다.

## 요약

| 내 커밋 | 포함 파일 | 직접 만든 파일 | 수정한 파일 | 남아 있는 내 코드 줄 |
|---|---|---|---|---|
| 31 | 14 | 14 | 0 | 744 |

## 직접 만든 파일

| 파일 | 내 줄 / 전체 | 비율 |
|---|---|---|
| [`Assets/_Prefabs/JCW_Prefabs/Avatar/VRHandAnimator.cs`](Assets/_Prefabs/JCW_Prefabs/Avatar/VRHandAnimator.cs) | 146 / 146 | 100% |
| [`Assets/_Scripts/JCW_Scripts/Avatar/AvatarManager.cs`](Assets/_Scripts/JCW_Scripts/Avatar/AvatarManager.cs) | 67 / 67 | 100% |
| [`Assets/_Scripts/JCW_Scripts/Avatar/AvatarSelector.cs`](Assets/_Scripts/JCW_Scripts/Avatar/AvatarSelector.cs) | 13 / 16 | 81% |
| [`Assets/_Scripts/JCW_Scripts/FireplaceDoor/FirewoodDispenser.cs`](Assets/_Scripts/JCW_Scripts/FireplaceDoor/FirewoodDispenser.cs) | 33 / 33 | 100% |
| [`Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceDoor.cs`](Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceDoor.cs) | 52 / 52 | 100% |
| [`Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceFirewood.cs`](Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceFirewood.cs) | 35 / 37 | 95% |
| [`Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceManager.cs`](Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceManager.cs) | 95 / 95 | 100% |
| [`Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceSocket.cs`](Assets/_Scripts/JCW_Scripts/FireplaceDoor/FurnaceSocket.cs) | 45 / 45 | 100% |
| [`Assets/_Scripts/JCW_Scripts/HandAnimatorController.cs`](Assets/_Scripts/JCW_Scripts/HandAnimatorController.cs) | 28 / 28 | 100% |
| [`Assets/_Scripts/JCW_Scripts/SkyboxRotator.cs`](Assets/_Scripts/JCW_Scripts/SkyboxRotator.cs) | 15 / 19 | 79% |
| [`Assets/_Scripts/JCW_Scripts/VRIKCalibrator.cs`](Assets/_Scripts/JCW_Scripts/VRIKCalibrator.cs) | 107 / 107 | 100% |
| [`Assets/_Scripts/JCW_Scripts/machine/Coin.cs`](Assets/_Scripts/JCW_Scripts/machine/Coin.cs) | 33 / 33 | 100% |
| [`Assets/_Scripts/JCW_Scripts/machine/VendingMachine.cs`](Assets/_Scripts/JCW_Scripts/machine/VendingMachine.cs) | 37 / 38 | 97% |
| [`Assets/_Scripts/JCW_Scripts/machine/VendingMachineSlot.cs`](Assets/_Scripts/JCW_Scripts/machine/VendingMachineSlot.cs) | 38 / 38 | 100% |

## 내 커밋 기록

<details><summary>커밋 31개 펼치기</summary>

| 날짜 | 커밋 | 메시지 |
|---|---|---|
| 2026-06-19 | `dd03c3a` | 라이팅 수정 |
| 2026-06-18 | `dd320e4` | 사격장 좀비슈팅 추가 |
| 2026-06-18 | `2604bc2` | 사격장 활 추가,치사 머리 콜라이더 제거 |
| 2026-06-18 | `555681c` | 사격장 하드모드 타겟,푸시버튼,타이머 위치수정,라이플 연사기능 추가 |
| 2026-06-17 | `717ef54` | feat:사격장 라이플 추가 |
| 2026-06-17 | `5237fc0` | 권총,사격장 bgm연동 |
| 2026-06-17 | `636fd88` | feat:사격장 추가 |
| 2026-06-17 | `41e91ee` | feat:권총추가 |
| 2026-06-16 | `10c84ff` | feat:옷걸이 추가,룸2 조명추가 |
| 2026-06-16 | `3b48a59` | feat: 자판기 인터랙션 시스템 구현 |
| 2026-06-15 | `dcbd3fe` | feat: 난로 인터랙션 시스템 구현 |
| 2026-06-15 | `921857b` | feat: 난로 인터랙션 시스템 구현 |
| 2026-06-14 | `ea7a05f` | feat:플레이어 손가락 추적 구현 |
| 2026-06-12 | `f8a2187` | feat:소품 오브젝트 추가 [리스트있음] |
| 2026-06-12 | `efe9e5b` | fix:메타파일 추가 |
| 2026-06-12 | `1fe0fc0` | feat:집 추가 |
| 2026-06-12 | `c49a391` | feat:하우스 프리팹 xr origin,드레스룸 추가 |
| 2026-06-12 | `90fe6c4` | feat:드레스룸 추가 |
| 2026-06-12 | `c875648` | fix:freetoolkskit.meta |
| 2026-06-12 | `f0e74a7` | feat:소품 오브젝트 추가 [리스트있음] |
| 2026-06-11 | `c8b0453` | fix:플레이어 오프셋 조정 |
| 2026-06-11 | `bc783d4` | fix:파일명 수정,오류 픽스 |
| 2026-06-11 | `8ba987b` | feat:플레이어 오프셋 값 조정 |
| 2026-06-11 | `ddc3d49` | fix:툰셰이더 패키지매니저 설치 |
| 2026-06-10 | `770698e` | feat:플레이어 추가 |
| 2026-06-10 | `a180970` | feat:하늘 회전 추가,핵폭발 이펙트 추가,에셋 폴더이동 |
| 2026-06-10 | `e7d2646` | feat:소품추가,스카이추가,지형추가,글로벌블륨추가 |
| 2026-06-09 | `ef1ed35` | chore:테스트씬 업데이트 |
| 2026-06-09 | `7d2ea5e` | feat:두트윈 에셋 추가,테스트씬 업데이트,난로 도어 테스트 스크립트 |
| 2026-06-09 | `079e7d6` | feat:월드추가 |
| 2026-06-09 | `1e6830c` | feat:소품 오브젝트 추가 |

</details>
