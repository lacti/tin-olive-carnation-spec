# tin-olive-carnation-spec

정체를 알 수 없는 tin-olive-carnation 프로젝트의 사양을 정리하기 위한 곳입니다.

## 진행

- 본 사양은 각각 사람들이 돌아가며 추가/정리합니다.
- 추가된 사양은 지정된 기간 (보통 1주) 동안 개발하여 각자의 repository에 반영합니다.
- 각자가 구현한 방법을 공유하고 더 나은 방법을 찾아봅니다.
- 최대한 경이롭고 놀라운 방법으로 구현할 수 있는 방법을 찾아봅니다.

### 작업자

- [lacti](https://github.com/lacti/tin-olive-carnation)
- [dplusic](https://github.com/dplusic/tin-olive-carnation)

## 사양

### 1주차

본 서비스는 구름 사진을 공유하는 serverless 서비스입니다.

- user는 자신의 정보를 가지고 sign in/up을 수행하여,
  - 인증에 필요한 최소 정보(phone number 혹은 email 인증)와 nickname을 가집니다.
- 자신의 credential을 가지고 cloud image를 upload하고,
- public timeline에서는 upload한 image들을 시간 순으로 나열해서 확인할 수 있습니다.
  - view에 대한 spec은 따로 하지 않지만, image, uploaded time, writer 정도는 노출해야 합니다.
