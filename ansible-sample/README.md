# ansible-sample
Ansible作成時のスケルトン

## ホストOS
CentOS 7.xに対応しています。

## 実行コマンド
```
ansible-playbook --inventory-file ./hosts/dev ./dev.yml
```

■varの中身を指定して渡す場合は下記コマンドを追加して付与
```
--extra-vars "db_name=hoge"
```

■ローカル環境下でのAnsibleホスト環境構築は下記パッケージのインストールが必要です。
```
sudo yum install MySQL-python ansible
```
