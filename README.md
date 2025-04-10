## 📖 상세 내용

이 프로젝트는 **오픈소스 기반 데이터 분석과 AI 기술을 활용하여 지자체 교통사고 데이터를 분석하고, 효과적인 사고 예방 및 대응 방안을 제시하는 AI 관제 솔루션 개발**을 목표로 합니다.

단순한 기술 구현을 넘어서, **교통사고·화재·범죄 등의 사고 데이터를 다양한 오픈소스 도구로 심층 분석**하고, 이를 통해 **사고 다발 지역 및 취약 지점을 식별**하였습니다.

또한, 분석 결과를 바탕으로 **AI 기반 CCTV 시스템의 도입 가능성을 제시**하였으며, 실시간 영상 분석을 통해 사고 발생 즉시 경고 및 자동 통보가 가능한 체계를 설계했습니다.

이를 통해 기존의 인력 중심 대응보다 **더 신속하고 정확한 초기 대응이 가능**해지고, 각 지자체의 관제 플랫폼과 연동해 **사고 대응 역량을 전반적으로 향상**시킬 수 있습니다.

이 프로젝트는 데이터 분석과 오픈소스, AI 기술을 실질적인 공공안전 향상에 접목시킨 사례로, **시민 안전 강화를 위한 기술적 접근을 실현**한 것입니다.

## 🛠️ 개발스택

- python, html, Pandas, Folium

## 📱 담당한 기능

- 유성구 교통사고 데이터 정제
- 데이터 시각화
- 솔루션 해결방안 제시
- RTMP 주소 변환 및 실시간 스트리밍

## 🥹시행착오를 겪었던 부분

- RTMP 주소를 입력하여 웹에서 실시간으로 스트리밍할려고 했지만 실패

## 💡극복한점 & 깨달은 점

- 교통사고 데이터를 분석하고 이를 지도에 시각화하는 과정에서, 실제 사고 다발 구역과 사각지대를 확인할 수 있었고, 이를 통해 데이터 기반 문제 해결의 가능성을 체감할 수 있었습니다.
- RTMP 주소를 웹 환경에서 사용할 수 있도록 HLS(HTTP Live Streaming) 형식의 HTTP 주소로 변환하여 실시간 스트리밍 구현에 성공하였습니다. 이를 통해 브라우저 기반의 영상 스트리밍이 가능해졌습니다.
