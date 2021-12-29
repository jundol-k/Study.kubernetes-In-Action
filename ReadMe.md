# Kubernetes in action Study

쿠버네티스인액션 책을 공부하며 작성한 파일들입니다.

yml, yaml 등.

책의 예제들이 최신화가 되어있지않아 2021.12월 기준 모든 파일들은 gke에서 정상작동하는것을 확인했습니다.

# Chapter 13
PSP 기능은 k8s 1.21 버전에서 deprecated 되었으며 1.25 버전에서 완전히 없어질 예정입니다.   
일부 기능이 이미 gke에서 정상적으로 동작하지 않습니다. (21.12.29 기준 1.21).  
참고: https://kubernetes.io/blog/2021/04/06/podsecuritypolicy-deprecation-past-present-and-future/

# Chapter 14
## limit.yml    
GKE 기준 노드 최대 CPU 사용 가능량이 800M 이여서 도서와 상이한 부분이 있습니다.
