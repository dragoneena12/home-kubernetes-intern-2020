# home-kubernetes-intern-2020

## 別途やること
- 証明書とkubeconfigの生成・配置
  - kubeconfigにおいてkubeletのapi-serverの参照先をロードバランサ（10.0.0.10）に設定
- 各種バイナリを `files` ディレクトリに設置
- ネットワーク設定とか
- `/boot/firmware/cmdline.txt` に `cgroup_memory=1 cgroup_enable=memory` を追記して再起動