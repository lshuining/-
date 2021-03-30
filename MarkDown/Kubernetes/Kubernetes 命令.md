## Kubernetes

#### 应用yaml文件

```shell
kubectl apply -f xxx.yaml
```

#### kubect get 显示资源列表信息

```
#获取类型为Deployment 的资源列表
kubectl get deployment

#获取pod 的资源列表
kubectl get pod

#获取node 的资源列表
kubectl get node
```

#### 命名空间

在命令后面加 ``` -a ``` 或 ``` --all-namespaces``` 可查看在**命名空间里面的所有对象。**

