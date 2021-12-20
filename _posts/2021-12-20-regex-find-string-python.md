---
layout: post
tags: [regex, python]
title: 파이썬 배운것들 정리
author: BangleCoder
lastupdate: 2021-12-20
---

##짤막메모

- 파이썬 혹은 아나콘다 중 하나만 깔아도 파이썬 사용이 가능하다.
  - 난 이걸 몰라서 애로사항이 꽃폈다....
- pip : npm, maven과 같은 파이썬 라이브러리 관리 시스템
- 파이썬에서 JSON과 유사한 형식의 자료형은 딕셔너리다.

##정규표현식을 통해 부분 문자열 모두 찾기

```python
import re

[m.start() for m in re.finditer('찾을부분문자열', '전체문자열' ]
```
