* Following this guide: https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/

❯ operator-sdk init --domain aypee.net --repo=github.com/swemarx/k8s-controller
❯ operator-sdk create api --group=core --version=v1 --kind=Pod --controller=true --resource=false
