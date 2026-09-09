# AWS Evidence

AWS SAA ハンズオンで取得した公開用エビデンスです。

各画像は公開前にマスキング確認済みです。

## IAM 基本操作

- [IAM ダッシュボード](iam/iam-01-dashboard.png)
- [AdministratorAccess ポリシー設定](iam/iam-02-admin-policy.png)
- [IAM ユーザー作成](iam/iam-03-user-created.png)
- [IAM グループへのユーザー割り当て](iam/iam-04-group-assignment.png)
- [MFA 有効化](iam/iam-05-mfa-enabled.png)

## VPC / Network

- [VPC 作成](vpc/vpc-01-vpc.png)
- [Public / Private Subnet 作成](vpc/vpc-02-subnets.png)
- [Public Route Table 設定](vpc/vpc-03-public-route-table.png)
- [Subnet 設定確認](vpc/vpc-04-subnet-details.png)
- [RDS Security Group](vpc/vpc-05-rds-security-group.png)
- [EC2 Security Group](vpc/vpc-06-ec2-security-group.png)

## Amazon RDS

- [RDS Subnet Group](rds/rds-01-subnet-group.png)
- [RDS PostgreSQL インスタンス](rds/rds-02-instance.png)
- [EF Core Migration / RDS 接続確認](rds/rds-03-migration-and-health.png)

## CloudWatch Metrics

- [EC2 CPUUtilization](cloudwatch/cloudwatch-01-ec2-cpu.png)
- [RDS DatabaseConnections](cloudwatch/cloudwatch-02-rds-connections.png)
- [RDS メトリクス確認](cloudwatch/cloudwatch-03-rds-metric.png)

## EC2 IAM Role / CloudWatch Logs

- [EC2 用 IAM Role](ec2-iam-role/observability-01-iam-role.png)
- [IAM Role 一覧](ec2-iam-role/observability-02-role-list.png)
- [CloudWatch Logs ロググループ](ec2-iam-role/observability-03-log-group.png)
- [Docker awslogs 設定](ec2-iam-role/observability-04-docker-awslogs.png)
- [Invoice API ログイベント](ec2-iam-role/observability-05-log-events.png)

## Application Load Balancer

- [ALB Security Group](alb/alb-01-security-group.png)
- [Target Group](alb/alb-02-target-group.png)
- [Application Load Balancer](alb/alb-03-load-balancer.png)
- [ALB Listener / Routing](alb/alb-04-listener.png)
- [ALB HTTP Security Group 設定](alb/alb-05-security-group-http.png)

## 関連ドキュメント

AWS 構成全体、ConoHa VPS との比較、構築内容については
[プロジェクト README](../../../README.md) を参照してください。