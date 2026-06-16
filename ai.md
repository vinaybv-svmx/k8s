# Kubernetes Resource Summary

## Namespace: ai-analytics-patch

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/ai-analytics-patch-7c8cb65887-8zx7h | 1/1 | Running | 0 | 4d2h | 10.111.222.106 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/ai-analytics-patch | ClusterIP | 172.20.206.63 | <none> | 8000/TCP | 403d | app=ai-analytics-patch |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/ai-analytics-patch | 1/1 | 1 | 1 | 403d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.19 | app=ai-analytics-patch |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/ai-analytics-patch-558d6b9d6b | 0 | 0 | 0 | 63d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:5.0.9 | app=ai-analytics-patch,pod-template-hash=558d6b9d6b |
| replicaset.apps/ai-analytics-patch-5668d4f9db | 0 | 0 | 0 | 99d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:5.0.5 | app=ai-analytics-patch,pod-template-hash=5668d4f9db |
| replicaset.apps/ai-analytics-patch-5c4dd945cb | 0 | 0 | 0 | 181d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.12 | app=ai-analytics-patch,pod-template-hash=5c4dd945cb |
| replicaset.apps/ai-analytics-patch-66b87c6b9 | 0 | 0 | 0 | 238d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.72 | app=ai-analytics-patch,pod-template-hash=66b87c6b9 |
| replicaset.apps/ai-analytics-patch-67f75c988d | 0 | 0 | 0 | 194d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.11 | app=ai-analytics-patch,pod-template-hash=67f75c988d |
| replicaset.apps/ai-analytics-patch-6b54676545 | 0 | 0 | 0 | 221d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.73 | app=ai-analytics-patch,pod-template-hash=6b54676545 |
| replicaset.apps/ai-analytics-patch-798444bc45 | 0 | 0 | 0 | 194d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.11 | app=ai-analytics-patch,pod-template-hash=798444bc45 |
| replicaset.apps/ai-analytics-patch-7c8cb65887 | 1 | 1 | 1 | 4d2h | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.19 | app=ai-analytics-patch,pod-template-hash=7c8cb65887 |
| replicaset.apps/ai-analytics-patch-7d76945959 | 0 | 0 | 0 | 11d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.15 | app=ai-analytics-patch,pod-template-hash=7d76945959 |
| replicaset.apps/ai-analytics-patch-d7d4f88 | 0 | 0 | 0 | 63d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:5.0.8 | app=ai-analytics-patch,pod-template-hash=d7d4f88 |
| replicaset.apps/ai-analytics-patch-dc77998d9 | 0 | 0 | 0 | 271d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.64 | app=ai-analytics-patch,pod-template-hash=dc77998d9 |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-analytics-patch | Deployment/ai-analytics-patch | cpu: 0%/80%, memory: 68%/80% | 1 | 2 | 1 | 403d |

---

## Namespace: ai-analytics-prod

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/ai-analytics-prod-54565d67d4-2mz5m | 1/1 | Running | 0 | 11h | 10.111.118.240 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-lhxrv | 1/1 | Running | 0 | 4d23h | 10.111.201.250 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-m2v2h | 1/1 | Running | 0 | 4d23h | 10.111.255.248 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-mz5dk | 1/1 | Running | 0 | 4d23h | 10.111.228.190 | ip-10-111-238-32.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/ai-analytics-prod | ClusterIP | 172.20.26.92 | <none> | 8000/TCP | 403d | app=ai-analytics-prod |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/ai-analytics-prod | 4/4 | 4 | 4 | 403d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.15 | app=ai-analytics-prod |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/ai-analytics-prod-54565d67d4 | 4 | 4 | 4 | 4d23h | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.15 | app=ai-analytics-prod,pod-template-hash=54565d67d4 |
| replicaset.apps/ai-analytics-prod-5675c69d79 | 0 | 0 | 0 | 188d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.11 | app=ai-analytics-prod,pod-template-hash=5675c69d79 |
| replicaset.apps/ai-analytics-prod-66f9f88679 | 0 | 0 | 0 | 262d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:ai-analytics-prod | app=ai-analytics-prod,pod-template-hash=66f9f88679 |
| replicaset.apps/ai-analytics-prod-6c8bf9c76c | 0 | 0 | 0 | 48d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:5.0.9 | app=ai-analytics-prod,pod-template-hash=6c8bf9c76c |
| replicaset.apps/ai-analytics-prod-796d549577 | 0 | 0 | 0 | 179d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.12 | app=ai-analytics-prod,pod-template-hash=796d549577 |
| replicaset.apps/ai-analytics-prod-7b9d6488f9 | 0 | 0 | 0 | 227d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.72 | app=ai-analytics-prod,pod-template-hash=7b9d6488f9 |
| replicaset.apps/ai-analytics-prod-7f69d8659d | 0 | 0 | 0 | 5d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.15 | app=ai-analytics-prod,pod-template-hash=7f69d8659d |
| replicaset.apps/ai-analytics-prod-85ff86fd95 | 0 | 0 | 0 | 217d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.73 | app=ai-analytics-prod,pod-template-hash=85ff86fd95 |
| replicaset.apps/ai-analytics-prod-b854c4f45 | 0 | 0 | 0 | 188d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:4.0.11 | app=ai-analytics-prod,pod-template-hash=b854c4f45 |
| replicaset.apps/ai-analytics-prod-c7db44f9 | 0 | 0 | 0 | 95d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:5.0.5 | app=ai-analytics-prod,pod-template-hash=c7db44f9 |
| replicaset.apps/ai-analytics-prod-c95746b6c | 0 | 0 | 0 | 262d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:3.0.64 | app=ai-analytics-prod,pod-template-hash=c95746b6c |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-analytics-prod | Deployment/ai-analytics-prod | cpu: 0%/80%, memory: 92%/80% | 2 | 4 | 4 | 403d |

---

## Namespace: ai-console-patch

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/ai-console-patch-us-east-1-7ffd8954d7-7tmrq | 1/1 | Running | 0 | 11d | 10.111.178.124 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-h9jhh | 1/1 | Running | 0 | 7d17h | 10.111.129.45 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-nbl6r | 1/1 | Running | 0 | 11d | 10.111.102.185 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-p24cb | 1/1 | Running | 0 | 11d | 10.111.72.88 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-qg7hb | 1/1 | Running | 0 | 11d | 10.111.248.190 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-vmzqf | 1/1 | Running | 0 | 11d | 10.111.205.136 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/ai-console-patch-us-east-1 | ClusterIP | 172.20.173.236 | <none> | 5000/TCP | 404d | app=ai-console-patch-us-east-1 |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/ai-console-patch-us-east-1 | 6/6 | 6 | 6 | 404d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-patch-us-east-1 |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/ai-console-patch-us-east-1-55864b84fd | 0 | 0 | 0 | 238d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.3-88-6cf3090 | app=ai-console-patch-us-east-1,pod-template-hash=55864b84fd |
| replicaset.apps/ai-console-patch-us-east-1-589b458c8b | 0 | 0 | 0 | 63d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.3.0-101-4f408f4 | app=ai-console-patch-us-east-1,pod-template-hash=589b458c8b |
| replicaset.apps/ai-console-patch-us-east-1-5bb5bf5676 | 0 | 0 | 0 | 102d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.1-96-34bc54e | app=ai-console-patch-us-east-1,pod-template-hash=5bb5bf5676 |
| replicaset.apps/ai-console-patch-us-east-1-656c6b5f74 | 0 | 0 | 0 | 103d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.1-96-34bc54e | app=ai-console-patch-us-east-1,pod-template-hash=656c6b5f74 |
| replicaset.apps/ai-console-patch-us-east-1-65855857d9 | 0 | 0 | 0 | 195d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.0-94-59c6048 | app=ai-console-patch-us-east-1,pod-template-hash=65855857d9 |
| replicaset.apps/ai-console-patch-us-east-1-6db77f5cc9 | 0 | 0 | 0 | 195d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.3-88-6cf3090 | app=ai-console-patch-us-east-1,pod-template-hash=6db77f5cc9 |
| replicaset.apps/ai-console-patch-us-east-1-6dc6fd657d | 0 | 0 | 0 | 249d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.2-87-92797f3 | app=ai-console-patch-us-east-1,pod-template-hash=6dc6fd657d |
| replicaset.apps/ai-console-patch-us-east-1-74655c8554 | 0 | 0 | 0 | 103d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.1-96-34bc54e | app=ai-console-patch-us-east-1,pod-template-hash=74655c8554 |
| replicaset.apps/ai-console-patch-us-east-1-7ffd8954d7 | 6 | 6 | 6 | 11d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-patch-us-east-1,pod-template-hash=7ffd8954d7 |
| replicaset.apps/ai-console-patch-us-east-1-8577dc66cd | 0 | 0 | 0 | 99d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.3.0-100-cbbf9d7 | app=ai-console-patch-us-east-1,pod-template-hash=8577dc66cd |
| replicaset.apps/ai-console-patch-us-east-1-9dcfff5bf | 0 | 0 | 0 | 180d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.1-96-34bc54e | app=ai-console-patch-us-east-1,pod-template-hash=9dcfff5bf |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-console-patch-us-east-1 | Deployment/ai-console-patch-us-east-1 | cpu: 14%/70%, memory: 91%/80% | 3 | 6 | 6 | 355d |

---

## Namespace: ai-console-prod

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/ai-console-prod-us-east-1-844879c998-62fb4 | 1/1 | Running | 0 | 4d23h | 10.111.103.190 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-cpst5 | 1/1 | Running | 0 | 4d23h | 10.111.202.177 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-gw4jh | 1/1 | Running | 0 | 4d23h | 10.111.172.238 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-hqvbm | 1/1 | Running | 0 | 4d23h | 10.111.169.35 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-r6prb | 1/1 | Running | 0 | 47h | 10.111.115.74 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-z2lxx | 1/1 | Running | 0 | 4d23h | 10.111.203.154 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/ai-console-prod-us-east-1 | ClusterIP | 172.20.224.198 | <none> | 5000/TCP | 404d | app=ai-console-prod-us-east-1 |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/ai-console-prod-us-east-1 | 6/6 | 6 | 6 | 395d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-prod-us-east-1 |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/ai-console-prod-us-east-1-57d7987659 | 0 | 0 | 0 | 95d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.3.0-100-cbbf9d7 | app=ai-console-prod-us-east-1,pod-template-hash=57d7987659 |
| replicaset.apps/ai-console-prod-us-east-1-588df99fdc | 0 | 0 | 0 | 48d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.3.0-101-4f408f4 | app=ai-console-prod-us-east-1,pod-template-hash=588df99fdc |
| replicaset.apps/ai-console-prod-us-east-1-65989d69f9 | 0 | 0 | 0 | 278d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.0-83-e2326b8 | app=ai-console-prod-us-east-1,pod-template-hash=65989d69f9 |
| replicaset.apps/ai-console-prod-us-east-1-69d7567667 | 0 | 0 | 0 | 262d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.1-86-28cd1a2 | app=ai-console-prod-us-east-1,pod-template-hash=69d7567667 |
| replicaset.apps/ai-console-prod-us-east-1-6d697fbbb5 | 0 | 0 | 0 | 188d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.0-94-59c6048 | app=ai-console-prod-us-east-1,pod-template-hash=6d697fbbb5 |
| replicaset.apps/ai-console-prod-us-east-1-799dcc65df | 0 | 0 | 0 | 179d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:13.0.1-96-34bc54e | app=ai-console-prod-us-east-1,pod-template-hash=799dcc65df |
| replicaset.apps/ai-console-prod-us-east-1-844879c998 | 6 | 6 | 6 | 4d23h | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-prod-us-east-1,pod-template-hash=844879c998 |
| replicaset.apps/ai-console-prod-us-east-1-869c686794 | 0 | 0 | 0 | 5d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-prod-us-east-1,pod-template-hash=869c686794 |
| replicaset.apps/ai-console-prod-us-east-1-89f8ff94c | 0 | 0 | 0 | 277d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.0-85-5507ac3 | app=ai-console-prod-us-east-1,pod-template-hash=89f8ff94c |
| replicaset.apps/ai-console-prod-us-east-1-b9f89644c | 0 | 0 | 0 | 249d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.2-87-92797f3 | app=ai-console-prod-us-east-1,pod-template-hash=b9f89644c |
| replicaset.apps/ai-console-prod-us-east-1-ddbdccbcf | 0 | 0 | 0 | 227d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:12.3.3-88-6cf3090 | app=ai-console-prod-us-east-1,pod-template-hash=ddbdccbcf |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-console-prod-us-east-1 | Deployment/ai-console-prod-us-east-1 | cpu: 13%/70%, memory: 88%/80% | 3 | 6 | 6 | 355d |

---

## Namespace: aisrvhistory-executor-patch

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/aisrvhistory-executor-patch-74c6bcc45f-bc827 | 1/1 | Running | 0 | 3d14h | 10.111.228.227 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-patch-74c6bcc45f-ml8pw | 1/1 | Running | 0 | 3d14h | 10.111.213.125 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-patch-74c6bcc45f-z5mds | 1/1 | Running | 0 | 3d14h | 10.111.154.193 | ip-10-111-186-238.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/aisrvhistory-executor-patch | ClusterIP | 172.20.49.229 | <none> | 8000/TCP | 98d | app=aisrvhistory-executor-patch |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/aisrvhistory-executor-patch | 3/3 | 3 | 3 | 98d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.87 | app=aisrvhistory-executor-patch |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/aisrvhistory-executor-patch-558b595c8 | 0 | 0 | 0 | 56d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.131 | app=aisrvhistory-executor-patch,pod-template-hash=558b595c8 |
| replicaset.apps/aisrvhistory-executor-patch-559855bd84 | 0 | 0 | 0 | 56d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.132 | app=aisrvhistory-executor-patch,pod-template-hash=559855bd84 |
| replicaset.apps/aisrvhistory-executor-patch-64df65b866 | 0 | 0 | 0 | 54d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:PR.647.10 | app=aisrvhistory-executor-patch,pod-template-hash=64df65b866 |
| replicaset.apps/aisrvhistory-executor-patch-699d6c68f4 | 0 | 0 | 0 | 53d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.133 | app=aisrvhistory-executor-patch,pod-template-hash=699d6c68f4 |
| replicaset.apps/aisrvhistory-executor-patch-6d8498c9fb | 0 | 0 | 0 | 54d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:PR.647.15 | app=aisrvhistory-executor-patch,pod-template-hash=6d8498c9fb |
| replicaset.apps/aisrvhistory-executor-patch-6ff64544fb | 0 | 0 | 0 | 12d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.85 | app=aisrvhistory-executor-patch,pod-template-hash=6ff64544fb |
| replicaset.apps/aisrvhistory-executor-patch-748ccc67bd | 0 | 0 | 0 | 54d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:PR.650.17 | app=aisrvhistory-executor-patch,pod-template-hash=748ccc67bd |
| replicaset.apps/aisrvhistory-executor-patch-74c6bcc45f | 3 | 3 | 3 | 3d14h | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.87 | app=aisrvhistory-executor-patch,pod-template-hash=74c6bcc45f |
| replicaset.apps/aisrvhistory-executor-patch-76665579d8 | 0 | 0 | 0 | 60d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.130 | app=aisrvhistory-executor-patch,pod-template-hash=76665579d8 |
| replicaset.apps/aisrvhistory-executor-patch-7bf55db546 | 0 | 0 | 0 | 18d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.135 | app=aisrvhistory-executor-patch,pod-template-hash=7bf55db546 |
| replicaset.apps/aisrvhistory-executor-patch-7c4f54cbb8 | 0 | 0 | 0 | 53d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.134 | app=aisrvhistory-executor-patch,pod-template-hash=7c4f54cbb8 |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-srvhistory-executor-patch-us-east-1 | Deployment/aisrvhistory-executor-patch | cpu: 0%/80%, memory: 16%/70% | 3 | 4 | 3 | 98d |

---

## Namespace: aisrvhistory-executor-prod

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/aisrvhistory-executor-prod-7f5c4cb699-9wcwt | 1/1 | Running | 0 | 4d23h | 10.111.239.194 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-prod-7f5c4cb699-pxgm6 | 1/1 | Running | 0 | 4d23h | 10.111.180.73 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-prod-7f5c4cb699-qsnlh | 1/1 | Running | 0 | 4d23h | 10.111.136.241 | ip-10-111-186-238.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/aisrvhistory-executor-prod | ClusterIP | 172.20.235.88 | <none> | 8000/TCP | 95d | app=aisrvhistory-executor-prod |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/aisrvhistory-executor-prod | 3/3 | 3 | 3 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.85 | app=aisrvhistory-executor-prod |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/aisrvhistory-executor-prod-56447b6766 | 0 | 0 | 0 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.121 | app=aisrvhistory-executor-prod,pod-template-hash=56447b6766 |
| replicaset.apps/aisrvhistory-executor-prod-5b7d74576f | 0 | 0 | 0 | 5d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.85 | app=aisrvhistory-executor-prod,pod-template-hash=5b7d74576f |
| replicaset.apps/aisrvhistory-executor-prod-69cdbb69cd | 0 | 0 | 0 | 60d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.129 | app=aisrvhistory-executor-prod,pod-template-hash=69cdbb69cd |
| replicaset.apps/aisrvhistory-executor-prod-6b86d4f57b | 0 | 0 | 0 | 81d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.124 | app=aisrvhistory-executor-prod,pod-template-hash=6b86d4f57b |
| replicaset.apps/aisrvhistory-executor-prod-6c669464cc | 0 | 0 | 0 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.121 | app=aisrvhistory-executor-prod,pod-template-hash=6c669464cc |
| replicaset.apps/aisrvhistory-executor-prod-6cb8cdd786 | 0 | 0 | 0 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:0.0.66 | app=aisrvhistory-executor-prod,pod-template-hash=6cb8cdd786 |
| replicaset.apps/aisrvhistory-executor-prod-7499b7d5db | 0 | 0 | 0 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:0.0.66 | app=aisrvhistory-executor-prod,pod-template-hash=7499b7d5db |
| replicaset.apps/aisrvhistory-executor-prod-759fc4746c | 0 | 0 | 0 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.121 | app=aisrvhistory-executor-prod,pod-template-hash=759fc4746c |
| replicaset.apps/aisrvhistory-executor-prod-79b94865b | 0 | 0 | 0 | 18d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.135 | app=aisrvhistory-executor-prod,pod-template-hash=79b94865b |
| replicaset.apps/aisrvhistory-executor-prod-7f5c4cb699 | 3 | 3 | 3 | 4d23h | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.85 | app=aisrvhistory-executor-prod,pod-template-hash=7f5c4cb699 |
| replicaset.apps/aisrvhistory-executor-prod-868477bc4 | 0 | 0 | 0 | 48d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:5.0.134 | app=aisrvhistory-executor-prod,pod-template-hash=868477bc4 |

### Horizontal Pod Autoscalers

| Name | Reference | Targets | MinPods | MaxPods | Replicas | Age |
|---|---|---|---|---|---|---|
| horizontalpodautoscaler.autoscaling/ai-srvhistory-executor-prod-us-east-1 | Deployment/aisrvhistory-executor-prod | cpu: 0%/80%, memory: 16%/70% | 3 | 4 | 3 | 95d |

---

## Namespace: ai-ka-patch

### Pods

| Name | Ready | Status | Restarts | Age | IP | Node | Nominated Node | Readiness Gates |
|---|---|---|---|---|---|---|---|---|
| pod/ai-ka-answer-patch-5c77c9f56d-c5fnm | 1/1 | Running | 0 | 11d | 10.111.99.53 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-ka-answer-patch-5c77c9f56d-hqcwm | 1/1 | Running | 0 | 11d | 10.111.166.45 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ai-ka-client-patch-67ff465548-n7ghz | 1/1 | Running | 0 | 11d | 10.111.140.185 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-ka-document-patch-5cd78d5b57-5htxt | 1/1 | Running | 0 | 11d | 10.111.236.4 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ai-ka-document-patch-5cd78d5b57-65w2w | 1/1 | Running | 0 | 11d | 10.111.64.41 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-ka-document-patch-5cd78d5b57-kq28m | 1/1 | Running | 0 | 11d | 10.111.163.108 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-ka-job-patch-6dc78d4457-4bzvf | 1/1 | Running | 0 | 10d | 10.111.96.161 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-ka-max-patch-7dd57df695-lbblq | 1/1 | Running | 0 | 8d | 10.111.131.120 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-ka-max-patch-7dd57df695-zwqlq | 1/1 | Running | 0 | 8d | 10.111.75.125 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/aika-oauth-allinone-patch-5db9ddc679-jltgw | 1/1 | Running | 0 | 11d | 10.111.121.64 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| Name | Type | Cluster IP | External IP | Ports | Age | Selector |
|---|---|---|---|---|---|---|
| service/ai-ka-answer-patch | ClusterIP | 172.20.255.61 | <none> | 8000/TCP | 403d | app=ai-ka-answer-patch |
| service/ai-ka-client-patch | ClusterIP | 172.20.107.51 | <none> | 3000/TCP | 403d | app=ai-ka-client-patch |
| service/ai-ka-document-patch | ClusterIP | 172.20.56.246 | <none> | 8000/TCP | 403d | app=ai-ka-document-patch |
| service/aika-job-allinone-patch | ClusterIP | 172.20.20.223 | <none> | 8080/TCP | 377d | app=aika-job-allinone-patch |
| service/aika-max-allinone-patch | ClusterIP | 172.20.216.250 | <none> | 8080/TCP | 377d | app=aika-max-allinone-patch |
| service/aika-oauth-allinone-patch | ClusterIP | 172.20.98.148 | <none> | 7070/TCP | 403d | app=aika-oauth-allinone-patch |

### Deployments

| Name | Ready | Up-to-date | Available | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| deployment.apps/ai-ka-answer-patch | 2/2 | 2 | 2 | 403d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-patch |
| deployment.apps/ai-ka-client-patch | 1/1 | 1 | 1 | 403d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-patch |
| deployment.apps/ai-ka-document-patch | 3/3 | 3 | 3 | 403d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-patch |
| deployment.apps/ai-ka-job-patch | 1/1 | 1 | 1 | 377d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch |
| deployment.apps/ai-ka-max-patch | 2/2 | 2 | 2 | 377d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-patch |
| deployment.apps/aika-oauth-allinone-patch | 1/1 | 1 | 1 | 403d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-patch |

### ReplicaSets

| Name | Desired | Current | Ready | Age | Containers | Images | Selector |
|---|---|---|---|---|---|---|---|
| replicaset.apps/ai-ka-answer-patch-59665b8fb7 | 0 | 0 | 0 | 77d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.7.6 | app=ai-ka-answer-patch,pod-template-hash=59665b8fb7 |
| replicaset.apps/ai-ka-answer-patch-5c77c9f56d | 2 | 2 | 2 | 11d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-patch,pod-template-hash=5c77c9f56d |
| replicaset.apps/ai-ka-answer-patch-6476dbd579 | 0 | 0 | 0 | 63d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-answer-patch,pod-template-hash=6476dbd579 |
| replicaset.apps/ai-ka-answer-patch-674dcd4bd9 | 0 | 0 | 0 | 145d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.7 | app=ai-ka-answer-patch,pod-template-hash=674dcd4bd9 |
| replicaset.apps/ai-ka-answer-patch-678996997c | 0 | 0 | 0 | 192d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.6 | app=ai-ka-answer-patch,pod-template-hash=678996997c |
| replicaset.apps/ai-ka-answer-patch-6fd698c775 | 0 | 0 | 0 | 82d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-answer-patch,pod-template-hash=6fd698c775 |
| replicaset.apps/ai-ka-answer-patch-7885b7977f | 0 | 0 | 0 | 98d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.16 | app=ai-ka-answer-patch,pod-template-hash=7885b7977f |
| replicaset.apps/ai-ka-answer-patch-78fbd9b6c7 | 0 | 0 | 0 | 18d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-answer-patch,pod-template-hash=78fbd9b6c7 |
| replicaset.apps/ai-ka-answer-patch-8447dfd9c5 | 0 | 0 | 0 | 77d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-answer-patch,pod-template-hash=8447dfd9c5 |
| replicaset.apps/ai-ka-answer-patch-849b967b5 | 0 | 0 | 0 | 266d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.20 | app=ai-ka-answer-patch,pod-template-hash=849b967b5 |
| replicaset.apps/ai-ka-answer-patch-fc98b5d4f | 0 | 0 | 0 | 231d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.21 | app=ai-ka-answer-patch,pod-template-hash=fc98b5d4f |
| replicaset.apps/ai-ka-client-patch-56478f6c6c | 0 | 0 | 0 | 98d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.11 | app=ai-ka-client-patch,pod-template-hash=56478f6c6c |
| replicaset.apps/ai-ka-client-patch-56cdbf4f | 0 | 0 | 0 | 63d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.14 | app=ai-ka-client-patch,pod-template-hash=56cdbf4f |
| replicaset.apps/ai-ka-client-patch-5986955547 | 0 | 0 | 0 | 145d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.4 | app=ai-ka-client-patch,pod-template-hash=5986955547 |
| replicaset.apps/ai-ka-client-patch-5fc489958f | 0 | 0 | 0 | 301d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.4.5 | app=ai-ka-client-patch,pod-template-hash=5fc489958f |
| replicaset.apps/ai-ka-client-patch-6585cc549c | 0 | 0 | 0 | 285d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.4.5 | app=ai-ka-client-patch,pod-template-hash=6585cc549c |
| replicaset.apps/ai-ka-client-patch-67ff465548 | 1 | 1 | 1 | 11d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-patch,pod-template-hash=67ff465548 |
| replicaset.apps/ai-ka-client-patch-6fbc646d4c | 0 | 0 | 0 | 180d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.3 | app=ai-ka-client-patch,pod-template-hash=6fbc646d4c |
| replicaset.apps/ai-ka-client-patch-7b8d646687 | 0 | 0 | 0 | 270d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.4.8 | app=ai-ka-client-patch,pod-template-hash=7b8d646687 |
| replicaset.apps/ai-ka-client-patch-7bf7c65955 | 0 | 0 | 0 | 192d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.2 | app=ai-ka-client-patch,pod-template-hash=7bf7c65955 |
| replicaset.apps/ai-ka-client-patch-84b664bff | 0 | 0 | 0 | 82d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.13 | app=ai-ka-client-patch,pod-template-hash=84b664bff |
| replicaset.apps/ai-ka-client-patch-bb94f4896 | 0 | 0 | 0 | 18d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.14 | app=ai-ka-client-patch,pod-template-hash=bb94f4896 |
| replicaset.apps/ai-ka-document-patch-5484c6959c | 0 | 0 | 0 | 77d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-document-patch,pod-template-hash=5484c6959c |
| replicaset.apps/ai-ka-document-patch-5bc486468f | 0 | 0 | 0 | 98d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.16 | app=ai-ka-document-patch,pod-template-hash=5bc486468f |
| replicaset.apps/ai-ka-document-patch-5cd657ddc4 | 0 | 0 | 0 | 18d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-document-patch,pod-template-hash=5cd657ddc4 |
| replicaset.apps/ai-ka-document-patch-5cd78d5b57 | 3 | 3 | 3 | 11d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-patch,pod-template-hash=5cd78d5b57 |
| replicaset.apps/ai-ka-document-patch-6754c48d9f | 0 | 0 | 0 | 192d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.6 | app=ai-ka-document-patch,pod-template-hash=6754c48d9f |
| replicaset.apps/ai-ka-document-patch-675659ccc5 | 0 | 0 | 0 | 231d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.21 | app=ai-ka-document-patch,pod-template-hash=675659ccc5 |
| replicaset.apps/ai-ka-document-patch-697669fb79 | 0 | 0 | 0 | 266d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.20 | app=ai-ka-document-patch,pod-template-hash=697669fb79 |
| replicaset.apps/ai-ka-document-patch-6fc9b584f7 | 0 | 0 | 0 | 77d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.7.6 | app=ai-ka-document-patch,pod-template-hash=6fc9b584f7 |
| replicaset.apps/ai-ka-document-patch-7fc8f74dc7 | 0 | 0 | 0 | 63d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-document-patch,pod-template-hash=7fc8f74dc7 |
| replicaset.apps/ai-ka-document-patch-9d9f54d8f | 0 | 0 | 0 | 82d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-document-patch,pod-template-hash=9d9f54d8f |
| replicaset.apps/ai-ka-document-patch-dcb9b968c | 0 | 0 | 0 | 145d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.7 | app=ai-ka-document-patch,pod-template-hash=dcb9b968c |
| replicaset.apps/ai-ka-job-patch-59645878b9 | 0 | 0 | 0 | 60d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-job-allinone-patch,pod-template-hash=59645878b9 |
| replicaset.apps/ai-ka-job-patch-5cbf9b66cc | 0 | 0 | 0 | 18d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-job-allinone-patch,pod-template-hash=5cbf9b66cc |
| replicaset.apps/ai-ka-job-patch-5d5c789fb7 | 0 | 0 | 0 | 10d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=5d5c789fb7 |
| replicaset.apps/ai-ka-job-patch-659dc8b4fb | 0 | 0 | 0 | 11d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=659dc8b4fb |
| replicaset.apps/ai-ka-job-patch-684cddfb57 | 0 | 0 | 0 | 10d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=684cddfb57 |
| replicaset.apps/ai-ka-job-patch-68cff4577b | 0 | 0 | 0 | 10d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=68cff4577b |
| replicaset.apps/ai-ka-job-patch-6dc78d4457 | 1 | 1 | 1 | 10d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=6dc78d4457 |
| replicaset.apps/ai-ka-job-patch-75d6cff977 | 0 | 0 | 0 | 82d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-job-allinone-patch,pod-template-hash=75d6cff977 |
| replicaset.apps/ai-ka-job-patch-855b766796 | 0 | 0 | 0 | 81d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-job-allinone-patch,pod-template-hash=855b766796 |
| replicaset.apps/ai-ka-job-patch-859d4bb5bf | 0 | 0 | 0 | 10d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch,pod-template-hash=859d4bb5bf |
| replicaset.apps/ai-ka-job-patch-b685645c5 | 0 | 0 | 0 | 81d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-job-allinone-patch,pod-template-hash=b685645c5 |
| replicaset.apps/ai-ka-max-patch-56c494f57d | 0 | 0 | 0 | 158d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.244 | app=aika-max-allinone-patch,pod-template-hash=56c494f57d |
| replicaset.apps/ai-ka-max-patch-5bb8bd689c | 0 | 0 | 0 | 11d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-patch,pod-template-hash=5bb8bd689c |
| replicaset.apps/ai-ka-max-patch-5f598bc6cb | 0 | 0 | 0 | 82d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-max-allinone-patch,pod-template-hash=5f598bc6cb |
| replicaset.apps/ai-ka-max-patch-65695f7f9d | 0 | 0 | 0 | 145d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.370 | app=aika-max-allinone-patch,pod-template-hash=65695f7f9d |
| replicaset.apps/ai-ka-max-patch-65f8bbb89d | 0 | 0 | 0 | 60d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-max-allinone-patch,pod-template-hash=65f8bbb89d |
| replicaset.apps/ai-ka-max-patch-76d794df6d | 0 | 0 | 0 | 98d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.137 | app=aika-max-allinone-patch,pod-template-hash=76d794df6d |
| replicaset.apps/ai-ka-max-patch-7cd8994f8f | 0 | 0 | 0 | 192d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.142 | app=aika-max-allinone-patch,pod-template-hash=7cd8994f8f |
| replicaset.apps/ai-ka-max-patch-7d875fb647 | 0 | 0 | 0 | 10d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-patch,pod-template-hash=7d875fb647 |
| replicaset.apps/ai-ka-max-patch-7dd57df695 | 2 | 2 | 2 | 8d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-patch,pod-template-hash=7dd57df695 |
| replicaset.apps/ai-ka-max-patch-bb599cf88 | 0 | 0 | 0 | 18d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-max-allinone-patch,pod-template-hash=bb599cf88 |
| replicaset.apps/ai-ka-max-patch-f85b986d9 | 0 | 0 | 0 | 180d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.244 | app=aika-max-allinone-patch,pod-template-hash=f85b986d9 |
| replicaset.apps/aika-oauth-allinone-patch-5db9ddc679 | 1 | 1 | 1 | 11d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-patch,pod-template-hash=5db9ddc679 |
| replicaset.apps/aika-oauth-allinone-patch-6675849857 | 0 | 0 | 0 | 267d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.91 | app=aika-oauth-allinone-patch,pod-template-hash=6675849857 |
| replicaset.apps/aika-oauth-allinone-patch-66985bc7c8 | 0 | 0 | 0 | 270d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.90 | app=aika-oauth-allinone-patch,pod-template-hash=66985bc7c8 |
| replicaset.apps/aika-oauth-allinone-patch-6878c885d8 | 0 | 0 | 0 | 60d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.30 | app=aika-oauth-allinone-patch,pod-template-hash=6878c885d8 |
| replicaset.apps/aika-oauth-allinone-patch-68c64969b4 | 0 | 0 | 0 | 192d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.21 | app=aika-oauth-allinone-patch,pod-template-hash=68c64969b4 |
| replicaset.apps/aika-oauth-allinone-patch-6b49878fd4 | 0 | 0 | 0 | 180d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.36 | app=aika-oauth-allinone-patch,pod-template-hash=6b49878fd4 |
| replicaset.apps/aika-oauth-allinone-patch-79859dd769 | 0 | 0 | 0 | 188d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.22 | app=aika-oauth-allinone-patch,pod-template-hash=79859dd769 |
| replicaset.apps/aika-oauth-allinone-patch-79dcbc78dc | 0 | 0 | 0 | 82d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.26 | app=aika-oauth-allinone-patch,pod-template-hash=79dcbc78dc |
| replicaset.apps/aika-oauth-allinone-patch-7b678769b7 | 0 | 0 | 0 | 145d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.50 | app=aika-oauth-allinone-patch,pod-template-hash=7b678769b7 |
| replicaset.apps/aika-oauth-allinone-patch-7f4b56648c | 0 | 0 | 0 | 231d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.93 | app=aika-oauth-allinone-patch,pod-template-hash=7f4b56648c |
| replicaset.apps/aika-oauth-allinone-patch-d46fc5454 | 0 | 0 | 0 | 98d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.21 | app=aika-oauth-allinone-patch,pod-template-hash=d46fc5454 |
