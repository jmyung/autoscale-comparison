# Autoscaling-comparison
노드단위 vs 팟 단위 오토스케일링 시연 및 비교

> ## 1. 노드(NODE) 단위 오토스케일링

AWS 오토스케일링을 이용하여 노드단위 확장을 해본다.

### 우리가 만들 아키텍쳐
[![aws](doc/architecture.png)]()

### 핸드온 [클릭](doc/1.node-scale.md)


> ## 2. 팟(POD) 단위 오토스케일링

Kubernetes Horizontal Pod Autoscaler를 이용한다.


[![pod](https://d33wubrfki0l68.cloudfront.net/4fe1ef7265a93f5f564bd3fbb0269ebd10b73b4e/1775d/images/docs/horizontal-pod-autoscaler.svg)]()

### 핸드온 [클릭](doc/2.pod-scale.md)


> ## 3. 둘간의 비교

[![vs](doc/node-vs-pod.png)]()


> ## 4. MSA화 비즈니스 대상 찾기

blabla
