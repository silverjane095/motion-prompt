<!-- 이 파일은 tools/build.mjs 가 meta.json 으로 만든 것입니다. 고칠 때는 이 파일이 아니라 meta.json 을 편집하세요. -->

# 모션그래픽 연출 2탄

24 개 이름 · #121–144 · 팩 `motion2` · 언어: [English](README.md) / [日本語](README.ja.md)

이름을 찾았으면 그대로 AI에게 말하면 됩니다. "몇 초 동안", "얼마나 세게", "무엇이 움직이는지"를 덧붙이면 생각한 모습에 더 가까워집니다.

![모션그래픽 연출 2탄 — 견본](../../assets/preview-motion2.gif)

## 움직임 기법

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#121](https://showheyohtaki.github.io/motion-prompt/#121) | **안티시페이션** | Anticipation | 앞으로 움직이기 전에 잠깐 뒤로 당김 | 버튼이 오른쪽으로 튀어 나가기 전에 안티시페이션을 넣어 주세요. 0.3초 동안 살짝 뒤로 당겼다가 찌그러진 뒤 출발하게 해 주세요. |
| [#122](https://showheyohtaki.github.io/motion-prompt/#122) | **팔로우 스루** | Follow-through | 몸이 멈춘 뒤에도 일부가 계속 흔들림 | 캐릭터가 멈춘 뒤 머리카락과 깃발에 팔로우 스루를 넣어 주세요. 0.5초 정도 계속 흔들리다가 잦아들게 해 주세요. |
| [#123](https://showheyohtaki.github.io/motion-prompt/#123) | **바운스** | Bounce | 떨어져서 점점 낮게 튀다가 멈춤 | 공을 위에서 떨어뜨려 바운스시켜 주세요. 3번 튀고, 튈 때마다 점점 낮아지게 해 주세요. |
| [#124](https://showheyohtaki.github.io/motion-prompt/#124) | **위글** | Wiggle | 작고 불규칙하게 계속 떨림 | 알림 벨에 은은한 위글을 넣어 주세요. 최대 10° 정도로, 울리는 동안 계속 흔들리게 해 주세요. |
| [#125](https://showheyohtaki.github.io/motion-prompt/#125) | **펄스** | Pulse | 심장 박동처럼 크기가 두근거림 | 하트 아이콘을 펄스로 움직여 주세요. 1.2초마다 10% 정도 커졌다가 돌아오게 해 주세요. |
| [#126](https://showheyohtaki.github.io/motion-prompt/#126) | **모션 패스** | Motion path | 직접 정한 곡선을 따라 움직임 | 종이비행기를 이 곡선을 모션 패스로 삼아 4초 동안 날려 주세요. 진행 방향을 바라보도록 방향도 돌려 주세요. |
| [#127](https://showheyohtaki.github.io/motion-prompt/#127) | **핑퐁 루프** | Ping-pong loop | 앞으로 재생했다가 거꾸로 재생하기를 반복함 | 로딩 점을 핑퐁 루프로 왕복시켜 주세요. 편도 1초예요. |
| [#128](https://showheyohtaki.github.io/motion-prompt/#128) | **스톱모션 스타일** | Stop-motion style | 프레임을 덜어 내 뚝뚝 끊기듯 움직임 | 이 움직임을 스톱모션 스타일로 만들어 주세요. 초당 8프레임이고, 프레임마다 위치를 살짝 흔들어 주세요. |

## 글자·도형 연출

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#129](https://showheyohtaki.github.io/motion-prompt/#129) | **텍스트 스크램블** | Text scramble | 글자가 무작위로 뒤섞이다가 자리 잡음 | 헤드라인을 텍스트 스크램블로 등장시켜 주세요. 1초 정도 무작위 글자가 바뀌다가 왼쪽부터 차례로 자리 잡게 해 주세요. |
| [#130](https://showheyohtaki.github.io/motion-prompt/#130) | **웨이브 텍스트** | Wave text | 글자가 파도처럼 차례로 오르내림 | 로고 글자를 웨이브 텍스트로 움직여 주세요. 글자마다 앞 글자보다 조금씩 늦게, 위아래로 20px 정도요. |
| [#131](https://showheyohtaki.github.io/motion-prompt/#131) | **텍스트 온 패스** | Text on a path | 글자가 선이나 곡선을 따라 흐름 | 태그라인을 텍스트 온 패스로 물결선을 따라 왼쪽에서 오른쪽으로 흐르게 해 주세요. 한 바퀴에 5초예요. |
| [#132](https://showheyohtaki.github.io/motion-prompt/#132) | **가변 폰트 애니메이션** | Variable font animation | 글자 굵기가 부드럽게 바뀜 | 제목에 가변 폰트 애니메이션을 써 주세요. 1초 동안 Thin에서 Black으로(굵기 100에서 900으로) 바꿔 주세요. |
| [#133](https://showheyohtaki.github.io/motion-prompt/#133) | **텍스트 마스크** | Text mask | 글자 모양으로 오려 내 안쪽에 그림을 보여 줌 | OCEAN이라는 단어를 텍스트 마스크로 써서 안에 바다 영상을 보여 주세요. 마지막 1초에는 영상 전체를 드러내 주세요. |
| [#134](https://showheyohtaki.github.io/motion-prompt/#134) | **리피터** | Repeater | 도형을 복제하고 복제본을 돌림 | 리피터로 이 꽃잎을 원형으로 12개 복제해 주세요. 4초에 한 바퀴씩 돌게 해 주세요. |
| [#135](https://showheyohtaki.github.io/motion-prompt/#135) | **만화경 효과** | Kaleidoscope | 거울에 비친 무늬가 대칭으로 퍼져 나감 | 로고 뒤에 만화경 효과를 넣어 주세요. 8방향 거울 대칭으로, 퍼지면서 천천히 돌게 해 주세요. |
| [#136](https://showheyohtaki.github.io/motion-prompt/#136) | **라인 보일** | Line boil | 손으로 그린 선이 프레임마다 일렁임 | 손그림 일러스트에 라인 보일을 넣어 주세요. 초당 10프레임이고, 선은 2~3px만 움직이게 해 주세요. |

## 전환·하이라이트

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#137](https://showheyohtaki.github.io/motion-prompt/#137) | **푸시 트랜지션** | Push transition | 다음 장면이 현재 장면을 밀어냄 | 다음 슬라이드로는 오른쪽에서 들어오는 푸시 트랜지션으로 0.8초 동안 넘어가 주세요. |
| [#138](https://showheyohtaki.github.io/motion-prompt/#138) | **블라인드 트랜지션** | Blinds transition | 가는 띠 사이로 다음 장면이 열림 | 장면 전환을 블라인드 트랜지션으로 해 주세요. 가로 띠 7개가 1초에 걸쳐 열리게 해 주세요. |
| [#139](https://showheyohtaki.github.io/motion-prompt/#139) | **큐브 트랜지션** | Cube transition | 정육면체가 돌듯이 장면이 바뀜 | 제품 사진 전환을 큐브 트랜지션으로 해 주세요. 0.8초 동안 왼쪽으로 90° 돌려 주세요. |
| [#140](https://showheyohtaki.github.io/motion-prompt/#140) | **페이지 컬** | Page curl | 종이처럼 말려 넘어가며 다음 페이지를 보여 줌 | 다음 장으로는 오른쪽 아래 모서리에서 시작하는 페이지 컬로 1.2초 동안 넘어가 주세요. |
| [#141](https://showheyohtaki.github.io/motion-prompt/#141) | **픽셀레이트** | Pixelate | 거친 블록으로 바뀐 뒤 장면이 전환됨 | 픽셀레이트 트랜지션을 써 주세요. 0.6초 동안 모자이크가 점점 거칠어지고, 가장 거친 순간에 장면이 바뀌게 해 주세요. |
| [#142](https://showheyohtaki.github.io/motion-prompt/#142) | **섀터** | Shatter | 유리처럼 깨지고 파편이 날아감 | 제목이 나오기 전에 이전 장면을 섀터로 깨뜨려 주세요. 먼저 금이 가고, 그다음 1초 정도에 걸쳐 파편이 떨어지게 해 주세요. |
| [#143](https://showheyohtaki.github.io/motion-prompt/#143) | **분해도** | Exploded view | 부품이 분리되며 내부 구조를 보여 줌 | 제품 분해도를 보여 주세요. 부품 4개가 1초 동안 벌어지고, 각각 이름 라벨을 붙여 주세요. |
| [#144](https://showheyohtaki.github.io/motion-prompt/#144) | **스플릿 스크린** | Split screen | 화면을 나눠 여러 장면을 나란히 보여 줌 | 스플릿 스크린으로 세 장면을 한 번에 보여 주세요. 한 화면에서 두 화면, 세 화면으로 각각 0.5초씩 나눠 주세요. |

번호를 누르면 갤러리의 움직이는 견본이 열립니다. 이름 하나의 시간·이징 값·참고 코드: `api/v1/en/e/<id>.txt` ([#121](../../api/v1/en/e/121.txt)).

[전체 팩](../README.md)
