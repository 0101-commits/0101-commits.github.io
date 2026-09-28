# 0101-commits.github.io

GitHub Pages **사용자 루트 사이트**(`https://0101-commits.github.io/`)입니다. `index.html` 한 장으로, 접속 즉시 `/economic-site/`(경제현황 터미널)로 리다이렉트합니다.

## 왜 필요한가

- 카카오 앱(ECOM)의 '사이트 도메인'이 루트(`https://0101-commits.github.io`)로 등록되어 있어, 카카오톡 메시지 하단 앱 이름을 누르면 루트로 이동합니다. 이 저장소가 없거나 Pages가 꺼지면 **404**가 뜹니다.
- 같은 도메인 아래 프로젝트 사이트(`/mindmap/`, `/HR-job-AP/`, `/elizax_talenx/`, `/economic-site/` 등)는 각 저장소가 따로 배포하며, 이 저장소와 무관하게 동작합니다.

## 구성

| 파일 | 역할 |
|------|------|
| `index.html` | meta refresh + `location.replace`로 `/economic-site/` 이동, canonical 지정 |

## 공개 범위(Visibility) 주의

- 이 저장소에는 민감정보가 없습니다(리다이렉트 HTML 1개).
- private으로 전환하면 GitHub Free 플랜에서는 Pages가 중단되어 카카오 링크가 404가 됩니다. **public 유지를 권장합니다.**
