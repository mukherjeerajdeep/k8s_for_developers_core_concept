Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\erajmuk> docker version
Client:
 Cloud integration: v1.0.23
 Version:           20.10.14
 API version:       1.41
 Go version:        go1.16.15
 Git commit:        a224086
 Built:             Thu Mar 24 01:53:11 2022
 OS/Arch:           windows/amd64
 Context:           default
 Experimental:      true

Server: Docker Desktop 4.7.0 (77141)
 Engine:
  Version:          20.10.14
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.16.15
  Git commit:       87a90dc
  Built:            Thu Mar 24 01:46:14 2022
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.5.11
  GitCommit:        3df54a852345ae127d1fa3092b95168e4a88e2f8
 runc:
  Version:          1.0.3
  GitCommit:        v1.0.3-0-gf46b6ba
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> kubectl version
Client Version: version.Info{Major:"1", Minor:"22", GitVersion:"v1.22.5", GitCommit:"5c99e2ac2ff9a3c549d9ca665e7bc05a3e18f07e", GitTreeState:"clean", BuildDate:"2021-12-16T08:38:33Z", GoVersion:"go1.16.12", Compiler:"gc", Platform:"windows/amd64"}
Server Version: version.Info{Major:"1", Minor:"22", GitVersion:"v1.22.5", GitCommit:"5c99e2ac2ff9a3c549d9ca665e7bc05a3e18f07e", GitTreeState:"clean", BuildDate:"2021-12-16T08:32:32Z", GoVersion:"go1.16.12", Compiler:"gc", Platform:"linux/amd64"}
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> kubectl cluster-info
Kubernetes control plane is running at https://kubernetes.docker.internal:6443
CoreDNS is running at https://kubernetes.docker.internal:6443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> kubectl get all
NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   2m16s
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> docker images
REPOSITORY                                                                   TAG                                                                        IMAGE ID       CREATED         SIZE
pyapp                                                                        5.0                                                                        d2a580984e26   2 months ago    131MB
pyapp                                                                        6.0                                                                        f5d6fa74ecca   2 months ago    131MB
pyapp                                                                        3.0                                                                        e119c158b509   2 months ago    131MB
old_entrypoint                                                               4.0                                                                        774596012299   2 months ago    131MB
pyapp                                                                        1.0                                                                        b710f46bde5d   2 months ago    129MB
pyapp                                                                        2.0                                                                        04566fb7bd60   2 months ago    129MB
mini-builder                                                                 1.0                                                                        433eae5895d8   2 months ago    934MB
mini-exec                                                                    1.0                                                                        cb81e893a0ef   2 months ago    8.21MB
mini-linter                                                                  1.0                                                                        8c07bf20bf74   2 months ago    937MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes                      kubernetes-v1.22.5-cni-v0.8.5-critools-v1.17.0-cri-dockerd-v0.2.0-debian   7414669e8008   3 months ago    347MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-apiserver            v1.22.5                                                                    059e6cd8cf78   6 months ago    128MB
k8s.gcr.io/kube-apiserver                                                    v1.22.5                                                                    059e6cd8cf78   6 months ago    128MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-proxy                v1.22.5                                                                    8f8fdd6672d4   6 months ago    104MB
k8s.gcr.io/kube-proxy                                                        v1.22.5                                                                    8f8fdd6672d4   6 months ago    104MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-scheduler            v1.22.5                                                                    935d8fdc2d52   6 months ago    52.7MB
k8s.gcr.io/kube-scheduler                                                    v1.22.5                                                                    935d8fdc2d52   6 months ago    52.7MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-controller-manager   v1.22.5                                                                    04185bc88e08   6 months ago    122MB
k8s.gcr.io/kube-controller-manager                                           v1.22.5                                                                    04185bc88e08   6 months ago    122MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-etcd                 3.5.0-0                                                                    004811815584   12 months ago   295MB
k8s.gcr.io/etcd                                                              3.5.0-0                                                                    004811815584   12 months ago   295MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-coredns              v1.8.4                                                                     8d147537fb7d   13 months ago   47.6MB
k8s.gcr.io/coredns/coredns                                                   v1.8.4                                                                     8d147537fb7d   13 months ago   47.6MB
docker/desktop-vpnkit-controller                                             v2.0                                                                       8c2c38aa676e   14 months ago   21MB
hubproxy.docker.internal:5000/docker/desktop-vpnkit-controller               v2.0                                                                       8c2c38aa676e   14 months ago   21MB
docker/desktop-storage-provisioner                                           v2.0                                                                       99f89471f470   14 months ago   41.9MB
hubproxy.docker.internal:5000/docker/desktop-storage-provisioner             v2.0                                                                       99f89471f470   14 months ago   41.9MB
hubproxy.docker.internal:5000/docker/desktop-kubernetes-pause                3.5                                                                        ed210e3e4a5b   15 months ago   683kB
k8s.gcr.io/pause                                                             3.5                                                                        ed210e3e4a5b   15 months ago   683kB
PS C:\Users\erajmuk> Set-Alias -Name k8s -Value kubectl
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s version
PS C:\Users\erajmuk> on.Info{Major:"1", Minor:"22", GitVersion:"v1.22.5", GitCommit:"5c99e2ac2ff9a3c549d9ca665e7bc05a3e18f07e", GitTreeState:"clPS C:\Users\erajmuk> -12-16T08:38:33Z", GoVersion:"go1.16.12", Compiler:"gc", Platform:"windows/amd64"}
PS C:\Users\erajmuk> ^C.Info{Major:"1", Minor:"22", GitVersion:"v1.22.5", GitCommit:"5c99e2ac2ff9a3c549d9ca665e7bc05a3e18f07e", GitTreeState:"clPS C:\Users\erajmuk> ^C2-16T08:32:32Z", GoVersion:"go1.16.12", Compiler:"gc", Platform:"linux/amd64"}
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^Cbectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.5.0/aio/deploy/recommended.yaml
PS C:\Users\erajmuk> ^Cshboard created
PS C:\Users\erajmuk> ^Ces-dashboard created
PS C:\Users\erajmuk> ^Cboard created
PS C:\Users\erajmuk> ^Coard-certs created
PS C:\Users\erajmuk> ^Coard-csrf created
PS C:\Users\erajmuk> ^Coard-key-holder created
PS C:\Users\erajmuk> ^Cshboard-settings created
PS C:\Users\erajmuk> ^C.k8s.io/kubernetes-dashboard created
PS C:\Users\erajmuk> ^Cization.k8s.io/kubernetes-dashboard created
PS C:\Users\erajmuk> ^Cization.k8s.io/kubernetes-dashboard created
PS C:\Users\erajmuk> ^C.authorization.k8s.io/kubernetes-dashboard created
PS C:\Users\erajmuk> ^Ctes-dashboard created
PS C:\Users\erajmuk> ^Ccs-scraper created
PS C:\Users\erajmuk> ^Crd-metrics-scraper created
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk> ^C
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s describe secret -n kube-system
Name:         attachdetach-controller-token-zjfqg
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: attachdetach-controller
              kubernetes.io/service-account.uid: 22916393-f2e0-439a-84bb-d2428c2f2798

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJhdHRhY2hkZXRhY2gtY29udHJvbGxlci10b2tlbi16amZxZyIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJhdHRhY2hkZXRhY2gtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjIyOTE2MzkzLWYyZTAtNDM5YS04NGJiLWQyNDI4YzJmMjc5OCIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTphdHRhY2hkZXRhY2gtY29udHJvbGxlciJ9.hrHWxnl4KtYR9jPlOTsr6dct3Ekg-bIIc1V7l6U2KeF66NJyzCinAau9zlATCwfLkB76wjSYClVefwjdLzD47hWemeaPgcnWJLQbVlwMTEKnDPk2IOTnN5oCSqFJYECedZGdjrbOIC1KPrI48_DwGCcNY8qetwjZyrAOf8k0dEdY9ZFkBxmH-douQk4oZ7d5bI6906ae5Ph5pJN9lLj6gH9TuBE_dNojKHkosOt1BDmLbhd3PEiGMKDlDOaU4nPPQpapcJvKZKiklfmbjOGjyqpz4aqVq-nm0369RjyG4a9FNPSCGiVTToiGlcuSX4SNckxRXgF7ljwpuWf4_gg5mg


Name:         bootstrap-signer-token-mx8t2
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: bootstrap-signer
              kubernetes.io/service-account.uid: 9367d771-d260-49ad-a73c-855e2345cd00

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJib290c3RyYXAtc2lnbmVyLXRva2VuLW14OHQyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImJvb3RzdHJhcC1zaWduZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiI5MzY3ZDc3MS1kMjYwLTQ5YWQtYTczYy04NTVlMjM0NWNkMDAiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06Ym9vdHN0cmFwLXNpZ25lciJ9.kCBo3WYrNLdjG5bAtcLV2SDluDpjdQ1KPlVHHDjtEIldXCsarVBClaG0q54eWhGA69QzAUH6fyxCRUnuOzYBVBn8ezuKVXBhAvFGRgrFx_y4QEfT1e7aJRsqJ_Ip840Q9QWSHxZLsn8BDL8-Sqa6EP8kMXLQn5rAw7O99T7CrMugX_ad6u2EWvrJ8Zof1JFrXsUjYjaC2aVJgtQoZBkAlm3AFi1Fi3HnsOiWwHP240Pb68HeuyXwNCWPMIfGIy0wFtBssxuaez8bYgNIPqL8acR9k6eZxU5bzQ5qXArVNP4oNxD3g_0lP6rY6p7KRrBx5b6vWD7_AlafjnsBFY1xeQ


Name:         bootstrap-token-abcdef
Namespace:    kube-system
Labels:       <none>
Annotations:  <none>

Type:  bootstrap.kubernetes.io/token

Data
====
usage-bootstrap-signing:         4 bytes
auth-extra-groups:               47 bytes
expiration:                      20 bytes
token-id:                        6 bytes
token-secret:                    16 bytes
usage-bootstrap-authentication:  4 bytes


Name:         certificate-controller-token-9gpxn
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: certificate-controller
              kubernetes.io/service-account.uid: 37fe1954-f6a7-45db-ac99-f34b4f7a6e1e

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJjZXJ0aWZpY2F0ZS1jb250cm9sbGVyLXRva2VuLTlncHhuIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImNlcnRpZmljYXRlLWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiIzN2ZlMTk1NC1mNmE3LTQ1ZGItYWM5OS1mMzRiNGY3YTZlMWUiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06Y2VydGlmaWNhdGUtY29udHJvbGxlciJ9.tGHIQvRFRI0_UI2hcDXHxgRGHHNixj4c23WgFqYi20p7lQdk4nbXTp0VMxhgX7bRYx2OfkO5FZ45LGdSjiZHpa5i5Y6w8yVw5-kO0yuCpxf_2Y7NjIjWXMQ-VKJfWmYLGbuKCFuJ2M76fKGLER-ZGmw4Uyn2yut3t0W1X-erTDgSdIAbmn-Zuy1Y3TvpbrMoSMWo6MqRZDWA6u4WWFDJ5K6dlc4LyriUTWkADM4bbqWu-y-ign3THHfx_mPexggrU7aUQRWf11SqGUD56KmfmLkAPsayfn__Qm5ov0zMHngshNJzvXMu4ZzRJ1o6lu3bVvjyqJI-h8NfSW5UsNn9xw


Name:         clusterrole-aggregation-controller-token-sk4v7
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: clusterrole-aggregation-controller
              kubernetes.io/service-account.uid: 3292b64a-77d8-4512-9623-4f49cfec9ab8

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJjbHVzdGVycm9sZS1hZ2dyZWdhdGlvbi1jb250cm9sbGVyLXRva2VuLXNrNHY3Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImNsdXN0ZXJyb2xlLWFnZ3JlZ2F0aW9uLWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiIzMjkyYjY0YS03N2Q4LTQ1MTItOTYyMy00ZjQ5Y2ZlYzlhYjgiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06Y2x1c3RlcnJvbGUtYWdncmVnYXRpb24tY29udHJvbGxlciJ9.gOD9z1ZpxAfYV-d1jx0Xl3RIanC-UNzfuRJp9aIWtYy_cKXVeMFdT5ZEuSP_gui5tRxcUrCpbP_7XwogQBQGKtPNrwIvXpNn9XkIYtjeSZL4T9KRAfipMiBHY4Vm9Z5TWzRjsedVEiN8mFNJF4Tf9RA2uSYF5hEV5kItgRVNwA32rAZNQSXyJffAdNgB5hkD1dTkA9kjMthgirwk2bGZH4gfqO3RPJXpIansMV25gLzagjtTfSQFWKu6F9fDNwqjrKqdyPOw2r1v7SXoKjywFVMt6K-CwT0QnjHzKrEn6bZhF00Eo8XW_HcX--8gw0eb4fv7ZW8dwl5E9QfInFuubg


Name:         coredns-token-qxbsx
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: coredns
              kubernetes.io/service-account.uid: 11ee978a-17c2-4236-86ab-8acb6c1c4df7

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJjb3JlZG5zLXRva2VuLXF4YnN4Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImNvcmVkbnMiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiIxMWVlOTc4YS0xN2MyLTQyMzYtODZhYi04YWNiNmMxYzRkZjciLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06Y29yZWRucyJ9.O_mV6ev4dnwNWQ6wZ8766YWWQqcK6rTL6KIqaETQZI3skz-p6U2gK-4y3Q0z5yQzAfvVr8rXaE_sjpSzXyx9FZeef4jXD0YAZMFNy1WWpLsGnA6COhS7A773BjxsUM57UGeFsfwncP23SQ-jQTZaQ75zc6_UrudXNrekp-T6m_iJyzNgi9TBMxU_oH_rHDW4l27SRXHD2T0oxYnKJtv1J6qPL25NflIBd21t9KMq07AoQXeR9r6iEO8gV7PxoNfk8fOx7XDbbLQTpDRxzSPf0RkuAMXjUV4ovw4SMoV4TK2K2ehMRGw-63hsqLkh0qAVn7ykZkjmn2dbmHiJitrr7Q


Name:         cronjob-controller-token-bgpbm
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: cronjob-controller
              kubernetes.io/service-account.uid: c3e7521a-5fdc-4e85-87ff-faeb49b2ccc0

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJjcm9uam9iLWNvbnRyb2xsZXItdG9rZW4tYmdwYm0iLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiY3JvbmpvYi1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiYzNlNzUyMWEtNWZkYy00ZTg1LTg3ZmYtZmFlYjQ5YjJjY2MwIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmNyb25qb2ItY29udHJvbGxlciJ9.lccTtySECzfNk4vr8eJ9jPS57FNXyOZK6DzdqrKMyXP19YagfdIaZuynYyWlUH0uSaeIKlTK7gscfXiXJNLFZogHgiQpoAZm1yKPRkryxXuGh4R0Q-hLm6G98adLGExsMaJsk1HU8vCav3jJJ6DdBXQWvFXcEocpEfVkjm7ZJYdykc2Gjcl7OWUwLGza5EKvJSDu7Z6DhQn9cALUal_SkV-Xjfr7_BIyaS6oNf59tWz_MO5Nf4NkkSlQcFIFeS3yF9jy-ZV3v-qZwbq3mAiRZh5qZ3nOBOxKUlNYCfOVix8pKzdfnnO3gZ2XtHDHpJn7ADXe9Vjoe5LiW7NX4kY2Nw


Name:         daemon-set-controller-token-x5qhw
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: daemon-set-controller
              kubernetes.io/service-account.uid: 5f267604-4583-4e3b-9080-e9056c100d34

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJkYWVtb24tc2V0LWNvbnRyb2xsZXItdG9rZW4teDVxaHciLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZGFlbW9uLXNldC1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiNWYyNjc2MDQtNDU4My00ZTNiLTkwODAtZTkwNTZjMTAwZDM0Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmRhZW1vbi1zZXQtY29udHJvbGxlciJ9.jXaXXOnVMTLGNnlsrA2llPkMSCLgrUMdqZXxZIMSoNA1FGacO8ue-4RWGOjPrRPOek8Anc5l_VlJz-JSw_jalC86sWQEOIybRmKlG_-OEAm20cVUapPL7hVkClU_M-OuaP0vbS_CnRcQjP2Ug5WgWd4Yepvcmx1CWRXylEBiyUFBITztfy6tQXm3AjtKQu5zDolWgTpRL5RVrmsWWKRHZpp541uMl3R2P9d9na2P6xhkRV9Xi9hPrIep2VsAVEGGGGuo9SgnO7ktndKWMSR3w8jnktpgQ9xLQuRYPbccscdrPK7mEhVK-LkEDX7irgwf6lYJkm1Xa-gZRruKZTSv3Q


Name:         default-token-v4jw2
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: default
              kubernetes.io/service-account.uid: e4417e08-73e0-4cf2-8c7c-013ad2703bee

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJkZWZhdWx0LXRva2VuLXY0ancyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImRlZmF1bHQiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiJlNDQxN2UwOC03M2UwLTRjZjItOGM3Yy0wMTNhZDI3MDNiZWUiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06ZGVmYXVsdCJ9.ZyBiF_Egm2Ua7wcB3SjAc35Oy_YRe05DqJYQxbamqlAewmphd-ugGTuTAOkAfDGlue3k3jdccsc5I09SsqEfk9yOMDwfgvaZZUvHfIOhMBGUQIIQXsDxtodAVA-8HqNId3KDKEj6_P6SJ25ZVFNKXELqGARlX-FnbRwWyr7PRANEEYpF2H6ITR2vBybjtA9D5D6bXccYZUjmLrlec31pGeAeDd1-p6z30GcXElXXlDZU24lpmd88xmBV1ZwvNfyPDpXOCPiNLVeLBWqfewFVi0_whjU0l6oZYnb_r6_WAnAn3QKGNj3_nKD4mM76lbdyrVRG8JNFks9BabLCZIfgRQ


Name:         deployment-controller-token-vvx79
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: deployment-controller
              kubernetes.io/service-account.uid: 02524f2d-2e7f-410b-b787-746aa3dbb9f3

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJkZXBsb3ltZW50LWNvbnRyb2xsZXItdG9rZW4tdnZ4NzkiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZGVwbG95bWVudC1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMDI1MjRmMmQtMmU3Zi00MTBiLWI3ODctNzQ2YWEzZGJiOWYzIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmRlcGxveW1lbnQtY29udHJvbGxlciJ9.HroFdnY-K0VZ0bJz-30ehkC9GU2Z2-1HH2kleGey9xf0bRFNIGZxAy8udHl0yQS5DADCYFIHh-HlbVbtqFmywUKF1SwIPq9QIfsS2Jz4eBEpzk-WfCPA3vh8wAsTo4AJNqZ3Jc46PI2_3XAdj7w2CgGSTeG66Myoz7gSjKMTKYKzpg5-cjRcl3fLqg_m1Fg_tawp1-bltTd2cVanDgBiMhU4VfMakVUys2XLHl7rhEgGASIN0cW0t8nFnoTCelwBSr675WpArwjhxj0Mlmo9FNnpcSIlV0qAEFyBOWZK-DYb84GmFJ_vzT3jBgcm0sQLocyjORXJPo7DIB4FXrZXYA


Name:         disruption-controller-token-kntpk
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: disruption-controller
              kubernetes.io/service-account.uid: 298def45-1e7d-42b0-b2b7-28307565924b

Type:  kubernetes.io/service-account-token

Data
====
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJkaXNydXB0aW9uLWNvbnRyb2xsZXItdG9rZW4ta250cGsiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZGlzcnVwdGlvbi1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMjk4ZGVmNDUtMWU3ZC00MmIwLWIyYjctMjgzMDc1NjU5MjRiIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmRpc3J1cHRpb24tY29udHJvbGxlciJ9.skQphALM2GS-dNwKmbcLnlchGLW-JGB7WAYXkt2b_1MUEn1hlZeHUqjhGaMR6HdjFHPTDQUvlK__ojISnM3f9eAXOE_XQyHBurjPbj5j9hG_4_32twUaAyjRVGyvmFO2yv3AQ3axdiAsRhmTaVSa7WUd0pOknwPcPgNDbZX27dz82zcOUGj09Nd-NgmQx4k5TI2sK5KTmpfgMxAq3TFSKiq0PHt3BJSinNV_uXqjHR0jVXQMZBa_jDGntqhL1UnPnuwaDK7eWNN9dVgPv3X1EqajBeiwogf8lVXDl1Ql6DmQMVPWjWSto1bwrdMYB6mXrsB1OCIMAvPXQ2PVJgrV9g
ca.crt:     1099 bytes


Name:         endpoint-controller-token-gzk7d
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: endpoint-controller
              kubernetes.io/service-account.uid: daec1c35-eec2-4385-971c-fca844c9090f

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJlbmRwb2ludC1jb250cm9sbGVyLXRva2VuLWd6azdkIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImVuZHBvaW50LWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiJkYWVjMWMzNS1lZWMyLTQzODUtOTcxYy1mY2E4NDRjOTA5MGYiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06ZW5kcG9pbnQtY29udHJvbGxlciJ9.WgmGTKKqmMaHEVNOrx6qSqzIVJDEZ3Wn1iLrXkKjNSj4lChY7kO5L-sHLcz0cO_x6zx4-TQVoB0DH1DG3XD3GB2SvlrBrKQhdraaewkqkCD9sBuYEeoDWIyHq-lEmHMPpWii3xlQ4Uvoi8Tb8C7AOh0Fm1yeEQIvII62vrTNDsBeSTppWhyAFi68-wzgwTdE_cHqNO6K66FvrrDjLP6PtZEgx7T8LRBDdnbEGzIeKp70MvMkHGdTmzazOmHepIPNyLGuCwYDHv_IdEts4DkkQSVW5VF2JcEr69oRzdH0-fcbU0A4NgbBf-BtcYteI0n7TIOpY08TqUlnjx0wUcATYQ


Name:         endpointslice-controller-token-v2hhj
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: endpointslice-controller
              kubernetes.io/service-account.uid: ca724c39-8fb7-4750-bd24-279e586d2282

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJlbmRwb2ludHNsaWNlLWNvbnRyb2xsZXItdG9rZW4tdjJoaGoiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZW5kcG9pbnRzbGljZS1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiY2E3MjRjMzktOGZiNy00NzUwLWJkMjQtMjc5ZTU4NmQyMjgyIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmVuZHBvaW50c2xpY2UtY29udHJvbGxlciJ9.Y_EZ-ztvyg_gthPmFIamqfoEs9A-hk_PnRtr--bs87OmVJDUhepXCK96pjgqWxp72V6_PSxduup1KGnpnlK2Em4g2Y1d7-p_MkviAoxefThyqcolnAvQA_ZF-JJzSAl-x0sA1K3CY1ZGRzReJF0UJlfnox1E6KszkEbj5H5Yyn_LNM2OoPpPAsfNxm8xWcTEpc0fVjjZkY8H3aumSyZEcreeBBOHUj2VJ4aEOq8cDxPoo326Xz5Vys4W1w0TVL32KRjjDUbUHBr-rSYGp-rSOZtTEg6FmPHh4u3WfI7RMf5Iq65ADc0a3GUTP1qGR6shO58X25eTkFHKhVKCsb3DBw


Name:         endpointslicemirroring-controller-token-drgs6
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: endpointslicemirroring-controller
              kubernetes.io/service-account.uid: 99b6e1ec-1f2e-4462-85e3-b99fcb425915

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJlbmRwb2ludHNsaWNlbWlycm9yaW5nLWNvbnRyb2xsZXItdG9rZW4tZHJnczYiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZW5kcG9pbnRzbGljZW1pcnJvcmluZy1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiOTliNmUxZWMtMWYyZS00NDYyLTg1ZTMtYjk5ZmNiNDI1OTE1Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmVuZHBvaW50c2xpY2VtaXJyb3JpbmctY29udHJvbGxlciJ9.rCpZnG8R82dy1X3PItrAn29MRy4fZgMwOaJM6wUBPd-rz3kZ9EuoP2D1CZGrqSyfPI2mrSsb9Wv3GCrI1xaejcXG7ZlhVEt9nWtCBs3XSy35yNOk8XaWibQCGRoRxbsIAyua1cqWHlN0CsuNa4c30wDP6lHW5r0qYqjtNT-QmaPVEpPjaeWLfeh3NuLamL4uM3zJf7vMuMKYWhvrARem4tK0RZ0HzHzeSTEsCXEKNdDGSR6ilbhe5BdfuFAXm2c1jvNvYflDiLMrDxdHqU0Ma-O79zWGf41-3ANwpqS0fl6xs7j-q7Prob8d1JTLm8QneEhq7Vwj836uq4TiPlCO3g


Name:         ephemeral-volume-controller-token-hnbrh
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: ephemeral-volume-controller
              kubernetes.io/service-account.uid: e7881f8a-7173-41bf-bcfb-2dafe3d49509

Type:  kubernetes.io/service-account-token

Data
====
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJlcGhlbWVyYWwtdm9sdW1lLWNvbnRyb2xsZXItdG9rZW4taG5icmgiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZXBoZW1lcmFsLXZvbHVtZS1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiZTc4ODFmOGEtNzE3My00MWJmLWJjZmItMmRhZmUzZDQ5NTA5Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmVwaGVtZXJhbC12b2x1bWUtY29udHJvbGxlciJ9.qdNUB6RUPWEADjixZKISI4XedUnIgQfNfst6NFI8fKvGbW3vbApgZOJlxWQdklG6EiZ52H7t8xd7beNzhm0Ixh4WatSOr-HyUuFV-XU_L6LlVKnuhxWi-Ex19kxpd3RENFt5qw4Pf5Le1HAyBLrJhbqK2WRCec-ftprCJ3hBDgc3hvcaZ7mCLcicwWw-H8CsuVjNqNcqXqpev8yS4OBvP-2KJTJWc_Rxwnhk7j-7Hj4_2673yTGnMpsskvzoZrNrG7gjrvLw-ALNl0H_GIK1w53lS4t2K5M76ao38KghyGvqsFwA3JYhI0aDrFjaR55T9rGbTlDlnyKj5mrS3o8UeA
ca.crt:     1099 bytes


Name:         expand-controller-token-7dvxs
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: expand-controller
              kubernetes.io/service-account.uid: f9e1a431-b55c-466b-b94e-bf9850c62e5e

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJleHBhbmQtY29udHJvbGxlci10b2tlbi03ZHZ4cyIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJleHBhbmQtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImY5ZTFhNDMxLWI1NWMtNDY2Yi1iOTRlLWJmOTg1MGM2MmU1ZSIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTpleHBhbmQtY29udHJvbGxlciJ9.hypnIShGgYW-uSdwuQ02IMRfG4uyaXft7BialwAWBKn4oXkyxrpnZXfh-s-WRRo7F_QnTw_vMKLXFyEmj2Z9nm48EmxSNke2reWkcpqEJXaYrioKBma27zEI-UdFDL2eMeWUPdrZmcjDV2YvJdAFqcNmv6Fh6V1okZ-sgify2iSg7cSDmTnr7EVUvsS6d9zK8e3g2no0RqCtS0uc85l3BgMHuPV7MiRFMeMFli8SyoV6quJHB__SXBYg4aUNYHGNK-nvHWIIo-Wd41Anx5-bIKHl2Gt0zjScE6m5WddYpCVRbmbxZnIspjZIufoMGNsaeIa9qLLKOtYO6WrwCPRAkQ


Name:         generic-garbage-collector-token-gzf7q
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: generic-garbage-collector
              kubernetes.io/service-account.uid: 2e9146fd-bb68-4164-8f94-0dd800f4f08a

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJnZW5lcmljLWdhcmJhZ2UtY29sbGVjdG9yLXRva2VuLWd6ZjdxIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6ImdlbmVyaWMtZ2FyYmFnZS1jb2xsZWN0b3IiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiIyZTkxNDZmZC1iYjY4LTQxNjQtOGY5NC0wZGQ4MDBmNGYwOGEiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06Z2VuZXJpYy1nYXJiYWdlLWNvbGxlY3RvciJ9.cy-bCRFOQeLbo8FA4I0oLmcobObWo5H5XKJDzeEg_un-EAXEyf3oGnGOTYb47Ak0atlxuXqOMjDFVD4JH_4NkNRlbujP_ctvUDFgSpak5AhnrnrbiEzALBfc5xlk2vIbg7DT8fptiPYe_SlnmMAa6rP19Szoa5tAsgILuk2Sfv3PsYuq7RpOeXM4hc5BgueIhdiSUwG-aRpjR82iypthTxO8jKiN4Kl8eJxCUkzl4c-kfAAswNYlIKoXX4nTibqdHZZgkrmcIYdF6ucXfm0y-Y6BDDOcAp71E-rORuE64EBIFyH_wqtnH0GRSNJFrGzAwkJTVnE-Mw1XeEwS3rUvVA


Name:         horizontal-pod-autoscaler-token-9gnww
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: horizontal-pod-autoscaler
              kubernetes.io/service-account.uid: e6ccd68f-9048-4d1a-8482-f2b8f8a74e2e

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJob3Jpem9udGFsLXBvZC1hdXRvc2NhbGVyLXRva2VuLTlnbnd3Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6Imhvcml6b250YWwtcG9kLWF1dG9zY2FsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiJlNmNjZDY4Zi05MDQ4LTRkMWEtODQ4Mi1mMmI4ZjhhNzRlMmUiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06aG9yaXpvbnRhbC1wb2QtYXV0b3NjYWxlciJ9.pXQgRSF3dTQKFGytBxGRVNVhph6ksX8I-4l2glohN1UctPi9zAXEjRd7ZgXRd2nH7b3EnNbDXvirdimp5Q3-Nba30MgTkmZoVkUjdhjNRE3s5CURxhu4A_afnP3BotiKSukIj_Wk5QQbsFPYk7Khchweu3gFmM4eexcifZSI06RyVU7cgzzt4Gk8TiFFAF0wCNI4gqfk4vTI8QUk2mx_0cTip_qtMVDYJyV4lknJmRq4Egd7Kb01-rSrlxa5oPZo17OWjaCSo4bWkA-b_NUzbISs0V-J14ZesGNQXNd6ubS3jir6Gf4pIITQXXg_2ujzfIZ3nxJN9VuW2MbZ-BsyaA


Name:         job-controller-token-6t2s8
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: job-controller
              kubernetes.io/service-account.uid: 57eade45-4c10-4c72-9144-95645f5378a9

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJqb2ItY29udHJvbGxlci10b2tlbi02dDJzOCIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJqb2ItY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjU3ZWFkZTQ1LTRjMTAtNGM3Mi05MTQ0LTk1NjQ1ZjUzNzhhOSIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTpqb2ItY29udHJvbGxlciJ9.c52gCFFpwg6fBotAin-ePnYMhpzD09_NzfOunNKjuq7aR3fzZoCka9NeuTOrxMol9jngOURt_prdeClkh6hCRu6DOPZAfTDjMrGF9laNldx328Ioa8B2wGjUenoiuLRFr3bbV83ksyRPmBJIALCvUfbu3LoKOb9yl-955wYKsyOFEtNH7OM30tRzAWobbFbU2CnEOLRCvon295CrzxHi16J9inOEFdFWS9GsoMq6cN05HmOZF015c3IO0-o13ZT2z9wEZxvQUFoXY3HL5ykJC3SkIGT-MS6P5R8rwx5jCD3qq_R2bSn2RBZKfA-PkrDABwqHU32wJ3wTGwIbOiLdlg


Name:         kube-proxy-token-fd8rp
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: kube-proxy
              kubernetes.io/service-account.uid: 0b290e0b-c1fb-425e-841a-1b4412775f24

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJrdWJlLXByb3h5LXRva2VuLWZkOHJwIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6Imt1YmUtcHJveHkiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiIwYjI5MGUwYi1jMWZiLTQyNWUtODQxYS0xYjQ0MTI3NzVmMjQiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06a3ViZS1wcm94eSJ9.Ppph7--aX-sOu7sBav2qUHg6492ELjCc827wcWjn9d8jffFQ_ysN2Vir7n_GqIplPQ0p3PIS2VhgbfDPqImxYcbU6jN9-kNB6_cNJujEn9kpjqT2Yl7Et-9PB6jR-EFXcjl8Ce-sFdNV0mjD_DR521vDG_t0Q4NZSkpgxZ6sytezzWptQdItqRAIOhb-6ZHeXQVVIc3IU4dgQgL6Swrs-acGcP71BZ9-zANLiX5TaWXwTrtEFfusBKHMpy3D9XAS2pNJklj22Sbe-meCEQpXrUQFFUlvsxWfJn1Q_KSa5KQOUJpMdrd2a-2JhZHUNrgCD7sFCbfwapQxIIr_KkahMA


Name:         namespace-controller-token-g5pb9
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: namespace-controller
              kubernetes.io/service-account.uid: c05bce62-cdb3-498c-82d4-b085553a712e

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJuYW1lc3BhY2UtY29udHJvbGxlci10b2tlbi1nNXBiOSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJuYW1lc3BhY2UtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImMwNWJjZTYyLWNkYjMtNDk4Yy04MmQ0LWIwODU1NTNhNzEyZSIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTpuYW1lc3BhY2UtY29udHJvbGxlciJ9.l5FtTHeYgTNGNMELVfhNQGcVv9-rl_zIMV_qU6035SWsc0-krQZ0L6W5J4o_27kltDuTO-ICHL1t4NcqccBeF6A-m7OI9XUABo3ImrPxECZwt8LG4-q37pC82-GWpE8wBEKnoeaEneSTXAADUKAi9MigvOMZ7zXBP-DXM_hlv7laCFFLV3YUuQeexToOI5FzfODd0BQNQpbPR8cDm1a_chPy1vhBurX7B_2-nyBxBN61uL5f3kCxbEIJSfOO9RCTDwuSfI3O7pxvOCPgXYG0KIVaSmJHP6RsTf-fTnyPNgT1scJfNblT1woZuZxvkhL84zquW8JaXTpN8Slws3dF1Q


Name:         node-controller-token-wknvs
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: node-controller
              kubernetes.io/service-account.uid: 28c6fdde-4c1c-4021-8c01-8ce3e69e3168

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJub2RlLWNvbnRyb2xsZXItdG9rZW4td2tudnMiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoibm9kZS1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMjhjNmZkZGUtNGMxYy00MDIxLThjMDEtOGNlM2U2OWUzMTY4Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOm5vZGUtY29udHJvbGxlciJ9.EDilHGhORKLkRoVD6x7BtWtlXc7tPMysHXLiOVWArcAaj0iNVMfh6u_IoVZWsQ5uABdqyJy5ireE4nz89jTfNCIzh3ewCRlVa6RWAnc1qC_o_PaomEDuTPobibcqSAo9BA5nKA680PYj7gB5Yo6gpB3XQzxVl4EixrLbKYnDOWSheYN0f_aa6M8shkb-sqB1DtXZuzCTYjkN1JmeKgc8Tt8Hw0oBq6Qf4P9dUm7p-T-1vlmEZ1R4ECJfHQ7YKlKwxku000OK4jHAp26iFiqRyE9YaeAsTS5Lv843vK4IB5L_Q3u2QlmETXwo7JlB3JRXD3WBXQuBhRdkoKq5czfZbg


Name:         persistent-volume-binder-token-4pd2c
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: persistent-volume-binder
              kubernetes.io/service-account.uid: 0767c429-9940-4661-aa32-6e81ca41be49

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJwZXJzaXN0ZW50LXZvbHVtZS1iaW5kZXItdG9rZW4tNHBkMmMiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoicGVyc2lzdGVudC12b2x1bWUtYmluZGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMDc2N2M0MjktOTk0MC00NjYxLWFhMzItNmU4MWNhNDFiZTQ5Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnBlcnNpc3RlbnQtdm9sdW1lLWJpbmRlciJ9.meLHDnY1hHvDs3NQ79Po_XuDmkONFR4pvBWdzR8XxKwAJwrmaaDpN5Zy7sz7SlLaWMEDBBgnm7JtuIlx_4iFLkjXenqbtX-xtDlBD1b0SVq7jx3jKBRToRD8ugNmm5803BjDUf6Fi9AiowZOadxz5IN9w-WKAv6rVZMv6s0Ka_l_5valverH058ptZsc5nPeA6Gu3OkQZCFNOO-iInbfx4nK-TgQcZOGzv_2-RrgJiaa9L5-LbLH_cv_JW9mXvMAm5RSDi-SY9nnDoJw1MAB6wP4CA7lHiEw1NZSFSU2-EubttEv5XhKtDCjx6gqdyvIUPg7UaMVShGI_HErKeNhIw


Name:         pod-garbage-collector-token-p4v2f
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: pod-garbage-collector
              kubernetes.io/service-account.uid: a36a4a03-8e58-4436-b0d3-b72fe5017af5

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJwb2QtZ2FyYmFnZS1jb2xsZWN0b3ItdG9rZW4tcDR2MmYiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoicG9kLWdhcmJhZ2UtY29sbGVjdG9yIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiYTM2YTRhMDMtOGU1OC00NDM2LWIwZDMtYjcyZmU1MDE3YWY1Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnBvZC1nYXJiYWdlLWNvbGxlY3RvciJ9.mLSTNGX7qhtgZMWVErxLKyeWsUk6VUKmEbSvzXD4MeS_hRiMzCKXSB-irwnQRhHjN-fM4ViDfywqoibRvqTKCUv2AqA7r8gzOz9y95ZnXonot6bL_3qjjrXw6iD5nH_AwbnObeAaWa8OLnyGzq7FnNyB9r4JYyWgDZbvBKyCpk8mhBQ0rT5K3SPEAnQJ9iI6kM60GQHx4qrH-xj_ozh_B8f4WpJ5Iqm8FrkflVQF2O3IF-I_NsoSBPUaoqHxuPh3tdnTR3L4hzbYxslsTUUJ-_Oz2gpoSnrUroDcvLnV_zSomh9p38Zxta4WNrgBRYQ6BusSJDGh-wGLpK__pV-URQ


Name:         pv-protection-controller-token-ftzts
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: pv-protection-controller
              kubernetes.io/service-account.uid: 0821a760-f6d0-4f0b-89b2-5393afd13218

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJwdi1wcm90ZWN0aW9uLWNvbnRyb2xsZXItdG9rZW4tZnR6dHMiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoicHYtcHJvdGVjdGlvbi1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMDgyMWE3NjAtZjZkMC00ZjBiLTg5YjItNTM5M2FmZDEzMjE4Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnB2LXByb3RlY3Rpb24tY29udHJvbGxlciJ9.RslWOMI-Hqh5ypwbPpvtc8E4eIO0vifj6gUkv3EwGxZ0Xx_ADNDv8jcMZpMydOVflI16B_J9TzAjcVrCujCpd3T_HKeuTUKXMrTNrOmEWlgdE90rF3Nun7GG2Dnb0enFra0kp8B3gqONpassrf5EQ7yPtEw6jyummTmCND2cVEbe_h4HENS6MR7UasBsL5qFN15BYhYqymRQ2Nzc-fxxfjzEdigCnyO0MHmGOZWVr7YyoEZYlVaQp1Pb-SOmeC12ySRDRwxbqMK2Ru8PiGdGKogORMYdSSZko7wZxzRfdy0HGKpgn2bguLGb2Dv5SkC_bBdPj3Lsvh0y4nIStNkrFw


Name:         pvc-protection-controller-token-l56rf
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: pvc-protection-controller
              kubernetes.io/service-account.uid: 85aeeb2e-df0d-41b3-b417-bebb0beedf73

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJwdmMtcHJvdGVjdGlvbi1jb250cm9sbGVyLXRva2VuLWw1NnJmIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InB2Yy1wcm90ZWN0aW9uLWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiI4NWFlZWIyZS1kZjBkLTQxYjMtYjQxNy1iZWJiMGJlZWRmNzMiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06cHZjLXByb3RlY3Rpb24tY29udHJvbGxlciJ9.duIy3JiozNOu-tgVFr4n6kZhBQllXhvpM3Temh3wsQzipNOPT7RxrJqUO1_IzdlYRFjQ5Zf9htiBjJJGiCTVqm2FVAY5GEE8cd8FmMMDPTgvUOnzyNNu2dXWvb4zu0fHA9bNGdnYoOTJyU51Zgb9yNDiYULNQDpjosADOZPiqCgT80upMdkmuL56UG192FqX9N4VsxtEmjfcS5Awj-iBIDmWsDyO5aRr-6Aj_rU1m9U6gixe28fXbuOarbyfiPJw7C8ljU6DTECT53kgkUN1LRsKxuPdzyUYnwW8L_5r7GXEZriToVgha27QFCxeU9OmHf_wIBxDzPFHaVTOphIwTw


Name:         replicaset-controller-token-fmlqk
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: replicaset-controller
              kubernetes.io/service-account.uid: 78fd5809-f68f-47f4-8925-8b0255207996

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJyZXBsaWNhc2V0LWNvbnRyb2xsZXItdG9rZW4tZm1scWsiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoicmVwbGljYXNldC1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiNzhmZDU4MDktZjY4Zi00N2Y0LTg5MjUtOGIwMjU1MjA3OTk2Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnJlcGxpY2FzZXQtY29udHJvbGxlciJ9.AGEpYvSmnBpDC7S4Dzv5tkEXUEVuLoRAmuXSqjyiAJwv9DRr58qh46Z3MBRhSPoJEES5UkcNxyA3BWI4N5lZ7LpvgEkHcDuL-8S4lU8I7VWzL7E4xQoR4w77C69tT5B6R1_8T2Cr7uGE82Mn36CDA77afwIdL_3jkqIf1ZFju89lHdwLXx-e5cOGAkw5rAj9IFqR5zjdw8LQIMp_rifGIRU9dEzW5-htGgTkXVN2IGLxptdLfwMiDEvT_wjcsZ8TLJvahGnIACxhmp6VIy4nnxUYSD_WxLTXI1FgJIdizT-KuMyreLfW7ZoNL58jF5yyWpmNgoHTmr9n3iCjEmmZkw


Name:         replication-controller-token-qnsg9
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: replication-controller
              kubernetes.io/service-account.uid: d700c3c9-42d5-4256-a79b-7c12bd356c49

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJyZXBsaWNhdGlvbi1jb250cm9sbGVyLXRva2VuLXFuc2c5Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InJlcGxpY2F0aW9uLWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiJkNzAwYzNjOS00MmQ1LTQyNTYtYTc5Yi03YzEyYmQzNTZjNDkiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06cmVwbGljYXRpb24tY29udHJvbGxlciJ9.pQw7WXFSnPWR-sYyBk1uxsurgbxwRsVLl5AgeFMDpja_CgUfMboiu9nkXlhYxnRsAlU9mXFBYz06j3xKctQjCfTL7ZzvZkDQuoNDOEPIghrIYgsfkOxe3wtBdmCDLsRQTTFmnl7FH9EdRSSn-UAHyCOsHU9xPYzkbjNueiVtId1VNNzNlLEagfnSIQAA3Mb97XQv9hycKZWijVYDRIiBWh2ZQFq3ThOtWisglwj8fdxqbHRinRiwlmBaKT_aaprfuXogLBbFNrEdaOV3abbuSinOTokBtlBmtHH94m1iHHpMNR5RLZKJB4YCKT1OHMl8ZFtLvbftWpLvKsJ_tGSoQA


Name:         resourcequota-controller-token-tgbtf
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: resourcequota-controller
              kubernetes.io/service-account.uid: 560d3f1b-3715-45a8-b895-881e975cf9fb

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJyZXNvdXJjZXF1b3RhLWNvbnRyb2xsZXItdG9rZW4tdGdidGYiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoicmVzb3VyY2VxdW90YS1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiNTYwZDNmMWItMzcxNS00NWE4LWI4OTUtODgxZTk3NWNmOWZiIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnJlc291cmNlcXVvdGEtY29udHJvbGxlciJ9.t9ESGkXollJHR06ZgRwMUXr18JgtUAW-chATSZfPjXeKCLy9zjZUvL_EuGWzwdlGRwEoNAxJfEBmNovEq2a_1FPzDTZyKDCJe6anFzQ-3XE4KUZnF1X55wWatvxFB3YnIipUrX4Q1IFX1W7e5PBwDQti9FsDU8vB3uDwSHqyhdcSn9YRrwLnZ-M_MRSve-RTuEZauIB_2nDoWoIXlJoL3mGrWV2GnJ-N999IQQZYS3S8sdUrTZZ1aQYFDg8MAqUcMrEd0DuUVEhrIAb1V3QncL6d8f4H9jA0z0cOmVjQYm2kmLohsJYRUeDjRJZ9EZrjbN01gc867oKOhv8B_Ix22A


Name:         root-ca-cert-publisher-token-2rdf8
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: root-ca-cert-publisher
              kubernetes.io/service-account.uid: 5c7dc2ca-f7f7-4f16-abad-6b88d4f036c4

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJyb290LWNhLWNlcnQtcHVibGlzaGVyLXRva2VuLTJyZGY4Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InJvb3QtY2EtY2VydC1wdWJsaXNoZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiI1YzdkYzJjYS1mN2Y3LTRmMTYtYWJhZC02Yjg4ZDRmMDM2YzQiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06cm9vdC1jYS1jZXJ0LXB1Ymxpc2hlciJ9.R7mGFeTVfJnrUC_FxWE9UBTCLQqoY2HrwtYXIvPN7JG18ZIR__Qwp6LVtmjv07rVt9KHigFUcOCoWm1EtJOXHl4NmqWRFpLcwOkH-idSA2qdigXE6RbPoJj_wIa0bOQUwXTsyJUoYxjxjL7gimnlC-6Qz04NeoPoyW4hwvxyHvCRGNp1lhG4YHWaMCvtP4K9ruddzT-jeOxR84OzhIRGgcfxcguPljg0gOXIUKX1LUEBU2EXWDYw1VvOX9dekQOJcBLUNVzTTCK7zmUX_gaM_4BJ8CzIZ762d5aLlOnlgMKS9nGlwwfLYR0u3yLv5yqLc4inN9V9SDWfPttNWO1GCQ


Name:         service-account-controller-token-9jfqf
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: service-account-controller
              kubernetes.io/service-account.uid: bd4caf19-19b4-42aa-afea-a5fea1ba7e8f

Type:  kubernetes.io/service-account-token

Data
====
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJzZXJ2aWNlLWFjY291bnQtY29udHJvbGxlci10b2tlbi05amZxZiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJzZXJ2aWNlLWFjY291bnQtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImJkNGNhZjE5LTE5YjQtNDJhYS1hZmVhLWE1ZmVhMWJhN2U4ZiIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTpzZXJ2aWNlLWFjY291bnQtY29udHJvbGxlciJ9.ncOCWDLFRl9zTXsf_3BopS4Mv3tNWhwzG_kwcDYFprTwCQ5wzTjjvHJ3L_PYtuuB8c_qOUPPrfyvTPRsCTJh3dNNadALGy6Dvrt9Pn9wrTcN6qEd8-zvAfQ1w6ErnidWXg6HDKfeOMylPHvpJAYB5bCZb8qBpWQ9FrnbZe4FVUgd2ZAb5_2UYLn736LrpRwa8DRe1aIvb85Qh5BRxgCli541z6MSfO738hrsRtgiQq2kOPUH4dPIUn8cSNCZDvq2ucW5KcLbvytKeiA2Awnr4VVQwe-uzF7FQkpjfqqAHfvb7jrHpYPAec9zctuG3dftnNk1PhkbYXaGQGbCoUdKcA
ca.crt:     1099 bytes


Name:         service-controller-token-x2hfb
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: service-controller
              kubernetes.io/service-account.uid: 189bc910-814e-4f6d-b524-4509c5311f89

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJzZXJ2aWNlLWNvbnRyb2xsZXItdG9rZW4teDJoZmIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoic2VydmljZS1jb250cm9sbGVyIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMTg5YmM5MTAtODE0ZS00ZjZkLWI1MjQtNDUwOWM1MzExZjg5Iiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOnNlcnZpY2UtY29udHJvbGxlciJ9.p0utUsHlvMa07sIoObuuB9NFq4YdsrX0osjmXcXuG48yXw3jiOUkkV_ARRzmGJ2oUtHe430JRhE-StPsEhxTn-P96R9AkwSkxFRq1ZQ7QLWtZyPlDi01JYbxI7O3JiUUd1pI-mVcS4DMfyD7_u7s5LOLqwkPEX2u5hAcli3wJO3jP01kW7MFAdA5mBYis5VjjfDbm1pSRR8pkZnJjBYeuPf8J2KTmeV05h3sGnlikTs5yH2qsCfp5HnG-Ts05nAyW1HF12zZ5vZQA_2fuhFpBPHeUVhe2VTPUe_dqolyXlpHOp6vfUQqzDNdjTzU9wMXqVqQMenLo9tnA5BanRhI2g


Name:         statefulset-controller-token-hgxvk
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: statefulset-controller
              kubernetes.io/service-account.uid: d88c47df-fdcd-4122-947b-eb682ff8d428

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJzdGF0ZWZ1bHNldC1jb250cm9sbGVyLXRva2VuLWhneHZrIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InN0YXRlZnVsc2V0LWNvbnRyb2xsZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiJkODhjNDdkZi1mZGNkLTQxMjItOTQ3Yi1lYjY4MmZmOGQ0MjgiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06c3RhdGVmdWxzZXQtY29udHJvbGxlciJ9.PegrWI4LDZ2XJE0-JFQdjOiysP3iOaaqMZM9XKu4srHG77qznswvJChxqEHZbf_T9y0OLP-FU18wdEZnDTyaQtQxM2BWOVcFoB_UNrivUCFBcfBlLmax9CzX3lbGW7dJ0t0dvG7OZWYXz77RahQCc0uCpe_7ameYRrpWZqjO6Gin2mUAtHhGAsZiutLnUwFp4d71FpOwMGbk_f1KfMobrDrxGMkUlS-Byh5wWg4_8e0KPW0IT9V0qZz-OEJeyWUS1mofgWt_p-5_cOICsL8AL5Z3L7J7WlAURzSwqmxtZfxGdm6fjmhZOOdlqpq2MiL8RsiFUl67H26nn41R8p78cQ


Name:         storage-provisioner-token-r7667
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: storage-provisioner
              kubernetes.io/service-account.uid: 66019197-6712-4252-8338-2f3d27b147d9

Type:  kubernetes.io/service-account-token

Data
====
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJzdG9yYWdlLXByb3Zpc2lvbmVyLXRva2VuLXI3NjY3Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InN0b3JhZ2UtcHJvdmlzaW9uZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiI2NjAxOTE5Ny02NzEyLTQyNTItODMzOC0yZjNkMjdiMTQ3ZDkiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06c3RvcmFnZS1wcm92aXNpb25lciJ9.H2xE1ORhLR9SYSjbUHDkHHQ_WaHvwJFB_er9k_PiUF9YSqHXOEC7WblmVZKfOPtQAv4RiHLBV2My0af7EXGF1a-4HuY3ck1AvI9mMlBKTqgaLf9W1G9n4lpetgfXIuD-lxG74forRS4U4tn1nNTsVJM1UBFzZ_nnl3di8AOFA1o04cJj7vs5QjKvbeu-56q5vq2CWBehqXn1sAO7YMaKCo_sxLhByep9sRHvRkBc5mDHwLXHXuF8ugFuYXEKnoK5gALBfcSjKiZmGpo_qkkn0aFMa5pkJaGVfILC7FQpI88_VcZoLVRePQxQ6ZPobrwnTuh7Z-feuf8Pj0RFVPtizw
ca.crt:     1099 bytes


Name:         token-cleaner-token-kvzbc
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: token-cleaner
              kubernetes.io/service-account.uid: 9afcf3d2-4c8f-408a-aa66-4be9cefef50f

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJ0b2tlbi1jbGVhbmVyLXRva2VuLWt2emJjIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQubmFtZSI6InRva2VuLWNsZWFuZXIiLCJrdWJlcm5ldGVzLmlvL3NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC51aWQiOiI5YWZjZjNkMi00YzhmLTQwOGEtYWE2Ni00YmU5Y2VmZWY1MGYiLCJzdWIiOiJzeXN0ZW06c2VydmljZWFjY291bnQ6a3ViZS1zeXN0ZW06dG9rZW4tY2xlYW5lciJ9.FUG4Cnnc6hCu3Tb-U0O53Hc7n_aKoBVAxCkt7siy8Iny1QibrivYnnuEU33-YAOProqqlx2oH57cyc7RFIUbo6LVENya4GJFQd9PrI-oMpy--XEou-lbNCdvmiZ-iSdtEQEdNpgCBwxmQIS4Jrp8by9LUFzUrx2oxSxCZVglMXTHW4y2tTXAD1SwPcyhkIEcw_UKle6YpDXjoh4wLhFum5zJ-VTzV9V31-SKtivLSEtSmzlWwNhQivnFE2QJO7EB6zXwhh1EoNpUgy8cLVcoSKxUbBa6IIvlCiQ23K9Cjf_Kr-TXFqJ5EMNqTPK38WDht5XFATpqAr-tZy8ZtIZGeA


Name:         ttl-after-finished-controller-token-5s78z
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: ttl-after-finished-controller
              kubernetes.io/service-account.uid: 6f869505-53da-40e7-9db9-1b9c4008da9b

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJ0dGwtYWZ0ZXItZmluaXNoZWQtY29udHJvbGxlci10b2tlbi01czc4eiIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJ0dGwtYWZ0ZXItZmluaXNoZWQtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6IjZmODY5NTA1LTUzZGEtNDBlNy05ZGI5LTFiOWM0MDA4ZGE5YiIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTp0dGwtYWZ0ZXItZmluaXNoZWQtY29udHJvbGxlciJ9.DKYCIEQVy69B7iFfPBvwp20AJPMY-AU4eGhikePvJmtM1maVz0TCVIoHwt8BRdHWEdEZsIsdgouCCm1H4Dnl_wpt7jFBptItAj4Km5LaUIY5nVqAXUBiaZt72UJ4UL7NFCB00IzJMmjWHHkDu0o03lgXn0xN7p3IwiTwHwLpWernG59gBqE3Y-nE3rOj__T-_l3dekc8Fkm5l92_qTDKb9fa1doyaRMrS9hiuKXv7Ey_Bfxu8yNr02zZiWlrUon3imSfjlJ9Xw9DVm3BM2SMPGvnd6qIgW-xEeh4HKyIaey3ciOhSgz9g3qZtv-Yj8nyH-dU6bENad2r_ToEiC4mOg


Name:         ttl-controller-token-9cw4t
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: ttl-controller
              kubernetes.io/service-account.uid: e35b061e-f63e-47ee-881a-425b48894b35

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJ0dGwtY29udHJvbGxlci10b2tlbi05Y3c0dCIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJ0dGwtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImUzNWIwNjFlLWY2M2UtNDdlZS04ODFhLTQyNWI0ODg5NGIzNSIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTp0dGwtY29udHJvbGxlciJ9.ArkT1qA-vkKRleSWkQ73q0lpm80WaYtSKdwVRDXIJG2BdzK3yQINeBJJYi-XCb22BTx-xt0-hK_OHN68RL6KSrOL00fFsNW4CG5q2I4CBp22qi6sL6a3LTnFGL7Hzvgkp1R0Jifd6EkpAinmzAAG-upS65u39GmbyH93tlG4FjXJxH6ZCjpErIbO3qfBDlsn8PYZK-of0cQPFo4vDCrVuNX-awKbWyA6daDWW6nw3i7PShfLuvfqMWIulxeVeJjHpGIsKlRbGKekpdWU5g-EWEo7NcHNcmBLPXlqui_HtqvOp6QMpCbBWgqkAY_Gh9rUlQNRrci5cWsKxYe5-j8IzA


Name:         vpnkit-controller-token-qbhvk
Namespace:    kube-system
Labels:       <none>
Annotations:  kubernetes.io/service-account.name: vpnkit-controller
              kubernetes.io/service-account.uid: cf1db491-6334-48c7-ba93-142a097da199

Type:  kubernetes.io/service-account-token

Data
====
ca.crt:     1099 bytes
namespace:  11 bytes
token:      eyJhbGciOiJSUzI1NiIsImtpZCI6IklLdzNQa3ROZWpqWHhmdG14aGFPMHliVEE3ZmkyUzZ2bU9jUHNQaDF3M1UifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJ2cG5raXQtY29udHJvbGxlci10b2tlbi1xYmh2ayIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50Lm5hbWUiOiJ2cG5raXQtY29udHJvbGxlciIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VydmljZS1hY2NvdW50LnVpZCI6ImNmMWRiNDkxLTYzMzQtNDhjNy1iYTkzLTE0MmEwOTdkYTE5OSIsInN1YiI6InN5c3RlbTpzZXJ2aWNlYWNjb3VudDprdWJlLXN5c3RlbTp2cG5raXQtY29udHJvbGxlciJ9.p45kXFThPKC2Zsh0iZaGjzhkrI-P1-3sTFRWwBprAqLOnT6503SL5isrSNifTvbwWXN76453b3Fo9xolMoCMa4XvinhJ-rLu6K1qp3c7Qg0wMMq-BR6Z9hLzzsToJZwtdLKlADBDeS8CinwVIECWO58Icnsvnh9McHvmbQXsI0aKRUXAyrOCLyRBY9YoFJhtonwPnxsP_0cJSFWelYa8hNkNHm1DbxlAfTCZOM9FPkVPCRpwz8YhsExMxF_rqBYfk0avc4PXi_0AtpGG4luJBXFeJXD3qjcYLyLFXcHPwDryWTQR-zR-EBPNhOCr8o3R9askQugs4ik0PWABNGkHQw
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s proxy
Starting to serve on 127.0.0.1:8001
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s
kubectl controls the Kubernetes cluster manager.

 Find more information at: https://kubernetes.io/docs/reference/kubectl/overview/

Basic Commands (Beginner):
  create        Create a resource from a file or from stdin
  expose        Take a replication controller, service, deployment or pod and expose it as a new Kubernetes service
  run           Run a particular image on the cluster
  set           Set specific features on objects

Basic Commands (Intermediate):
  explain       Get documentation for a resource
  get           Display one or many resources
  edit          Edit a resource on the server
  delete        Delete resources by file names, stdin, resources and names, or by resources and label selector

Deploy Commands:
  rollout       Manage the rollout of a resource
  scale         Set a new size for a deployment, replica set, or replication controller
  autoscale     Auto-scale a deployment, replica set, stateful set, or replication controller

Cluster Management Commands:
  certificate   Modify certificate resources.
  cluster-info  Display cluster information
  top           Display resource (CPU/memory) usage
  cordon        Mark node as unschedulable
  uncordon      Mark node as schedulable
  drain         Drain node in preparation for maintenance
  taint         Update the taints on one or more nodes

Troubleshooting and Debugging Commands:
  describe      Show details of a specific resource or group of resources
  logs          Print the logs for a container in a pod
  attach        Attach to a running container
  exec          Execute a command in a container
  port-forward  Forward one or more local ports to a pod
  proxy         Run a proxy to the Kubernetes API server
  cp            Copy files and directories to and from containers
  auth          Inspect authorization
  debug         Create debugging sessions for troubleshooting workloads and nodes

Advanced Commands:
  diff          Diff the live version against a would-be applied version
  apply         Apply a configuration to a resource by file name or stdin
  patch         Update fields of a resource
  replace       Replace a resource by file name or stdin
  wait          Experimental: Wait for a specific condition on one or many resources
  kustomize     Build a kustomization target from a directory or URL.

Settings Commands:
  label         Update the labels on a resource
  annotate      Update the annotations on a resource
  completion    Output shell completion code for the specified shell (bash or zsh)

Other Commands:
  api-resources Print the supported API resources on the server
  api-versions  Print the supported API versions on the server, in the form of "group/version"
  config        Modify kubeconfig files
  plugin        Provides utilities for interacting with plugins
  version       Print the client and server version information

Usage:
  kubectl [flags] [options]

Use "kubectl <command> --help" for more information about a given command.
Use "kubectl options" for a list of global command-line options (applies to all commands).
PS C:\Users\erajmuk> k8s get all
NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   23h
PS C:\Users\erajmuk> k8s run my-nginx --image=nginx:alpine
pod/my-nginx created
PS C:\Users\erajmuk> k8s get pods
NAME       READY   STATUS              RESTARTS   AGE
my-nginx   0/1     ContainerCreating   0          11s
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s get services
NAME         TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   24h
PS C:\Users\erajmuk> k8s port-forward my-nginx 8080:80
Forwarding from 127.0.0.1:8080 -> 80
Forwarding from [::1]:8080 -> 80
Handling connection for 8080
Handling connection for 8080
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s get pods
NAME       READY   STATUS    RESTARTS   AGE
my-nginx   1/1     Running   0          3m38s
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s delete pod my-nginx
pod "my-nginx" deleted
PS C:\Users\erajmuk> k8s get pods
No resources found in default namespace.
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> kubeconfig
kubeconfig : The term 'kubeconfig' is not recognized as the name of a cmdlet, function, script file, or
operable program. Check the spelling of the name, or if a path was included, verify that the path is
correct and try again.
At line:1 char:1
+ kubeconfig
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (kubeconfig:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\erajmuk>
PS C:\Users\erajmuk> ls


    Directory: C:\Users\erajmuk


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         09-Mar-22     21:19                .android
d-----         06-May-22     13:06                .atom
d-----         14-Apr-22     16:06                .docker
d-----         25-Mar-22     21:19                .idlerc
d-----         12-Mar-22     18:10                .ipython
d-----         30-Jun-22     19:04                .kube
d-----         09-Mar-22     20:26                .ms-ad
d-----         09-Mar-22     21:16                .ssh
d-----         20-Apr-22     15:34                .VirtualBox
d-----         17-Mar-22     19:19                .vscode
d-r---         09-Mar-22     14:33                3D Objects
d-r---         09-Mar-22     14:33                Contacts
d-r---         19-May-22     12:33                Desktop
d-----         09-Mar-22     14:42                Documents
d-r---         01-Jul-22     19:16                Downloads
d-r---         09-Mar-22     14:33                Favorites
d-r---         09-Mar-22     14:33                Links
d-r---         09-Mar-22     14:33                Music
d-r---         22-Feb-22     11:09                OneDrive
dar--l         29-Jun-22     10:21                OneDrive - Ericsson
d-----         24-Mar-22     12:13                Postman Agent
d-----         28-Apr-22     14:25                PycharmProjects
d-r---         09-Mar-22     14:33                Saved Games
d-r---         09-Mar-22     16:30                Searches
d-r---         09-Mar-22     14:33                Videos
-a----         03-May-22     18:11           5620 .bash_history
-a----         21-Mar-22     12:43            471 .gitconfig
-a----         20-Jun-22     15:16             20 .lesshst
-a----         09-Mar-22     21:02             14 .minttyrc
-a----         18-Apr-22     12:04             76 Microsoft.PowerShell_profile


PS C:\Users\erajmuk> cat .\.kube\config
apiVersion: v1
clusters:
- cluster:
    certificate-authority-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSUMvakNDQWVhZ0F3SUJBZ0lCQURBTkJna3Foa2lHOXcwQkFRc0ZBREFWTVJNd0VRWURWUVFERXdwcmRXSmwKY201bGRHVnpNQjRYRFRJeU1EWXpNREUyTlRrMU1sb1hEVE15TURZeU56RTJOVGsxTWxvd0ZURVRNQkVHQTFVRQpBeE1LYTNWaVpYSnVaWFJsY3pDQ0FTSXdEUVlKS29aSWh2Y05BUUVCQlFBRGdnRVBBRENDQVFvQ2dnRUJBTTVUCkNKeHFzeFh1QzBjelBHd3dMSkNDN01rSXdUeWhoYkpVZlFWRERYZ2dHNXQwcEZpMEo5cHFjT21ydWJHQUdPeG0KUkNKYmRmNkwvUGhHN2U2RUkvWTBkMUpmZ1MvVlh1alZPQmU0WDl5c2w1STVLM0dEb1k4SWt4QlpGdksyOC94NApnQUw3amlydkYwemwvR2IwUCtlbG0xVlNxY24vb2M3d29TVWRHTng3aWtrVEs2WkpjclpKcHNQOHY3RHV6THV0CmJjWmlCVnMyNEZYdy9ZMkdqWTFJdk1lTy8rVEhLSTgzZWxRWDd5VHdJWU14cGxiVjhHVzZwSHBobFZKWUZNVnMKU29OUDlkcnFqaEN4YUtubTcxYkFoVER2NW5YVGlZczU1ZWxXak5lbkNXOHhCMFdzdlFTbjlCbWI5Rm9DbzRhdQp2M2pBY0lIRGNEMVpFam42NDNjQ0F3RUFBYU5aTUZjd0RnWURWUjBQQVFIL0JBUURBZ0trTUE4R0ExVWRFd0VCCi93UUZNQU1CQWY4d0hRWURWUjBPQkJZRUZHWkZxclUvTnQ3M25PZzcvY24ycTBLYklEQURNQlVHQTFVZEVRUU8KTUF5Q0NtdDFZbVZ5Ym1WMFpYTXdEUVlKS29aSWh2Y05BUUVMQlFBRGdnRUJBRkFUem00a3IyNUpmREU0Z3NWNAplSDhuOGVXRk0yd0w5c3NMQmdYN3MrbjlCcVR6OW5YSDVaSHFvZzhkU28xSWdiY1hxV290UWUxV3BoN3BGaWZoCmpac2Z0bHp3MzlRR0M2ZnBEWSthKzZjcEo2cDQ0NmloU29hMHkzYzJLMG5WSm9QNERoKzl2SmhxM2Y2VU9ydloKL3V4WVZxYjRLRlYvbXM3T3ZZWk1yYytGSjdvbElqb201alQ2ZURWUWdEbGNRSmRxN1YzVEZ6Z1VEM2NYdThPUgpHME5aaFFqOENpTzYzS3RnRklrZU1QTENXam5oNTRCbm5NTnBLaC9lMUQrejhsYlBOZ0EzMU0raFlQWFBJVWh0CjZZbnFDcmx6VThhSEp3ZG9mYlFKQk5Nb3kvRk1qQ0J0Mk5xYVlVV3hsOVVhOEo4NjZSdEhBS0FGTUx5cmdFWVgKdWRRPQotLS0tLUVORCBDRVJUSUZJQ0FURS0tLS0tCg==
    server: https://kubernetes.docker.internal:6443
  name: docker-desktop
contexts:
- context:
    cluster: docker-desktop
    user: docker-desktop
  name: docker-desktop
current-context: docker-desktop
kind: Config
preferences: {}
users:
- name: docker-desktop
  user:
    client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURRakNDQWlxZ0F3SUJBZ0lJY1RlT3ZzaG9QSHN3RFFZSktvWklodmNOQVFFTEJRQXdGVEVUTUJFR0ExVUUKQXhNS2EzVmlaWEp1WlhSbGN6QWVGdzB5TWpBMk16QXhOalU1TlRKYUZ3MHlNekEyTXpBeE5qVTVOVE5hTURZeApGekFWQmdOVkJBb1REbk41YzNSbGJUcHRZWE4wWlhKek1Sc3dHUVlEVlFRREV4SmtiMk5yWlhJdFptOXlMV1JsCmMydDBiM0F3Z2dFaU1BMEdDU3FHU0liM0RRRUJBUVVBQTRJQkR3QXdnZ0VLQW9JQkFRRFNDaTg1TWN2MVFYZk8KRkJibHR4RFJQSzNFNkFKR1RZUEtsUmNyWWVMUk1ZTTgxL0Faa09Fak1vd3BPZ1JibDJaVS90NE1OOHR2YkJqRwpxWWs0a0ZGcFlYTHNRSU1lbG9mSkxqTEgxcFUxcWcvN1k3MmJWUlp5aWU2SkFKYndsOGRWUXVGWmloSEd4ckFSCnlud29yU1FqUkdOcUlFVExsbllPVkl4ZVgrMWkrMjRhdmgxbW9RY3ZBRG92QjAyR1NmTzJHbXhUU2U5c2djeU0KcjBtYWt3Vll3b3NlcmY3WHByUk9GQ01KSWdPangrcDV0VmIvY2hxVkRnNW44blNnU1BpTHlncTYweGRUc0Fucwo2THpLdjFqbVN1OWhiWlRqSUpiWGhkMjZGZXNXblVVTjJkTjZHZEtQRW1HcVBWQWlVSEgyZEVPMnF1VUFzWkc5CmRUOUd0YXNIQWdNQkFBR2pkVEJ6TUE0R0ExVWREd0VCL3dRRUF3SUZvREFUQmdOVkhTVUVEREFLQmdnckJnRUYKQlFjREFqQU1CZ05WSFJNQkFmOEVBakFBTUI4R0ExVWRJd1FZTUJhQUZHWkZxclUvTnQ3M25PZzcvY24ycTBLYgpJREFETUIwR0ExVWRFUVFXTUJTQ0VtUnZZMnRsY2kxbWIzSXRaR1Z6YTNSdmNEQU5CZ2txaGtpRzl3MEJBUXNGCkFBT0NBUUVBRFRVVXVzVkNJb2FmdXBPR0luVFA4akxONmY2TldLeWExdDYxYmpRUUtYZER6aTFwVTVSdk9vaDgKL0I1bHBNUTZHWU1rU01uUjBQdXI2a2hCU1kzaThJRi96WmFLendrSDU4ZXRmby9rSlpmdHljeXB2cGhQOGowagpGTzhyOUNoYzFGZ0tMRElnc1BSRDEzcTVDTnFRbmNCdVF4K3llNjRCZGlHTXpyTy96c2NpSytWVkdFQms3ZTNVCkdpNk5oakdZSHhXY1JFQ1h2ejE2Z1RhVXJFaEgzd1NaMkxpTlZTRnNQYzk1N1UvVm5wV0wyaWNxd2x4VE9EbEwKM2x4N2FJTnNNQkxPdTJ6bUdOVk9uczlEdkhRcUswVWdoTlJZcEJuR0FBTFZxS3cwZkxyTkQ3ZGJhYjNKZnZpZgpQSGVoRkxJQ210MDk1TG9yallTd1U2QUZ6QTg0MHc9PQotLS0tLUVORCBDRVJUSUZJQ0FURS0tLS0tCg==
    client-key-data: LS0tLS1CRUdJTiBSU0EgUFJJVkFURSBLRVktLS0tLQpNSUlFb3dJQkFBS0NBUUVBMGdvdk9USEw5VUYzemhRVzViY1EwVHl0eE9nQ1JrMkR5cFVYSzJIaTBUR0RQTmZ3CkdaRGhJektNS1RvRVc1ZG1WUDdlRERmTGIyd1l4cW1KT0pCUmFXRnk3RUNESHBhSHlTNHl4OWFWTmFvUCsyTzkKbTFVV2NvbnVpUUNXOEpmSFZVTGhXWW9SeHNhd0VjcDhLSzBrSTBSamFpQkV5NVoyRGxTTVhsL3RZdnR1R3I0ZApacUVITHdBNkx3ZE5oa256dGhwc1UwbnZiSUhNaks5Sm1wTUZXTUtMSHEzKzE2YTBUaFFqQ1NJRG84ZnFlYlZXCi8zSWFsUTRPWi9KMG9FajRpOG9LdXRNWFU3QUo3T2k4eXI5WTVrcnZZVzJVNHlDVzE0WGR1aFhyRnAxRkRkblQKZWhuU2p4SmhxajFRSWxCeDluUkR0cXJsQUxHUnZYVS9ScldyQndJREFRQUJBb0lCQUFRL0duZFFqMndVOThRZAoyZHlwRjlqekhoeEdDSTI5VVhYT0Q5cmJyc2RGOWY1TDYxbkkrUlJLR0ZWWkMrK0NIeHFHMEp4MG9GTlBYeXpkCkRwNHJKTW81b3lZdG83a0JtQnMwS09pcmFQYmR5bGJ0ekU2UXFOU0YvMkdidG5HRTBBM2tQVVFmSzM3V1U0YjQKamd3UWZCT09kV2dXNE8wd3pKQTdtMTdwRjVhUnIxeTZ2cEIxNUsyc2doTWdZLysyS3duL0pzejBJd25xekphRApaWWs0S0VwT043OVRZUTczMkYrY0NFRkZLS3hMdHpOL1pxSmRqWmVsNVNDMU4xb0lvR1pqL2Y4VVVnWEsxMjNUCldGWmF2clRhUFFoLzgrdi9qQVQ3NGFlbFdsd2w0dEpqTERac1VZKzYyRFJiQVZERmRhWjRqdHJXSVlQTU9reEEKdk1ZV3REa0NnWUVBMDVDWVE1Y1Iyb2xhYVJtQWF4SmQ4UTArNFg0RS9XekdLVFczdEhTb01oRkQvOFAwVGViQgpBcklRZlE2d1RacCs1WHY5YXJwZXlTZnplWk9KeUYrVHdKeG11T1dkNmR6dFNsR1ovQ0YvQzZxUFFaQlN1c0hnCmVHTERoaXNnVUtNYzB3OHAwMk54SWJGNkFkL0srWmRWT3dNWnljVWJXWVRyVG5ndExxV2RXRTBDZ1lFQS9pZVgKWm0wZzAzZ0R3NkZSdW5CcGMwU0x5V2w0dWZWVXdRaUhJRlR0QzVzL2pHaWNvc1VPeCs4RDNpU3RPdUFPa3lhUAo1MHFrYk5LakIzcUFPNUNCdmRNYW1VNUpvMHg1ZXVPY1kvckUxSTV2eFQ3WmQya0llTVpQMXZrNDFxS1l5NWNoCkdxTFRNeFFBVlNBd3RnZldPd1Y1aFJMTGtJVktsMnFRVWNZWk9xTUNnWUVBbXFieFZ6OUFjdExDLzE3LzY4VWkKWE1wRTlBcnQxTjlGdit3Zm5NOUdBRXQwdkt0ZWsrK2htYm5XcWNRcUJxQndNSXJCaGRvMDNiRFJuMGJGaW02cgprRG9FTVJiUXA1cXk3d2ZWbTJSVS9ZOHhaMGo3NEw5R3VsbmYrZHplbzNPSTU1UUhEQnArSVpZZHpPN3Q3aU84Cnp3V0dQV05UaWMzTFFMSkN2UDJkbG1VQ2dZQk14QUtiNG14ZTAwbzN4YnNjMkNWUnRxdU9PM2hHbXM1dHU3aXMKMEZvRS9uQjBaWWlpTldrZ2hKWWplK3FDOVBnU0JEekUvS3VyWHZmMUkxQW1MYUN5aUZmcFpGY2pwczZ1aXA5TApKNHhhTTJlWktVR2dLcTV2WkY3ckxMMjVQc1Z1QVFqenRhaWJMZmhudmVCWXF3ZFBMbmtrODZkZTBKUFdKazdQCkZFbThod0tCZ0VydHJoQW5CZmp4N21FOW9FUlZnQndWV1pYOXFrbE9RS2xDblJ0NmMzLy9RR0UyNXJScEhzNHAKMjh1ZHFKelZUYytBVjBVL1ZyRDFIY0N0YkkyRkZ2RGVVb3RIQnRWVmNMbmUzc2k0cmFkY2JFV3haMjF6TmZiTwplVlBMa0lPZWhkU3ZHWnc4anVsVm82c2pxaGs2MzBJOWJUYzR0SHVWdmpId1VCNkhsMHlvCi0tLS0tRU5EIFJTQSBQUklWQVRFIEtFWS0tLS0tCg==
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s create -f 'C:\Rajdeep_Mukherjee\Pluralsight_K8s\nginx.pod.yml' --save-config
error: error validating "C:\\Rajdeep_Mukherjee\\Pluralsight_K8s\\nginx.pod.yml": error validating data: apiVersion not set; if you choose to ignore these errors, turn validation off with --validate=false
PS C:\Users\erajmuk> k8s create -f 'C:\Rajdeep_Mukherjee\Pluralsight_K8s\nginx.pod.yml' --save-config
pod/my-nginx created
PS C:\Users\erajmuk> k8s get pods
NAME       READY   STATUS    RESTARTS   AGE
my-nginx   1/1     Running   0          55s
PS C:\Users\erajmuk> k8s get pod my-nginx -o yaml
apiVersion: v1
kind: Pod
metadata:
  annotations:
    kubectl.kubernetes.io/last-applied-configuration: |
      {"apiVersion":"v1","kind":"Pod","metadata":{"annotations":{},"labels":{"app":"nginx","rel":"stable"},"name":"my-nginx","namespace":"default"},"spec":{"containers":[{"image":"nginx:alpine","name":"my-nginx","ports":[{"containerPort":80}]}]}}
  creationTimestamp: "2022-07-01T17:47:31Z"
  labels:
    app: nginx
    rel: stable
  name: my-nginx
  namespace: default
  resourceVersion: "40906"
  uid: 8fc91e67-3dc9-4dd3-b681-29c22dbd638c
spec:
  containers:
  - image: nginx:alpine
    imagePullPolicy: IfNotPresent
    name: my-nginx
    ports:
    - containerPort: 80
      protocol: TCP
    resources: {}
    terminationMessagePath: /dev/termination-log
    terminationMessagePolicy: File
    volumeMounts:
    - mountPath: /var/run/secrets/kubernetes.io/serviceaccount
      name: kube-api-access-rtnrk
      readOnly: true
  dnsPolicy: ClusterFirst
  enableServiceLinks: true
  nodeName: docker-desktop
  preemptionPolicy: PreemptLowerPriority
  priority: 0
  restartPolicy: Always
  schedulerName: default-scheduler
  securityContext: {}
  serviceAccount: default
  serviceAccountName: default
  terminationGracePeriodSeconds: 30
  tolerations:
  - effect: NoExecute
    key: node.kubernetes.io/not-ready
    operator: Exists
    tolerationSeconds: 300
  - effect: NoExecute
    key: node.kubernetes.io/unreachable
    operator: Exists
    tolerationSeconds: 300
  volumes:
  - name: kube-api-access-rtnrk
    projected:
      defaultMode: 420
      sources:
      - serviceAccountToken:
          expirationSeconds: 3607
          path: token
      - configMap:
          items:
          - key: ca.crt
            path: ca.crt
          name: kube-root-ca.crt
      - downwardAPI:
          items:
          - fieldRef:
              apiVersion: v1
              fieldPath: metadata.namespace
            path: namespace
status:
  conditions:
  - lastProbeTime: null
    lastTransitionTime: "2022-07-01T17:47:31Z"
    status: "True"
    type: Initialized
  - lastProbeTime: null
    lastTransitionTime: "2022-07-01T17:47:33Z"
    status: "True"
    type: Ready
  - lastProbeTime: null
    lastTransitionTime: "2022-07-01T17:47:33Z"
    status: "True"
    type: ContainersReady
  - lastProbeTime: null
    lastTransitionTime: "2022-07-01T17:47:31Z"
    status: "True"
    type: PodScheduled
  containerStatuses:
  - containerID: docker://09bf9121bddd148c5cfbbde172a2ea0fbaec3dddadb4a52e532d796e692def7e
    image: nginx:alpine
    imageID: docker-pullable://nginx@sha256:8e38930f0390cbd79b2d1528405fb17edcda5f4a30875ecf338ebaa598dc994e
    lastState: {}
    name: my-nginx
    ready: true
    restartCount: 0
    started: true
    state:
      running:
        startedAt: "2022-07-01T17:47:32Z"
  hostIP: 192.168.65.4
  phase: Running
  podIP: 10.1.0.9
  podIPs:
  - ip: 10.1.0.9
  qosClass: BestEffort
  startTime: "2022-07-01T17:47:31Z"
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s exec my-nginx -it sh
kubectl exec [POD] [COMMAND] is DEPRECATED and will be removed in a future version. Use kubectl exec [POD] -- [COMMAND] instead.
/ #
/ #
/ #
/ #
/ # ls
bin                   home                  proc                  sys
dev                   lib                   root                  tmp
docker-entrypoint.d   media                 run                   usr
docker-entrypoint.sh  mnt                   sbin                  var
etc                   opt                   srv
/ #
/ #
/ #
/ # xit
sh: xit: not found
/ # exit
command terminated with exit code 127
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>










































































































































PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk>
PS C:\Users\erajmuk> k8s get pods
NAME       READY   STATUS    RESTARTS   AGE
my-nginx   1/1     Running   0          12h
PS C:\Users\erajmuk> cd ..
PS C:\Users> cd ..
PS C:\> cd .\Rajdeep_Mukherjee\
PS C:\Rajdeep_Mukherjee> cd .\Pluralsight_K8s\
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s> ls -lah
Get-ChildItem : A parameter cannot be found that matches parameter name 'lah'.
At line:1 char:4
+ ls -lah
+    ~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell.Commands.GetChildItemCommand

PS C:\Rajdeep_Mukherjee\Pluralsight_K8s> l
l : The term 'l' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ l
+ ~
    + CategoryInfo          : ObjectNotFound: (l:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Rajdeep_Mukherjee\Pluralsight_K8s> dir


    Directory: C:\Rajdeep_Mukherjee\Pluralsight_K8s


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         02-Jul-22     08:40                1_Kubernetes-developers-core-concepts


PS C:\Rajdeep_Mukherjee\Pluralsight_K8s>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s> cd .\1_Kubernetes-developers-core-concepts\
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts> cd .\03\
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> ls


    Directory: C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         27-Jan-21     20:31        1865675 creating-pods-slides.pdf
-a----         02-Jul-22     08:51            438 nginx.livenessprobe.yaml


PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s apply -f .\nginx.livenessprobe.yaml
The Pod "my-nginx" is invalid: spec: Forbidden: pod updates may not change fields other than `spec.containers[*].image`, `spec.initContainers[*].image`, `spec.activeDeadlineSeconds`, `spec.tolerations` (only additions to existing tolerations) or `spec.terminationGracePeriodSeconds` (allow it to be set to 1 if it was previously negative)
  core.PodSpec{
        Volumes:        {{Name: "kube-api-access-rtnrk", VolumeSource: {Projected: &{Sources: {{ServiceAccountToken: &{ExpirationSeconds: 3607, Path: "token"}}, {ConfigMap: &{LocalObjectReference: {Name: "kube-root-ca.crt"}, Items: {{Key: "ca.crt", Path: "ca.crt"}}}}, {DownwardAPI: &{Items: {{Path: "namespace", FieldRef: &{APIVersion: "v1", FieldPath: "metadata.namespace"}}}}}}, DefaultMode: &420}}}},
        InitContainers: nil,
        Containers: []core.Container{
                {
                        ... // 9 identical fields
                        VolumeMounts:  {{Name: "kube-api-access-rtnrk", ReadOnly: true, MountPath: "/var/run/secrets/kubernetes.io/serviceaccount"}},
                        VolumeDevices: nil,
-                       LivenessProbe: &core.Probe{
-                               Handler: core.Handler{
-                                       HTTPGet: &core.HTTPGetAction{Path: "/index.html", Port: intstr.IntOrString{...}, Scheme: "HTTP"},
-                               },
-                               InitialDelaySeconds: 15,
-                               TimeoutSeconds:      2,
-                               PeriodSeconds:       5,
-                               SuccessThreshold:    1,
-                               FailureThreshold:    1,
-                       },
+                       LivenessProbe:  nil,
                        ReadinessProbe: nil,
                        StartupProbe:   nil,
                        ... // 8 identical fields
                },
        },
        EphemeralContainers: nil,
        RestartPolicy:       "Always",
        ... // 25 identical fields
  }

PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s get pods
NAME       READY   STATUS    RESTARTS   AGE
my-nginx   1/1     Running   0          13h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s delete pod my-nginx
pod "my-nginx" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s apply -f .\nginx.livenessprobe.yaml
pod/my-nginx created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s get pods
NAME       READY   STATUS    RESTARTS   AGE
my-nginx   1/1     Running   0          6s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s describe pods my-nginx
Name:         my-nginx
Namespace:    default
Priority:     0
Node:         docker-desktop/192.168.65.4
Start Time:   Sat, 02 Jul 2022 08:53:54 +0200
Labels:       app=nginx
Annotations:  <none>
Status:       Running
IP:           10.1.0.10
IPs:
  IP:  10.1.0.10
Containers:
  my-nginx:
    Container ID:   docker://e801ab533fc10f08c5084eb9973f4f5bfecf0d06d96710d2191894e4f2d7230f
    Image:          nginx:alpine
    Image ID:       docker-pullable://nginx@sha256:8e38930f0390cbd79b2d1528405fb17edcda5f4a30875ecf338ebaa598dc994e
    Port:           80/TCP
    Host Port:      0/TCP
    State:          Running
      Started:      Sat, 02 Jul 2022 08:53:55 +0200
    Ready:          True
    Restart Count:  0
    Liveness:       http-get http://:80/index.html delay=15s timeout=2s period=5s #success=1 #failure=1
    Environment:    <none>
    Mounts:
      /var/run/secrets/kubernetes.io/serviceaccount from kube-api-access-58m2c (ro)
Conditions:
  Type              Status
  Initialized       True
  Ready             True
  ContainersReady   True
  PodScheduled      True
Volumes:
  kube-api-access-58m2c:
    Type:                    Projected (a volume that contains injected data from multiple sources)
    TokenExpirationSeconds:  3607
    ConfigMapName:           kube-root-ca.crt
    ConfigMapOptional:       <nil>
    DownwardAPI:             true
QoS Class:                   BestEffort
Node-Selectors:              <none>
Tolerations:                 node.kubernetes.io/not-ready:NoExecute op=Exists for 300s
                             node.kubernetes.io/unreachable:NoExecute op=Exists for 300s
Events:
  Type    Reason     Age   From               Message
  ----    ------     ----  ----               -------
  Normal  Scheduled  39s   default-scheduler  Successfully assigned default/my-nginx to docker-desktop
  Normal  Pulled     39s   kubelet            Container image "nginx:alpine" already present on machine
  Normal  Created    39s   kubelet            Created container my-nginx
  Normal  Started    38s   kubelet            Started container my-nginx
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s cluster info
Error: unknown command "cluster" for "kubectl"

Did you mean this?
        cluster-info

Run 'kubectl --help' for usage.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s cluster-info
Kubernetes control plane is running at https://kubernetes.docker.internal:6443
CoreDNS is running at https://kubernetes.docker.internal:6443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> k8s get all
NAME           READY   STATUS    RESTARTS   AGE
pod/my-nginx   1/1     Running   0          20m

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\03> cd ..
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts> cd .\04\
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME           READY   STATUS    RESTARTS   AGE
pod/my-nginx   1/1     Running   0          35m

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s apply -f .\nginx.deployment.yml
deployment.apps/my-nginx created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get pods
NAME                        READY   STATUS    RESTARTS   AGE
my-nginx                    1/1     Running   0          38m
my-nginx-66c4655884-5ttcg   1/1     Running   0          8s
my-nginx-66c4655884-f5dzp   1/1     Running   0          8s
my-nginx-66c4655884-k6mv8   1/1     Running   0          8s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments
NAME       READY   UP-TO-DATE   AVAILABLE   AGE
my-nginx   3/3     3            3           18s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments -l
Error: flag needs an argument: 'l' in -l
See 'kubectl get --help' for usage.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments -l app=front
No resources found in default namespace.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s scale -f .\nginx.deployment.yml --replicas 5
deployment.apps/my-nginx scaled
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get pods
NAME                        READY   STATUS    RESTARTS   AGE
my-nginx                    1/1     Running   0          40m
my-nginx-66c4655884-2wd7n   1/1     Running   0          5s
my-nginx-66c4655884-5ttcg   1/1     Running   0          119s
my-nginx-66c4655884-f5dzp   1/1     Running   0          119s
my-nginx-66c4655884-k6mv8   1/1     Running   0          119s
my-nginx-66c4655884-rnzrs   1/1     Running   0          5s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s describe my-nginx-66c4655884-2wd7n
error: the server doesn't have a resource type "my-nginx-66c4655884-2wd7n"
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s describe pod  my-nginx-66c4655884-2wd7n
Name:         my-nginx-66c4655884-2wd7n
Namespace:    default
Priority:     0
Node:         docker-desktop/192.168.65.4
Start Time:   Sat, 02 Jul 2022 09:34:38 +0200
Labels:       app=my-nginx
              pod-template-hash=66c4655884
Annotations:  <none>
Status:       Running
IP:           10.1.0.15
IPs:
  IP:           10.1.0.15
Controlled By:  ReplicaSet/my-nginx-66c4655884
Containers:
  my-nginx:
    Container ID:   docker://c068b0038d08d7f6e23c172aec1b2fa09b89f7c494e58bdbcdea9634b7c7e63f
    Image:          nginx:alpine
    Image ID:       docker-pullable://nginx@sha256:8e38930f0390cbd79b2d1528405fb17edcda5f4a30875ecf338ebaa598dc994e
    Port:           80/TCP
    Host Port:      0/TCP
    State:          Running
      Started:      Sat, 02 Jul 2022 09:34:39 +0200
    Ready:          True
    Restart Count:  0
    Limits:
      cpu:     100m
      memory:  128Mi
    Requests:
      cpu:        100m
      memory:     128Mi
    Environment:  <none>
    Mounts:
      /var/run/secrets/kubernetes.io/serviceaccount from kube-api-access-tmhgb (ro)
Conditions:
  Type              Status
  Initialized       True
  Ready             True
  ContainersReady   True
  PodScheduled      True
Volumes:
  kube-api-access-tmhgb:
    Type:                    Projected (a volume that contains injected data from multiple sources)
    TokenExpirationSeconds:  3607
    ConfigMapName:           kube-root-ca.crt
    ConfigMapOptional:       <nil>
    DownwardAPI:             true
QoS Class:                   Guaranteed
Node-Selectors:              <none>
Tolerations:                 node.kubernetes.io/not-ready:NoExecute op=Exists for 300s
                             node.kubernetes.io/unreachable:NoExecute op=Exists for 300s
Events:
  Type    Reason     Age   From               Message
  ----    ------     ----  ----               -------
  Normal  Scheduled  57s   default-scheduler  Successfully assigned default/my-nginx-66c4655884-2wd7n to docker-desktop
  Normal  Pulled     56s   kubelet            Container image "nginx:alpine" already present on machine
  Normal  Created    56s   kubelet            Created container my-nginx
  Normal  Started    56s   kubelet            Started container my-nginx
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME                            READY   STATUS    RESTARTS   AGE
pod/my-nginx                    1/1     Running   0          45m
pod/my-nginx-66c4655884-2wd7n   1/1     Running   0          4m20s
pod/my-nginx-66c4655884-5ttcg   1/1     Running   0          6m14s
pod/my-nginx-66c4655884-f5dzp   1/1     Running   0          6m14s
pod/my-nginx-66c4655884-k6mv8   1/1     Running   0          6m14s
pod/my-nginx-66c4655884-rnzrs   1/1     Running   0          4m20s

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/my-nginx   5/5     5            5           6m14s

NAME                                  DESIRED   CURRENT   READY   AGE
replicaset.apps/my-nginx-66c4655884   5         5         5       6m14s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s describe deployment my-nginx
Name:                   my-nginx
Namespace:              default
CreationTimestamp:      Sat, 02 Jul 2022 09:32:44 +0200
Labels:                 <none>
Annotations:            deployment.kubernetes.io/revision: 1
Selector:               app=my-nginx
Replicas:               5 desired | 5 updated | 5 total | 5 available | 0 unavailable
StrategyType:           RollingUpdate
MinReadySeconds:        0
RollingUpdateStrategy:  25% max unavailable, 25% max surge
Pod Template:
  Labels:  app=my-nginx
  Containers:
   my-nginx:
    Image:      nginx:alpine
    Port:       80/TCP
    Host Port:  0/TCP
    Limits:
      cpu:        100m
      memory:     128Mi
    Environment:  <none>
    Mounts:       <none>
  Volumes:        <none>
Conditions:
  Type           Status  Reason
  ----           ------  ------
  Progressing    True    NewReplicaSetAvailable
  Available      True    MinimumReplicasAvailable
OldReplicaSets:  <none>
NewReplicaSet:   my-nginx-66c4655884 (5/5 replicas created)
Events:
  Type    Reason             Age    From                   Message
  ----    ------             ----   ----                   -------
  Normal  ScalingReplicaSet  7m22s  deployment-controller  Scaled up replica set my-nginx-66c4655884 to 3
  Normal  ScalingReplicaSet  5m28s  deployment-controller  Scaled up replica set my-nginx-66c4655884 to 5
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s describe deployments --show-labels
Error: unknown flag: --show-labels
See 'kubectl describe --help' for usage.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments --show-labels
NAME       READY   UP-TO-DATE   AVAILABLE   AGE     LABELS
my-nginx   5/5     5            5           8m32s   <none>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete my-nginx
error: the server doesn't have a resource type "my-nginx"
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete deployment my-nginx
deployment.apps "my-nginx" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME           READY   STATUS    RESTARTS   AGE
pod/my-nginx   1/1     Running   0          51m

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s apply -f .\nginx.deployment.yml --save=config
Error: unknown flag: --save
See 'kubectl apply --help' for usage.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s apply -f .\nginx.deployment.yml --save-config
Error: unknown flag: --save-config
See 'kubectl apply --help' for usage.
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s create -f .\nginx.deployment.yml --save-config
deployment.apps/my-nginx created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME                            READY   STATUS    RESTARTS   AGE
pod/my-nginx                    1/1     Running   0          53m
pod/my-nginx-66c4655884-8pl6c   1/1     Running   0          8s
pod/my-nginx-66c4655884-fmhpw   1/1     Running   0          8s
pod/my-nginx-66c4655884-nbqzb   1/1     Running   0          8s

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/my-nginx   3/3     3            3           8s

NAME                                  DESIRED   CURRENT   READY   AGE
replicaset.apps/my-nginx-66c4655884   3         3         3       8s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments --show-labels                 NAME       READY   UP-TO-DATE   AVAILABLE   AGE   LABELS
my-nginx   3/3     3            3           45s   <none>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s create -f .\k8s.nginx.deployment.yml --save-config
pod/label-demo created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get deployments --show-labels
NAME       READY   UP-TO-DATE   AVAILABLE   AGE     LABELS
my-nginx   3/3     3            3           5m34s   <none>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> get po --show-labels
get : The term 'get' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ get po --show-labels
+ ~~~
    + CategoryInfo          : ObjectNotFound: (get:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> get pod --show-labels
get : The term 'get' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of
the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ get pod --show-labels
+ ~~~
    + CategoryInfo          : ObjectNotFound: (get:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get pod --show-labels
NAME                        READY   STATUS    RESTARTS   AGE     LABELS
label-demo                  1/1     Running   0          7m13s   app=nginx,environment=production
my-nginx                    1/1     Running   0          66m     app=nginx
my-nginx-66c4655884-8pl6c   1/1     Running   0          12m     app=my-nginx,pod-template-hash=66c4655884
my-nginx-66c4655884-fmhpw   1/1     Running   0          12m     app=my-nginx,pod-template-hash=66c4655884
my-nginx-66c4655884-nbqzb   1/1     Running   0          12m     app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels
NAME                            READY   STATUS    RESTARTS   AGE     LABELS
pod/label-demo                  1/1     Running   0          7m50s   app=nginx,environment=production
pod/my-nginx                    1/1     Running   0          66m     app=nginx
pod/my-nginx-66c4655884-8pl6c   1/1     Running   0          13m     app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-fmhpw   1/1     Running   0          13m     app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-nbqzb   1/1     Running   0          13m     app=my-nginx,pod-template-hash=66c4655884

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE   LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   38h   component=apiserver,provider=kubernetes

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE   LABELS
deployment.apps/my-nginx   3/3     3            3           13m   <none>

NAME                                  DESIRED   CURRENT   READY   AGE   LABELS
replicaset.apps/my-nginx-66c4655884   3         3         3       13m   app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete deployment my-nginx                    deployment.apps "my-nginx" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels
NAME             READY   STATUS    RESTARTS   AGE   LABELS
pod/label-demo   1/1     Running   0          10m   app=nginx,environment=production
pod/my-nginx     1/1     Running   0          69m   app=nginx

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE   LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h   component=apiserver,provider=kubernetes
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete pod
error: resource(s) were provided, but no name was specified
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete pod label-demo
pod "label-demo" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME           READY   STATUS    RESTARTS   AGE
pod/my-nginx   1/1     Running   0          69m

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s create -f .\k8s.nginx.deployment.yml --save-config
pod/label-demo created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all
NAME             READY   STATUS    RESTARTS   AGE
pod/label-demo   1/1     Running   0          3s
pod/my-nginx     1/1     Running   0          70m

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete pod label-demo
pod "label-demo" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s create -f .\nginx.deployment.yml --save-config
deployment.apps/my-nginx created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all                                       NAME                            READY   STATUS    RESTARTS   AGE
pod/my-nginx                    1/1     Running   0          70m
pod/my-nginx-66c4655884-gdp6d   1/1     Running   0          4s
pod/my-nginx-66c4655884-tb2t7   1/1     Running   0          4s
pod/my-nginx-66c4655884-zddxv   1/1     Running   0          4s

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/my-nginx   3/3     3            3           4s

NAME                                  DESIRED   CURRENT   READY   AGE
replicaset.apps/my-nginx-66c4655884   3         3         3       4s
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels
NAME                            READY   STATUS    RESTARTS   AGE   LABELS
pod/my-nginx                    1/1     Running   0          70m   app=nginx
pod/my-nginx-66c4655884-gdp6d   1/1     Running   0          19s   app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-tb2t7   1/1     Running   0          19s   app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-zddxv   1/1     Running   0          19s   app=my-nginx,pod-template-hash=66c4655884

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE   LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h   component=apiserver,provider=kubernetes

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE   LABELS
deployment.apps/my-nginx   3/3     3            3           19s   <none>

NAME                                  DESIRED   CURRENT   READY   AGE   LABELS
replicaset.apps/my-nginx-66c4655884   3         3         3       19s   app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s delete deployment my-nginx
deployment.apps "my-nginx" deleted
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels
NAME           READY   STATUS    RESTARTS   AGE   LABELS
pod/my-nginx   1/1     Running   0          71m   app=nginx

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE   LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h   component=apiserver,provider=kubernetes
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s create -f .\nginx.deployment.yml --save-config
deployment.apps/my-nginx created
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels                         NAME                            READY   STATUS    RESTARTS   AGE   LABELS
pod/my-nginx                    1/1     Running   0          71m   app=nginx
pod/my-nginx-66c4655884-k75p6   1/1     Running   0          3s    app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-lgzp6   1/1     Running   0          3s    app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-zktlq   1/1     Running   0          3s    app=my-nginx,pod-template-hash=66c4655884

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE   LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   39h   component=apiserver,provider=kubernetes

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE   LABELS
deployment.apps/my-nginx   3/3     3            3           3s    app=my-nginx

NAME                                  DESIRED   CURRENT   READY   AGE   LABELS
replicaset.apps/my-nginx-66c4655884   3         3         3       3s    app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> kubectl get po --show-labels
NAME                        READY   STATUS    RESTARTS   AGE    LABELS
my-nginx                    1/1     Running   0          73m    app=nginx
my-nginx-66c4655884-k75p6   1/1     Running   0          103s   app=my-nginx,pod-template-hash=66c4655884
my-nginx-66c4655884-lgzp6   1/1     Running   0          103s   app=my-nginx,pod-template-hash=66c4655884
my-nginx-66c4655884-zktlq   1/1     Running   0          103s   app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04> k8s get all --show-labels                         NAME                            READY   STATUS    RESTARTS   AGE   LABELS
pod/my-nginx                    1/1     Running   0          32h   app=nginx
pod/my-nginx-66c4655884-k75p6   1/1     Running   0          31h   app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-lgzp6   1/1     Running   0          31h   app=my-nginx,pod-template-hash=66c4655884
pod/my-nginx-66c4655884-zktlq   1/1     Running   0          31h   app=my-nginx,pod-template-hash=66c4655884

NAME                 TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE     LABELS
service/kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   2d22h   component=apiserver,provider=kubernetes

NAME                       READY   UP-TO-DATE   AVAILABLE   AGE   LABELS
deployment.apps/my-nginx   3/3     3            3           31h   app=my-nginx

NAME                                  DESIRED   CURRENT   READY   AGE   LABELS
replicaset.apps/my-nginx-66c4655884   3         3         3       31h   app=my-nginx,pod-template-hash=66c4655884
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>
PS C:\Rajdeep_Mukherjee\Pluralsight_K8s\1_Kubernetes-developers-core-concepts\04>