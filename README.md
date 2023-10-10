# digitech-wiki

서울디지텍고등학교 교내 위키인 디지텍 위키입니다.
빠른개발, 용이한 편집 기록 열람을 위해 python 기반 공식문서 개발 라이브러리인 mkdocs와 mkdocs-material을 사용하여 개발하였습니다.

로컬에서 실행하기 위해선 의존성을 위해 `requirements.txt`에 있는 라이브러리들을 설치해야합니다.

`pip install -r requirements.txt`

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs -h` - Print help message and exit.

# 트러블 슈팅

## 클라우드플레어 clone 문제

클라우드플레어 페이지스 사용시 커밋기록을 다 가져오지 않고 코드만 가져오는 바람에 깃 커밋 기록 기반으로 작동하는 ``git-revision-date-localized-plugin`가 제대로 작동하지 않음

->

ghPages로 배포 환경 변경

## ghpages 수정 적용 성능 이슈

ghpages 사용시
