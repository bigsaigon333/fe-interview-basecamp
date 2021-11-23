# 웹팩이란?

## 결론

- 웹팩이란 프로그램을 실행하는데 필요한 모든 모듈을 하나 이상의 파일로 만들어주는 모듈 번들러입니다.

## 설명

- 웹팩은 entry(진입점)부터 시작하여 사용하는 모듈의 dependency graph를 작성합니다.

- 웹팩은 js, json, css, 이미지 파일 등 모든 파일들을 모듈으로 취급하여 dependency graph를 작성하지만, js, json 만 해석할 수 있습니다. 로더를 사용하면 웹팩이 js, json 외 다른 유형의 파일도 처리하여 어플리케이션에서 유효한 모듈으로 변환합니다.

- 로더는 특정 유형의 모듈을 변환하는 데 사용되지만, 플러그인을 활용하여 번들 최적화, 자산 관리 및 환경 변수 주입과 같은 광범위한 작업을 수행할 수 있습니다.

- output은 웹팩이 생성하는 번들을 내보낼 위치와 이러한 파일의 이름을 지정하는 방법을 알립니다.

## 요약

- 웹팩이란 프로그램을 실행하는데 필요한 모든 모듈을 하나 이상의 파일로 만들어주는 모듈 번들러로서 entry부터 loader를 거쳐 plugin을 적용하여 output을 만들어냅니다.