# Kubernetes Resource Summary

## Namespace: ai-analytics-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-analytics-patch-7c8cb65887-8zx7h | 1/1 | Running | 0 | 4d2h | 10.111.222.106 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-analytics-patch | ClusterIP | 172.20.206.63 | <none> | 8000/TCP | 403d | app=ai-analytics-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-analytics-patch | 1/1 | 1 | 1 | 403d | ai-analytics-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.19 | app=ai-analytics-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-analytics-patch | Deployment/ai-analytics-patch | cpu: 0%/80%, memory: 68%/80% | 1 | 2 | 1 | 403d |

---

## Namespace: ai-analytics-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-analytics-prod-54565d67d4-2mz5m | 1/1 | Running | 0 | 11h | 10.111.118.240 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-lhxrv | 1/1 | Running | 0 | 4d23h | 10.111.201.250 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-m2v2h | 1/1 | Running | 0 | 4d23h | 10.111.255.248 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ai-analytics-prod-54565d67d4-mz5dk | 1/1 | Running | 0 | 4d23h | 10.111.228.190 | ip-10-111-238-32.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-analytics-prod | ClusterIP | 172.20.26.92 | <none> | 8000/TCP | 403d | app=ai-analytics-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-analytics-prod | 4/4 | 4 | 4 | 403d | ai-analytics-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-analyticservice:6.0.15 | app=ai-analytics-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-analytics-prod | Deployment/ai-analytics-prod | cpu: 0%/80%, memory: 92%/80% | 2 | 4 | 4 | 403d |

---

## Namespace: ai-console-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-console-patch-us-east-1-7ffd8954d7-7tmrq | 1/1 | Running | 0 | 11d | 10.111.178.124 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-h9jhh | 1/1 | Running | 0 | 7d17h | 10.111.129.45 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-nbl6r | 1/1 | Running | 0 | 11d | 10.111.102.185 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-p24cb | 1/1 | Running | 0 | 11d | 10.111.72.88 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-qg7hb | 1/1 | Running | 0 | 11d | 10.111.248.190 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-console-patch-us-east-1-7ffd8954d7-vmzqf | 1/1 | Running | 0 | 11d | 10.111.205.136 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-console-patch-us-east-1 | ClusterIP | 172.20.173.236 | <none> | 5000/TCP | 404d | app=ai-console-patch-us-east-1 |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-console-patch-us-east-1 | 6/6 | 6 | 6 | 404d | ai-console-patch-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-patch-us-east-1 |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-console-patch-us-east-1 | Deployment/ai-console-patch-us-east-1 | cpu: 14%/70%, memory: 91%/80% | 3 | 6 | 6 | 355d |

---

## Namespace: ai-console-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-console-prod-us-east-1-844879c998-62fb4 | 1/1 | Running | 0 | 4d23h | 10.111.103.190 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-cpst5 | 1/1 | Running | 0 | 4d23h | 10.111.202.177 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-gw4jh | 1/1 | Running | 0 | 4d23h | 10.111.172.238 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-hqvbm | 1/1 | Running | 0 | 4d23h | 10.111.169.35 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-r6prb | 1/1 | Running | 0 | 47h | 10.111.115.74 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ai-console-prod-us-east-1-844879c998-z2lxx | 1/1 | Running | 0 | 4d23h | 10.111.203.154 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-console-prod-us-east-1 | ClusterIP | 172.20.224.198 | <none> | 5000/TCP | 404d | app=ai-console-prod-us-east-1 |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-console-prod-us-east-1 | 6/6 | 6 | 6 | 395d | ai-console-prod-us-east-1 | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-console:14.0.0-105-172014f | app=ai-console-prod-us-east-1 |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-console-prod-us-east-1 | Deployment/ai-console-prod-us-east-1 | cpu: 13%/70%, memory: 88%/80% | 3 | 6 | 6 | 355d |

---

## Namespace: ai-executor-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisrvhistory-executor-patch-74c6bcc45f-bc827 | 1/1 | Running | 0 | 3d14h | 10.111.228.227 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-patch-74c6bcc45f-ml8pw | 1/1 | Running | 0 | 3d14h | 10.111.213.125 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-patch-74c6bcc45f-z5mds | 1/1 | Running | 0 | 3d14h | 10.111.154.193 | ip-10-111-186-238.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisrvhistory-executor-patch | ClusterIP | 172.20.49.229 | <none> | 8000/TCP | 98d | app=aisrvhistory-executor-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisrvhistory-executor-patch | 3/3 | 3 | 3 | 98d | aisrvhistory-executor-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.87 | app=aisrvhistory-executor-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-executor-patch-us-east-1 | Deployment/aisrvhistory-executor-patch | cpu: 0%/80%, memory: 16%/70% | 3 | 4 | 3 | 98d |

---

## Namespace: ai-executor-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisrvhistory-executor-prod-7f5c4cb699-9wcwt | 1/1 | Running | 0 | 4d23h | 10.111.239.194 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-prod-7f5c4cb699-pxgm6 | 1/1 | Running | 0 | 4d23h | 10.111.180.73 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/aisrvhistory-executor-prod-7f5c4cb699-qsnlh | 1/1 | Running | 0 | 4d23h | 10.111.136.241 | ip-10-111-186-238.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisrvhistory-executor-prod | ClusterIP | 172.20.235.88 | <none> | 8000/TCP | 95d | app=aisrvhistory-executor-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisrvhistory-executor-prod | 3/3 | 3 | 3 | 95d | aisrvhistory-executor-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-executor:6.0.85 | app=aisrvhistory-executor-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-executor-prod-us-east-1 | Deployment/aisrvhistory-executor-prod | cpu: 0%/80%, memory: 16%/70% | 3 | 4 | 3 | 95d |

---

## Namespace: ai-ka-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
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

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-ka-answer-patch | ClusterIP | 172.20.255.61 | <none> | 8000/TCP | 403d | app=ai-ka-answer-patch |
| service/ai-ka-client-patch | ClusterIP | 172.20.107.51 | <none> | 3000/TCP | 403d | app=ai-ka-client-patch |
| service/ai-ka-document-patch | ClusterIP | 172.20.56.246 | <none> | 8000/TCP | 403d | app=ai-ka-document-patch |
| service/aika-job-allinone-patch | ClusterIP | 172.20.20.223 | <none> | 8080/TCP | 377d | app=aika-job-allinone-patch |
| service/aika-max-allinone-patch | ClusterIP | 172.20.216.250 | <none> | 8080/TCP | 377d | app=aika-max-allinone-patch |
| service/aika-oauth-allinone-patch | ClusterIP | 172.20.98.148 | <none> | 7070/TCP | 403d | app=aika-oauth-allinone-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-ka-answer-patch | 2/2 | 2 | 2 | 403d | ai-ka-answer-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-patch |
| deployment.apps/ai-ka-client-patch | 1/1 | 1 | 1 | 403d | ai-ka-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-patch |
| deployment.apps/ai-ka-document-patch | 3/3 | 3 | 3 | 403d | ai-ka-document-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-patch |
| deployment.apps/ai-ka-job-patch | 1/1 | 1 | 1 | 377d | ai-ka-job-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-patch |
| deployment.apps/ai-ka-max-patch | 2/2 | 2 | 2 | 377d | ai-ka-max-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-patch |
| deployment.apps/aika-oauth-allinone-patch | 1/1 | 1 | 1 | 403d | ai-ka-oauth-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
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

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-ka-answer-patch-us-east-1 | Deployment/ai-ka-answer-patch | cpu: 5%/80% | 2 | 3 | 2 | 403d |
| horizontalpodautoscaler.autoscaling/ai-ka-document-patch-us-east-1 | Deployment/ai-ka-document-patch | cpu: 4%/60% | 3 | 24 | 3 | 403d |

---

## Namespace: ai-ka-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-ka-answer-prod-9cd587886-7bvxf | 1/1 | Running | 0 | 4d23h | 10.111.70.189 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-ka-answer-prod-9cd587886-7xfqs | 1/1 | Running | 0 | 4d23h | 10.111.245.254 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-ka-client-prod-86bdb875b6-9w2j4 | 1/1 | Running | 0 | 4d23h | 10.111.163.153 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-ka-document-prod-7dfd77b7f5-6mvm8 | 1/1 | Running | 0 | 4d23h | 10.111.105.213 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-ka-document-prod-7dfd77b7f5-gw282 | 1/1 | Running | 0 | 4d23h | 10.111.138.208 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-ka-document-prod-7dfd77b7f5-rvns6 | 1/1 | Running | 0 | 4d23h | 10.111.158.45 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ai-ka-job-prod-76bd69c76d-mzf5c | 1/1 | Running | 0 | 4d23h | 10.111.185.22 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-ka-max-prod-66bb4f65f7-5qs7b | 1/1 | Running | 0 | 4d23h | 10.111.200.64 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-ka-max-prod-66bb4f65f7-hdb9v | 1/1 | Running | 0 | 4d23h | 10.111.161.188 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/aika-oauth-allinone-prod-5c954c9b54-twscm | 1/1 | Running | 0 | 4d23h | 10.111.113.206 | ip-10-111-65-28.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-ka-answer-prod | ClusterIP | 172.20.84.146 | <none> | 8000/TCP | 395d | app=ai-ka-answer-prod |
| service/ai-ka-client-prod | ClusterIP | 172.20.17.1 | <none> | 3000/TCP | 395d | app=ai-ka-client-prod |
| service/ai-ka-document-prod | ClusterIP | 172.20.116.125 | <none> | 8000/TCP | 395d | app=ai-ka-document-prod |
| service/aika-job-allinone-prod | ClusterIP | 172.20.253.193 | <none> | 8080/TCP | 395d | app=aika-job-allinone-prod |
| service/aika-max-allinone-prod | ClusterIP | 172.20.27.184 | <none> | 8080/TCP | 395d | app=aika-max-allinone-prod |
| service/aika-oauth-allinone-prod | ClusterIP | 172.20.148.54 | <none> | 7070/TCP | 395d | app=aika-oauth-allinone-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-ka-answer-prod | 2/2 | 2 | 2 | 395d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-prod |
| deployment.apps/ai-ka-client-prod | 1/1 | 1 | 1 | 395d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-prod |
| deployment.apps/ai-ka-document-prod | 3/3 | 3 | 3 | 395d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-prod |
| deployment.apps/ai-ka-job-prod | 1/1 | 1 | 1 | 395d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-prod |
| deployment.apps/ai-ka-max-prod | 2/2 | 2 | 2 | 395d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-prod |
| deployment.apps/aika-oauth-allinone-prod | 1/1 | 1 | 1 | 395d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/ai-ka-answer-prod-558b9dd566 | 0 | 0 | 0 | 262d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.20 | app=ai-ka-answer-prod,pod-template-hash=558b9dd566 |
| replicaset.apps/ai-ka-answer-prod-5f8b8fdcf6 | 0 | 0 | 0 | 136d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.7 | app=ai-ka-answer-prod,pod-template-hash=5f8b8fdcf6 |
| replicaset.apps/ai-ka-answer-prod-5f9d49dcfc | 0 | 0 | 0 | 5d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-prod,pod-template-hash=5f9d49dcfc |
| replicaset.apps/ai-ka-answer-prod-6c748576d6 | 0 | 0 | 0 | 227d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.21 | app=ai-ka-answer-prod,pod-template-hash=6c748576d6 |
| replicaset.apps/ai-ka-answer-prod-6f8dcf49cd | 0 | 0 | 0 | 95d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.16 | app=ai-ka-answer-prod,pod-template-hash=6f8dcf49cd |
| replicaset.apps/ai-ka-answer-prod-6f9f899b5d | 0 | 0 | 0 | 279d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.17 | app=ai-ka-answer-prod,pod-template-hash=6f9f899b5d |
| replicaset.apps/ai-ka-answer-prod-79f578b854 | 0 | 0 | 0 | 48d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-answer-prod,pod-template-hash=79f578b854 |
| replicaset.apps/ai-ka-answer-prod-8cdc4cdd4 | 0 | 0 | 0 | 370d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.3.31 | app=ai-ka-answer-prod,pod-template-hash=8cdc4cdd4 |
| replicaset.apps/ai-ka-answer-prod-9cd587886 | 2 | 2 | 2 | 4d23h | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-answer-prod,pod-template-hash=9cd587886 |
| replicaset.apps/ai-ka-answer-prod-cf94776db | 0 | 0 | 0 | 81d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-answer-prod,pod-template-hash=cf94776db |
| replicaset.apps/ai-ka-answer-prod-d5f79f474 | 0 | 0 | 0 | 188d | ai-ka-answer-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.6 | app=ai-ka-answer-prod,pod-template-hash=d5f79f474 |
| replicaset.apps/ai-ka-client-prod-557fb9f944 | 0 | 0 | 0 | 370d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.3.11 | app=ai-ka-client-prod,pod-template-hash=557fb9f944 |
| replicaset.apps/ai-ka-client-prod-57654d5968 | 0 | 0 | 0 | 279d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.4.5 | app=ai-ka-client-prod,pod-template-hash=57654d5968 |
| replicaset.apps/ai-ka-client-prod-588b7f8b68 | 0 | 0 | 0 | 188d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.2 | app=ai-ka-client-prod,pod-template-hash=588b7f8b68 |
| replicaset.apps/ai-ka-client-prod-5bf99df8c6 | 0 | 0 | 0 | 81d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.13 | app=ai-ka-client-prod,pod-template-hash=5bf99df8c6 |
| replicaset.apps/ai-ka-client-prod-5fbb595cb | 0 | 0 | 0 | 48d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.14 | app=ai-ka-client-prod,pod-template-hash=5fbb595cb |
| replicaset.apps/ai-ka-client-prod-668d478d96 | 0 | 0 | 0 | 136d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.4 | app=ai-ka-client-prod,pod-template-hash=668d478d96 |
| replicaset.apps/ai-ka-client-prod-67f5cc5b44 | 0 | 0 | 0 | 179d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.5.3 | app=ai-ka-client-prod,pod-template-hash=67f5cc5b44 |
| replicaset.apps/ai-ka-client-prod-79975b8968 | 0 | 0 | 0 | 95d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.6.11 | app=ai-ka-client-prod,pod-template-hash=79975b8968 |
| replicaset.apps/ai-ka-client-prod-7b78688f68 | 0 | 0 | 0 | 262d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:0.4.8 | app=ai-ka-client-prod,pod-template-hash=7b78688f68 |
| replicaset.apps/ai-ka-client-prod-86bdb875b6 | 1 | 1 | 1 | 4d23h | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-prod,pod-template-hash=86bdb875b6 |
| replicaset.apps/ai-ka-client-prod-8fdff6f5c | 0 | 0 | 0 | 5d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-client:1.0.3 | app=ai-ka-client-prod,pod-template-hash=8fdff6f5c |
| replicaset.apps/ai-ka-document-prod-56bffbdfbd | 0 | 0 | 0 | 5d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-prod,pod-template-hash=56bffbdfbd |
| replicaset.apps/ai-ka-document-prod-586c5f565 | 0 | 0 | 0 | 279d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.17 | app=ai-ka-document-prod,pod-template-hash=586c5f565 |
| replicaset.apps/ai-ka-document-prod-5c59ddb5df | 0 | 0 | 0 | 48d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.19 | app=ai-ka-document-prod,pod-template-hash=5c59ddb5df |
| replicaset.apps/ai-ka-document-prod-67d846c8b9 | 0 | 0 | 0 | 95d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.16 | app=ai-ka-document-prod,pod-template-hash=67d846c8b9 |
| replicaset.apps/ai-ka-document-prod-6cdb98b789 | 0 | 0 | 0 | 262d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.20 | app=ai-ka-document-prod,pod-template-hash=6cdb98b789 |
| replicaset.apps/ai-ka-document-prod-7874bd5f97 | 0 | 0 | 0 | 227d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.4.21 | app=ai-ka-document-prod,pod-template-hash=7874bd5f97 |
| replicaset.apps/ai-ka-document-prod-7b4fd45c57 | 0 | 0 | 0 | 81d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.6.18 | app=ai-ka-document-prod,pod-template-hash=7b4fd45c57 |
| replicaset.apps/ai-ka-document-prod-7d488d988c | 0 | 0 | 0 | 136d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.7 | app=ai-ka-document-prod,pod-template-hash=7d488d988c |
| replicaset.apps/ai-ka-document-prod-7dfd77b7f5 | 3 | 3 | 3 | 4d23h | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:1.0.7 | app=ai-ka-document-prod,pod-template-hash=7dfd77b7f5 |
| replicaset.apps/ai-ka-document-prod-b49f966fc | 0 | 0 | 0 | 370d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.3.31 | app=ai-ka-document-prod,pod-template-hash=b49f966fc |
| replicaset.apps/ai-ka-document-prod-bdb66cb49 | 0 | 0 | 0 | 188d | ai-ka-document-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka:0.5.6 | app=ai-ka-document-prod,pod-template-hash=bdb66cb49 |
| replicaset.apps/ai-ka-job-prod-54c88d95cd | 0 | 0 | 0 | 81d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-job-allinone-prod,pod-template-hash=54c88d95cd |
| replicaset.apps/ai-ka-job-prod-55f9697544 | 0 | 0 | 0 | 179d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.244 | app=aika-job-allinone-prod,pod-template-hash=55f9697544 |
| replicaset.apps/ai-ka-job-prod-5777d67764 | 0 | 0 | 0 | 227d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.781 | app=aika-job-allinone-prod,pod-template-hash=5777d67764 |
| replicaset.apps/ai-ka-job-prod-584584b6f8 | 0 | 0 | 0 | 95d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.137 | app=aika-job-allinone-prod,pod-template-hash=584584b6f8 |
| replicaset.apps/ai-ka-job-prod-6cb4cc74d4 | 0 | 0 | 0 | 188d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.142 | app=aika-job-allinone-prod,pod-template-hash=6cb4cc74d4 |
| replicaset.apps/ai-ka-job-prod-6d6669684d | 0 | 0 | 0 | 279d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.674 | app=aika-job-allinone-prod,pod-template-hash=6d6669684d |
| replicaset.apps/ai-ka-job-prod-76bd69c76d | 1 | 1 | 1 | 4d23h | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-prod,pod-template-hash=76bd69c76d |
| replicaset.apps/ai-ka-job-prod-78dbf9ccc6 | 0 | 0 | 0 | 262d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.778 | app=aika-job-allinone-prod,pod-template-hash=78dbf9ccc6 |
| replicaset.apps/ai-ka-job-prod-7c89dd9968 | 0 | 0 | 0 | 136d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.370 | app=aika-job-allinone-prod,pod-template-hash=7c89dd9968 |
| replicaset.apps/ai-ka-job-prod-7c955ccf6 | 0 | 0 | 0 | 48d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-job-allinone-prod,pod-template-hash=7c955ccf6 |
| replicaset.apps/ai-ka-job-prod-7cbb4fbb69 | 0 | 0 | 0 | 5d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-job-allinone-prod,pod-template-hash=7cbb4fbb69 |
| replicaset.apps/ai-ka-max-prod-56fdf4b56c | 0 | 0 | 0 | 227d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.781 | app=aika-max-allinone-prod,pod-template-hash=56fdf4b56c |
| replicaset.apps/ai-ka-max-prod-6678c6647c | 0 | 0 | 0 | 188d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.142 | app=aika-max-allinone-prod,pod-template-hash=6678c6647c |
| replicaset.apps/ai-ka-max-prod-66bb4f65f7 | 2 | 2 | 2 | 4d23h | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-prod,pod-template-hash=66bb4f65f7 |
| replicaset.apps/ai-ka-max-prod-68459545df | 0 | 0 | 0 | 48d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.147 | app=aika-max-allinone-prod,pod-template-hash=68459545df |
| replicaset.apps/ai-ka-max-prod-695ff87d44 | 0 | 0 | 0 | 4d23h | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.2.0.124 | app=aika-max-allinone-prod,pod-template-hash=695ff87d44 |
| replicaset.apps/ai-ka-max-prod-779bc47 | 0 | 0 | 0 | 136d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.370 | app=aika-max-allinone-prod,pod-template-hash=779bc47 |
| replicaset.apps/ai-ka-max-prod-7c4797fdc | 0 | 0 | 0 | 81d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.141 | app=aika-max-allinone-prod,pod-template-hash=7c4797fdc |
| replicaset.apps/ai-ka-max-prod-7df4d678bc | 0 | 0 | 0 | 262d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.778 | app=aika-max-allinone-prod,pod-template-hash=7df4d678bc |
| replicaset.apps/ai-ka-max-prod-7f8fb6965 | 0 | 0 | 0 | 279d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.1.0.674 | app=aika-max-allinone-prod,pod-template-hash=7f8fb6965 |
| replicaset.apps/ai-ka-max-prod-d48966cc9 | 0 | 0 | 0 | 179d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:25.3.0.244 | app=aika-max-allinone-prod,pod-template-hash=d48966cc9 |
| replicaset.apps/ai-ka-max-prod-fdfc87cbf | 0 | 0 | 0 | 95d | max | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-max:26.1.0.137 | app=aika-max-allinone-prod,pod-template-hash=fdfc87cbf |
| replicaset.apps/aika-oauth-allinone-prod-5655975644 | 0 | 0 | 0 | 188d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.22 | app=aika-oauth-allinone-prod,pod-template-hash=5655975644 |
| replicaset.apps/aika-oauth-allinone-prod-5955d4d48b | 0 | 0 | 0 | 48d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.30 | app=aika-oauth-allinone-prod,pod-template-hash=5955d4d48b |
| replicaset.apps/aika-oauth-allinone-prod-59f98d97c9 | 0 | 0 | 0 | 179d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.36 | app=aika-oauth-allinone-prod,pod-template-hash=59f98d97c9 |
| replicaset.apps/aika-oauth-allinone-prod-5c954c9b54 | 1 | 1 | 1 | 4d23h | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-prod,pod-template-hash=5c954c9b54 |
| replicaset.apps/aika-oauth-allinone-prod-5cf94d6b4c | 0 | 0 | 0 | 4d23h | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.2.0.14 | app=aika-oauth-allinone-prod,pod-template-hash=5cf94d6b4c |
| replicaset.apps/aika-oauth-allinone-prod-6444c8845f | 0 | 0 | 0 | 136d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.3.0.50 | app=aika-oauth-allinone-prod,pod-template-hash=6444c8845f |
| replicaset.apps/aika-oauth-allinone-prod-65cdd847bd | 0 | 0 | 0 | 262d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.91 | app=aika-oauth-allinone-prod,pod-template-hash=65cdd847bd |
| replicaset.apps/aika-oauth-allinone-prod-7646669567 | 0 | 0 | 0 | 81d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.26 | app=aika-oauth-allinone-prod,pod-template-hash=7646669567 |
| replicaset.apps/aika-oauth-allinone-prod-7ddf76958f | 0 | 0 | 0 | 279d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.76 | app=aika-oauth-allinone-prod,pod-template-hash=7ddf76958f |
| replicaset.apps/aika-oauth-allinone-prod-b54447cdb | 0 | 0 | 0 | 227d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:25.1.0.93 | app=aika-oauth-allinone-prod,pod-template-hash=b54447cdb |
| replicaset.apps/aika-oauth-allinone-prod-d54db574d | 0 | 0 | 0 | 95d | oauth | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-ka-oauth:26.1.0.21 | app=aika-oauth-allinone-prod,pod-template-hash=d54db574d |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-ka-answer-prod-us-east-1 | Deployment/ai-ka-answer-prod | cpu: 5%/80% | 2 | 3 | 2 | 395d |
| horizontalpodautoscaler.autoscaling/ai-ka-document-prod-us-east-1 | Deployment/ai-ka-document-prod | cpu: 4%/60% | 3 | 24 | 3 | 395d |

---

## Namespace: ai-troubleshooting-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-sidp-patch-85d498f768-2mksf | 1/1 | Running | 0 | 2d22h | 10.111.70.253 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ai-sidp-patch-85d498f768-cfn6w | 1/1 | Running | 0 | 2d22h | 10.111.140.112 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-sidp-patch-85d498f768-x6fvj | 1/1 | Running | 0 | 2d22h | 10.111.196.93 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-troubleshooting-agent-patch-6cb54c96f7-6rlq6 | 1/1 | Running | 0 | 7d15h | 10.111.95.138 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ai-troubleshooting-agent-patch-6cb54c96f7-n79wn | 1/1 | Running | 0 | 7d15h | 10.111.202.144 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-sidp-patch | ClusterIP | 172.20.60.213 | <none> | 8000/TCP | 14d | app=ai-sidp-patch |
| service/ai-troubleshooting-agent-patch | ClusterIP | 172.20.97.47 | <none> | 8000/TCP | 13d | app=ai-troubleshooting-agent-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-sidp-patch | 3/3 | 3 | 3 | 14d | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.75 | app=ai-sidp-patch |
| deployment.apps/ai-troubleshooting-agent-patch | 2/2 | 2 | 2 | 13d | ai-troubleshooting-agent-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/ai-sidp-patch-6d49d798d5 | 0 | 0 | 0 | 14d | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:0.0.52 | app=ai-sidp-patch,pod-template-hash=6d49d798d5 |
| replicaset.apps/ai-sidp-patch-76f8756f8b | 0 | 0 | 0 | 11d | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.74 | app=ai-sidp-patch,pod-template-hash=76f8756f8b |
| replicaset.apps/ai-sidp-patch-7c9847cd | 0 | 0 | 0 | 7d15h | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.74 | app=ai-sidp-patch,pod-template-hash=7c9847cd |
| replicaset.apps/ai-sidp-patch-85d498f768 | 3 | 3 | 3 | 2d22h | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.75 | app=ai-sidp-patch,pod-template-hash=85d498f768 |
| replicaset.apps/ai-sidp-patch-cfc687677 | 0 | 0 | 0 | 13d | ai-sidp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:0.0.72 | app=ai-sidp-patch,pod-template-hash=cfc687677 |
| replicaset.apps/ai-troubleshooting-agent-patch-6cb54c96f7 | 2 | 2 | 2 | 7d15h | ai-troubleshooting-agent-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-patch,pod-template-hash=6cb54c96f7 |
| replicaset.apps/ai-troubleshooting-agent-patch-6d746cd7f | 0 | 0 | 0 | 12d | ai-troubleshooting-agent-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-patch,pod-template-hash=6d746cd7f |
| replicaset.apps/ai-troubleshooting-agent-patch-77458b9b7 | 0 | 0 | 0 | 13d | ai-troubleshooting-agent-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:0.0.36 | app=ai-troubleshooting-agent-patch,pod-template-hash=77458b9b7 |
| replicaset.apps/ai-troubleshooting-agent-patch-cb89dc64c | 0 | 0 | 0 | 13d | ai-troubleshooting-agent-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:0.0.42 | app=ai-troubleshooting-agent-patch,pod-template-hash=cb89dc64c |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-sidp-patch-us-east-1 | Deployment/ai-sidp-patch | cpu: 1%/80%, memory: 91%/70% | 1 | 3 | 3 | 14d |
| horizontalpodautoscaler.autoscaling/ai-troubleshooting-agent-patch-us-east-1 | Deployment/ai-troubleshooting-agent-patch | cpu: 2%/80%, memory: 31%/70% | 2 | 3 | 2 | 13d |

---

## Namespace: ai-troubleshooting-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-sidp-prod-6c56cf586d-4xbcz | 1/1 | Running | 0 | 4d23h | 10.111.183.60 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ai-sidp-prod-6c56cf586d-9nrbg | 1/1 | Running | 0 | 4d23h | 10.111.129.114 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ai-sidp-prod-6c56cf586d-fwpjr | 1/1 | Running | 0 | 4d23h | 10.111.155.36 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ai-troubleshooting-agent-prod-56c4944d75-b5mr7 | 1/1 | Running | 0 | 4d23h | 10.111.65.157 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ai-troubleshooting-agent-prod-56c4944d75-cgnsv | 1/1 | Running | 0 | 4d23h | 10.111.125.27 | ip-10-111-65-28.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-sidp-prod | ClusterIP | 172.20.179.252 | <none> | 8000/TCP | 5d2h | app=ai-sidp-prod |
| service/ai-troubleshooting-agent-prod | ClusterIP | 172.20.125.145 | <none> | 8000/TCP | 5d2h | app=ai-troubleshooting-agent-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-sidp-prod | 3/3 | 3 | 3 | 5d2h | ai-sidp-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.74 | app=ai-sidp-prod |
| deployment.apps/ai-troubleshooting-agent-prod | 2/2 | 2 | 2 | 5d2h | ai-troubleshooting-agent-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/ai-sidp-prod-6c56cf586d | 3 | 3 | 3 | 4d23h | ai-sidp-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.74 | app=ai-sidp-prod,pod-template-hash=6c56cf586d |
| replicaset.apps/ai-sidp-prod-8c5f85846 | 0 | 0 | 0 | 5d2h | ai-sidp-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-service-intelligence-dp:6.0.74 | app=ai-sidp-prod,pod-template-hash=8c5f85846 |
| replicaset.apps/ai-troubleshooting-agent-prod-56c4944d75 | 2 | 2 | 2 | 4d23h | ai-troubleshooting-agent-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-prod,pod-template-hash=56c4944d75 |
| replicaset.apps/ai-troubleshooting-agent-prod-8b8498945 | 0 | 0 | 0 | 5d2h | ai-troubleshooting-agent-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-troubleshooting-agent:6.0.43 | app=ai-troubleshooting-agent-prod,pod-template-hash=8b8498945 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-sidp-prod-us-east-1 | Deployment/ai-sidp-prod | cpu: 0%/80%, memory: 89%/70% | 1 | 3 | 3 | 5d2h |
| horizontalpodautoscaler.autoscaling/ai-troubleshooting-agent-prod-us-east-1 | Deployment/ai-troubleshooting-agent-prod | cpu: 3%/80%, memory: 31%/70% | 2 | 3 | 2 | 5d2h |

---

## Namespace: aiassethub-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aiassethub-patch-6c95bfb8f8-j4ncm | 1/1 | Running | 0 | 12h | 10.111.138.162 | ip-10-111-173-237.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aiassethub-patch | ClusterIP | 172.20.121.90 | <none> | 8000/TCP | 238d | app=aiassethub-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aiassethub-patch | 1/1 | 1 | 1 | 238d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.26 | app=aiassethub-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aiassethub-patch-58cffc5d77 | 0 | 0 | 0 | 98d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:3.0.80 | app=aiassethub-patch,pod-template-hash=58cffc5d77 |
| replicaset.apps/aiassethub-patch-6654cdc4d5 | 0 | 0 | 0 | 63d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.29 | app=aiassethub-patch,pod-template-hash=6654cdc4d5 |
| replicaset.apps/aiassethub-patch-66d74fdb6f | 0 | 0 | 0 | 19d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.31 | app=aiassethub-patch,pod-template-hash=66d74fdb6f |
| replicaset.apps/aiassethub-patch-67bf586dd5 | 0 | 0 | 0 | 62d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.30 | app=aiassethub-patch,pod-template-hash=67bf586dd5 |
| replicaset.apps/aiassethub-patch-69698b6cdf | 0 | 0 | 0 | 12d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.23 | app=aiassethub-patch,pod-template-hash=69698b6cdf |
| replicaset.apps/aiassethub-patch-6c95bfb8f8 | 1 | 1 | 1 | 12h | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.26 | app=aiassethub-patch,pod-template-hash=6c95bfb8f8 |
| replicaset.apps/aiassethub-patch-7589494966 | 0 | 0 | 0 | 2d22h | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.25 | app=aiassethub-patch,pod-template-hash=7589494966 |
| replicaset.apps/aiassethub-patch-77db7c756d | 0 | 0 | 0 | 151d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:3.0.79 | app=aiassethub-patch,pod-template-hash=77db7c756d |
| replicaset.apps/aiassethub-patch-7d8d4df5cc | 0 | 0 | 0 | 90d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.28 | app=aiassethub-patch,pod-template-hash=7d8d4df5cc |
| replicaset.apps/aiassethub-patch-9d495f49c | 0 | 0 | 0 | 98d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.25 | app=aiassethub-patch,pod-template-hash=9d495f49c |
| replicaset.apps/aiassethub-patch-fbd65c4cb | 0 | 0 | 0 | 151d | aiassethub-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:3.0.80 | app=aiassethub-patch,pod-template-hash=fbd65c4cb |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aiassethub-patch-us-east-1 | Deployment/aiassethub-patch | cpu: 1%/80%, memory: 15%/70% | 1 | 2 | 1 | 238d |

---

## Namespace: aiassethub-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aiassethub-prod-85d456df47-5brp8 | 1/1 | Running | 0 | 4d | 10.111.196.174 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aiassethub-prod | ClusterIP | 172.20.10.167 | <none> | 8000/TCP | 238d | app=aiassethub-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aiassethub-prod | 1/1 | 1 | 1 | 238d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.23 | app=aiassethub-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aiassethub-prod-5cb4b46d89 | 0 | 0 | 0 | 53d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.30 | app=aiassethub-prod,pod-template-hash=5cb4b46d89 |
| replicaset.apps/aiassethub-prod-69c5b8484f | 0 | 0 | 0 | 225d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:0.0.45 | app=aiassethub-prod,pod-template-hash=69c5b8484f |
| replicaset.apps/aiassethub-prod-6dc66f698f | 0 | 0 | 0 | 136d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:3.0.80 | app=aiassethub-prod,pod-template-hash=6dc66f698f |
| replicaset.apps/aiassethub-prod-6f6d76bbb5 | 0 | 0 | 0 | 193d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:0.0.69 | app=aiassethub-prod,pod-template-hash=6f6d76bbb5 |
| replicaset.apps/aiassethub-prod-7965b8fb6f | 0 | 0 | 0 | 81d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.28 | app=aiassethub-prod,pod-template-hash=7965b8fb6f |
| replicaset.apps/aiassethub-prod-7c98759fd7 | 0 | 0 | 0 | 4d23h | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.31 | app=aiassethub-prod,pod-template-hash=7c98759fd7 |
| replicaset.apps/aiassethub-prod-84b45d9c5c | 0 | 0 | 0 | 95d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.25 | app=aiassethub-prod,pod-template-hash=84b45d9c5c |
| replicaset.apps/aiassethub-prod-85d456df47 | 1 | 1 | 1 | 4d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:5.0.23 | app=aiassethub-prod,pod-template-hash=85d456df47 |
| replicaset.apps/aiassethub-prod-88d9bd5b9 | 0 | 0 | 0 | 238d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:0.0.40 | app=aiassethub-prod,pod-template-hash=88d9bd5b9 |
| replicaset.apps/aiassethub-prod-dc595b84f | 0 | 0 | 0 | 17d | aiassethub-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-assethub:4.0.31 | app=aiassethub-prod,pod-template-hash=dc595b84f |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aiassethub-prod-us-east-1 | Deployment/aiassethub-prod | cpu: 3%/80%, memory: 17%/70% | 1 | 2 | 1 | 238d |

---

## Namespace: aiconfig-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aiconfig-patch-fd74bddf9-7w7rh | 1/1 | Running | 0 | 4d1h | 10.111.74.109 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/aiconfig-patch-fd74bddf9-9msqw | 1/1 | Running | 0 | 4d1h | 10.111.230.248 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/aiconfig-patch-fd74bddf9-ccxch | 1/1 | Running | 0 | 4d1h | 10.111.224.33 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/aiconfig-patch-fd74bddf9-f6nvs | 1/1 | Running | 0 | 4d1h | 10.111.141.7 | ip-10-111-131-191.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aiconfig-patch | ClusterIP | 172.20.148.246 | <none> | 8000/TCP | 418d | app=aiconfig-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aiconfig-patch | 4/4 | 4 | 4 | 418d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.30 | app=aiconfig-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aiconfig-patch-5dc6c8556c | 0 | 0 | 0 | 63d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.41 | app=aiconfig-patch,pod-template-hash=5dc6c8556c |
| replicaset.apps/aiconfig-patch-5dddf87499 | 0 | 0 | 0 | 238d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:3.0.273 | app=aiconfig-patch,pod-template-hash=5dddf87499 |
| replicaset.apps/aiconfig-patch-5fc44657f5 | 0 | 0 | 0 | 63d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.42 | app=aiconfig-patch,pod-template-hash=5fc44657f5 |
| replicaset.apps/aiconfig-patch-688dbbc994 | 0 | 0 | 0 | 11d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.25 | app=aiconfig-patch,pod-template-hash=688dbbc994 |
| replicaset.apps/aiconfig-patch-6cf94b4f67 | 0 | 0 | 0 | 7d21h | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.25 | app=aiconfig-patch,pod-template-hash=6cf94b4f67 |
| replicaset.apps/aiconfig-patch-7b8b69849f | 0 | 0 | 0 | 99d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.37 | app=aiconfig-patch,pod-template-hash=7b8b69849f |
| replicaset.apps/aiconfig-patch-855d7b5bcf | 0 | 0 | 0 | 194d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:4.0.29 | app=aiconfig-patch,pod-template-hash=855d7b5bcf |
| replicaset.apps/aiconfig-patch-8579b7d947 | 0 | 0 | 0 | 63d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.40 | app=aiconfig-patch,pod-template-hash=8579b7d947 |
| replicaset.apps/aiconfig-patch-86866d8f87 | 0 | 0 | 0 | 202d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:4.0.28 | app=aiconfig-patch,pod-template-hash=86866d8f87 |
| replicaset.apps/aiconfig-patch-bbc9c6787 | 0 | 0 | 0 | 181d | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:4.0.30 | app=aiconfig-patch,pod-template-hash=bbc9c6787 |
| replicaset.apps/aiconfig-patch-fd74bddf9 | 4 | 4 | 4 | 4d1h | aiconfig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.30 | app=aiconfig-patch,pod-template-hash=fd74bddf9 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aiconfig-patch-us-east-1 | Deployment/aiconfig-patch | cpu: 1%/80%, memory: 172%/80% | 2 | 4 | 4 | 418d |

---

## Namespace: aiconfig-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aiconfig-prod-85fd794c74-6k48d | 1/1 | Running | 0 | 10h | 10.111.163.45 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/aiconfig-prod-85fd794c74-7knmv | 1/1 | Running | 0 | 4d23h | 10.111.233.236 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/aiconfig-prod-85fd794c74-lxb52 | 1/1 | Running | 0 | 28h | 10.111.83.96 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/aiconfig-prod-85fd794c74-qd5k2 | 1/1 | Running | 0 | 4d23h | 10.111.142.8 | ip-10-111-173-237.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aiconfig-prod | ClusterIP | 172.20.87.22 | <none> | 8000/TCP | 395d | app=aiconfig-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aiconfig-prod | 4/4 | 4 | 4 | 395d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.25 | app=aiconfig-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aiconfig-prod-56f775fcd5 | 0 | 0 | 0 | 5d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.25 | app=aiconfig-prod,pod-template-hash=56f775fcd5 |
| replicaset.apps/aiconfig-prod-59864b55d8 | 0 | 0 | 0 | 179d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:4.0.30 | app=aiconfig-prod,pod-template-hash=59864b55d8 |
| replicaset.apps/aiconfig-prod-598b954596 | 0 | 0 | 0 | 48d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.42 | app=aiconfig-prod,pod-template-hash=598b954596 |
| replicaset.apps/aiconfig-prod-5db955586d | 0 | 0 | 0 | 279d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:3.0.264 | app=aiconfig-prod,pod-template-hash=5db955586d |
| replicaset.apps/aiconfig-prod-66d69bd56d | 0 | 0 | 0 | 188d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:4.0.28 | app=aiconfig-prod,pod-template-hash=66d69bd56d |
| replicaset.apps/aiconfig-prod-67476fc79f | 0 | 0 | 0 | 395d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:1.0.169 | app=aiconfig-prod,pod-template-hash=67476fc79f |
| replicaset.apps/aiconfig-prod-67d4cf77f6 | 0 | 0 | 0 | 227d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:3.0.273 | app=aiconfig-prod,pod-template-hash=67d4cf77f6 |
| replicaset.apps/aiconfig-prod-7765bdc976 | 0 | 0 | 0 | 95d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:5.0.37 | app=aiconfig-prod,pod-template-hash=7765bdc976 |
| replicaset.apps/aiconfig-prod-7bcdf8978d | 0 | 0 | 0 | 371d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:2.0.247 | app=aiconfig-prod,pod-template-hash=7bcdf8978d |
| replicaset.apps/aiconfig-prod-85fd794c74 | 4 | 4 | 4 | 4d23h | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:6.0.25 | app=aiconfig-prod,pod-template-hash=85fd794c74 |
| replicaset.apps/aiconfig-prod-868449cd86 | 0 | 0 | 0 | 262d | aiconfig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-configservice:3.0.269 | app=aiconfig-prod,pod-template-hash=868449cd86 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aiconfig-prod-us-east-1 | Deployment/aiconfig-prod | cpu: 1%/80%, memory: 86%/80% | 2 | 4 | 4 | 395d |

---

## Namespace: aidataguide-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aidataguide-patch-7548d96d64-zqctl | 1/1 | Running | 0 | 11d | 10.111.185.81 | ip-10-111-128-40.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aidataguide-patch | ClusterIP | 172.20.87.30 | <none> | 8000/TCP | 404d | app=aidataguide-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aidataguide-patch | 1/1 | 1 | 1 | 404d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.17 | app=aidataguide-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aidataguide-patch-5f47fb64d4 | 0 | 0 | 0 | 78d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.75 | app=aidataguide-patch,pod-template-hash=5f47fb64d4 |
| replicaset.apps/aidataguide-patch-647c756496 | 0 | 0 | 0 | 375d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.49 | app=aidataguide-patch,pod-template-hash=647c756496 |
| replicaset.apps/aidataguide-patch-66b5dcfbf6 | 0 | 0 | 0 | 194d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.52 | app=aidataguide-patch,pod-template-hash=66b5dcfbf6 |
| replicaset.apps/aidataguide-patch-6bbf47d7d4 | 0 | 0 | 0 | 99d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.54 | app=aidataguide-patch,pod-template-hash=6bbf47d7d4 |
| replicaset.apps/aidataguide-patch-6fbb545964 | 0 | 0 | 0 | 375d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.49 | app=aidataguide-patch,pod-template-hash=6fbb545964 |
| replicaset.apps/aidataguide-patch-74b948c4fb | 0 | 0 | 0 | 391d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.44 | app=aidataguide-patch,pod-template-hash=74b948c4fb |
| replicaset.apps/aidataguide-patch-7548d96d64 | 1 | 1 | 1 | 18d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.17 | app=aidataguide-patch,pod-template-hash=7548d96d64 |
| replicaset.apps/aidataguide-patch-7559464c9b | 0 | 0 | 0 | 97d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.74 | app=aidataguide-patch,pod-template-hash=7559464c9b |
| replicaset.apps/aidataguide-patch-7795fc4b8d | 0 | 0 | 0 | 29d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.77 | app=aidataguide-patch,pod-template-hash=7795fc4b8d |
| replicaset.apps/aidataguide-patch-c5f8b8b6d | 0 | 0 | 0 | 61d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.76 | app=aidataguide-patch,pod-template-hash=c5f8b8b6d |
| replicaset.apps/aidataguide-patch-d775675f6 | 0 | 0 | 0 | 26d | aidataguide-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.16 | app=aidataguide-patch,pod-template-hash=d775675f6 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aidataguide-patch-us-east-1 | Deployment/aidataguide-patch | cpu: 1%/80%, memory: 20%/70% | 1 | 2 | 1 | 404d |

---

## Namespace: aidataguide-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aidataguide-prod-64cfd76c65-4zq4q | 1/1 | Running | 0 | 4d23h | 10.111.183.95 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/aidataguide-prod-64cfd76c65-mqs2n | 1/1 | Running | 0 | 4d23h | 10.111.141.121 | ip-10-111-131-191.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aidataguide-prod | ClusterIP | 172.20.250.38 | <none> | 8000/TCP | 404d | app=aidataguide-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aidataguide-prod | 2/2 | 2 | 2 | 404d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.17 | app=aidataguide-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aidataguide-prod-5469f9fc8c | 0 | 0 | 0 | 4d23h | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.17 | app=aidataguide-prod,pod-template-hash=5469f9fc8c |
| replicaset.apps/aidataguide-prod-569fbf748d | 0 | 0 | 0 | 188d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.52 | app=aidataguide-prod,pod-template-hash=569fbf748d |
| replicaset.apps/aidataguide-prod-5d967b4cdb | 0 | 0 | 0 | 370d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.49 | app=aidataguide-prod,pod-template-hash=5d967b4cdb |
| replicaset.apps/aidataguide-prod-5db68bf5fd | 0 | 0 | 0 | 404d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.38 | app=aidataguide-prod,pod-template-hash=5db68bf5fd |
| replicaset.apps/aidataguide-prod-64cfd76c65 | 2 | 2 | 2 | 4d23h | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.1.17 | app=aidataguide-prod,pod-template-hash=64cfd76c65 |
| replicaset.apps/aidataguide-prod-676d9b8d4d | 0 | 0 | 0 | 95d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.54 | app=aidataguide-prod,pod-template-hash=676d9b8d4d |
| replicaset.apps/aidataguide-prod-6dc9d8ddb6 | 0 | 0 | 0 | 391d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.44 | app=aidataguide-prod,pod-template-hash=6dc9d8ddb6 |
| replicaset.apps/aidataguide-prod-7bdb68f75b | 0 | 0 | 0 | 200d | aidataguide-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-dataguide:0.0.49 | app=aidataguide-prod,pod-template-hash=7bdb68f75b |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aidataguide-prod-us-east-1 | Deployment/aidataguide-prod | cpu: 1%/80%, memory: 19%/70% | 2 | 4 | 2 | 404d |

---

## Namespace: aig-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aig-patch-6d898b7bcd-rnkjw | 1/1 | Running | 0 | 4d1h | 10.111.150.39 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/aig-patch-6d898b7bcd-vlxqs | 1/1 | Running | 0 | 4d1h | 10.111.214.216 | ip-10-111-238-32.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aig-patch | ClusterIP | 172.20.112.185 | <none> | 8000/TCP | 395d | app=aig-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aig-patch | 2/2 | 2 | 2 | 395d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.36 | app=aig-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aig-patch-59f55c7698 | 0 | 0 | 0 | 12d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-patch,pod-template-hash=59f55c7698 |
| replicaset.apps/aig-patch-5cdf546f | 0 | 0 | 0 | 12d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-patch,pod-template-hash=5cdf546f |
| replicaset.apps/aig-patch-5d5d86477b | 0 | 0 | 0 | 19d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.45 | app=aig-patch,pod-template-hash=5d5d86477b |
| replicaset.apps/aig-patch-6568bf5576 | 0 | 0 | 0 | 18d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.45 | app=aig-patch,pod-template-hash=6568bf5576 |
| replicaset.apps/aig-patch-65b7558c7b | 0 | 0 | 0 | 54d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:PR.410.70 | app=aig-patch,pod-template-hash=65b7558c7b |
| replicaset.apps/aig-patch-6d898b7bcd | 2 | 2 | 2 | 4d1h | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.36 | app=aig-patch,pod-template-hash=6d898b7bcd |
| replicaset.apps/aig-patch-6d9d947b6 | 0 | 0 | 0 | 56d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.42 | app=aig-patch,pod-template-hash=6d9d947b6 |
| replicaset.apps/aig-patch-767797cb96 | 0 | 0 | 0 | 56d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.43 | app=aig-patch,pod-template-hash=767797cb96 |
| replicaset.apps/aig-patch-84f958bc68 | 0 | 0 | 0 | 34d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:PR.398.73 | app=aig-patch,pod-template-hash=84f958bc68 |
| replicaset.apps/aig-patch-85b4cbc776 | 0 | 0 | 0 | 34d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:PR.398.72 | app=aig-patch,pod-template-hash=85b4cbc776 |
| replicaset.apps/aig-patch-d54b96bc8 | 0 | 0 | 0 | 34d | aig-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.44 | app=aig-patch,pod-template-hash=d54b96bc8 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aig-patch-us-east-1 | Deployment/aig-patch | cpu: 1%/80%, memory: 19%/80% | 2 | 4 | 2 | 395d |

---

## Namespace: aig-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aig-prod-58c8f565d9-g448l | 1/1 | Running | 0 | 4d23h | 10.111.87.196 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/aig-prod-58c8f565d9-j9dkb | 1/1 | Running | 0 | 4d23h | 10.111.89.14 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aig-prod | ClusterIP | 172.20.168.127 | <none> | 8000/TCP | 395d | app=aig-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aig-prod | 2/2 | 2 | 2 | 395d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aig-prod-58485868bd | 0 | 0 | 0 | 76d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.39 | app=aig-prod,pod-template-hash=58485868bd |
| replicaset.apps/aig-prod-588967c9cc | 0 | 0 | 0 | 179d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:4.0.36 | app=aig-prod,pod-template-hash=588967c9cc |
| replicaset.apps/aig-prod-58c8f565d9 | 2 | 2 | 2 | 4d23h | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-prod,pod-template-hash=58c8f565d9 |
| replicaset.apps/aig-prod-5d64d9fd58 | 0 | 0 | 0 | 95d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.36 | app=aig-prod,pod-template-hash=5d64d9fd58 |
| replicaset.apps/aig-prod-5db69f49b6 | 0 | 0 | 0 | 49d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.43 | app=aig-prod,pod-template-hash=5db69f49b6 |
| replicaset.apps/aig-prod-647dbc69f4 | 0 | 0 | 0 | 18d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.45 | app=aig-prod,pod-template-hash=647dbc69f4 |
| replicaset.apps/aig-prod-6777f889 | 0 | 0 | 0 | 95d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.36 | app=aig-prod,pod-template-hash=6777f889 |
| replicaset.apps/aig-prod-7f6df8d7fd | 0 | 0 | 0 | 4d23h | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-prod,pod-template-hash=7f6df8d7fd |
| replicaset.apps/aig-prod-84b9d54fd7 | 0 | 0 | 0 | 136d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:4.0.39 | app=aig-prod,pod-template-hash=84b9d54fd7 |
| replicaset.apps/aig-prod-85595c884b | 0 | 0 | 0 | 5d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:6.0.34 | app=aig-prod,pod-template-hash=85595c884b |
| replicaset.apps/aig-prod-86c4959f94 | 0 | 0 | 0 | 81d | aig-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-aig:5.0.38 | app=aig-prod,pod-template-hash=86c4959f94 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aig-prod-us-east-1 | Deployment/aig-prod | cpu: 2%/80%, memory: 24%/80% | 2 | 4 | 2 | 395d |

---

## Namespace: aihelp-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-client-aihelp-patch-6495d4d76c-fdgds | 1/1 | Running | 0 | 11d | 10.111.177.115 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-patch-6c66d79949-29jw7 | 1/1 | Running | 0 | 5d | 10.111.198.16 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-patch-6c66d79949-7gjz8 | 1/1 | Running | 0 | 5d2h | 10.111.109.203 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-patch-6c66d79949-9xxht | 1/1 | Running | 0 | 5d2h | 10.111.182.169 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-patch-6c66d79949-d4wwm | 1/1 | Running | 0 | 5d2h | 10.111.133.213 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-patch-6c66d79949-g5nw8 | 1/1 | Running | 0 | 5d2h | 10.111.72.37 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-patch-d4f9f85b-bgpjl | 1/1 | Running | 0 | 5d2h | 10.111.178.111 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-patch-d4f9f85b-cmfds | 1/1 | Running | 0 | 5d2h | 10.111.106.70 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-patch-d4f9f85b-ds2md | 1/1 | Running | 0 | 5d2h | 10.111.242.208 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-patch-d4f9f85b-mlcpk | 1/1 | Running | 0 | 5d2h | 10.111.144.241 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-patch-d4f9f85b-zgp68 | 1/1 | Running | 0 | 5d2h | 10.111.102.62 | ip-10-111-65-28.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-client-aihelp-patch | ClusterIP | 172.20.22.248 | <none> | 3000/TCP | 402d | app=ai-client-aihelp-patch |
| service/ai-report-aihelp-patch | ClusterIP | 172.20.215.171 | <none> | 8000/TCP | 402d | app=ai-report-aihelp-patch |
| service/ai-server-aihelp-patch | ClusterIP | 172.20.215.70 | <none> | 8000/TCP | 402d | app=ai-server-aihelp-patch |
| service/redis-aihelp-patch | ClusterIP | 172.20.145.254 | <none> | 6379/TCP | 402d | app=redis-aihelp-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-client-aihelp-patch | 1/1 | 1 | 1 | 402d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.73 | app=ai-client-aihelp-patch |
| deployment.apps/ai-report-aihelp-patch | 5/5 | 5 | 5 | 402d | ai-help-report-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.6 | app=ai-report-aihelp-patch |
| deployment.apps/ai-server-aihelp-patch | 5/5 | 5 | 5 | 402d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.65 | app=ai-server-aihelp-patch |
| deployment.apps/redis-aihelp-patch | 0/0 | 0 | 0 | 402d | redis-aihelp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-redis:7 | app=redis-aihelp-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/ai-client-aihelp-patch-554b79fc7d | 0 | 0 | 0 | 28d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.69 | app=ai-client-aihelp-patch,pod-template-hash=554b79fc7d |
| replicaset.apps/ai-client-aihelp-patch-589f47ddc9 | 0 | 0 | 0 | 382d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.2.18 | app=ai-client-aihelp-patch,pod-template-hash=589f47ddc9 |
| replicaset.apps/ai-client-aihelp-patch-5fb5588dd7 | 0 | 0 | 0 | 375d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.3.20 | app=ai-client-aihelp-patch,pod-template-hash=5fb5588dd7 |
| replicaset.apps/ai-client-aihelp-patch-6495d4d76c | 1 | 1 | 1 | 18d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.73 | app=ai-client-aihelp-patch,pod-template-hash=6495d4d76c |
| replicaset.apps/ai-client-aihelp-patch-66d4f89c7d | 0 | 0 | 0 | 27d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.72 | app=ai-client-aihelp-patch,pod-template-hash=66d4f89c7d |
| replicaset.apps/ai-client-aihelp-patch-67df6bffd6 | 0 | 0 | 0 | 28d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.67 | app=ai-client-aihelp-patch,pod-template-hash=67df6bffd6 |
| replicaset.apps/ai-client-aihelp-patch-6f885b9469 | 0 | 0 | 0 | 18d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.72 | app=ai-client-aihelp-patch,pod-template-hash=6f885b9469 |
| replicaset.apps/ai-client-aihelp-patch-6fd68cf875 | 0 | 0 | 0 | 402d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.2.18 | app=ai-client-aihelp-patch,pod-template-hash=6fd68cf875 |
| replicaset.apps/ai-client-aihelp-patch-7568c44bcc | 0 | 0 | 0 | 192d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.4.36 | app=ai-client-aihelp-patch,pod-template-hash=7568c44bcc |
| replicaset.apps/ai-client-aihelp-patch-7f7d8d6658 | 0 | 0 | 0 | 11d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:1.0.3 | app=ai-client-aihelp-patch,pod-template-hash=7f7d8d6658 |
| replicaset.apps/ai-client-aihelp-patch-84fbc8f6fd | 0 | 0 | 0 | 61d | ai-help-client-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.65 | app=ai-client-aihelp-patch,pod-template-hash=84fbc8f6fd |
| replicaset.apps/ai-report-aihelp-patch-586b6668fb | 0 | 0 | 0 | 192d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-patch,pod-template-hash=586b6668fb |
| replicaset.apps/ai-report-aihelp-patch-5cfdf685f6 | 0 | 0 | 0 | 375d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.3.12 | app=ai-report-aihelp-patch,pod-template-hash=5cfdf685f6 |
| replicaset.apps/ai-report-aihelp-patch-5f694c49c6 | 0 | 0 | 0 | 15d | ai-help-report-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.5 | app=ai-report-aihelp-patch,pod-template-hash=5f694c49c6 |
| replicaset.apps/ai-report-aihelp-patch-668bcd9b8 | 0 | 0 | 0 | 402d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.1.26 | app=ai-report-aihelp-patch,pod-template-hash=668bcd9b8 |
| replicaset.apps/ai-report-aihelp-patch-67cdc4d8f7 | 0 | 0 | 0 | 18d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-patch,pod-template-hash=67cdc4d8f7 |
| replicaset.apps/ai-report-aihelp-patch-6c66d79949 | 5 | 5 | 5 | 5d2h | ai-help-report-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.6 | app=ai-report-aihelp-patch,pod-template-hash=6c66d79949 |
| replicaset.apps/ai-report-aihelp-patch-6ccf847946 | 0 | 0 | 0 | 382d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.1.26 | app=ai-report-aihelp-patch,pod-template-hash=6ccf847946 |
| replicaset.apps/ai-report-aihelp-patch-75d9888856 | 0 | 0 | 0 | 18d | ai-help-report-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.4 | app=ai-report-aihelp-patch,pod-template-hash=75d9888856 |
| replicaset.apps/ai-report-aihelp-patch-7b47f45bf6 | 0 | 0 | 0 | 402d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.1.26 | app=ai-report-aihelp-patch,pod-template-hash=7b47f45bf6 |
| replicaset.apps/ai-server-aihelp-patch-546f78d887 | 0 | 0 | 0 | 28d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.49 | app=ai-server-aihelp-patch,pod-template-hash=546f78d887 |
| replicaset.apps/ai-server-aihelp-patch-554b9f5dfc | 0 | 0 | 0 | 28d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.48 | app=ai-server-aihelp-patch,pod-template-hash=554b9f5dfc |
| replicaset.apps/ai-server-aihelp-patch-584f8fb54f | 0 | 0 | 0 | 18d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.52 | app=ai-server-aihelp-patch,pod-template-hash=584f8fb54f |
| replicaset.apps/ai-server-aihelp-patch-58cd46f7f9 | 0 | 0 | 0 | 18d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.53 | app=ai-server-aihelp-patch,pod-template-hash=58cd46f7f9 |
| replicaset.apps/ai-server-aihelp-patch-66dbd4f685 | 0 | 0 | 0 | 47d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.44 | app=ai-server-aihelp-patch,pod-template-hash=66dbd4f685 |
| replicaset.apps/ai-server-aihelp-patch-68cfb8c9f | 0 | 0 | 0 | 27d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.52 | app=ai-server-aihelp-patch,pod-template-hash=68cfb8c9f |
| replicaset.apps/ai-server-aihelp-patch-6b547449bf | 0 | 0 | 0 | 47d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.42 | app=ai-server-aihelp-patch,pod-template-hash=6b547449bf |
| replicaset.apps/ai-server-aihelp-patch-8f547dcbc | 0 | 0 | 0 | 42d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.47 | app=ai-server-aihelp-patch,pod-template-hash=8f547dcbc |
| replicaset.apps/ai-server-aihelp-patch-944cdd495 | 0 | 0 | 0 | 47d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.45 | app=ai-server-aihelp-patch,pod-template-hash=944cdd495 |
| replicaset.apps/ai-server-aihelp-patch-d4f9f85b | 5 | 5 | 5 | 5d2h | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.65 | app=ai-server-aihelp-patch,pod-template-hash=d4f9f85b |
| replicaset.apps/ai-server-aihelp-patch-d7c69cd6c | 0 | 0 | 0 | 14d | ai-help-server-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.57 | app=ai-server-aihelp-patch,pod-template-hash=d7c69cd6c |
| replicaset.apps/redis-aihelp-patch-777c855fcc | 0 | 0 | 0 | 402d | redis-aihelp-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-redis:7 | app=redis-aihelp-patch,pod-template-hash=777c855fcc |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-help-report-patch-us-east-1 | Deployment/ai-report-aihelp-patch | cpu: 1%/80%, memory: 593557913600m/700Mi | 3 | 5 | 5 | 402d |
| horizontalpodautoscaler.autoscaling/ai-help-server-patch-us-east-1 | Deployment/ai-server-aihelp-patch | cpu: 5%/80%, memory: 705136230400m/700Mi | 3 | 5 | 5 | 402d |

---

## Namespace: aihelp-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ai-client-aihelp-prod-8d996887b-892z7 | 1/1 | Running | 0 | 4d23h | 10.111.164.211 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-prod-7bdbb9bbf8-dcg2z | 1/1 | Running | 0 | 4d23h | 10.111.187.101 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-prod-7bdbb9bbf8-pjsgv | 1/1 | Running | 0 | 4d23h | 10.111.87.18 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-prod-7bdbb9bbf8-wqzs4 | 1/1 | Running | 0 | 4d23h | 10.111.188.26 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ai-report-aihelp-prod-7bdbb9bbf8-wxlw2 | 1/1 | Running | 0 | 4d23h | 10.111.219.178 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-6k8x5 | 1/1 | Running | 0 | 4d23h | 10.111.116.240 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-9xbcc | 1/1 | Running | 0 | 4d23h | 10.111.242.133 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-g696q | 1/1 | Running | 0 | 4d23h | 10.111.133.175 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-vvsqr | 1/1 | Running | 0 | 4d23h | 10.111.194.26 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-wq4dt | 1/1 | Running | 0 | 4d23h | 10.111.104.193 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ai-server-aihelp-prod-c8c68f8b5-x9g8r | 1/1 | Running | 0 | 4d23h | 10.111.176.64 | ip-10-111-135-235.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ai-client-aihelp-prod | ClusterIP | 172.20.112.226 | <none> | 3000/TCP | 395d | app=ai-client-aihelp-prod |
| service/ai-report-aihelp-prod | ClusterIP | 172.20.205.246 | <none> | 8000/TCP | 395d | app=ai-report-aihelp-prod |
| service/ai-server-aihelp-prod | ClusterIP | 172.20.234.182 | <none> | 8000/TCP | 395d | app=ai-server-aihelp-prod |
| service/redis-aihelp-prod | ClusterIP | 172.20.28.116 | <none> | 6379/TCP | 403d | app=redis-aihelp-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/ai-client-aihelp-prod | 1/1 | 1 | 1 | 395d | ai-help-client-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.73 | app=ai-client-aihelp-prod |
| deployment.apps/ai-report-aihelp-prod | 4/4 | 4 | 4 | 395d | ai-help-report-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.6 | app=ai-report-aihelp-prod |
| deployment.apps/ai-server-aihelp-prod | 6/6 | 6 | 6 | 395d | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.65 | app=ai-server-aihelp-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/ai-client-aihelp-prod-54559f6c77 | 0 | 0 | 0 | 5d2h | ai-help-client-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.73 | app=ai-client-aihelp-prod,pod-template-hash=54559f6c77 |
| replicaset.apps/ai-client-aihelp-prod-594757f4bb | 0 | 0 | 0 | 103d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.4.36 | app=ai-client-aihelp-prod,pod-template-hash=594757f4bb |
| replicaset.apps/ai-client-aihelp-prod-69fbbf5874 | 0 | 0 | 0 | 190d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.4.36 | app=ai-client-aihelp-prod,pod-template-hash=69fbbf5874 |
| replicaset.apps/ai-client-aihelp-prod-7c9f57f76b | 0 | 0 | 0 | 395d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.2.18 | app=ai-client-aihelp-prod,pod-template-hash=7c9f57f76b |
| replicaset.apps/ai-client-aihelp-prod-8587f8c56b | 0 | 0 | 0 | 373d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.3.20 | app=ai-client-aihelp-prod,pod-template-hash=8587f8c56b |
| replicaset.apps/ai-client-aihelp-prod-85b9fdc76 | 0 | 0 | 0 | 81d | ai-client | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.4.36 | app=ai-client-aihelp-prod,pod-template-hash=85b9fdc76 |
| replicaset.apps/ai-client-aihelp-prod-8d996887b | 1 | 1 | 1 | 4d23h | ai-help-client-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.73 | app=ai-client-aihelp-prod,pod-template-hash=8d996887b |
| replicaset.apps/ai-client-aihelp-prod-c765f6476 | 0 | 0 | 0 | 61d | ai-help-client-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-client:0.5.65 | app=ai-client-aihelp-prod,pod-template-hash=c765f6476 |
| replicaset.apps/ai-report-aihelp-prod-55f58465df | 0 | 0 | 0 | 373d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.3.12 | app=ai-report-aihelp-prod,pod-template-hash=55f58465df |
| replicaset.apps/ai-report-aihelp-prod-576789f9c6 | 0 | 0 | 0 | 373d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.3.12 | app=ai-report-aihelp-prod,pod-template-hash=576789f9c6 |
| replicaset.apps/ai-report-aihelp-prod-5c95499b6 | 0 | 0 | 0 | 395d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.2.8 | app=ai-report-aihelp-prod,pod-template-hash=5c95499b6 |
| replicaset.apps/ai-report-aihelp-prod-66cbbcc9d5 | 0 | 0 | 0 | 190d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-prod,pod-template-hash=66cbbcc9d5 |
| replicaset.apps/ai-report-aihelp-prod-69cc9f9fbd | 0 | 0 | 0 | 81d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-prod,pod-template-hash=69cc9f9fbd |
| replicaset.apps/ai-report-aihelp-prod-6b874f779b | 0 | 0 | 0 | 81d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-prod,pod-template-hash=6b874f779b |
| replicaset.apps/ai-report-aihelp-prod-6bd7f7cf44 | 0 | 0 | 0 | 103d | ai-report | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.4.20 | app=ai-report-aihelp-prod,pod-template-hash=6bd7f7cf44 |
| replicaset.apps/ai-report-aihelp-prod-77c5cc48dc | 0 | 0 | 0 | 5d2h | ai-help-report-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.6 | app=ai-report-aihelp-prod,pod-template-hash=77c5cc48dc |
| replicaset.apps/ai-report-aihelp-prod-7bdbb9bbf8 | 4 | 4 | 4 | 4d23h | ai-help-report-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-report:0.5.6 | app=ai-report-aihelp-prod,pod-template-hash=7bdbb9bbf8 |
| replicaset.apps/ai-server-aihelp-prod-584795f97b | 0 | 0 | 0 | 373d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.3.23 | app=ai-server-aihelp-prod,pod-template-hash=584795f97b |
| replicaset.apps/ai-server-aihelp-prod-5bd48d7d9c | 0 | 0 | 0 | 81d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.4.43 | app=ai-server-aihelp-prod,pod-template-hash=5bd48d7d9c |
| replicaset.apps/ai-server-aihelp-prod-649f5655 | 0 | 0 | 0 | 61d | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.33 | app=ai-server-aihelp-prod,pod-template-hash=649f5655 |
| replicaset.apps/ai-server-aihelp-prod-64d66dd645 | 0 | 0 | 0 | 61d | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.32 | app=ai-server-aihelp-prod,pod-template-hash=64d66dd645 |
| replicaset.apps/ai-server-aihelp-prod-668797d44d | 0 | 0 | 0 | 5d2h | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.65 | app=ai-server-aihelp-prod,pod-template-hash=668797d44d |
| replicaset.apps/ai-server-aihelp-prod-766896fc65 | 0 | 0 | 0 | 190d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.4.43 | app=ai-server-aihelp-prod,pod-template-hash=766896fc65 |
| replicaset.apps/ai-server-aihelp-prod-7849964764 | 0 | 0 | 0 | 103d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.4.43 | app=ai-server-aihelp-prod,pod-template-hash=7849964764 |
| replicaset.apps/ai-server-aihelp-prod-799dbcd9c9 | 0 | 0 | 0 | 373d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.3.23 | app=ai-server-aihelp-prod,pod-template-hash=799dbcd9c9 |
| replicaset.apps/ai-server-aihelp-prod-7b9597979 | 0 | 0 | 0 | 190d | ai-server | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.4.43 | app=ai-server-aihelp-prod,pod-template-hash=7b9597979 |
| replicaset.apps/ai-server-aihelp-prod-8d58fb8f7 | 0 | 0 | 0 | 42d | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.47 | app=ai-server-aihelp-prod,pod-template-hash=8d58fb8f7 |
| replicaset.apps/ai-server-aihelp-prod-c8c68f8b5 | 6 | 6 | 6 | 4d23h | ai-help-server-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-help-server:0.5.65 | app=ai-server-aihelp-prod,pod-template-hash=c8c68f8b5 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-help-report-prod-us-east-1 | Deployment/ai-report-aihelp-prod | cpu: 1%/80%, memory: 565757Ki/700Mi | 3 | 6 | 4 | 395d |
| horizontalpodautoscaler.autoscaling/ai-help-server-prod-us-east-1 | Deployment/ai-server-aihelp-prod | cpu: 42%/80%, memory: 859112106666m/700Mi | 3 | 6 | 6 | 395d |

---

## Namespace: aischeduler-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aischeduler-patch-687fcbc495-75gkf | 1/1 | Running | 0 | 11d | 10.111.250.83 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/aischeduler-patch-687fcbc495-kwh92 | 1/1 | Running | 0 | 11d | 10.111.118.89 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/aischeduler-patch-687fcbc495-ljkrv | 1/1 | Running | 0 | 11d | 10.111.168.251 | ip-10-111-128-40.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aischeduler-patch | ClusterIP | 172.20.172.216 | <none> | 8000/TCP | 418d | app=aischeduler-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aischeduler-patch | 3/3 | 3 | 3 | 418d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.4.8 | app=aischeduler-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aischeduler-patch-54fd95bf76 | 0 | 0 | 0 | 146d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.17 | app=aischeduler-patch,pod-template-hash=54fd95bf76 |
| replicaset.apps/aischeduler-patch-59f98698f6 | 0 | 0 | 0 | 98d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.17 | app=aischeduler-patch,pod-template-hash=59f98698f6 |
| replicaset.apps/aischeduler-patch-65b4f79954 | 0 | 0 | 0 | 190d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.16 | app=aischeduler-patch,pod-template-hash=65b4f79954 |
| replicaset.apps/aischeduler-patch-687fcbc495 | 3 | 3 | 3 | 11d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.4.8 | app=aischeduler-patch,pod-template-hash=687fcbc495 |
| replicaset.apps/aischeduler-patch-6ffcb66fb | 0 | 0 | 0 | 18d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.19 | app=aischeduler-patch,pod-template-hash=6ffcb66fb |
| replicaset.apps/aischeduler-patch-789fd5c87b | 0 | 0 | 0 | 270d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.31 | app=aischeduler-patch,pod-template-hash=789fd5c87b |
| replicaset.apps/aischeduler-patch-797f954888 | 0 | 0 | 0 | 243d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.32 | app=aischeduler-patch,pod-template-hash=797f954888 |
| replicaset.apps/aischeduler-patch-868f969f75 | 0 | 0 | 0 | 190d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.16 | app=aischeduler-patch,pod-template-hash=868f969f75 |
| replicaset.apps/aischeduler-patch-c97659d6d | 0 | 0 | 0 | 82d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.18 | app=aischeduler-patch,pod-template-hash=c97659d6d |
| replicaset.apps/aischeduler-patch-d6948b8cb | 0 | 0 | 0 | 54d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.19 | app=aischeduler-patch,pod-template-hash=d6948b8cb |
| replicaset.apps/aischeduler-patch-f9f665748 | 0 | 0 | 0 | 192d | aischeduler-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.16 | app=aischeduler-patch,pod-template-hash=f9f665748 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-scheduler-patch-us-east-1 | Deployment/aischeduler-patch | cpu: 9%/80%, memory: 66%/92% | 3 | 6 | 3 | 418d |

---

## Namespace: aischeduler-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aischeduler-prod-6494bcf9d8-4pnq4 | 1/1 | Running | 0 | 4d23h | 10.111.86.150 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/aischeduler-prod-6494bcf9d8-bjk7b | 1/1 | Running | 0 | 4d23h | 10.111.169.9 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/aischeduler-prod-6494bcf9d8-w67cr | 1/1 | Running | 0 | 4d23h | 10.111.215.81 | ip-10-111-238-32.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aischeduler-prod | ClusterIP | 172.20.193.142 | <none> | 8000/TCP | 418d | app=aischeduler-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aischeduler-prod | 3/3 | 3 | 3 | 418d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.4.8 | app=aischeduler-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aischeduler-prod-5467b77d5f | 0 | 0 | 0 | 136d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.17 | app=aischeduler-prod,pod-template-hash=5467b77d5f |
| replicaset.apps/aischeduler-prod-59c56bcbcf | 0 | 0 | 0 | 227d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.32 | app=aischeduler-prod,pod-template-hash=59c56bcbcf |
| replicaset.apps/aischeduler-prod-5dc99f94d5 | 0 | 0 | 0 | 95d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.17 | app=aischeduler-prod,pod-template-hash=5dc99f94d5 |
| replicaset.apps/aischeduler-prod-6494bcf9d8 | 3 | 3 | 3 | 4d23h | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.4.8 | app=aischeduler-prod,pod-template-hash=6494bcf9d8 |
| replicaset.apps/aischeduler-prod-65f459b589 | 0 | 0 | 0 | 188d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.2.16 | app=aischeduler-prod,pod-template-hash=65f459b589 |
| replicaset.apps/aischeduler-prod-6896957fd9 | 0 | 0 | 0 | 262d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.31 | app=aischeduler-prod,pod-template-hash=6896957fd9 |
| replicaset.apps/aischeduler-prod-6db554f57d | 0 | 0 | 0 | 4d23h | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.4.8 | app=aischeduler-prod,pod-template-hash=6db554f57d |
| replicaset.apps/aischeduler-prod-76849c7b47 | 0 | 0 | 0 | 81d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.18 | app=aischeduler-prod,pod-template-hash=76849c7b47 |
| replicaset.apps/aischeduler-prod-77c797fdc | 0 | 0 | 0 | 371d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.29 | app=aischeduler-prod,pod-template-hash=77c797fdc |
| replicaset.apps/aischeduler-prod-7db6cd6959 | 0 | 0 | 0 | 277d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.1.30 | app=aischeduler-prod,pod-template-hash=7db6cd6959 |
| replicaset.apps/aischeduler-prod-b8cf86b85 | 0 | 0 | 0 | 48d | aischeduler-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-scheduler:1.3.19 | app=aischeduler-prod,pod-template-hash=b8cf86b85 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-scheduler-prod-us-east-1 | Deployment/aischeduler-prod | cpu: 5%/80%, memory: 64%/92% | 3 | 6 | 3 | 418d |

---

## Namespace: aisfm-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisfm-patch-84f47d75d6-brprz | 1/1 | Running | 0 | 81m | 10.111.228.67 | ip-10-111-233-47.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisfm-patch | ClusterIP | 172.20.149.205 | <none> | 8000/TCP | 321d | app=aisfm-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisfm-patch | 1/1 | 1 | 1 | 321d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.26 | app=aisfm-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisfm-patch-54576f9c64 | 0 | 0 | 0 | 88d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.56 | app=aisfm-patch,pod-template-hash=54576f9c64 |
| replicaset.apps/aisfm-patch-5689fc8b86 | 0 | 0 | 0 | 6d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.23 | app=aisfm-patch,pod-template-hash=5689fc8b86 |
| replicaset.apps/aisfm-patch-6fd57987b8 | 0 | 0 | 0 | 180d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.43 | app=aisfm-patch,pod-template-hash=6fd57987b8 |
| replicaset.apps/aisfm-patch-7659556476 | 0 | 0 | 0 | 145d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.45 | app=aisfm-patch,pod-template-hash=7659556476 |
| replicaset.apps/aisfm-patch-775b87f54d | 0 | 0 | 0 | 99d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.54 | app=aisfm-patch,pod-template-hash=775b87f54d |
| replicaset.apps/aisfm-patch-849bf9678d | 0 | 0 | 0 | 56d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.57 | app=aisfm-patch,pod-template-hash=849bf9678d |
| replicaset.apps/aisfm-patch-84cd54674d | 0 | 0 | 0 | 154d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.44 | app=aisfm-patch,pod-template-hash=84cd54674d |
| replicaset.apps/aisfm-patch-84f47d75d6 | 1 | 1 | 1 | 81m | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.26 | app=aisfm-patch,pod-template-hash=84f47d75d6 |
| replicaset.apps/aisfm-patch-84f6ff64d8 | 0 | 0 | 0 | 19d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.18 | app=aisfm-patch,pod-template-hash=84f6ff64d8 |
| replicaset.apps/aisfm-patch-86d5498d89 | 0 | 0 | 0 | 11d | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.23 | app=aisfm-patch,pod-template-hash=86d5498d89 |
| replicaset.apps/aisfm-patch-d59565d58 | 0 | 0 | 0 | 2d23h | aisfm-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.25 | app=aisfm-patch,pod-template-hash=d59565d58 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aisfm-patch | Deployment/aisfm-patch | cpu: 2%/80%, memory: 18%/70% | 1 | 2 | 1 | 321d |

---

## Namespace: aisfm-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisfm-prod-7476b7dcc7-kfk7j | 1/1 | Running | 0 | 4d23h | 10.111.132.180 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/aisfm-prod-7476b7dcc7-tfw6p | 1/1 | Running | 0 | 4d23h | 10.111.92.96 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisfm-prod | ClusterIP | 172.20.33.53 | <none> | 8000/TCP | 315d | app=aisfm-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisfm-prod | 2/2 | 2 | 2 | 315d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.23 | app=aisfm-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisfm-prod-54696d885d | 0 | 0 | 0 | 280d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:3.0.2 | app=aisfm-prod,pod-template-hash=54696d885d |
| replicaset.apps/aisfm-prod-556fc65fd6 | 0 | 0 | 0 | 294d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:0.0.117 | app=aisfm-prod,pod-template-hash=556fc65fd6 |
| replicaset.apps/aisfm-prod-67bbdd56f8 | 0 | 0 | 0 | 136d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.45 | app=aisfm-prod,pod-template-hash=67bbdd56f8 |
| replicaset.apps/aisfm-prod-6d4ff44cb6 | 0 | 0 | 0 | 179d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.43 | app=aisfm-prod,pod-template-hash=6d4ff44cb6 |
| replicaset.apps/aisfm-prod-7476b7dcc7 | 2 | 2 | 2 | 4d23h | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.23 | app=aisfm-prod,pod-template-hash=7476b7dcc7 |
| replicaset.apps/aisfm-prod-75789dd456 | 0 | 0 | 0 | 227d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:3.0.3 | app=aisfm-prod,pod-template-hash=75789dd456 |
| replicaset.apps/aisfm-prod-7cfd44cdb6 | 0 | 0 | 0 | 81d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.56 | app=aisfm-prod,pod-template-hash=7cfd44cdb6 |
| replicaset.apps/aisfm-prod-7db874cb46 | 0 | 0 | 0 | 48d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.57 | app=aisfm-prod,pod-template-hash=7db874cb46 |
| replicaset.apps/aisfm-prod-8479644f4 | 0 | 0 | 0 | 95d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:5.0.54 | app=aisfm-prod,pod-template-hash=8479644f4 |
| replicaset.apps/aisfm-prod-85d48c5c86 | 0 | 0 | 0 | 5d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:6.0.23 | app=aisfm-prod,pod-template-hash=85d48c5c86 |
| replicaset.apps/aisfm-prod-c96cd6954 | 0 | 0 | 0 | 188d | aisfm-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sfm:4.0.41 | app=aisfm-prod,pod-template-hash=c96cd6954 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/aisfm-prod | Deployment/aisfm-prod | cpu: 1%/80%, memory: 20%/70% | 2 | 4 | 2 | 315d |

---

## Namespace: aisrvhistory-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisrvhistory-patch-797fd88c4d-rl4mx | 1/1 | Running | 0 | 3d14h | 10.111.114.87 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/aisrvhistory-patch-797fd88c4d-w64rw | 1/1 | Running | 0 | 3d14h | 10.111.155.127 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/aisrvhistory-planner-patch-d494694bd-4d4s7 | 1/1 | Running | 0 | 3d14h | 10.111.157.15 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/aisrvhistory-planner-patch-d494694bd-5jjrk | 1/1 | Running | 0 | 3d14h | 10.111.123.97 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/aisrvhistory-planner-patch-d494694bd-jrd2b | 1/1 | Running | 0 | 3d14h | 10.111.206.37 | ip-10-111-233-47.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisrvhistory-executor-patch | ClusterIP | 172.20.23.171 | <none> | 8000/TCP | 217d | app=aisrvhistory-executor-patch |
| service/aisrvhistory-patch | ClusterIP | 172.20.43.152 | <none> | 8000/TCP | 418d | app=aisrvhistory-patch |
| service/aisrvhistory-planner-patch | ClusterIP | 172.20.111.46 | <none> | 8000/TCP | 217d | app=aisrvhistory-planner-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisrvhistory-patch | 2/2 | 2 | 2 | 418d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.94 | app=aisrvhistory-patch |
| deployment.apps/aisrvhistory-planner-patch | 3/3 | 3 | 3 | 217d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.87 | app=aisrvhistory-planner-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisrvhistory-patch-5b679bb9c7 | 0 | 0 | 0 | 53d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.135 | app=aisrvhistory-patch,pod-template-hash=5b679bb9c7 |
| replicaset.apps/aisrvhistory-patch-5b8797474c | 0 | 0 | 0 | 56d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.132 | app=aisrvhistory-patch,pod-template-hash=5b8797474c |
| replicaset.apps/aisrvhistory-patch-5bd8c8b675 | 0 | 0 | 0 | 61d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.130 | app=aisrvhistory-patch,pod-template-hash=5bd8c8b675 |
| replicaset.apps/aisrvhistory-patch-5d46b6b48c | 0 | 0 | 0 | 54d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:PR.647.165 | app=aisrvhistory-patch,pod-template-hash=5d46b6b48c |
| replicaset.apps/aisrvhistory-patch-76bb99f55c | 0 | 0 | 0 | 60d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.131 | app=aisrvhistory-patch,pod-template-hash=76bb99f55c |
| replicaset.apps/aisrvhistory-patch-77d6dbbbb5 | 0 | 0 | 0 | 56d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.133 | app=aisrvhistory-patch,pod-template-hash=77d6dbbbb5 |
| replicaset.apps/aisrvhistory-patch-797fd88c4d | 2 | 2 | 2 | 3d14h | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.94 | app=aisrvhistory-patch,pod-template-hash=797fd88c4d |
| replicaset.apps/aisrvhistory-patch-7df74fb4f5 | 0 | 0 | 0 | 19d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.136 | app=aisrvhistory-patch,pod-template-hash=7df74fb4f5 |
| replicaset.apps/aisrvhistory-patch-86b9b8c67f | 0 | 0 | 0 | 53d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.134 | app=aisrvhistory-patch,pod-template-hash=86b9b8c67f |
| replicaset.apps/aisrvhistory-patch-b75df6f6c | 0 | 0 | 0 | 12d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.93 | app=aisrvhistory-patch,pod-template-hash=b75df6f6c |
| replicaset.apps/aisrvhistory-patch-bfc46b95 | 0 | 0 | 0 | 54d | aisrvhistory-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:PR.651.179 | app=aisrvhistory-patch,pod-template-hash=bfc46b95 |
| replicaset.apps/aisrvhistory-planner-patch-57474c9fc9 | 0 | 0 | 0 | 56d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.347 | app=aisrvhistory-planner-patch,pod-template-hash=57474c9fc9 |
| replicaset.apps/aisrvhistory-planner-patch-57cfdb5ff7 | 0 | 0 | 0 | 54d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:PR.647.10 | app=aisrvhistory-planner-patch,pod-template-hash=57cfdb5ff7 |
| replicaset.apps/aisrvhistory-planner-patch-5955f6c6f7 | 0 | 0 | 0 | 56d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.348 | app=aisrvhistory-planner-patch,pod-template-hash=5955f6c6f7 |
| replicaset.apps/aisrvhistory-planner-patch-5f579b5fdc | 0 | 0 | 0 | 54d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:PR.650.13 | app=aisrvhistory-planner-patch,pod-template-hash=5f579b5fdc |
| replicaset.apps/aisrvhistory-planner-patch-5f85b8d468 | 0 | 0 | 0 | 7d21h | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-patch,pod-template-hash=5f85b8d468 |
| replicaset.apps/aisrvhistory-planner-patch-76ff588b7 | 0 | 0 | 0 | 12d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-patch,pod-template-hash=76ff588b7 |
| replicaset.apps/aisrvhistory-planner-patch-7745cd58d7 | 0 | 0 | 0 | 53d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.350 | app=aisrvhistory-planner-patch,pod-template-hash=7745cd58d7 |
| replicaset.apps/aisrvhistory-planner-patch-7bd55dc7c9 | 0 | 0 | 0 | 53d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.349 | app=aisrvhistory-planner-patch,pod-template-hash=7bd55dc7c9 |
| replicaset.apps/aisrvhistory-planner-patch-7fd5cd76d9 | 0 | 0 | 0 | 18d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.351 | app=aisrvhistory-planner-patch,pod-template-hash=7fd5cd76d9 |
| replicaset.apps/aisrvhistory-planner-patch-c5848699f | 0 | 0 | 0 | 54d | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:PR.650.11 | app=aisrvhistory-planner-patch,pod-template-hash=c5848699f |
| replicaset.apps/aisrvhistory-planner-patch-d494694bd | 3 | 3 | 3 | 3d14h | aisrvhistory-planner-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.87 | app=aisrvhistory-planner-patch,pod-template-hash=d494694bd |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-patch-us-east-1 | Deployment/aisrvhistory-patch | cpu: 1%/80%, memory: 15%/80% | 2 | 4 | 2 | 418d |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-planner-patch-us-east-1 | Deployment/aisrvhistory-planner-patch | cpu: 3%/80%, memory: 21%/70% | 3 | 4 | 3 | 217d |

---

## Namespace: aisrvhistory-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisrvhistory-planner-prod-7d6ffb4dbd-gsmx6 | 1/1 | Running | 0 | 4d22h | 10.111.168.214 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/aisrvhistory-planner-prod-7d6ffb4dbd-q9tq8 | 1/1 | Running | 0 | 4d22h | 10.111.247.128 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/aisrvhistory-planner-prod-7d6ffb4dbd-s5ppb | 1/1 | Running | 0 | 4d22h | 10.111.96.196 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/aisrvhistory-prod-6446f79c84-bm27b | 1/1 | Running | 0 | 4d23h | 10.111.186.245 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/aisrvhistory-prod-6446f79c84-jkdjc | 1/1 | Running | 0 | 4d23h | 10.111.75.55 | ip-10-111-99-36.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisrvhistory-executor-prod | ClusterIP | 172.20.57.102 | <none> | 8000/TCP | 217d | app=aisrvhistory-executor-prod |
| service/aisrvhistory-planner-prod | ClusterIP | 172.20.73.170 | <none> | 8000/TCP | 217d | app=aisrvhistory-planner-prod |
| service/aisrvhistory-prod | ClusterIP | 172.20.152.35 | <none> | 8000/TCP | 418d | app=aisrvhistory-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisrvhistory-planner-prod | 3/3 | 3 | 3 | 217d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-prod |
| deployment.apps/aisrvhistory-prod | 2/2 | 2 | 2 | 418d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.93 | app=aisrvhistory-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisrvhistory-planner-prod-567dfb9b58 | 0 | 0 | 0 | 4d23h | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-prod,pod-template-hash=567dfb9b58 |
| replicaset.apps/aisrvhistory-planner-prod-59c795766c | 0 | 0 | 0 | 136d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:0.0.331 | app=aisrvhistory-planner-prod,pod-template-hash=59c795766c |
| replicaset.apps/aisrvhistory-planner-prod-5cdcc76d9b | 0 | 0 | 0 | 95d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.122 | app=aisrvhistory-planner-prod,pod-template-hash=5cdcc76d9b |
| replicaset.apps/aisrvhistory-planner-prod-687d6d9554 | 0 | 0 | 0 | 48d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.350 | app=aisrvhistory-planner-prod,pod-template-hash=687d6d9554 |
| replicaset.apps/aisrvhistory-planner-prod-6d8786f49 | 0 | 0 | 0 | 95d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.122 | app=aisrvhistory-planner-prod,pod-template-hash=6d8786f49 |
| replicaset.apps/aisrvhistory-planner-prod-6fbd74c9db | 0 | 0 | 0 | 75d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.341 | app=aisrvhistory-planner-prod,pod-template-hash=6fbd74c9db |
| replicaset.apps/aisrvhistory-planner-prod-745cccbcdd | 0 | 0 | 0 | 81d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.340 | app=aisrvhistory-planner-prod,pod-template-hash=745cccbcdd |
| replicaset.apps/aisrvhistory-planner-prod-7d6ffb4dbd | 3 | 3 | 3 | 4d22h | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-prod,pod-template-hash=7d6ffb4dbd |
| replicaset.apps/aisrvhistory-planner-prod-7ff8b66fc7 | 0 | 0 | 0 | 5d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:6.0.85 | app=aisrvhistory-planner-prod,pod-template-hash=7ff8b66fc7 |
| replicaset.apps/aisrvhistory-planner-prod-994ccd856 | 0 | 0 | 0 | 18d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.351 | app=aisrvhistory-planner-prod,pod-template-hash=994ccd856 |
| replicaset.apps/aisrvhistory-planner-prod-dff45f798 | 0 | 0 | 0 | 60d | aisrvhistory-planner-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-sh-planner:5.0.345 | app=aisrvhistory-planner-prod,pod-template-hash=dff45f798 |
| replicaset.apps/aisrvhistory-prod-55bb6849b9 | 0 | 0 | 0 | 48d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.135 | app=aisrvhistory-prod,pod-template-hash=55bb6849b9 |
| replicaset.apps/aisrvhistory-prod-58dc47785f | 0 | 0 | 0 | 60d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.130 | app=aisrvhistory-prod,pod-template-hash=58dc47785f |
| replicaset.apps/aisrvhistory-prod-5b785f9477 | 0 | 0 | 0 | 95d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.122 | app=aisrvhistory-prod,pod-template-hash=5b785f9477 |
| replicaset.apps/aisrvhistory-prod-5d57fc4688 | 0 | 0 | 0 | 5d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.93 | app=aisrvhistory-prod,pod-template-hash=5d57fc4688 |
| replicaset.apps/aisrvhistory-prod-5fd5ff9787 | 0 | 0 | 0 | 81d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.125 | app=aisrvhistory-prod,pod-template-hash=5fd5ff9787 |
| replicaset.apps/aisrvhistory-prod-6446f79c84 | 2 | 2 | 2 | 4d23h | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.93 | app=aisrvhistory-prod,pod-template-hash=6446f79c84 |
| replicaset.apps/aisrvhistory-prod-66c7d5bb4c | 0 | 0 | 0 | 130d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:4.0.71 | app=aisrvhistory-prod,pod-template-hash=66c7d5bb4c |
| replicaset.apps/aisrvhistory-prod-6b5f7b76b9 | 0 | 0 | 0 | 4d23h | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:6.0.93 | app=aisrvhistory-prod,pod-template-hash=6b5f7b76b9 |
| replicaset.apps/aisrvhistory-prod-77b66f499f | 0 | 0 | 0 | 18d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.136 | app=aisrvhistory-prod,pod-template-hash=77b66f499f |
| replicaset.apps/aisrvhistory-prod-7d79fc9889 | 0 | 0 | 0 | 95d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:5.0.122 | app=aisrvhistory-prod,pod-template-hash=7d79fc9889 |
| replicaset.apps/aisrvhistory-prod-85f77cb575 | 0 | 0 | 0 | 111d | aisrvhistory-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-srvhistory:4.0.74 | app=aisrvhistory-prod,pod-template-hash=85f77cb575 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-planner-prod-us-east-1 | Deployment/aisrvhistory-planner-prod | cpu: 3%/80%, memory: 38%/70% | 3 | 4 | 3 | 217d |
| horizontalpodautoscaler.autoscaling/ai-srvhistory-prod-us-east-1 | Deployment/aisrvhistory-prod | cpu: 1%/80%, memory: 34%/80% | 2 | 4 | 2 | 418d |

---

## Namespace: aisummary-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisummary-patch-7c7c774bf9-p44gw | 1/1 | Running | 0 | 2d22h | 10.111.174.11 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/aisummary-patch-7c7c774bf9-vzq9s | 1/1 | Running | 0 | 2d22h | 10.111.221.165 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisummary-patch | ClusterIP | 172.20.54.227 | <none> | 8000/TCP | 417d | app=aisummary-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisummary-patch | 2/2 | 2 | 2 | 417d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.12 | app=aisummary-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisummary-patch-5797dbd9bd | 0 | 0 | 0 | 201d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:4.0.5 | app=aisummary-patch,pod-template-hash=5797dbd9bd |
| replicaset.apps/aisummary-patch-5c55fbb694 | 0 | 0 | 0 | 99d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.7 | app=aisummary-patch,pod-template-hash=5c55fbb694 |
| replicaset.apps/aisummary-patch-69d8b9d644 | 0 | 0 | 0 | 88d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.10 | app=aisummary-patch,pod-template-hash=69d8b9d644 |
| replicaset.apps/aisummary-patch-6cb4b884cb | 0 | 0 | 0 | 56d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.11 | app=aisummary-patch,pod-template-hash=6cb4b884cb |
| replicaset.apps/aisummary-patch-6dc74755cd | 0 | 0 | 0 | 88d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.9 | app=aisummary-patch,pod-template-hash=6dc74755cd |
| replicaset.apps/aisummary-patch-7c7c774bf9 | 2 | 2 | 2 | 2d22h | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.12 | app=aisummary-patch,pod-template-hash=7c7c774bf9 |
| replicaset.apps/aisummary-patch-7d9774fcd8 | 0 | 0 | 0 | 18d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.13 | app=aisummary-patch,pod-template-hash=7d9774fcd8 |
| replicaset.apps/aisummary-patch-86f5f4dd | 0 | 0 | 0 | 88d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.8 | app=aisummary-patch,pod-template-hash=86f5f4dd |
| replicaset.apps/aisummary-patch-cb7c84b4 | 0 | 0 | 0 | 12d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.11 | app=aisummary-patch,pod-template-hash=cb7c84b4 |
| replicaset.apps/aisummary-patch-d4cbc5776 | 0 | 0 | 0 | 154d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:4.0.7 | app=aisummary-patch,pod-template-hash=d4cbc5776 |
| replicaset.apps/aisummary-patch-db97cf5cd | 0 | 0 | 0 | 144d | aisummary-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:4.0.8 | app=aisummary-patch,pod-template-hash=db97cf5cd |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-summary-patch-us-east-1 | Deployment/aisummary-patch | cpu: 3%/80%, memory: 32%/80% | 2 | 4 | 2 | 417d |

---

## Namespace: aisummary-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aisummary-prod-cc66c8874-jr2np | 1/1 | Running | 0 | 4d23h | 10.111.233.80 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/aisummary-prod-cc66c8874-ns6g6 | 1/1 | Running | 0 | 4d23h | 10.111.141.97 | ip-10-111-131-191.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/aisummary-prod | ClusterIP | 172.20.177.80 | <none> | 8000/TCP | 418d | app=aisummary-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/aisummary-prod | 2/2 | 2 | 2 | 418d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.11 | app=aisummary-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/aisummary-prod-5c9677bddb | 0 | 0 | 0 | 5d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.11 | app=aisummary-prod,pod-template-hash=5c9677bddb |
| replicaset.apps/aisummary-prod-68dc88978f | 0 | 0 | 0 | 18d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.13 | app=aisummary-prod,pod-template-hash=68dc88978f |
| replicaset.apps/aisummary-prod-6ffb58b8d5 | 0 | 0 | 0 | 279d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:3.0.12 | app=aisummary-prod,pod-template-hash=6ffb58b8d5 |
| replicaset.apps/aisummary-prod-765b78bc4c | 0 | 0 | 0 | 95d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.7 | app=aisummary-prod,pod-template-hash=765b78bc4c |
| replicaset.apps/aisummary-prod-796775d8b7 | 0 | 0 | 0 | 136d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:4.0.8 | app=aisummary-prod,pod-template-hash=796775d8b7 |
| replicaset.apps/aisummary-prod-7cb9749c89 | 0 | 0 | 0 | 48d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.11 | app=aisummary-prod,pod-template-hash=7cb9749c89 |
| replicaset.apps/aisummary-prod-7dd4f8887c | 0 | 0 | 0 | 188d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:4.0.5 | app=aisummary-prod,pod-template-hash=7dd4f8887c |
| replicaset.apps/aisummary-prod-856b99b697 | 0 | 0 | 0 | 227d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:3.0.15 | app=aisummary-prod,pod-template-hash=856b99b697 |
| replicaset.apps/aisummary-prod-b6954c95c | 0 | 0 | 0 | 262d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:3.0.14 | app=aisummary-prod,pod-template-hash=b6954c95c |
| replicaset.apps/aisummary-prod-cc66c8874 | 2 | 2 | 2 | 4d23h | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:6.0.11 | app=aisummary-prod,pod-template-hash=cc66c8874 |
| replicaset.apps/aisummary-prod-cfc6f8ffc | 0 | 0 | 0 | 81d | aisummary-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-ai-summary:5.0.10 | app=aisummary-prod,pod-template-hash=cfc6f8ffc |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/ai-summary-prod-us-east-1 | Deployment/aisummary-prod | cpu: 4%/80%, memory: 34%/80% | 2 | 4 | 2 | 418d |

---

## Namespace: amazon-guardduty

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/aws-guardduty-agent-2p7f2 | 1/1 | Running | 0 | 11d | 10.111.131.191 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-4xsbr | 1/1 | Running | 0 | 11d | 10.111.233.47 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-8xsc5 | 1/1 | Running | 0 | 11d | 10.111.109.229 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-b7qdr | 1/1 | Running | 0 | 11d | 10.111.82.117 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-bpj85 | 1/1 | Running | 0 | 11d | 10.111.197.112 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-cx7hw | 1/1 | Running | 0 | 11d | 10.111.173.237 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-dpk6g | 1/1 | Running | 0 | 11d | 10.111.186.238 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-g75jd | 1/1 | Running | 0 | 11d | 10.111.135.235 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-kcv2r | 1/1 | Running | 0 | 11d | 10.111.65.28 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-nmjtl | 1/1 | Running | 0 | 11d | 10.111.128.40 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-nvzx2 | 1/1 | Running | 0 | 11d | 10.111.242.186 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-q2dzg | 1/1 | Running | 0 | 11d | 10.111.211.170 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-wgb92 | 1/1 | Running | 0 | 5d2h | 10.111.167.65 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-x628h | 1/1 | Running | 0 | 11d | 10.111.99.36 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/aws-guardduty-agent-zlpjl | 1/1 | Running | 0 | 11d | 10.111.238.32 | ip-10-111-238-32.ec2.internal | <none> | <none> |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/aws-guardduty-agent | 15 | 15 | 15 | 15 | 15 | <none> | 431d | aws-guardduty-agent | 602401143452.dkr.ecr.us-east-1.amazonaws.com/aws-guardduty-agent:v1.15.0 | app.kubernetes.io/name=aws-guardduty-agent |

---

## Namespace: ingress-nginx-smax-api-ext-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-api-ext-patch-controller-2m2dx | 1/1 | Running | 0 | 11d | 10.111.113.48 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-6khzd | 1/1 | Running | 0 | 11d | 10.111.186.141 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-7m2sp | 1/1 | Running | 0 | 11d | 10.111.253.118 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-8hm87 | 1/1 | Running | 0 | 11d | 10.111.160.180 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-8jdmr | 1/1 | Running | 0 | 11d | 10.111.238.243 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-8kdz4 | 1/1 | Running | 0 | 11d | 10.111.174.126 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-mtvch | 1/1 | Running | 0 | 5d2h | 10.111.188.193 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-rm2hh | 1/1 | Running | 0 | 11d | 10.111.116.61 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-rqf5h | 1/1 | Running | 0 | 11d | 10.111.69.63 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-tb5pq | 1/1 | Running | 0 | 11d | 10.111.138.193 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-tmfr9 | 1/1 | Running | 0 | 11d | 10.111.237.60 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-vn5zk | 1/1 | Running | 0 | 11d | 10.111.239.220 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-wwkp6 | 1/1 | Running | 0 | 11d | 10.111.109.158 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-wzd4h | 1/1 | Running | 0 | 11d | 10.111.181.204 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-patch-controller-xtj29 | 1/1 | Running | 0 | 11d | 10.111.216.130 | ip-10-111-211-170.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-api-ext-patch-controller | LoadBalancer | 172.20.169.166 | a592af83085244bf98d6e1b398618085-f2840f8f9e28f5de.elb.us-east-1.amazonaws.com | 443:30724/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-api-ext-patch |
| service/ingress-nginx-smax-api-ext-patch-controller-admission | ClusterIP | 172.20.232.88 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-api-ext-patch |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-api-ext-patch-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-api-ext-patch |

---

## Namespace: ingress-nginx-smax-api-ext-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-api-ext-prod-controller-6s5v6 | 1/1 | Running | 0 | 11d | 10.111.245.112 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-7kvp9 | 1/1 | Running | 0 | 5d2h | 10.111.152.25 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-7zt2q | 1/1 | Running | 0 | 11d | 10.111.255.184 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-dbrrv | 1/1 | Running | 0 | 11d | 10.111.243.236 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-dhmmx | 1/1 | Running | 0 | 11d | 10.111.87.45 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-hlj4g | 1/1 | Running | 0 | 11d | 10.111.144.13 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-n25x8 | 1/1 | Running | 0 | 11d | 10.111.209.11 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-nchl9 | 1/1 | Running | 0 | 11d | 10.111.147.149 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-p557g | 1/1 | Running | 0 | 11d | 10.111.223.4 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-p8qft | 1/1 | Running | 0 | 11d | 10.111.149.81 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-tx9dq | 1/1 | Running | 0 | 11d | 10.111.70.98 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-x52pw | 1/1 | Running | 0 | 11d | 10.111.172.164 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-zjndw | 1/1 | Running | 0 | 11d | 10.111.120.23 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-zrm52 | 1/1 | Running | 0 | 11d | 10.111.166.24 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-ext-prod-controller-zxlhd | 1/1 | Running | 0 | 11d | 10.111.123.113 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-api-ext-prod-controller | LoadBalancer | 172.20.67.5 | a047b241bdaf44302aca3abedb0a4e5b-0ee3d14674a8bf47.elb.us-east-1.amazonaws.com | 443:32046/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-api-ext-prod |
| service/ingress-nginx-smax-api-ext-prod-controller-admission | ClusterIP | 172.20.90.145 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-api-ext-prod |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-api-ext-prod-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-api-ext-prod |

---

## Namespace: ingress-nginx-smax-api-internal-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-api-internal-patch-controller-4grxn | 1/1 | Running | 0 | 11d | 10.111.213.45 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-69wmz | 1/1 | Running | 0 | 11d | 10.111.173.100 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-c8rq4 | 1/1 | Running | 0 | 5d2h | 10.111.173.91 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-fc4wx | 1/1 | Running | 0 | 11d | 10.111.236.128 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-kv8h9 | 1/1 | Running | 0 | 11d | 10.111.138.64 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-lb4m4 | 1/1 | Running | 0 | 11d | 10.111.73.130 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-lmht2 | 1/1 | Running | 0 | 11d | 10.111.155.128 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-lp5gd | 1/1 | Running | 0 | 11d | 10.111.190.245 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-n4vwp | 1/1 | Running | 0 | 11d | 10.111.232.53 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-rf7gc | 1/1 | Running | 0 | 11d | 10.111.95.218 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-sqrjc | 1/1 | Running | 0 | 11d | 10.111.231.175 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-tpm4p | 1/1 | Running | 0 | 11d | 10.111.236.77 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-x5p4x | 1/1 | Running | 0 | 11d | 10.111.103.72 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-z7bnd | 1/1 | Running | 0 | 11d | 10.111.130.200 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-patch-controller-z7g6l | 1/1 | Running | 0 | 11d | 10.111.68.237 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-api-internal-patch-controller | LoadBalancer | 172.20.7.52 | a79f07bd624234ce5ab26c8c6d4edcb2-d00c4b772e54133a.elb.us-east-1.amazonaws.com | 443:31137/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-api-internal-patch |
| service/ingress-nginx-smax-api-internal-patch-controller-admission | ClusterIP | 172.20.93.7 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-api-internal-patch |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-api-internal-patch-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-api-internal-patch |

---

## Namespace: ingress-nginx-smax-api-internal-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-api-internal-prod-controller-5gp7p | 1/1 | Running | 0 | 11d | 10.111.251.240 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-crrgb | 1/1 | Running | 0 | 11d | 10.111.107.134 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-cxhbn | 1/1 | Running | 0 | 11d | 10.111.98.127 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-g5pl6 | 1/1 | Running | 0 | 11d | 10.111.121.159 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-ggzx7 | 1/1 | Running | 0 | 11d | 10.111.103.171 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-h89rn | 1/1 | Running | 0 | 11d | 10.111.151.20 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-jhf2k | 1/1 | Running | 0 | 11d | 10.111.188.135 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-r7kb6 | 1/1 | Running | 0 | 11d | 10.111.186.102 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-rhg9l | 1/1 | Running | 0 | 5d2h | 10.111.181.36 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-rxz65 | 1/1 | Running | 0 | 11d | 10.111.231.205 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-tr9zs | 1/1 | Running | 0 | 11d | 10.111.191.122 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-wd4w2 | 1/1 | Running | 0 | 11d | 10.111.237.67 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-wpr6w | 1/1 | Running | 0 | 11d | 10.111.206.127 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-xjj6v | 1/1 | Running | 0 | 11d | 10.111.144.79 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-api-internal-prod-controller-zvnhs | 1/1 | Running | 0 | 11d | 10.111.217.204 | ip-10-111-233-47.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-api-internal-prod-controller | LoadBalancer | 172.20.52.200 | a221c87b597ed46f6b56a419618f7fb6-ccfdf8ff7be88df9.elb.us-east-1.amazonaws.com | 443:30308/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-api-internal-prod |
| service/ingress-nginx-smax-api-internal-prod-controller-admission | ClusterIP | 172.20.22.46 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-api-internal-prod |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-api-internal-prod-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-api-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-api-internal-prod |

---

## Namespace: ingress-nginx-smax-io-ext-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-io-ext-patch-controller-7v84k | 1/1 | Running | 0 | 11d | 10.111.211.142 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-8pkmp | 1/1 | Running | 0 | 11d | 10.111.146.45 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-fbllp | 1/1 | Running | 0 | 11d | 10.111.157.141 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-g295r | 1/1 | Running | 0 | 11d | 10.111.65.189 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-g6gn6 | 1/1 | Running | 0 | 11d | 10.111.90.95 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-k2qkt | 1/1 | Running | 0 | 11d | 10.111.201.255 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-k58x7 | 1/1 | Running | 0 | 11d | 10.111.65.144 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-kcgmz | 1/1 | Running | 0 | 11d | 10.111.224.234 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-n8j2h | 1/1 | Running | 0 | 11d | 10.111.169.178 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-qbpkz | 1/1 | Running | 0 | 11d | 10.111.223.192 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-v9wm2 | 1/1 | Running | 0 | 11d | 10.111.129.71 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-xfw2h | 1/1 | Running | 0 | 11d | 10.111.225.103 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-z7rjq | 1/1 | Running | 0 | 11d | 10.111.108.104 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-zkfjt | 1/1 | Running | 0 | 5d2h | 10.111.186.26 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-patch-controller-zxffz | 1/1 | Running | 0 | 11d | 10.111.129.124 | ip-10-111-135-235.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-io-ext-patch-controller | LoadBalancer | 172.20.17.98 | ad2b510b693584d85b948e25dad4420f-32ebf26f7d3b34a6.elb.us-east-1.amazonaws.com | 80:30677/TCP,443:31838/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-io-ext-patch |
| service/ingress-nginx-smax-io-ext-patch-controller-admission | ClusterIP | 172.20.85.55 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-io-ext-patch |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-io-ext-patch-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-patch,app.kubernetes.io/name=ingress-nginx-smax-io-ext-patch |

---

## Namespace: ingress-nginx-smax-io-ext-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-io-ext-prod-controller-58ftb | 1/1 | Running | 0 | 11d | 10.111.209.74 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-6v2lz | 1/1 | Running | 0 | 11d | 10.111.173.214 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-b6bmm | 1/1 | Running | 0 | 11d | 10.111.152.178 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-d6fbn | 1/1 | Running | 0 | 11d | 10.111.246.98 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-h4bzg | 1/1 | Running | 0 | 11d | 10.111.66.8 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-hbswl | 1/1 | Running | 0 | 11d | 10.111.208.72 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-j9qvm | 1/1 | Running | 0 | 5d2h | 10.111.164.62 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-jvjrj | 1/1 | Running | 0 | 11d | 10.111.229.2 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-l5dc2 | 1/1 | Running | 0 | 11d | 10.111.111.140 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-q88jk | 1/1 | Running | 0 | 11d | 10.111.153.97 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-r6c8f | 1/1 | Running | 0 | 11d | 10.111.195.159 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-tnmms | 1/1 | Running | 0 | 11d | 10.111.76.150 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-x4jng | 1/1 | Running | 0 | 11d | 10.111.118.86 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-xcvpf | 1/1 | Running | 0 | 11d | 10.111.135.12 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-ext-prod-controller-zx2tc | 1/1 | Running | 0 | 11d | 10.111.179.98 | ip-10-111-131-191.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-io-ext-prod-controller | LoadBalancer | 172.20.124.81 | a154b9bee620e4946b5f82dd5685d833-833649c07e5f3304.elb.us-east-1.amazonaws.com | 80:30515/TCP,443:32056/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-io-ext-prod |
| service/ingress-nginx-smax-io-ext-prod-controller-admission | ClusterIP | 172.20.72.203 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-io-ext-prod |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-io-ext-prod-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-ext-prod,app.kubernetes.io/name=ingress-nginx-smax-io-ext-prod |

---

## Namespace: ingress-nginx-smax-io-internal-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-io-internal-patch-controller-5fxxp | 1/1 | Running | 0 | 11d | 10.111.136.196 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-6kwxg | 1/1 | Running | 0 | 5d2h | 10.111.167.145 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-8m4hw | 1/1 | Running | 0 | 11d | 10.111.243.139 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-ffrzz | 1/1 | Running | 0 | 11d | 10.111.173.12 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-flmq7 | 1/1 | Running | 0 | 11d | 10.111.195.107 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-fz26q | 1/1 | Running | 0 | 11d | 10.111.94.64 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-k67lz | 1/1 | Running | 0 | 11d | 10.111.132.154 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-kjvts | 1/1 | Running | 0 | 11d | 10.111.66.198 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-pg5q2 | 1/1 | Running | 0 | 11d | 10.111.173.19 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-q25cf | 1/1 | Running | 0 | 11d | 10.111.251.97 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-q9dn9 | 1/1 | Running | 0 | 11d | 10.111.111.84 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-rdlbz | 1/1 | Running | 0 | 11d | 10.111.160.210 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-s9kp9 | 1/1 | Running | 0 | 11d | 10.111.218.240 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-wj555 | 1/1 | Running | 0 | 11d | 10.111.212.183 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-patch-controller-wvszd | 1/1 | Running | 0 | 11d | 10.111.119.167 | ip-10-111-99-36.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-io-internal-patch-controller | LoadBalancer | 172.20.127.94 | a489f937411e94b649fc4a0158b858ba-9a10c52c4c843764.elb.us-east-1.amazonaws.com | 80:31815/TCP,443:32608/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-io-internal-patch |
| service/ingress-nginx-smax-io-internal-patch-controller-admission | ClusterIP | 172.20.1.20 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-io-internal-patch |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-io-internal-patch-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-patch,app.kubernetes.io/name=ingress-nginx-smax-io-internal-patch |

### Jobs

| NAME | STATUS | COMPLETIONS | DURATION | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| job.batch/ingress-nginx-smax-io-internal-patch-admission-create | Complete | 1/1 | 4s | 116d | create | registry.k8s.io/ingress-nginx/kube-webhook-certgen:v1.6.7@sha256:7c74a715af2c94cb734785b4d3ea1357b4f02b88e1e123c622a9cb68b62f669c | batch.kubernetes.io/controller-uid=b5a4f869-eb49-4f98-95fb-44f8ed6a725c |
| job.batch/ingress-nginx-smax-io-internal-patch-admission-patch | Complete | 1/1 | 4s | 116d | patch | registry.k8s.io/ingress-nginx/kube-webhook-certgen:v1.6.7@sha256:7c74a715af2c94cb734785b4d3ea1357b4f02b88e1e123c622a9cb68b62f669c | batch.kubernetes.io/controller-uid=9f18d278-b6d0-416b-96f1-bb2d5d26dca5 |

---

## Namespace: ingress-nginx-smax-io-internal-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/ingress-nginx-smax-io-internal-prod-controller-25jmn | 1/1 | Running | 0 | 5d2h | 10.111.190.205 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-65blk | 1/1 | Running | 0 | 11d | 10.111.208.76 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-bc28j | 1/1 | Running | 0 | 11d | 10.111.173.15 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-bf7tn | 1/1 | Running | 0 | 11d | 10.111.194.54 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-dfs5f | 1/1 | Running | 0 | 11d | 10.111.147.94 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-jvmss | 1/1 | Running | 0 | 11d | 10.111.153.208 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-ljffw | 1/1 | Running | 0 | 11d | 10.111.131.212 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-m2vm5 | 1/1 | Running | 0 | 11d | 10.111.72.166 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-mbp55 | 1/1 | Running | 0 | 11d | 10.111.196.70 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-rv58r | 1/1 | Running | 0 | 11d | 10.111.123.44 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-vcn5s | 1/1 | Running | 0 | 11d | 10.111.104.60 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-wbqvh | 1/1 | Running | 0 | 11d | 10.111.229.138 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-wzfxp | 1/1 | Running | 0 | 11d | 10.111.230.159 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-x2pfq | 1/1 | Running | 0 | 11d | 10.111.152.198 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/ingress-nginx-smax-io-internal-prod-controller-zm6kg | 1/1 | Running | 0 | 11d | 10.111.108.51 | ip-10-111-82-117.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/ingress-nginx-smax-io-internal-prod-controller | LoadBalancer | 172.20.136.125 | a2b35cad86a8e4957a41a6f6134ac079-2cfef9b4e1cb98a9.elb.us-east-1.amazonaws.com | 80:32052/TCP,443:30807/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-io-internal-prod |
| service/ingress-nginx-smax-io-internal-prod-controller-admission | ClusterIP | 172.20.3.186 | <none> | 443/TCP | 420d | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-io-internal-prod |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/ingress-nginx-smax-io-internal-prod-controller | 13 | 13 | 13 | 13 | 13 | kubernetes.io/os=linux | 420d | controller | registry.k8s.io/ingress-nginx/controller:v1.14.3@sha256:82917be97c0939f6ada1717bb39aa7e66c229d6cfb10dcfc8f1bd42f9efe0f81 | app.kubernetes.io/component=controller,app.kubernetes.io/instance=ingress-nginx-smax-io-internal-prod,app.kubernetes.io/name=ingress-nginx-smax-io-internal-prod |

### Jobs

| NAME | STATUS | COMPLETIONS | DURATION | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| job.batch/ingress-nginx-smax-io-internal-prod-admission-create | Complete | 1/1 | 6s | 109d | create | registry.k8s.io/ingress-nginx/kube-webhook-certgen:v1.5.2@sha256:e8825994b7a2c7497375a9b945f386506ca6a3eda80b89b74ef2db743f66a5ea | batch.kubernetes.io/controller-uid=2407eb17-addf-43d4-9989-695c625a1032 |
| job.batch/ingress-nginx-smax-io-internal-prod-admission-patch | Complete | 1/1 | 5s | 109d | patch | registry.k8s.io/ingress-nginx/kube-webhook-certgen:v1.6.7@sha256:7c74a715af2c94cb734785b4d3ea1357b4f02b88e1e123c622a9cb68b62f669c | batch.kubernetes.io/controller-uid=1789ced2-4fa7-4bdc-8087-91470acc0f6a |

---

## Namespace: newrelic

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/newrelic-bundle-kube-state-metrics-b9ccc4df-sjz9m | 1/1 | Running | 0 | 11d | 10.111.141.157 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-newrelic-prometheus-agent-0 | 1/1 | Running | 0 | 11d | 10.111.154.160 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nri-kube-events-75764df785-wxcnm | 2/2 | Running | 0 | 11d | 10.111.200.29 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nri-metadata-injection-7f8bff5697-x8rhg | 1/1 | Running | 0 | 11d | 10.111.133.145 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-ksm-67fdbc987-ql2m9 | 2/2 | Running | 0 | 11d | 10.111.183.21 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-42tmm | 2/2 | Running | 0 | 5d2h | 10.111.151.151 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-5vxgw | 2/2 | Running | 0 | 11d | 10.111.109.89 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-bj99b | 2/2 | Running | 0 | 11d | 10.111.240.166 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-crfvs | 2/2 | Running | 0 | 11d | 10.111.151.199 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-d7z4d | 2/2 | Running | 0 | 11d | 10.111.224.29 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-jb77p | 2/2 | Running | 0 | 11d | 10.111.253.244 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-l6lcs | 2/2 | Running | 0 | 11d | 10.111.145.181 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-mgqn8 | 2/2 | Running | 0 | 11d | 10.111.176.45 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-nglj5 | 2/2 | Running | 0 | 11d | 10.111.156.111 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-qgqtl | 2/2 | Running | 0 | 11d | 10.111.104.220 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-r94kt | 2/2 | Running | 0 | 11d | 10.111.180.87 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-sm86w | 2/2 | Running | 0 | 11d | 10.111.210.222 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-vfvs8 | 2/2 | Running | 0 | 11d | 10.111.81.106 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-w72rm | 2/2 | Running | 0 | 11d | 10.111.73.113 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/newrelic-bundle-nrk8s-kubelet-wmdjz | 2/2 | Running | 0 | 11d | 10.111.196.216 | ip-10-111-242-186.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/newrelic-bundle-kube-state-metrics | ClusterIP | 172.20.26.10 | <none> | 8080/TCP | 421d | app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=kube-state-metrics |
| service/newrelic-bundle-nri-metadata-injection | ClusterIP | 172.20.185.89 | <none> | 443/TCP | 421d | app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=nri-metadata-injection |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/newrelic-bundle-nrk8s-controlplane | 0 | 0 | 0 | 0 | 0 | kubernetes.io/os=linux | 421d | controlplane,forwarder | docker.io/newrelic/nri-kubernetes:3.54.0,docker.io/newrelic/k8s-events-forwarder:1.72.3 | app.kubernetes.io/component=controlplane,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure |
| daemonset.apps/newrelic-bundle-nrk8s-kubelet | 15 | 15 | 15 | 15 | 15 | kubernetes.io/os=linux | 421d | kubelet,agent | docker.io/newrelic/nri-kubernetes:3.54.0,docker.io/newrelic/infrastructure-bundle:3.3.13 | app.kubernetes.io/component=kubelet,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/newrelic-bundle-kube-state-metrics | 1/1 | 1 | 1 | 421d | kube-state-metrics | registry.k8s.io/kube-state-metrics/kube-state-metrics:v2.16.0 | app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=kube-state-metrics |
| deployment.apps/newrelic-bundle-nri-kube-events | 1/1 | 1 | 1 | 421d | kube-events,forwarder | docker.io/newrelic/nri-kube-events:2.18.1,docker.io/newrelic/k8s-events-forwarder:1.72.1 | app.kubernetes.io/name=nri-kube-events |
| deployment.apps/newrelic-bundle-nri-metadata-injection | 1/1 | 1 | 1 | 421d | nri-metadata-injection | docker.io/newrelic/k8s-metadata-injection:1.41.0 | app.kubernetes.io/name=nri-metadata-injection |
| deployment.apps/newrelic-bundle-nrk8s-ksm | 1/1 | 1 | 1 | 421d | ksm,forwarder | docker.io/newrelic/nri-kubernetes:3.54.0,docker.io/newrelic/k8s-events-forwarder:1.72.3 | app.kubernetes.io/component=ksm,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/newrelic-bundle-kube-state-metrics-b9ccc4df | 1 | 1 | 1 | 217d | kube-state-metrics | registry.k8s.io/kube-state-metrics/kube-state-metrics:v2.16.0 | app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=kube-state-metrics,pod-template-hash=b9ccc4df |
| replicaset.apps/newrelic-bundle-kube-state-metrics-d47796f54 | 0 | 0 | 0 | 421d | kube-state-metrics | registry.k8s.io/kube-state-metrics/kube-state-metrics:v2.15.0 | app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=kube-state-metrics,pod-template-hash=d47796f54 |
| replicaset.apps/newrelic-bundle-nri-kube-events-5554b574fc | 0 | 0 | 0 | 421d | kube-events,forwarder | newrelic/nri-kube-events:2.12.0,newrelic/k8s-events-forwarder:1.62.0 | app.kubernetes.io/name=nri-kube-events,pod-template-hash=5554b574fc |
| replicaset.apps/newrelic-bundle-nri-kube-events-75764df785 | 1 | 1 | 1 | 108d | kube-events,forwarder | docker.io/newrelic/nri-kube-events:2.18.1,docker.io/newrelic/k8s-events-forwarder:1.72.1 | app.kubernetes.io/name=nri-kube-events,pod-template-hash=75764df785 |
| replicaset.apps/newrelic-bundle-nri-kube-events-789fb69566 | 0 | 0 | 0 | 217d | kube-events,forwarder | newrelic/nri-kube-events:2.16.1,newrelic/k8s-events-forwarder:1.69.0 | app.kubernetes.io/name=nri-kube-events,pod-template-hash=789fb69566 |
| replicaset.apps/newrelic-bundle-nri-metadata-injection-648b449fc8 | 0 | 0 | 0 | 421d | nri-metadata-injection | newrelic/k8s-metadata-injection:1.32.2 | app.kubernetes.io/name=nri-metadata-injection,pod-template-hash=648b449fc8 |
| replicaset.apps/newrelic-bundle-nri-metadata-injection-67b6b69d4d | 0 | 0 | 0 | 217d | nri-metadata-injection | newrelic/k8s-metadata-injection:1.38.1 | app.kubernetes.io/name=nri-metadata-injection,pod-template-hash=67b6b69d4d |
| replicaset.apps/newrelic-bundle-nri-metadata-injection-7f8bff5697 | 1 | 1 | 1 | 108d | nri-metadata-injection | docker.io/newrelic/k8s-metadata-injection:1.41.0 | app.kubernetes.io/name=nri-metadata-injection,pod-template-hash=7f8bff5697 |
| replicaset.apps/newrelic-bundle-nrk8s-ksm-67fdbc987 | 1 | 1 | 1 | 108d | ksm,forwarder | docker.io/newrelic/nri-kubernetes:3.54.0,docker.io/newrelic/k8s-events-forwarder:1.72.3 | app.kubernetes.io/component=ksm,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure,pod-template-hash=67fdbc987 |
| replicaset.apps/newrelic-bundle-nrk8s-ksm-7b87777fdd | 0 | 0 | 0 | 421d | ksm,forwarder | newrelic/nri-kubernetes:3.38.0,newrelic/k8s-events-forwarder:1.63.1 | app.kubernetes.io/component=ksm,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure,pod-template-hash=7b87777fdd |
| replicaset.apps/newrelic-bundle-nrk8s-ksm-7bf7c8bb6b | 0 | 0 | 0 | 217d | ksm,forwarder | newrelic/nri-kubernetes:3.50.0,newrelic/k8s-events-forwarder:1.71.0 | app.kubernetes.io/component=ksm,app.kubernetes.io/instance=newrelic-bundle,app.kubernetes.io/name=newrelic-infrastructure,pod-template-hash=7bf7c8bb6b |

### StatefulSets

| NAME | READY | AGE | CONTAINERS | IMAGES |
| --- | --- | --- | --- | --- |
| statefulset.apps/newrelic-bundle-newrelic-prometheus-agent | 1/1 | 421d | prometheus | quay.io/prometheus/prometheus:v3.8.0 |

---

## Namespace: serviceboard-ai-patch

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/serviceboard-ai-patch-5d97c8f5c7-7ltnl | 1/1 | Running | 0 | 9d | 10.111.232.32 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/serviceboard-ai-patch-5d97c8f5c7-h6gp9 | 1/1 | Running | 0 | 9d | 10.111.135.21 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/serviceboard-ai-patch-5d97c8f5c7-qldrm | 1/1 | Running | 0 | 9d | 10.111.112.249 | ip-10-111-65-28.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/serviceboard-ai-patch | ClusterIP | 172.20.128.18 | <none> | 8000/TCP | 384d | app=serviceboard-ai-patch |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/serviceboard-ai-patch | 3/3 | 3 | 3 | 384d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.4.11 | app=serviceboard-ai-patch |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/serviceboard-ai-patch-5695f96f9d | 0 | 0 | 0 | 190d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.2.15 | app=serviceboard-ai-patch,pod-template-hash=5695f96f9d |
| replicaset.apps/serviceboard-ai-patch-5774fd8bbd | 0 | 0 | 0 | 98d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.10 | app=serviceboard-ai-patch,pod-template-hash=5774fd8bbd |
| replicaset.apps/serviceboard-ai-patch-59fd4d5447 | 0 | 0 | 0 | 384d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.49 | app=serviceboard-ai-patch,pod-template-hash=59fd4d5447 |
| replicaset.apps/serviceboard-ai-patch-5b54c5fdd8 | 0 | 0 | 0 | 54d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.12 | app=serviceboard-ai-patch,pod-template-hash=5b54c5fdd8 |
| replicaset.apps/serviceboard-ai-patch-5cf57d447c | 0 | 0 | 0 | 190d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.2.15 | app=serviceboard-ai-patch,pod-template-hash=5cf57d447c |
| replicaset.apps/serviceboard-ai-patch-5d97c8f5c7 | 3 | 3 | 3 | 9d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.4.11 | app=serviceboard-ai-patch,pod-template-hash=5d97c8f5c7 |
| replicaset.apps/serviceboard-ai-patch-5fc9486879 | 0 | 0 | 0 | 190d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.2.15 | app=serviceboard-ai-patch,pod-template-hash=5fc9486879 |
| replicaset.apps/serviceboard-ai-patch-647b55688c | 0 | 0 | 0 | 375d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-patch,pod-template-hash=647b55688c |
| replicaset.apps/serviceboard-ai-patch-748d8d6bd4 | 0 | 0 | 0 | 98d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.2.15 | app=serviceboard-ai-patch,pod-template-hash=748d8d6bd4 |
| replicaset.apps/serviceboard-ai-patch-7b9c4485c6 | 0 | 0 | 0 | 82d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.11 | app=serviceboard-ai-patch,pod-template-hash=7b9c4485c6 |
| replicaset.apps/serviceboard-ai-patch-9f5d5b966 | 0 | 0 | 0 | 98d | serviceboard-ai-patch | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.9 | app=serviceboard-ai-patch,pod-template-hash=9f5d5b966 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/serviceboard-ai-patch | Deployment/serviceboard-ai-patch | cpu: 5%/80%, memory: 65%/92% | 3 | 6 | 3 | 384d |

---

## Namespace: serviceboard-ai-prod

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/serviceboard-ai-prod-5fc9fcfb59-27dmg | 1/1 | Running | 0 | 9d | 10.111.184.217 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/serviceboard-ai-prod-5fc9fcfb59-pllfj | 1/1 | Running | 0 | 9d | 10.111.125.14 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/serviceboard-ai-prod-5fc9fcfb59-s4b9p | 1/1 | Running | 0 | 9d | 10.111.224.52 | ip-10-111-242-186.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/serviceboard-ai-prod | ClusterIP | 172.20.88.212 | <none> | 8000/TCP | 384d | app=serviceboard-ai-prod |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/serviceboard-ai-prod | 3/3 | 3 | 3 | 384d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.4.11 | app=serviceboard-ai-prod |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/serviceboard-ai-prod-56cb956f77 | 0 | 0 | 0 | 373d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=56cb956f77 |
| replicaset.apps/serviceboard-ai-prod-5f76b4b498 | 0 | 0 | 0 | 95d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.10 | app=serviceboard-ai-prod,pod-template-hash=5f76b4b498 |
| replicaset.apps/serviceboard-ai-prod-5fc9fcfb59 | 3 | 3 | 3 | 9d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.4.11 | app=serviceboard-ai-prod,pod-template-hash=5fc9fcfb59 |
| replicaset.apps/serviceboard-ai-prod-6c5df56d66 | 0 | 0 | 0 | 373d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=6c5df56d66 |
| replicaset.apps/serviceboard-ai-prod-6f4cb65d74 | 0 | 0 | 0 | 373d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=6f4cb65d74 |
| replicaset.apps/serviceboard-ai-prod-77654f58b8 | 0 | 0 | 0 | 81d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.11 | app=serviceboard-ai-prod,pod-template-hash=77654f58b8 |
| replicaset.apps/serviceboard-ai-prod-7d87cd84f9 | 0 | 0 | 0 | 373d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=7d87cd84f9 |
| replicaset.apps/serviceboard-ai-prod-895694cb6 | 0 | 0 | 0 | 371d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=895694cb6 |
| replicaset.apps/serviceboard-ai-prod-99749d85 | 0 | 0 | 0 | 371d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.1.53 | app=serviceboard-ai-prod,pod-template-hash=99749d85 |
| replicaset.apps/serviceboard-ai-prod-b4d896fb6 | 0 | 0 | 0 | 48d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.3.12 | app=serviceboard-ai-prod,pod-template-hash=b4d896fb6 |
| replicaset.apps/serviceboard-ai-prod-b58cddbb6 | 0 | 0 | 0 | 188d | serviceboard-ai-prod | 140526468817.dkr.ecr.us-east-1.amazonaws.com/svmx-serviceboard-ai:0.2.15 | app=serviceboard-ai-prod,pod-template-hash=b58cddbb6 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/serviceboard-ai-prod | Deployment/serviceboard-ai-prod | cpu: 7%/80%, memory: 67%/92% | 3 | 6 | 3 | 384d |

---

## Namespace: sumologic

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/sumologic-opentelemetry-operator-6ff5f976f8-9kjbs | 2/2 | Running | 0 | 11d | 10.111.199.240 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-events-0 | 1/1 | Running | 0 | 11d | 10.111.152.96 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-0 | 1/1 | Running | 0 | 11d | 10.111.73.216 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-1 | 1/1 | Running | 0 | 11d | 10.111.204.255 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-2 | 1/1 | Running | 0 | 11d | 10.111.132.97 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-44xcn | 1/1 | Running | 0 | 11d | 10.111.178.57 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-6847b | 1/1 | Running | 0 | 11d | 10.111.99.88 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-7jvdw | 1/1 | Running | 0 | 11d | 10.111.197.41 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-8t55s | 1/1 | Running | 0 | 11d | 10.111.140.143 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-95np9 | 1/1 | Running | 0 | 11d | 10.111.111.184 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-cbhr7 | 1/1 | Running | 0 | 11d | 10.111.160.120 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-flx48 | 1/1 | Running | 0 | 11d | 10.111.184.79 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-hh6sz | 1/1 | Running | 0 | 11d | 10.111.203.134 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-l5frw | 1/1 | Running | 0 | 11d | 10.111.149.234 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-n588f | 1/1 | Running | 0 | 11d | 10.111.216.202 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-nmqtd | 1/1 | Running | 0 | 11d | 10.111.194.60 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-pcvdz | 1/1 | Running | 0 | 5d2h | 10.111.178.120 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-v67n2 | 1/1 | Running | 0 | 11d | 10.111.201.172 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-vgd8n | 1/1 | Running | 0 | 11d | 10.111.115.40 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-otelcol-logs-collector-wbfhb | 1/1 | Running | 0 | 11d | 10.111.77.220 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/sumologic-sumologic-traces-sampler-5c64cb97fb-xvlcj | 1/1 | Running | 0 | 11d | 10.111.206.231 | ip-10-111-233-47.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/sumologic-opentelemetry-operator | ClusterIP | 172.20.31.200 | <none> | 8443/TCP,8080/TCP | 431d | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator |
| service/sumologic-opentelemetry-operator-webhook | ClusterIP | 172.20.98.57 | <none> | 443/TCP | 431d | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator |
| service/sumologic-sumologic-metadata-logs | ClusterIP | 172.20.77.126 | <none> | 4318/TCP,8888/TCP | 431d | app=sumologic-sumologic-otelcol-logs |
| service/sumologic-sumologic-otelcol-events | ClusterIP | 172.20.233.138 | <none> | 24231/TCP,8888/TCP | 431d | app=sumologic-sumologic-otelcol-events |
| service/sumologic-sumologic-otelcol-events-headless | ClusterIP | None | <none> | 24231/TCP,8888/TCP | 431d | app=sumologic-sumologic-otelcol-events |
| service/sumologic-sumologic-otelcol-logs-collector | ClusterIP | 172.20.49.249 | <none> | 8888/TCP | 431d | app.kubernetes.io/app-name=sumologic-sumologic-otelcol-logs-collector |
| service/sumologic-sumologic-otelcol-logs-headless | ClusterIP | None | <none> | 4318/TCP | 431d | app=sumologic-sumologic-otelcol-logs |
| service/sumologic-sumologic-traces-sampler-headless | ClusterIP | None | <none> | 1777/TCP,8888/TCP,4317/TCP,4318/TCP | 431d | app=sumologic-sumologic-traces-sampler |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/sumologic-sumologic-otelcol-logs-collector | 15 | 15 | 15 | 15 | 15 | kubernetes.io/os=linux | 431d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.145.0-sumo-0 | app.kubernetes.io/name=sumologic-sumologic-otelcol-logs-collector |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/sumologic-opentelemetry-operator | 1/1 | 1 | 1 | 431d | manager,kube-rbac-proxy | public.ecr.aws/sumologic/opentelemetry-operator:0.144.0,public.ecr.aws/sumologic/kube-rbac-proxy:v0.20.0 | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator |
| deployment.apps/sumologic-sumologic-traces-sampler | 1/1 | 1 | 1 | 431d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.145.0-sumo-0 | app=sumologic-sumologic-traces-sampler |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/sumologic-opentelemetry-operator-6ff5f976f8 | 1 | 1 | 1 | 108d | manager,kube-rbac-proxy | public.ecr.aws/sumologic/opentelemetry-operator:0.144.0,public.ecr.aws/sumologic/kube-rbac-proxy:v0.20.0 | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator,pod-template-hash=6ff5f976f8 |
| replicaset.apps/sumologic-opentelemetry-operator-9944c8b6f | 0 | 0 | 0 | 216d | manager,kube-rbac-proxy | public.ecr.aws/sumologic/opentelemetry-operator:0.131.0,public.ecr.aws/sumologic/kube-rbac-proxy:v0.19.1 | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator,pod-template-hash=9944c8b6f |
| replicaset.apps/sumologic-opentelemetry-operator-99657ddc5 | 0 | 0 | 0 | 215d | manager,kube-rbac-proxy | public.ecr.aws/sumologic/opentelemetry-operator:0.131.0,public.ecr.aws/sumologic/kube-rbac-proxy:v0.19.1 | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator,pod-template-hash=99657ddc5 |
| replicaset.apps/sumologic-opentelemetry-operator-bb65f4f4b | 0 | 0 | 0 | 431d | manager,kube-rbac-proxy | public.ecr.aws/sumologic/opentelemetry-operator:0.115.0,public.ecr.aws/sumologic/kube-rbac-proxy:v0.18.1 | app.kubernetes.io/component=controller-manager,app.kubernetes.io/name=opentelemetry-operator,pod-template-hash=bb65f4f4b |
| replicaset.apps/sumologic-sumologic-traces-sampler-5c64cb97fb | 1 | 1 | 1 | 108d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.145.0-sumo-0 | app=sumologic-sumologic-traces-sampler,pod-template-hash=5c64cb97fb |
| replicaset.apps/sumologic-sumologic-traces-sampler-78f7cbcb59 | 0 | 0 | 0 | 431d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.114.0-sumo-0 | app=sumologic-sumologic-traces-sampler,pod-template-hash=78f7cbcb59 |
| replicaset.apps/sumologic-sumologic-traces-sampler-847dffbcb8 | 0 | 0 | 0 | 216d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.130.1-sumo-0 | app=sumologic-sumologic-traces-sampler,pod-template-hash=847dffbcb8 |

### StatefulSets

| NAME | READY | AGE | CONTAINERS | IMAGES |
| --- | --- | --- | --- | --- |
| statefulset.apps/sumologic-sumologic-otelcol-events | 1/1 | 431d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.145.0-sumo-0 |
| statefulset.apps/sumologic-sumologic-otelcol-logs | 3/3 | 431d | otelcol | public.ecr.aws/sumologic/sumologic-otel-collector:0.145.0-sumo-0 |

### Horizontal Pod Autoscalers

| NAME | REFERENCE | TARGETS | MINPODS | MAXPODS | REPLICAS | AGE |
| --- | --- | --- | --- | --- | --- | --- |
| horizontalpodautoscaler.autoscaling/sumologic-sumologic-otelcol-logs | StatefulSet/sumologic-sumologic-otelcol-logs | cpu: 2%/80% | 3 | 10 | 3 | 431d |

---

## Namespace: synthetics

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/egress-proxy-59fcd6897f-88rq2 | 1/2 | CrashLoopBackOff | 3136 (100s ago) | 11d | 10.111.113.159 | ip-10-111-99-36.ec2.internal | <none> | <none> |
| pod/egress-proxy-59fcd6897f-gwqpw | 2/2 | Running | 0 | 11d | 10.111.163.165 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-6bcb68db44-dkfdd | 1/1 | Running | 0 | 11d | 10.111.162.130 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-node-api-runtime-29694047-8bq8n | 1/1 | Running | 0 | 3m36s | 10.111.151.149 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-node-api-runtime-29694047-bz7b2 | 0/1 | Completed | 0 | 8m7s | 10.111.141.66 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-node-api-runtime-29694047-qh85m | 0/1 | Completed | 0 | 9m33s | 10.111.186.68 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-node-api-runtime-29694047-w59pq | 0/1 | Completed | 0 | 4m36s | 10.111.186.68 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-node-browser-runtime-29655218-sdvc8 | 1/1 | Running | 1 (11d ago) | 11d | 10.111.212.226 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/synthetics-job-manager-ping-runtime-59fdf64cdf-zzvj2 | 1/1 | Running | 0 | 11d | 10.111.123.89 | ip-10-111-109-229.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/egress-proxy | ClusterIP | 172.20.210.252 | <none> | 3128/TCP | 26d | app=egress-proxy |
| service/synthetics-job-manager-ping | ClusterIP | 172.20.44.226 | <none> | 8080/TCP,8082/TCP | 26d | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=ping-runtime |
| service/synthetics-job-manager-synthetics-job-manager | ClusterIP | 172.20.45.180 | <none> | 8080/TCP,8082/TCP | 26d | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=synthetics-job-manager |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/egress-proxy | 1/2 | 2 | 1 | 26d | squid,log-tailer | ubuntu/squid:5.2-22.04_beta,busybox:1.36 | app=egress-proxy |
| deployment.apps/synthetics-job-manager | 1/1 | 1 | 1 | 26d | synthetics-job-manager | newrelic/synthetics-job-manager:release-532 | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=synthetics-job-manager |
| deployment.apps/synthetics-job-manager-ping-runtime | 1/1 | 1 | 1 | 26d | ping-runtime | newrelic/synthetics-ping-runtime:1.68.0 | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=ping-runtime |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/egress-proxy-59fcd6897f | 2 | 2 | 1 | 26d | squid,log-tailer | ubuntu/squid:5.2-22.04_beta,busybox:1.36 | app=egress-proxy,pod-template-hash=59fcd6897f |
| replicaset.apps/egress-proxy-68b68b4dd4 | 0 | 0 | 0 | 26d | squid,log-tailer | ubuntu/squid:5.2-22.04_beta,busybox:1.36 | app=egress-proxy,pod-template-hash=68b68b4dd4 |
| replicaset.apps/egress-proxy-9f7587dc8 | 0 | 0 | 0 | 26d | squid,log-tailer | ubuntu/squid:5.2-22.04_beta,busybox:1.36 | app=egress-proxy,pod-template-hash=9f7587dc8 |
| replicaset.apps/synthetics-job-manager-57dff79d65 | 0 | 0 | 0 | 26d | synthetics-job-manager | newrelic/synthetics-job-manager:release-532 | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=synthetics-job-manager,pod-template-hash=57dff79d65 |
| replicaset.apps/synthetics-job-manager-6bcb68db44 | 1 | 1 | 1 | 26d | synthetics-job-manager | newrelic/synthetics-job-manager:release-532 | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=synthetics-job-manager,pod-template-hash=6bcb68db44 |
| replicaset.apps/synthetics-job-manager-ping-runtime-59fdf64cdf | 1 | 1 | 1 | 26d | ping-runtime | newrelic/synthetics-ping-runtime:1.68.0 | app.kubernetes.io/instance=synthetics-job-manager,app.kubernetes.io/name=ping-runtime,pod-template-hash=59fdf64cdf |

### CronJobs

| NAME | SCHEDULE | TIMEZONE | SUSPEND | ACTIVE | LAST SCHEDULE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| cronjob.batch/synthetics-job-manager-node-api-runtime | * * * * * | <none> | False | 1 | 9m46s | 26d | node-api-runtime | newrelic/synthetics-node-api-runtime:rc1.20 | <none> |
| cronjob.batch/synthetics-job-manager-node-browser-runtime | * * * * * | <none> | False | 1 | 26d | 26d | node-browser-runtime | newrelic/synthetics-node-browser-runtime:rc1.20 | <none> |

### Jobs

| NAME | STATUS | COMPLETIONS | DURATION | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| job.batch/synthetics-job-manager-node-api-runtime-29694047 | Running | 3/6 | 9m33s | 9m33s | node-api-runtime | newrelic/synthetics-node-api-runtime:rc1.20 | batch.kubernetes.io/controller-uid=24b6641e-8ea4-4296-a1ef-0f8a5a3a00c9 |
| job.batch/synthetics-job-manager-node-browser-runtime-29655218 | Running | 0/6 | 26d | 26d | node-browser-runtime | newrelic/synthetics-node-browser-runtime:rc1.20 | batch.kubernetes.io/controller-uid=ceb777d7-d325-4e36-93f8-629aa4d7d946 |

---

## Namespace: wiz

### Pods

| NAME | READY | STATUS | RESTARTS | AGE | IP | NODE | NOMINATED NODE | READINESS GATES |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pod/wiz-integration-agent-7bfd6b4888-cckkl | 1/1 | Running | 0 | 11d | 10.111.113.225 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-admission-controller-6df9bbf78d-d4kv8 | 1/1 | Running | 0 | 4d4h | 10.111.225.18 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-admission-controller-6df9bbf78d-dds4q | 1/1 | Running | 0 | 4d4h | 10.111.139.18 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-admission-controller-audit-log-collect4hxxk | 1/1 | Running | 0 | 4d4h | 10.111.220.193 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-admission-controller-audit-log-collectdk2k9 | 1/1 | Running | 0 | 4d4h | 10.111.162.227 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-5cgk7 | 1/1 | Running | 0 | 5d2h | 10.111.185.121 | ip-10-111-167-65.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-5nll7 | 1/1 | Running | 1 (4d5h ago) | 11d | 10.111.239.214 | ip-10-111-238-32.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-62lks | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.220.202 | ip-10-111-233-47.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-6rwl8 | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.94.226 | ip-10-111-82-117.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-7dknw | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.188.62 | ip-10-111-173-237.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-7tgxc | 1/1 | Running | 1 (4d3h ago) | 11d | 10.111.202.166 | ip-10-111-197-112.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-8n24g | 1/1 | Running | 1 (4d5h ago) | 11d | 10.111.109.70 | ip-10-111-109-229.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-dfwcz | 1/1 | Running | 1 (4d3h ago) | 11d | 10.111.253.121 | ip-10-111-211-170.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-jsqzk | 1/1 | Running | 1 (4d5h ago) | 11d | 10.111.182.144 | ip-10-111-131-191.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-ncm2c | 1/1 | Running | 1 (4d5h ago) | 11d | 10.111.123.184 | ip-10-111-65-28.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-qjfzg | 1/1 | Running | 1 (4d5h ago) | 11d | 10.111.229.29 | ip-10-111-242-186.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-r9qpf | 1/1 | Running | 1 (4d3h ago) | 11d | 10.111.186.134 | ip-10-111-186-238.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-sgwg6 | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.187.78 | ip-10-111-135-235.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-sq42t | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.156.125 | ip-10-111-128-40.ec2.internal | <none> | <none> |
| pod/wiz-integration-wiz-sensor-tjmdx | 1/1 | Running | 1 (4d4h ago) | 11d | 10.111.95.192 | ip-10-111-99-36.ec2.internal | <none> | <none> |

### Services

| NAME | TYPE | CLUSTER-IP | EXTERNAL-IP | PORT(S) | AGE | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- |
| service/wiz-integration-wiz-admission-controller | ClusterIP | 172.20.91.48 | <none> | 443/TCP | 431d | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller |
| service/wiz-integration-wiz-admission-controller-audit-log-collector | ClusterIP | 172.20.59.158 | <none> | 443/TCP | 431d | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector |

### DaemonSets

| NAME | DESIRED | CURRENT | READY | UP-TO-DATE | AVAILABLE | NODE SELECTOR | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| daemonset.apps/wiz-integration-wiz-sensor | 13 | 13 | 13 | 13 | 13 | <none> | 431d | wiz-sensor | wizio.azurecr.io/sensor:v1 | app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-sensor |

### Deployments

| NAME | READY | UP-TO-DATE | AVAILABLE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| deployment.apps/wiz-integration-agent | 1/1 | 1 | 1 | 431d | wiz-broker | wiziopublic.azurecr.io/wiz-app/wiz-broker:3.0 | app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-broker |
| deployment.apps/wiz-integration-wiz-admission-controller | 2/2 | 2 | 2 | 431d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller |
| deployment.apps/wiz-integration-wiz-admission-controller-audit-log-collector | 2/2 | 2 | 2 | 431d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector |

### ReplicaSets

| NAME | DESIRED | CURRENT | READY | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- |
| replicaset.apps/wiz-integration-agent-797cf4657f | 0 | 0 | 0 | 431d | wiz-broker | wiziopublic.azurecr.io/wiz-app/wiz-broker:2.7 | app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-broker,pod-template-hash=797cf4657f |
| replicaset.apps/wiz-integration-agent-7bfd6b4888 | 1 | 1 | 1 | 108d | wiz-broker | wiziopublic.azurecr.io/wiz-app/wiz-broker:3.0 | app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-broker,pod-template-hash=7bfd6b4888 |
| replicaset.apps/wiz-integration-wiz-admission-controller-57599bbf77 | 0 | 0 | 0 | 76d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=57599bbf77 |
| replicaset.apps/wiz-integration-wiz-admission-controller-594db96769 | 0 | 0 | 0 | 69d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=594db96769 |
| replicaset.apps/wiz-integration-wiz-admission-controller-6845bfc77 | 0 | 0 | 0 | 13d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=6845bfc77 |
| replicaset.apps/wiz-integration-wiz-admission-controller-694d8f7777 | 0 | 0 | 0 | 62d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=694d8f7777 |
| replicaset.apps/wiz-integration-wiz-admission-controller-6bc595f4cb | 0 | 0 | 0 | 34d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=6bc595f4cb |
| replicaset.apps/wiz-integration-wiz-admission-controller-6df9bbf78d | 2 | 2 | 2 | 4d4h | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=6df9bbf78d |
| replicaset.apps/wiz-integration-wiz-admission-controller-79fcddbdc | 0 | 0 | 0 | 20d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=79fcddbdc |
| replicaset.apps/wiz-integration-wiz-admission-controller-7dfb579d4f | 0 | 0 | 0 | 48d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=7dfb579d4f |
| replicaset.apps/wiz-integration-wiz-admission-controller-858b5b7969 | 0 | 0 | 0 | 27d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=858b5b7969 |
| replicaset.apps/wiz-integration-wiz-admission-controller-9ff647c58 | 0 | 0 | 0 | 41d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=9ff647c58 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-6564784565 | 0 | 0 | 0 | 62d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=6564784565 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-6f888694bb | 0 | 0 | 0 | 34d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=6f888694bb |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-75c59c8b65 | 0 | 0 | 0 | 27d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=75c59c8b65 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-794bfd6db6 | 2 | 2 | 2 | 4d4h | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=794bfd6db6 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-7dc9bb65b4 | 0 | 0 | 0 | 41d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=7dc9bb65b4 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-7dd945cc8f | 0 | 0 | 0 | 48d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=7dd945cc8f |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-7fd657cd47 | 0 | 0 | 0 | 20d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=7fd657cd47 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-8446df589c | 0 | 0 | 0 | 13d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=8446df589c |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-84f5c4b969 | 0 | 0 | 0 | 76d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=84f5c4b969 |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-858dcfc8bd | 0 | 0 | 0 | 55d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=858dcfc8bd |
| replicaset.apps/wiz-integration-wiz-admission-controller-audit-log-collector-d846949b9 | 0 | 0 | 0 | 69d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-integration-wiz-admission-controller-audit-log-collector,pod-template-hash=d846949b9 |
| replicaset.apps/wiz-integration-wiz-admission-controller-b8c8d6f86 | 0 | 0 | 0 | 55d | wiz-admission-controller | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | app.kubernetes.io/chartName=wiz-admission-controller,app.kubernetes.io/instance=wiz-integration,app.kubernetes.io/name=wiz-admission-controller,pod-template-hash=b8c8d6f86 |

### CronJobs

| NAME | SCHEDULE | TIMEZONE | SUSPEND | ACTIVE | LAST SCHEDULE | AGE | CONTAINERS | IMAGES | SELECTOR |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| cronjob.batch/wiz-integration-wiz-admission-controller-manager | 0 * * * * | <none> | False | 0 | 56m | 431d | wiz-admission-controller-manager | wiziopublic.azurecr.io/wiz-app/wiz-admission-controller:2.11 | <none> |
| vinaybv@ptc.com@svmx-bastion-new:~$ |  |  |  |  |  |  |  |  |  |

---
