# AWS CDK Python Template

## Getting Started

以下の環境変数を設定してください。

- AWS_ACCESS_KEY_ID
- AWS_SECRET_ACCESS_KEY
- AWS_DEFAULT_REGION

VSCode で本プロジェクトを開き、コマンドパレット（Ctrl+Shift+P）から[Dev Containers: Reopen in Container...]を実行し、下記コマンドを実行してください。

```sh
mkdir -p app
cd app
cdk init app --language python
source .venv/bin/activate
pip install -r requirements.txt
cdk bootstrap
```
