<!-- 이 파일은 tools/build.mjs 가 meta.json 으로 만든 것입니다. 고칠 때는 이 파일이 아니라 meta.json 을 편집하세요. -->

# 랜딩 페이지·웹사이트 연출

24 개 이름 · #073–096 · 팩 `lp` · 언어: [English](README.md) / [日本語](README.ja.md) / [繁體中文](README.zh-Hant.md)

이름을 찾았으면 그대로 AI에게 말하면 됩니다. "몇 초 동안", "얼마나 세게", "무엇이 움직이는지"를 덧붙이면 생각한 모습에 더 가까워집니다.

## 스크롤 연출

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#073](https://showheyohtaki.github.io/motion-prompt/#073) | **패럴랙스** | Parallax scrolling | 스크롤하면 뒤쪽 배경 레이어가 콘텐츠보다 느리게 움직임 | 히어로 배경에 패럴랙스 스크롤을 적용해 주세요. 배경은 스크롤 거리의 0.3배만큼 움직이게 해 주세요. |
| [#074](https://showheyohtaki.github.io/motion-prompt/#074) | **스크롤 페이드인** | Fade-in on scroll | 화면에 들어온 요소가 서서히 나타남 | 각 섹션의 제목과 카드에 스크롤 페이드인을 적용해 주세요. 30px 아래에서 올라오며 0.6초 동안 나타나게 해 주세요. |
| [#075](https://showheyohtaki.github.io/motion-prompt/#075) | **스티키 헤더** | Sticky header | 스크롤해도 헤더가 상단에 고정됨 | 헤더를 스티키 헤더로 만들어 주세요. 상단에 붙으면 아래에 옅은 그림자를 넣어 주세요. |
| [#076](https://showheyohtaki.github.io/motion-prompt/#076) | **스크롤 고정(핀)** | Pinning | 섹션은 멈춰 있고 스크롤에 따라 안의 내용만 넘어감 | 3단계 섹션을 고정(핀)해 주시고, 스크롤할 때마다 사진과 번호가 한 단계씩 바뀌게 해 주세요. |
| [#077](https://showheyohtaki.github.io/motion-prompt/#077) | **가로 스크롤** | Horizontal scroll | 아래로 스크롤하면 내용이 옆으로 흘러감 | 작업 사례 섹션을 가로 스크롤로 바꿔 주세요. 아래로 스크롤한 만큼 카드가 왼쪽으로 움직이게 해 주세요. |
| [#078](https://showheyohtaki.github.io/motion-prompt/#078) | **스크롤 스냅** | Scroll snap | 스크롤이 다음 섹션 위치에 딱 맞춰 멈춤 | 섹션마다 스크롤 스냅을 넣어 주세요. 조금만 스크롤해도 다음 섹션의 시작 부분에 맞춰지게 해 주세요. |
| [#079](https://showheyohtaki.github.io/motion-prompt/#079) | **스크롤 진행 바** | Scroll progress bar | 상단 막대로 얼마나 읽었는지 보여 줌 | 글 페이지 상단에 스크롤 진행 바를 넣어 주세요. 두께는 4px, 색은 브랜드 주황색으로 해 주세요. |
| [#080](https://showheyohtaki.github.io/motion-prompt/#080) | **형광펜 애니메이션** | Highlighter animation | 중요한 단어 아래에 형광펜 줄이 그어짐 | 강조할 문구가 스크롤로 화면에 들어오면, 형광펜 애니메이션으로 그 아래에 노란 줄을 왼쪽에서 오른쪽으로 0.8초 동안 그어 주세요. |

## 마우스 올림·클릭 반응

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#081](https://showheyohtaki.github.io/motion-prompt/#081) | **호버 리프트** | Hover lift | 마우스를 올리면 그림자가 짙어지며 떠오름 | 카드에 호버 리프트를 넣어 주세요. 0.3초 동안 8px 위로 올라가고 그림자가 짙어지게 해 주세요. |
| [#082](https://showheyohtaki.github.io/motion-prompt/#082) | **호버 이미지 줌** | Image zoom on hover | 틀은 그대로 두고 사진만 확대됨 | 작업 사례 사진에 호버 이미지 줌을 넣어 주세요. 틀은 고정하고 안의 사진만 0.5초 동안 1.1배까지 커지게 해 주세요. |
| [#083](https://showheyohtaki.github.io/motion-prompt/#083) | **커서 팔로워** | Cursor follower | 도형이 마우스 포인터를 한 박자 늦게 따라감 | 사이트 전체에 커서 팔로워를 넣어 주세요. 지름 30px의 주황색 원이 포인터를 살짝 늦게 따라가게 해 주세요. |
| [#084](https://showheyohtaki.github.io/motion-prompt/#084) | **마그네틱 버튼** | Magnetic button | 커서가 가까이 오면 버튼이 끌려감 | 문의 버튼을 마그네틱 버튼으로 만들어 주세요. 커서 쪽으로 0.3배만큼 끌려가고, 커서가 멀어지면 탄력 있게 돌아오게 해 주세요. |
| [#085](https://showheyohtaki.github.io/motion-prompt/#085) | **리플 효과** | Ripple effect | 누른 자리에서 물결이 퍼져 나감 | 제출 버튼에 리플 효과를 넣어 주세요. 클릭한 지점에서 흰 원이 퍼지고 0.6초 동안 사라지게 해 주세요. |
| [#086](https://showheyohtaki.github.io/motion-prompt/#086) | **밑줄 애니메이션** | Underline animation | 마우스를 올린 링크의 밑줄이 왼쪽부터 늘어남 | 메뉴 링크에 밑줄 애니메이션을 넣어 주세요. 마우스를 올리면 0.3초 동안 왼쪽부터 늘어나고, 벗어나면 오른쪽으로 빠져나가게 해 주세요. |
| [#087](https://showheyohtaki.github.io/motion-prompt/#087) | **비포 애프터 슬라이더** | Before/after slider | 경계선을 드래그해 전후를 비교함 | 시공 사진을 비포 애프터 슬라이더로 보여 주세요. 가운데 선을 드래그하면 왼쪽의 시공 전과 오른쪽의 시공 후를 비교할 수 있게 해 주세요. |
| [#088](https://showheyohtaki.github.io/motion-prompt/#088) | **이탈 방지 팝업** | Exit-intent popup | 방문자가 페이지를 떠나려 할 때 뜨는 팝업 | 랜딩 페이지에 이탈 방지 팝업을 넣어 주세요. 커서가 화면 위쪽으로 나가면 쿠폰 팝업을 한 번만 띄워 주세요. |

## 로딩·이동·반복 연출

| 번호 | 이름 | 영어 이름 | 한 줄 설명 | AI에게 부탁하는 예 |
|---|---|---|---|---|
| [#089](https://showheyohtaki.github.io/motion-prompt/#089) | **프리로더** | Preloader | 페이지를 불러오는 동안 보여 주는 화면 | 사이트에 프리로더를 만들어 주세요. 로고와 퍼센트 숫자를 보여 주고, 100%가 되면 화면이 위로 걷히게 해 주세요. |
| [#090](https://showheyohtaki.github.io/motion-prompt/#090) | **레이지 로딩** | Lazy loading | 화면에 들어온 이미지만 불러옴 | 갤러리 이미지에 레이지 로딩을 적용해 주세요. 불러오기 전까지는 회색 자리 표시를 두고, 다 불러오면 0.3초 동안 페이드인해 주세요. |
| [#091](https://showheyohtaki.github.io/motion-prompt/#091) | **무한 스크롤** | Infinite scroll | 맨 아래에 닿으면 다음 항목이 자동으로 추가됨 | 소식 목록을 무한 스크롤로 만들어 주세요. 맨 아래에 로딩 표시를 보여 주고 항목을 10개씩 추가해 주세요. |
| [#092](https://showheyohtaki.github.io/motion-prompt/#092) | **페이지 전환** | Page transition | 두 페이지 사이를 이어 주는 애니메이션 | 페이지 전환을 넣어 주세요. 링크를 누르면 주황색 패널이 왼쪽에서 오른쪽으로 화면을 가로지르며 다음 페이지가 나타나게 해 주세요. |
| [#093](https://showheyohtaki.github.io/motion-prompt/#093) | **스무스 스크롤** | Smooth scroll | 페이지 내 링크가 툭 끊기지 않고 부드럽게 이동함 | 메뉴의 페이지 내 링크를 스무스 스크롤로 만들어 주세요. 고정 헤더 바로 아래에서 멈추게 해 주세요. |
| [#094](https://showheyohtaki.github.io/motion-prompt/#094) | **마키** | Marquee | 글자나 로고가 띠 모양으로 끝없이 흘러감 | 서비스 이름을 마키로 오른쪽에서 왼쪽으로 흘려 주세요. 끊김 없이 반복되게 하고, 속도는 초당 80px 정도로 해 주세요. |
| [#095](https://showheyohtaki.github.io/motion-prompt/#095) | **그라데이션 애니메이션** | Animated gradient | 배경색이 계속 움직이며 섞임 | 히어로 배경에 그라데이션 애니메이션을 넣어 주세요. 주황색과 파란색이 천천히 섞이고, 10초에 한 바퀴 돌게 해 주세요. |
| [#096](https://showheyohtaki.github.io/motion-prompt/#096) | **플로팅 애니메이션** | Floating animation | 요소가 위아래로 살랑살랑 떠다님 | 히어로의 휴대폰 이미지에 플로팅 애니메이션을 넣어 주세요. 위아래로 8px, 2.4초에 한 번 오르내리게 해 주세요. |

번호를 누르면 갤러리의 움직이는 견본이 열립니다. 이름 하나의 시간·이징 값·참고 코드: `api/v1/en/e/<id>.txt` ([#073](../../api/v1/en/e/073.txt)).

[전체 팩](../README.md)
