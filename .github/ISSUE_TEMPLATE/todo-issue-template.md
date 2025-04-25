name: "✨ TODO"
description: "새로운 할일 추가"
labels: ["todo"]
body:
  - type: textarea
    attributes:
      label: 📄 설명
      description: 새로운 기능에 대한 설명을 작성해 주세요.
      placeholder: 자세히 적을수록 좋습니다!
    validations:
      required: true
  - type: textarea
    attributes:
      label: 🙋🏻 참고 자료
      description: 참고 자료가 있다면 작성해 주세요.
