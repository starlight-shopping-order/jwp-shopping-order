# jwp-shopping-order

## API 설계

### Cart Item API

| HttpMethod | URL              | HttpStatus | Description           |
|------------|------------------|------------|-----------------------|
| GET        | /cart-items      | 200        | 카트 내 모든 상품을 조회한다.     |
| POST       | /cart-items      | 201        | 카트에 상품을 추가한다.         |
| PATCH      | /cart-items/{id} | 200        | 카트 내 특정 상품의 개수를 수정한다. |
| DELETE     | /cart-items/{id} | 204        | 카트 내 특정 상품을 제거한다.     |

### Product API

| HttpMethod | URL              | HttpStatus | Description           |
|------------|------------------|------------|-----------------------|
| GET        | /products        | 200        | 전체 상품을 조회한다.          |
| GET        | /products/{id}   | 200        | 특정 상품을 조회한다.          |
| POST       | /products        | 201        | 상품을 추가한다.             |
| POST       | /products        | 201        | 상품을 추가한다.             |
| PUT        | /products/{id}   | 200        | 상품 정보를 업데이트한다.        |
| DELETE     | /products/{id}   | 204        | 상품을 삭제한다.             |

## 코드리뷰 컨벤션

<img width="453" alt="스크린샷 2023-05-25 오후 5 55 07" src="https://github.com/starlight-shopping-order/jwp-shopping-order/assets/107979804/024f58db-61e2-454c-8f4d-b6f6a651e087">

- Request Change: 적극적으로 반영을 고려해 주세요.
- Comment: 웬만하면 반영해 주세요.
- Approve: 반영해도 좋고, 넘어가도 좋은 사소한 의견입니다.

## Issue 및 PR 컨벤션

1. issue 생성 및 체크리스트 생성


2. 브랜치 생성 
  - 브랜치 이름
    - `feature/~`: 기능 개발
    - `bugfix/~`: 심각하지는 않지만 문제가 있는 기능 수정
    - `hotfix/~`: 긴급하게 수정해야 할 사항

3. Pull Request 보내기

- PR 보낼 때, 오른쪽 설정에서 관련된 Label, Development(관련된 issue) 선택


<img width="322" alt="스크린샷 2023-05-25 오후 6 00 05" src="https://github.com/starlight-shopping-order/jwp-shopping-order/assets/107979804/9b040fca-af5b-41aa-95e5-c90b143d33b8">
