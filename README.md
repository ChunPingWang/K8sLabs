# Kubernetes 容器管理平台基本操作

## 為何需要 Kubernetes
> coreOS的創辦人 Kelsey Hightower 說 : Kubernetes 是一個用來建置平台的平台

![image](https://hackmd.io/_uploads/rkeJs5Yik1l.png)

[參考資料](https://www.opensourcerers.org/2021/12/06/kubernetes-is-a-platform-for-building-platforms/)

## Kubernetes 的前身 BORG
![截圖](https://hackmd.io/_uploads/HkSH5KoJkx.png)

[研究論文](https://research.google/pubs/large-scale-cluster-management-at-google-with-borg/)

> BORG在電影星際爭霸戰中，是可以用心智與大腦控制電子設備，Google的Infrastructure 的管理核心，即以此為名

![image](https://hackmd.io/_uploads/rJwVjtiJkg.png)

## K8s 基本架構
![image](https://hackmd.io/_uploads/HyyuQgAk1x.png)

## Labs 環境準備

### 安裝必要工具
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/)

### 下載 Labs 設定
```bash
git clone https://github.com/ChunPingWang/K8sLabs
cd K8sLabs/vagrant

# 下載虛擬機並啟動
vagrant up

# 啟動後登入虛擬機
vagrant ssh
```

### Vagrant 簡易教學
```bash
# 下列指令需在 ~/workspace/vagrant 下執行
cd ~/workspace/vargant

# 暫停虛擬機
vagrant suspend

# 啟動暫停的虛擬機
vagrant resume

# 刪除不使用的虛擬機
vagrant destroy
```

[以下內容省略...]