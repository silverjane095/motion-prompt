<!-- 이 파일은 tools/build.mjs 가 meta.json 으로 만든 것입니다. 고칠 때는 이 파일이 아니라 meta.json 을 편집하세요. -->

# 모션그래픽 동작

24 개 이름 · #001–024 · 팩 `motion` · 언어: [English](README.md) / [日本語](README.ja.md) / [繁體中文](README.zh-Hant.md)

이름을 찾았으면 그대로 AI에게 말하면 됩니다. "몇 초 동안", "얼마나 세게", "무엇이 움직이는지"를 덧붙이면 생각한 모습에 더 가까워집니다.

![모션그래픽 동작 — 견본](../../assets/preview-motion.gif)

## 등장·글자 연출

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#001](https://showheyohtaki.github.io/motion-prompt/#001) | **팝인** | Pop-in | 살짝 통통 튀면서 나타남 | 로고를 팝인으로 등장시켜 주세요. 0.4초 정도로, 오버슈트는 살짝만 주세요. |
| [#002](https://showheyohtaki.github.io/motion-prompt/#002) | **스태거** | Stagger | 요소들이 시간 차를 조금씩 두고 차례로 나타남 | 카드 5장을 스태거로 등장시켜 주세요. 왼쪽에서 오른쪽으로 0.08초 간격이에요. |
| [#003](https://showheyohtaki.github.io/motion-prompt/#003) | **버스트** | Burst | 무언가 나타날 때 선과 점이 바깥으로 터져 나감 | 하트가 나타나는 순간 주변에 버스트를 넣어 주세요. 짧은 선 8개가 0.3초 안에 사라지게 해 주세요. |
| [#004](https://showheyohtaki.github.io/motion-prompt/#004) | **라인 드로우** | Line draw | 선이 그려지듯 뻗어 나감 | 그래프의 꺾은선을 라인 드로우로 왼쪽부터 1.2초에 걸쳐 그려 주세요. |
| [#005](https://showheyohtaki.github.io/motion-prompt/#005) | **마스크 리빌** | Mask reveal | 보이지 않는 경계 뒤에서 글자가 솟아오름 | 제목을 마스크 리빌로 아래에서 올라오게 해 주세요. 0.6초로, 줄마다 앞줄보다 조금씩 늦게 나오게 해 주세요. |
| [#006](https://showheyohtaki.github.io/motion-prompt/#006) | **타이프라이터** | Typewriter | 타자를 치듯 한 글자씩 나타남 | 이 문장을 타이프라이터 효과로 보여 주세요. 글자당 0.05초이고, 끝에 커서를 붙여 주세요. |
| [#007](https://showheyohtaki.github.io/motion-prompt/#007) | **카운트업** | Count-up | 숫자가 최종 값까지 빠르게 올라감 | 숫자를 0에서 1,280까지 1.5초 동안 카운트업해 주세요. 끝에서는 천천히 멈추게 해 주세요. |
| [#008](https://showheyohtaki.github.io/motion-prompt/#008) | **키네틱 타이포그래피** | Kinetic typography | 말하는 내용에 맞춰 단어가 움직이고 커지고 돌아감 | 이 내레이션을 키네틱 타이포그래피로 만들어 주세요. 강조하는 단어는 크게 하고, 박자에 맞춰 내려앉게 해 주세요. |

## 움직임 다듬기

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#009](https://showheyohtaki.github.io/motion-prompt/#009) | **이징** | Easing | 한 속도로 움직이지 않고 빨라졌다 느려지며 움직임 | 이 이동에 이징을 넣어 주세요. 이즈 아웃으로, 멈출 때 느려지게 해 주세요. |
| [#010](https://showheyohtaki.github.io/motion-prompt/#010) | **오버슈트** | Overshoot | 목표를 조금 지나쳤다가 되돌아와 자리 잡음 | 게이지 바늘에 오버슈트를 주세요. 목표보다 10% 정도 지나쳤다가 돌아오게 해 주세요. |
| [#011](https://showheyohtaki.github.io/motion-prompt/#011) | **스쿼시 앤 스트레치** | Squash & stretch | 찌그러지고 늘어나며 탄력 있게 느껴지게 함 | 공이 착지할 때 스쿼시 앤 스트레치를 넣어 주세요. 찌그러짐은 약하게 해 주세요. |
| [#012](https://showheyohtaki.github.io/motion-prompt/#012) | **모핑** | Shape morph | 한 도형이 다른 도형으로 부드럽게 바뀜 | 원을 0.8초 동안 별로 모핑해 주세요. 도중에 색도 파란색에서 노란색으로 바꿔 주세요. |
| [#013](https://showheyohtaki.github.io/motion-prompt/#013) | **리퀴드 모션** | Liquid motion | 도형이 액체처럼 움직이고 합쳐짐 | 로고 등장을 리퀴드 모션으로 해 주세요. 물방울이 모여 로고 모양이 되게 해 주세요. |
| [#014](https://showheyohtaki.github.io/motion-prompt/#014) | **모션 트레일** | Motion trail | 움직이는 물체 뒤로 점점 옅어지는 잔상이 따라옴 | 날아가는 원에 모션 트레일을 붙여 주세요. 잔상은 5개이고, 뒤로 갈수록 옅어지게 해 주세요. |
| [#015](https://showheyohtaki.github.io/motion-prompt/#015) | **파티클** | Particles | 작은 조각이 많이 튀어나와 흩어짐 | 성공하는 순간 아래에서 파티클을 쏘아 올려 주세요. 4가지 색으로, 1.5초 안에 모두 떨어지게 해 주세요. |
| [#016](https://showheyohtaki.github.io/motion-prompt/#016) | **패럴랙스** | Parallax | 가까운 층과 먼 층을 다른 속도로 움직여 깊이감을 줌 | 이 풍경을 3개 층으로 나눠 패럴랙스로 스크롤해 주세요. 가까운 층일수록 빠르게 해 주세요. |

## 전환·하이라이트

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#017](https://showheyohtaki.github.io/motion-prompt/#017) | **마스크 트랜지션** | Mask transition | 커지는 도형 안에서 다음 장면이 나타남 | 다음 장면으로는 마스크 트랜지션으로 넘어가 주세요. 가운데에서 원이 0.7초 동안 커지게 해 주세요. |
| [#018](https://showheyohtaki.github.io/motion-prompt/#018) | **셰이프 트랜지션** | Shape transition | 도형이 화면을 덮었다가 걷히며 다음 장면이 드러남 | 장면 전환은 셰이프 트랜지션으로 해 주세요. 4가지 색의 사선 띠가 왼쪽에서 휩쓸며 들어오게 해 주세요. |
| [#019](https://showheyohtaki.github.io/motion-prompt/#019) | **리퀴드 트랜지션** | Liquid transition | 액체가 흘러 들어와 장면을 바꿈 | 여기는 리퀴드 트랜지션을 써 주세요. 파란 잉크가 위에서 흘러내려 화면을 채우게 해 주세요. |
| [#020](https://showheyohtaki.github.io/motion-prompt/#020) | **줌 스루** | Zoom through | 물체 안으로 줌인해 뚫고 지나가 다음 장면으로 넘어감 | 로고의 "O" 구멍으로 줌 스루해서 다음 장면으로 넘어가 주세요. 0.6초 동안 가속하면서요. |
| [#021](https://showheyohtaki.github.io/motion-prompt/#021) | **플립** | Flip | 카드처럼 뒤집혀 반대 면을 보여 줌 | 요금 카드를 0.5초 동안 플립해서 뒷면에 상세 내용을 보여 주세요. |
| [#022](https://showheyohtaki.github.io/motion-prompt/#022) | **라이트 스윕** | Light sweep | 빛의 띠가 표면을 가로지름 | 로고가 자리 잡은 뒤 라이트 스윕을 한 번 넣어 주세요. 왼쪽 위에서 오른쪽 아래로, 은은하게 해 주세요. |
| [#023](https://showheyohtaki.github.io/motion-prompt/#023) | **글리치** | Glitch | 고장 난 것처럼 화면이 깨지고 흐트러짐 | 제목에 짧은 글리치를 넣어 주세요. 0.3초로, 색 분리는 약하게 하고 깜빡임은 없게 해 주세요. |
| [#024](https://showheyohtaki.github.io/motion-prompt/#024) | **임팩트 셰이크** | Impact shake | 무언가 떨어져 닿을 때 화면 전체가 흔들림 | 헤드라인이 떨어져 닿을 때 임팩트 셰이크를 넣어 주세요. 0.4초 안에 잦아들게 해 주세요. |

번호를 누르면 갤러리의 움직이는 견본이 열립니다. 이름 하나의 시간·이징 값·참고 코드: `api/v1/en/e/<id>.txt` ([#001](../../api/v1/en/e/001.txt)).

[전체 팩](../README.md)
