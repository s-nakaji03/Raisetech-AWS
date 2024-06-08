# 第13回課題

- CircleCI のサンプルに ServerSpec や Ansible の処理を追加してください。
- Ansible はいきなりやりたいことを実装するのではなく、最低限の「必ず成功する Playbook」を用意して徐々に仕事を追加しましょう。

---

## 構成図

![構成図](images/lecture13/Diagram.png)

### 作成したコード

https://github.com/s-nakaji03/lecture13-CircleCI.ansible

- 実際のコード、実行結果の証跡など細かい設定はこちらのリポジトリへ記載しております。

### 使用ツール

```sh
1.CircleCI
- Cloudformation、Ansible、serverspecの実行

2.Cloudformation
- VPC、EC2、ELB、RDS、S3、IAMを作成

3.Ansible
- EC2へサンプルアプリケーション用の設定作業を行う
- MySQL、Ruby、Nginx、puma

4.serverspec
- アプリケーションレスポンス確認
```