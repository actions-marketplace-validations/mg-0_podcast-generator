# podcast-generator
# Sample workflow
```yml
name: Generate Feed
on: [push]
jobs:
  generate-feed:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout Repo
        uses: actions/checkout@v3
      - name: Run Feed Generator
        uses: MarkdeGraaff/podcast-generator@v1.0
```
