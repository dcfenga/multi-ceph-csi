本文记录如何在一套集群中部署两套Ceph CSI, 以支持不同的Ceph。

默认的Ceph CSI部署参考[ceph-csi](https://github.com/ceph/ceph-csi/tree/release-v3.6/deploy/cephfs/kubernetes)。

本文以Cpeh CSI 3.6.X版本为主。

# 部署CSI插件

根目录下执行`kubectl apply -f .`

# 部署StorageClass

切入目录storagecalss文件夹,然后执行：`kubectl apply -f .`

# 部署测试示例

切入目录example文件夹,然后执行：`kubectl apply -f .`