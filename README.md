# Tradeshift maven orb

Setting up CircleCI to build maven projects the Tradeshift way

To use this orb, try:

```
version: 2.1
orbs:
  setup-maven: tradeshift/maven-setup@1.0.0
jobs:
  myjob:
    docker:
      - image: "circleci/node:9.6.1"
    steps:
      - setup-maven

```
