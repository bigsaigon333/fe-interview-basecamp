# Rest Parameter(나머지 매개변수)란?

## 결론

- 나머지 매개변수란 함수에 전달된 매개변수 중 앞서 선언된 매개변수를 제외한 나머지를 포함하는 배열입니다.

## 설명

- `arguments` 객체를 대체하기 위해 ES6에 도입된 문법입니다.
- 나머지 매개변수는 반드시 하나여야 하며, 마지막 위치에서만 사용할 수 있습니다.
- 객체의 set 접근자 프로퍼티는 하나의 인자만 받도록 제한되기 때문에 나머지 매개변수를 사용할 수 없습니다.

## 요약

- 나머지 매개변수란 함수에 전달된 매개변수 중 앞서 선언된 매개변수를 제외한 나머지를 포함하는 배열으로서, 나머지 매개변수를 사용하면 정해지지 않은 수의 매개변수에 대응할 수 있습니다.

## Further Step

- destructuring(iterable, object)

## Reference

- 니콜라스 자카스 모던 자바스크립트 3.2.2 나머지 매개변수

- <https://stackoverflow.com/questions/59865420/using-es6-spread-operator-on-an-object-that-is-returned-from-a-function>
