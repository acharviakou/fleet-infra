# fleet-infra
Test repo

1. export GITHUB_TOKEN="********"
   export GITHUB_USER="acharviakou"

2. flux check --pre
3. flux bootstrap github \
  --owner=$GITHUB_USER \
  --repository=fleet-infra \
  --branch=main \
  --path=./clusters/local \
  --personal