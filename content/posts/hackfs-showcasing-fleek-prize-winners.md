---
template: post
draft: false
title: 'HackFS: Showcasing Fleek Prize Winners'
slug: HackFS-winners
date: 2020-08-24T04:00:00Z
socialimage: https://fleek-team-bucket.storage.fleek.co/fleekhackfswinners.jpeg
description: Thank you to Protocol Labs and ETH Global, the month of July - August
  2020 has been really exciting to watch developer teams build a bunch of awesome
  projects in the IPFS and Filecoin Ecosystem. The Fleek team was fortunate to be
  a Presenter Sponsor, giving an opening talk, workshops, office hours, etc. to the
  developer teams in HackFS, and had nearly 80 teams out of the 134 teams build on
  at least one or more Fleek product (Fleek Hosting, Fleek Storage, or Fleek's Space
  Daemon).
category: Announcement
tags:
- Hackathon

---
Thank you to Protocol Labs and ETH Global, the month of July - August 2020 has been really exciting to watch developer teams build a bunch of awesome projects in the IPFS and Filecoin Ecosystem.

The Fleek team was fortunate to be a Presenter Sponsor, giving an opening talk, workshops, office hours, etc. to the developer teams in HackFS, and had nearly 80 teams out of the 134 teams build on at least one or more Fleek product (Fleek Hosting, Fleek Storage, or Fleek's Space Daemon).

We wanted to take a moment and showcase some of the Fleek prize winners and share some of our thoughts on why they were special. We won't go over all the prize winners in detail, but here are all the Fleek winners:

* Best Use of **Fleek Space Daemon**: [Shop FS](https://hack.ethglobal.co/showcase/shop-fs-recSnBFT0TY7XgYNK)
* Best Use of **Fleek Hosting**: [BlockSig](https://hack.ethglobal.co/showcase/blocksig-recT3kpIaPtPKNek2), [Pyr](https://hack.ethglobal.co/showcase/pyr-rec9LKk3ZGMW6qrOa), [Web3API](https://hack.ethglobal.co/showcase/web3api-recItC5qPwuQmLqug), [IPFS-FPS](https://hack.ethglobal.co/showcase/ipfs-fps-rec1OcC5wSjdp1LEp), [Cadbury](https://hack.ethglobal.co/showcase/cadbury-reckhMFHOxGqXC8DY), [WFIL](https://hack.ethglobal.co/showcase/wfil-recCwbCnY2rnipjcR), [Parcel](https://hack.ethglobal.co/showcase/parcel-recMzBP7HUVYDYQIR),  [Public Annotation Network](https://hack.ethglobal.co/showcase/public-annotation-network-recnKxnp9epAR1fOF), [Sailplane](https://hack.ethglobal.co/showcase/sailplane-web-recoJM0CPadSrw9yj), [Pnlp.network](https://hack.ethglobal.co/showcase/pnlp-i-e-pulp-recmjUDBoPH8faOCC)
* Best Use of **Fleek Storage**: [BlockSig](https://hack.ethglobal.co/showcase/blocksig-recT3kpIaPtPKNek2), [Azureus](https://hack.ethglobal.co/showcase/azureus-recTkk0jGPXRrwg6Z), [Mobility Marketplace](https://hack.ethglobal.co/showcase/mobility-marketplace-rectlFaxjBi0m2S5j), [WatchdogDAO](https://hack.ethglobal.co/showcase/watchdog-dao-rec1ds7btRqO0ZhE3), [Browser Streaming](https://hack.ethglobal.co/showcase/browser-streaming-recBbvY9FuBJYI99c), [Access Denied](https://hack.ethglobal.co/showcase/access-denied-rec4tYQAw3m287S4o), [Dtok](https://hack.ethglobal.co/showcase/dtok-recqD1ftybrCndTYv), [IPFS Deploy for Java](https://hack.ethglobal.co/showcase/ipfs-deploy-for-java-recy6OKUfckknpvas), [Fractal](https://hack.ethglobal.co/showcase/fractal-rec9Pwf9Wu59jLEI7), [Eat Out Coin](https://hack.ethglobal.co/showcase/eat-out-coin-rec29E37C5glphmeI)

![](https://fleek-team-bucket.storage.fleek.co/fleekhackfswinners.jpeg)

## Showcase

#### Shop FS

The Shop FS team created a web app for encrypted file storage and an array of options to buy and sell decentralized content using Fleek Space Daemon. Not only did they show how IPFS and encryption tools can provide a fully private and peer-to-peer storage solution for end users, they also provided a way for users to list encrypted files on Ethereum for sale and created novel sharing mechanisms for the buyer to gain access to the encrypted file once their purchase is confirmed. All in a very private user experience. This confirms some of our expectations that developers will build web2 equivalents (sorta like dropbox + marketplace) that bring the privacy and peer to peer features to it.

**How was Shop FS made:**

"...with the introduction of a Fleek's Space Daemon which stores files in private encrypted form in buckets & a Node-Red Monitoring Service that overlooks all events happening on the contract through Graph and after verification of signatures from both sellers & buyers we ensure the buyer has private access to the file."

#### BlockSig

The BlockSig team built a fully private and encrypted notary service, like DocuSign, with all the documents to be notarized getting uploaded fully encrypted via the Space Daemon and Ethereum based tokens for signing authorization of the encrypted IPFS stored documents before sharing the encrypted files directly with the other users peer-to-peer. This is another great example of how the Space Daemon can be used to build privacy first and peer-to-peer web 2 equivalents, in this case like DocuSign.

**How BlockSig was made:**

They actually used all 3 Fleek products together, "...Fleek for Hosting \[our web apps front end\] & Storage, and the Space Daemon (which includes Textile buckets) to store encrypted files". And their explanation of interacting with Ethereum for tracking notary, "Once all signatures proofs have propagated on chain, the smart contract fires a "notarization request". The email oracle now generated a new token and sends to notary for signing." shows the endless use cases for building apps that utilize IPFS/Filecoin and Ethereum.

#### IPFS-FPS

The IPFS-FPS team created a fun and interacted first person shooter game combining web2 Unity tools with IPFS and Filecoin, where the mission of the game is to collect all the Filecoins while the app files are all referenced via IPFS. The gaming web application is hosted by Fleek Hosting.

Since the creation of the Fleek Hosting product we've used it to host our own sites and apps, and we love to see showcases of teams using it to build complex, even web2 based applications, that can leverage IPFS hosting.

**How IPFS-FPS was made:**

"Unity: Install Unity to create and export your game for IPFS. Github: Upload your game onto Github for continuous deployment. This will set up Fleek. Fleek: Fleek gets content from Github and publishes it on IPFS. Any updates to Github will automatically republish."

### Conclusion

Thank you to all the developers and participants of HackFS, especially those that leveraged the Fleek product suite. We had a ton of fun and helpful feedback from working hard with you all each day throughout the hackathon. We loved seeing web2 equivalents like Dropbox and DocuSign, have alternatives built where users can control their own data and trust the privacy while interacting with each other peer-to-peer using the Fleek Space Daemon. And to see the uptick in the Fleek Hosting and Storage products during the hackathon with nearly 80 teams building on them was amazing. The result being a bunch of awesome IPFS, Filecoin, and Ethereum based DApps. Congrats to all the prize winners!