---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

name: '문제'
description: 문제 Issue 작성 양식입니다.
title: '[n주차] '
body:
  - type: markdown
    attributes:
      value: |
        작성 예시 : "[n주차/이름] 핸디북 대주제 제목"
  - type: textarea
    id: bug-description
    attributes:
      label: 작업 요약
      description: 어떠한 기능을 추가하시는 건지 적어주세요.
      placeholder: 설명을 적어주세요.
    validations:
      required: true
