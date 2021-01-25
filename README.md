# Kubernetes

## Helm 安裝

## run

```bash
$ kubectl create namespace my-web
```

此時可以下以下指令，會發現 Helm 將我們前幾篇文章的元件一次建立完畢，

```bash
$ helm install my-web . -n my-web
$ kubectl get all
```

而開啟`web.backend.com`，work！

## Reference

2020-ithelp-contest

- 被選召的 Gopher 們，從零開始探索 Golang, Istio, K8s 數碼微服務世界, https://github.com/superj80820/2020-ithelp-contest
