# Git Usage Guide

## 커밋 메시지 Style Guide

좋은 커밋 메시지는 가독성을 높이고 유지보수에도 도움이 됩니다.

### Structure

커밋 메시지는 다음의 형태로 작성해주세요.

```
type: Short (50 chars or less) summary of changes
ex. docs: 50자 내외로 변경 사항을 요약한다
```

- 반드시 한글로 작성하고 50자를 넘기지 말아주세요.
- 문장의 끝에 마침표를 적지 말아주세요.
- 타입은 영문 소문자로 작성하고 콜론(`:`)을 붙여주세요.

#### Type of changes

| type      | usage |
|:----------| --- |
| feat:     | 새로운 기능 추가 |
| fix:      | 버그 수정 |
| docs:     | 문서 수정 |
| style:    | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 |
| refactor: | 코드 리팩터링 |
| test:     | 테스트 코드, 리팩터링 테스트 코드 추가 |
| chore:    | 빌드 업데이트, |
| ui:       | UI 수정 |

## References

- [Google Style Guide](https://github.com/google/styleguide)
- [뱅크샐러드 styleguide](https://github.com/banksalad/styleguide)

