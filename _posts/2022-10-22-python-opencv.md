---
layout: post
title:  "Python OpenCV"
date:   2022-10-22
excerpt: "Just about everything you'll need to style in the theme: headings, paragraphs, blockquotes, tables, code blocks, and more."
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

## OpenCV

OpenCV는 Open Source Computer Vision Library의 약어로 실시간 컴퓨터 비전을 목적으로 한 프로그래밍 라이브러리이다. 실시간 이미지 프로세싱에 중점을 둔 라이브러리이다.

## OpenCV 활용 용도

OpenCV 는 주로 HCL, 물체 인식, 안면 인식, 모바일 로보틱스, 제스쳐 인식, 자율 주행 등 다양한 분야에서 사용 된다고 한다.

## Example

```py
import cv2

img = cv2.imread('./pi.png')

cv2.imshow('image', img)
cv2.waitKey(0)
cv2.destroryWindows()
```

**[ 실행 결과 ]**
<img src="https://cdn.discordapp.com/attachments/942420868846460993/1034420917071253585/result.PNG" width="100">
