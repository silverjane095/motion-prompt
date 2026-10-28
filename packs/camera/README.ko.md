<!-- 이 파일은 tools/build.mjs 가 meta.json 으로 만든 것입니다. 고칠 때는 이 파일이 아니라 meta.json 을 편집하세요. -->

# 카메라 워크와 전환

24 개 이름 · #025–048 · 팩 `camera` · 언어: [English](README.md) / [日本語](README.ja.md) / [繁體中文](README.zh-Hant.md)

이름을 찾았으면 그대로 AI에게 말하면 됩니다. "몇 초 동안", "얼마나 세게", "무엇이 움직이는지"를 덧붙이면 생각한 모습에 더 가까워집니다.

![카메라 워크와 전환 — 견본](../../assets/preview-camera.gif)

## 카메라 움직임

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#025](https://showheyohtaki.github.io/motion-prompt/#025) | **팬** | Pan | 카메라를 좌우로 회전 | 카메라 위치는 고정한 채, 스카이라인을 왼쪽에서 오른쪽으로 5초에 걸쳐 천천히 팬해 주세요. |
| [#026](https://showheyohtaki.github.io/motion-prompt/#026) | **틸트** | Tilt | 카메라를 위아래로 회전 | 인물의 발끝에서 탑 꼭대기까지 천천히 틸트 업해 주세요. |
| [#027](https://showheyohtaki.github.io/motion-prompt/#027) | **돌리 인** | Dolly in | 카메라를 피사체 쪽으로 이동 | 그녀의 얼굴 쪽으로 천천히 돌리 인해 주세요. 줌이 아니라 카메라 자체를 움직여 주세요. |
| [#028](https://showheyohtaki.github.io/motion-prompt/#028) | **줌 인** | Zoom in | 렌즈로 확대(카메라 위치는 그대로) | 카메라는 움직이지 말고, 창가에 있는 인물에게 3초에 걸쳐 줌 인해 주세요. |
| [#029](https://showheyohtaki.github.io/motion-prompt/#029) | **트래킹 숏** | Tracking shot | 피사체와 나란히 이동 | 걷는 인물을 옆에서 같은 속도로 따라가며 트래킹 숏으로 찍어 주세요. |
| [#030](https://showheyohtaki.github.io/motion-prompt/#030) | **오빗** | Orbit (Arc shot) | 피사체 주위를 돌며 촬영 | 서 있는 인물을 화면 중앙에 둔 채, 인물 주위를 반 바퀴 오빗해 주세요. |
| [#031](https://showheyohtaki.github.io/motion-prompt/#031) | **크레인 업** | Crane up | 카메라를 위로 들어 올림 | 눈높이에서 시작해 마을 전체가 보일 때까지 크레인 업해 주세요. |
| [#032](https://showheyohtaki.github.io/motion-prompt/#032) | **돌리 줌** | Dolly zoom (Vertigo) | 피사체는 그대로, 배경만 일그러짐 | 그가 무언가를 깨닫는 순간 얼굴에 돌리 줌을 걸어 주세요. 인물 크기는 그대로 두고 배경만 멀어지게 해 주세요. |

## 촬영 방식·시간 연출

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#033](https://showheyohtaki.github.io/motion-prompt/#033) | **랙 포커스** | Rack focus | 앞과 뒤 사이에서 초점을 옮김 | 앞쪽의 컵에서 뒤에 있는 인물로 1초 동안 랙 포커스해 주세요. |
| [#034](https://showheyohtaki.github.io/motion-prompt/#034) | **핸드헬드** | Handheld | 손으로 든 것처럼 살짝 흔들림 | 걷는 인물 뒤를 따라가는 핸드헬드 숏으로 찍되, 흔들림은 약하게 해 주세요. |
| [#035](https://showheyohtaki.github.io/motion-prompt/#035) | **FPV 드론 숏** | FPV drone shot | 빠르고 몰입감 있게 날아서 통과 | FPV 드론 숏으로 나무 사이를 누비다가 강 위로 빠져나가 주세요. |
| [#036](https://showheyohtaki.github.io/motion-prompt/#036) | **더치 앵글** | Dutch angle | 화면을 비스듬히 기울임 | 불안한 장면이니 약 15도 정도의 더치 앵글을 써 주세요. |
| [#037](https://showheyohtaki.github.io/motion-prompt/#037) | **슬로 모션** | Slow motion | 동작을 느리게 재생 | 물보라가 튀는 순간을 슬로 모션으로 보여 주세요. |
| [#038](https://showheyohtaki.github.io/motion-prompt/#038) | **스피드 램프** | Speed ramp | 한 숏 안에서 속도를 바꿈 | 스피드 램프로, 보통 속도로 가다가 점프 정점에서 느려지고 다시 보통 속도로 돌아오게 해 주세요. |
| [#039](https://showheyohtaki.github.io/motion-prompt/#039) | **타임랩스** | Time-lapse | 몇 시간을 몇 초로 압축 | 해 질 녘부터 밤까지 도시에 불이 하나둘 켜지는 모습을 타임랩스로 보여 주세요. |
| [#040](https://showheyohtaki.github.io/motion-prompt/#040) | **프리즈 프레임** | Freeze frame | 동작을 잠깐 멈춤 | 그녀가 돌아보는 순간 프리즈 프레임으로 1초 동안 멈추고, 이름을 띄워 주세요. |

## 전환(트랜지션)

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#041](https://showheyohtaki.github.io/motion-prompt/#041) | **점프 컷** | Jump cut | 같은 구도에서 시간을 건너뜀 | 같은 구도의 점프 컷으로 이어 붙여 준비 과정을 빠르게 보여 주세요. |
| [#042](https://showheyohtaki.github.io/motion-prompt/#042) | **매치 컷** | Match cut | 모양이나 동작을 맞춰 장면을 전환 | 둥근 커피 잔에서 같은 위치에 있는 보름달로 매치 컷해 주세요. |
| [#043](https://showheyohtaki.github.io/motion-prompt/#043) | **휩 팬** | Whip pan | 빠르게 휘두른 팬의 블러로 다음 숏에 연결 | 오른쪽으로 휩 팬해서 다음 장소로 넘어가 주세요. |
| [#044](https://showheyohtaki.github.io/motion-prompt/#044) | **크로스 디졸브** | Cross dissolve | 앞 숏을 다음 숏에 겹쳐 서서히 바꿈 | 아침의 방에서 밤의 같은 방으로 1초 동안 크로스 디졸브해 주세요. |
| [#045](https://showheyohtaki.github.io/motion-prompt/#045) | **와이프** | Wipe | 움직이는 경계선이 화면을 바꿈 | 왼쪽에서 오른쪽으로 와이프해서 다음 장면으로 넘어가 주세요. |
| [#046](https://showheyohtaki.github.io/motion-prompt/#046) | **스매시 컷** | Smash cut | 대비되는 장면으로 갑자기 전환 | 조용한 침실에서 시끄러운 교차로로 스매시 컷해 주세요. |
| [#047](https://showheyohtaki.github.io/motion-prompt/#047) | **J컷** | J-cut | 다음 장면의 소리가 먼저 시작됨 | J컷으로, 바다 장면으로 넘어가기 전에 다음 장면의 파도 소리가 먼저 들리게 해 주세요. |
| [#048](https://showheyohtaki.github.io/motion-prompt/#048) | **L컷** | L-cut | 앞 장면의 소리가 이어짐 | L컷으로, 듣는 사람의 얼굴로 넘어간 뒤에도 그녀의 목소리가 계속 이어지게 해 주세요. |

번호를 누르면 갤러리의 움직이는 견본이 열립니다. 이름 하나의 시간·이징 값·참고 코드: `api/v1/en/e/<id>.txt` ([#025](../../api/v1/en/e/025.txt)).

[전체 팩](../README.md)
