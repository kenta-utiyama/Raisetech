## 第4回課題
- VPCの作成

![VPC](./img4/vpc.PNG)

- セキュリティグループの設定

![セキュリティグループ](./img4/securitygroup.PNG)


![セキュリティグループRDS1](./img4/rds_securitygroup.PNG)


![セキュリティグループRDS2](./img4/rds_securitygroup2.PNG)

- サブネットグループの設定

![サブネットグループ](./img4/subnetgroup.PNG)

- EC2インスタンスへSSH接続

![EC2への接続確認](./img4/EC2_kakunin.PNG)

- RDSの作成

![RDS](./img4/rds.PNG)

- EC2からRDSへの接続

![EC2からRDS](./img4/RDS_kakunin.PNG)

### 感想
コンソールからSSH接続を行うのに、権限問題やキーペアの配置で時間がかかりました。
また、EC2からRDSへの接続において、PWを打っても何も表示されず、何かが間違っているか足りてないのではないかと
考えました。
下記の3点を確認したらうまくいったので安心しました。
- VPCの接続先が同様か
- エンドポイントが間違っていないか
- セキュリティグループに設定漏れはないか