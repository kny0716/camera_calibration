# camera_calibration
<b5>
  
다양한 시점에서 촬영한 체스보드 동영상을 이용해 camera calibration을 하고, 이 결과를 이용해 렌즈 왜곡을 보정하는 프로젝트 입니다.
</b5>

## camera_calibration.py 실행 결과

``` +
## Camera Calibration Results
* The number of selected images = 12
* RMS error = 1.6472488111653205
* Camera matrix (K) =
[[1.82706846e+03 0.00000000e+00 1.01512766e+03]
 [0.00000000e+00 1.82953399e+03 5.20568218e+02]
 [0.00000000e+00 0.00000000e+00 1.00000000e+00]]
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 0.24739965 -1.14051711 -0.00626881  0.00995754  1.216575  ]

```

## distortion_correction.py 실행 결과

<b5> 위 camera calibration의 결과를 이용해 렌즈 왜곡 보정을 수행한 결과입니다. </b5>
 
https://github.com/user-attachments/assets/f9e5a4d0-22d1-462e-a64b-94d26ba5b057

