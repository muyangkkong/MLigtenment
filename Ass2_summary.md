## 전처리 전후 비교 요약

- **행/열 수 변화**: (891, 12) → (712, 6)
- **제거된 컬럼**: Name, Ticket, Cabin
- **결측치 처리**: Age, Embarked 결측치 제거
- **변환된 컬럼**: Sex, Embarked (문자열 → 숫자)
- **자료형 변경 요약**
  - Sex: object → int64
  - Embarked: object → int64
