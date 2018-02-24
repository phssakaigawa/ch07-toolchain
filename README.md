# コンテナ・ベース・オーケストレーション Docker/Kubernetesで作るクラウド時代のシステム基盤
## ch07 Kubernetes on IBM Container Service ToolChainサンプル

本レポジトリは、Github open-toolchainに公開されている[Continuously deliver a secure Docker app to a Bluemix Kubernetes Cluster](https://github.com/open-toolchain/secure-kube-toolchain)から、
内容をカスタマイズしたレポジトリです。

翔泳社から発行の[コンテナ・ベース・オーケストレーション Docker/Kubernetesで作るクラウド時代のシステム基盤](https://www.shoeisha.co.jp/book/detail/9784798155371)、
第7章 Kubernetes on IBM Container ServiceでIBM DevOps ToolChainのサンプル用にカスタマイズ公開されているレポジトリとなります。

[![BookImg](./img/bookimg.png)](https://www.shoeisha.co.jp/book/detail/9784798155371)

`ご注意`本レポジトリのToolChainデモにはIBM Cloudの従量料金(pay-as-you-go)アカウントとIBM Cloud Container Serviceの標準クラスター以上のクラスタの設定が必須です

### ToolChainをご自身のIBM Cloud アカウントにデプロイするには以下のCreate ToolChainボタンをクリックしてください。:
[![Deploy To Bluemix](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/phssakaigawa/ch07-toolchain)

# ![Icon](./.bluemix/secure-lock-kubernetes.png) Develop a Kubernetes app


### Continuously deliver a secure Docker app to a Kubernetes Cluster
This Hello World application uses Docker with Node.js and includes a DevOps toolchain that is preconfigured for continuous delivery with Vulnerability Advisor, source control, issue tracking, and online editing, and deployment to the IBM Bluemix Containers service.

Application code is stored in source control, along with its Dockerfile and its Kubernetes deployment script.
The target cluster is configured during toolchain setup (using a Bluemix API key and cluster name). You can later change these by altering the Delivery Pipeline configuration.
Any code change to the Git repo will automatically be built, validated and deployed into the Kubernetes cluster.

![Icon](./.bluemix/toolchain.png)

### To get started, click this button:
[![Deploy To Bluemix](https://console.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/phssakaigawa/bmxug-winter-2017-toolchain)

---
### Learn more 

* Blog [Continuously deliver your app to Kubernetes with Bluemix](https://www.ibm.com/blogs/bluemix/2017/07/continuously-deliver-your-app-to-kubernetes-with-bluemix/)
* Step by step [tutorial](https://www.ibm.com/devops/method/tutorials/tc_secure_kube)
* [Getting started with Bluemix clusters](https://console.bluemix.net/docs/containers/container_index.html?pos=2)
* [Getting started with toolchains](https://bluemix.net/devops/getting-started)
* [Documentation](https://console.ng.bluemix.net/docs/services/ContinuousDelivery/index.html?pos=2)
