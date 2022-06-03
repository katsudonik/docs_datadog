## 事前準備

Amazon Web Services インテグレーションをセットアップ

https://docs.datadoghq.com/ja/integrations/amazon_web_services/?tab=roledelegation


# EC2

- https://docs.datadoghq.com/ja/integrations/amazon_ec2/

# ECS

https://docs.datadoghq.com/ja/agent/amazon_ecs/?tab=awscli

# datadog agent

https://docs.datadoghq.com/ja/agent/

- ホストで実行すると、ホストからイベントとメトリクスを収集し、Datadog に送信する

## 確認事項

- osはどれか
    - ECS（Elastic Container Service）とEKS（Elastic Kubernetes Service)は異なる

- agentではECSを対象としているわけではなさそう
    - => ひとまず、amazon linuxとdockerをみておけばok?




