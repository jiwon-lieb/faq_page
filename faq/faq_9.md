---
title: "YOLOX를 활용한 비디오 파일(.mp4) 처리 방법"
slug: "video-processing-yolox"
author: "Jiwon"
createdDate: "2025-03-04"
category: "추론"
tags: ['Video Processing', 'YOLOX', 'Image Detection']
---
비디오 파일(.mp4)을 활용하여 YOLOX 모델을 사용하기 위해서는 추론을 실행하기 전에 OpenCV(`cv2`)와 같은 라이브러리를 사용하여 비디오의 각 프레임을 이미지로 변환해야 합니다. 변환된 프레임을 YOLOX 모델에 입력하면 실시간 객체 탐지가 가능합니다.
