- Monorepo for Goriant Game DeFi project


Tech Stack
- Web 2.5 Game DeFi

  - Authentication & Authorization by Firebase Auth
    + Google, Facebook, Twitter, GitHub and Email
    + Phone verification

  - Offchain
    + Server use GCP
      + Gradle 8.x
      + Java JDK 21
      + Netty 4.x
      + Websocket
      + Google Protobuf
      + MongoDB
      + MySQL
    + Game Client with Unity 2022.3.x
    + Infra
      + Github
      + GCP
      + K8S
      + Nginx with Session Stickness/Persistence

  - Onchain Goriant token trading platform
    + Player Stargazer Wallet
    + Docker
    + Euclid SDK
      - Setup guideline https://goriant.hashnode.dev/setup-constellation-dag-dev-env-for-metagraph-hackathon