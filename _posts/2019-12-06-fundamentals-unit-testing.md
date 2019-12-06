---
layout: post
title:  "Fundamentals of Unit Testing"
---

#Unit Test Fundamentals

유닛 테스트는 테스트 중인 시스템이 요구사항에 맞게 동작 하는지를 검증하기 위해 사용함
유닛 테스트 이름은 실패했을 경우 테스트중인 유닛의 디버그를 위해 필요한 문맥 정보를 포함 해야 함
<UnitOfWork>_<SpecificUnitUnderTest>_<ExpectedBehavior>
duplicateDetector_emptyString_emptyStringReturned
유닛 테스트의 입력 값과 출력값은 non-nullable 로 가정 but Null 에 대한 고려가 필요한 경우 @Nullable annotation 붙이기
테스트 중인 유닛의 다양한 상태를 그룹화 하고 각 그룹에서 적어도 하나의 대표 케이스에 대해 테스트 진행
Edge case(boundary case) 를 식별하고 테스트 하기
Index 에서 start 나 end case 같은것
