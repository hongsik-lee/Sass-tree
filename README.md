# Main file

메인 파일은 밑줄로 시작하지 않는 코드 기반의 유일한 Sass 파일이어야 한다. 이 파일은 `@import`와 주석만 포함되어야 한다.

sass/
|
|– abstracts/
|   |– _variables.scss    # Sass 변수
|   |– _functions.scss    # Sass 함수
|   |– _mixins.scss       # Sass 믹스인
|   |– _placeholders.scss # Sass 플레이스홀더
|
|– base/
|   |– _reset.scss       # 리셋/정규화
|   |– _typography.scss  # 타이포그래피 규칙
|   …                    # 기타.
|
|– components/
|   |– _buttons.scss     # 버튼
|   |– _carousel.scss    # 캐러셀
|   |– _cover.scss       # 커버
|   |– _dropdown.scss    # 드롭다운
|   …                    # 기타.
|
|– layout/
|   |– _navigation.scss  # 네비게이션
|   |– _grid.scss        # 그리드 시스템
|   |– _header.scss      # 헤더
|   |– _footer.scss      # 푸터
|   |– _sidebar.scss     # 사이드바
|   |– _forms.scss       # 폼
|   …                    # 기타.
|
|– pages/
|   |– _home.scss        # 홈 한정 스타일
|   |– _contact.scss     # 연락처 한정 스타일
|   …                    # 기타.
|
|– themes/
|   |– _theme.scss       # 디폴트 테마
|   |– _admin.scss       # 관리자 테마
|   …                    # 기타.
|
|– vendors/
|   |– _bootstrap.scss   # Bootstrap
|   |– _jquery-ui.scss   # jQuery UI
|   …                    # 기타.
|
`– main.scss             # 메인 Sass 파일