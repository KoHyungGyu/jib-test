# jib-test

Jib는 무엇을 하나요?
Jib는 애플리케이션을 컨테이너 이미지로 패키징하는 모든 단계를 처리합니다. Dockerfile을 만들거나 Docker를 설치하기 위한 권장사항을 알 필요가 없습니다.

Docker 빌드 흐름:
![image](https://user-images.githubusercontent.com/88372580/211752959-0b842a7f-162c-4896-bdde-0f29769cfd8f.png)

Docker를 사용하여 프로젝트에서 Container Registry까지의 단계를 보여주는 다이어그램

Jib 빌드 흐름:
![image](https://user-images.githubusercontent.com/88372580/211753009-ee038e0f-71dc-4046-86d1-d61c88d9e4a0.png)
Jib를 사용하여 프로젝트에서 Container Registry까지의 중간 단계를 보여주는 다이어그램

Jib는 애플리케이션을 종속 항목, 리소스, 클래스 등 별개의 레이어로 구성하고 Docker 이미지 레이어 캐싱을 활용하여 변경사항만 다시 빌드함으로써 빌드를 빠르게 유지합니다. Jib 레이어 구성과 작은 기본 이미지는 전체 이미지 크기를 작게 유지하여 성능과 휴대성을 향상시킵니다.

### 프로젝트 정보
![image](https://user-images.githubusercontent.com/88372580/211754839-0166645e-4ba4-443c-8512-6d1cf947f4d8.png)


### 참고자료
https://plugins.gradle.org/plugin/com.google.cloud.tools.jib

https://cloud.google.com/java/getting-started/jib?hl=ko
