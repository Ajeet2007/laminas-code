 -28,4 +28,4 @@ name: thanos
sources:
  - https://github.com/bitnami/bitnami-docker-thanos
  - https://thanos.io
version: 6.0.10
version: 6.0.11
  2  bitnami/thanos/values.yaml 
@@ -1357,7 +1357,7 @@ compactor:
  extraFlags: []
  ## @param compactor.strategyType Deployment Strategy Type, can be set to RollingUpdate or Recreate by default
  ##
  strategyType: RollingUpdate
  strategyType: Recreate
  ## @param compactor.podAffinityPreset Thanos Compactor pod affinity preset
  ## ref: https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#inter-pod-affinity-and-anti-affinity
  ##
