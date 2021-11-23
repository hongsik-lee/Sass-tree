# Abstracts

`abstracts/` 폴더는 프로젝트 전체에서 사용되는 모든 Sass 도구와 도우미를 수집합니다. 모든 전역 변수, 함수, mixin 및 자리 표시자를 여기에 넣어야 합니다.

이 폴더에 대한 경험적 규칙은 자체적으로 컴파일될 때 CSS 한 줄을 출력하지 않아야 한다는 것입니다. 이들은 Sass 도우미에 불과합니다.

– abstracts/
|   |– _variables.scss    # Sass 변수
|   |– _functions.scss    # Sass 함수
|   |– _mixins.scss       # Sass 믹스인
|   |– _placeholders.scss # Sass 플레이스홀더

