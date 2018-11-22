# Autoscaling-comparison
노드단위 vs 팟 단위 오토스케일링 시연 및 비교

> # 1. 노드(NODE) 단위 오토스케일링

AWS 오토스케일링을 이용하여 노드단위 확장을 해본다.

## 핸드온 [클릭](doc/1.node-scale.md)

## 우리가 만들 아키텍쳐
[![aws](https://github.com/jmyung/autoscale-comparison/blob/master/doc/architecture.png?raw=true)]()




> # 2. 팟(POD) 단위 오토스케일링

Kubernetes Horizontal Pod Autoscaler를 이용한다.

## 핸드온 [클릭](doc/2.pod-scale.md)

[![pod](https://d33wubrfki0l68.cloudfront.net/4fe1ef7265a93f5f564bd3fbb0269ebd10b73b4e/1775d/images/docs/horizontal-pod-autoscaler.svg)]()




> # 3. 둘간의 비교

[![vs](https://github.com/jmyung/autoscale-comparison/blob/master/doc/node-vs-pod.png?raw=true)]()
