# Namespace

- `Kubernetes`에서 동일한 `Physical Cluster`를 기반으로 하는 여러 개의 `Virtual Cluster`를 지원한다. 여기서 `Virtual Cluster`를 `Namespace`라고 한다.
- `Cluster Resource`를 `Resource Quota`를 통해 여러 사용자 사이에서 나누는 방법이다.
- `Kubernetes Resource`의 이름은 `Namespace` 내에서 유일해야하지만, 모든 `Namespace`를 통틀어서 유일할 필요는 없다.
- `Namespace`는 서로 중첩될 수 없다.
- 각 `Kubernetes Resource`는 하나의 `Namespace`에만 있을 수 있다.
- 동일한 `Namespace` 내에서 `Resource`를 구별하기 위해 `Label`을 사용한다.


----------------------------------------------------------------

## Reference

1. https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/