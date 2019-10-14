# rook-k8s
1运行common.yml
2operator
3cluster

集群拉取镜像后启动








[root@master ceph-create]# kubectl get pods -n rook-ceph
NAME                                  READY   STATUS      RESTARTS   AGE
rook-ceph-agent-5gj8q                 1/1     Running     0          44h
rook-ceph-agent-8bcrd                 1/1     Running     0          44h
rook-ceph-agent-nnsws                 1/1     Running     0          44h
rook-ceph-mgr-a-584b5fd44-7fvkc       1/1     Running     0          44h
rook-ceph-mon-a-6ffcdb7c76-2cxx6      1/1     Running     0          44h
rook-ceph-mon-b-7bf895cb45-8rt9x      1/1     Running     0          44h
rook-ceph-mon-c-c7ddcf547-c9dr4       1/1     Running     0          44h
rook-ceph-operator-7cdd55bcfd-52f8b   1/1     Running     0          44h
rook-ceph-osd-0-68694d46b-qvf7h       1/1     Running     0          44h
rook-ceph-osd-1-75468bb9ff-zpp54      1/1     Running     0          44h
rook-ceph-osd-2-b49959cc6-qxft8       1/1     Running     0          44h
rook-ceph-osd-prepare-master-5smfp    0/1     Completed   0          44h
rook-ceph-osd-prepare-node1-k6nlm     0/1     Completed   0          44h
rook-ceph-osd-prepare-node2-n98ws     0/1     Completed   0          44h
rook-ceph-tools-7cf4cc7568-vwbn9      1/1     Running     0          43h





4 dashboard-external-https.yaml创建服务
