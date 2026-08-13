# Awesome Golem with stars

[<img src="golem-logo.svg" align="right" width="150">](https://golem.network/)

> Welcome to **Awesome Golem**, a community-curated list of resources, links, projects, tools and applications on Golem!

The users of Golem run the reference implementation in the form of the Rust implementation, Yagna. Together the users make up the Golem Network, a P2P marketplace for computational resources where individuals can act as one of the two non-exclusive roles; a provider selling idle resources, or a requestor buying resources to run tasks.

## Contents

* [Golem](#golem)
* [Network Statistics](#network-statistics)
* [Golem Projects](#Golem-Projects)
  * [GPU Provider](#GPU-Provider)
  * [Ray on Golem](#Ray-on-Golem)
  * [golem-js - the JS SDK from Golem](#golem-js---the-JS-SDK-from-Golem)
  * [Jupyter on Golem](#Jupyter-on-Golem)
  * [Rendering on Golem](#Rendering-on-Golem)
  * [Reputation System](#Reputation-System)
* [Ecosystem](#Ecosystem)
  * [Blockchain Automations (aka Emeth.xyz)](#Blockchain-automations-\(aka-Emeth.xyz\))
* [Developer and Requestor Resources](#developer-and-requestor-resources)
* [Provider Resources](#provider-resources)
  * [Monitoring](#monitoring)
  * [Provisioning](#provisioning)
* [Learning Resources](#learning-resources)
  * [Presentations and Workshop Material](#presentations-and-workshop-material)
  * [Unraveling Golem's The Next Milestone Blog Series](#unraveling-golems-the-next-milestone-blog-series)
  * [GitHub Digest Blog Series](#github-digest-blog-series)
* [Archive](#Archive)
  * [Apps](#apps)

## Golem

* [Golem Network Platform](https://www.golem.network/platform) - Learn the Golem platform on the official Golem Network website.
* [Golem Network Discord](https://chat.golem.network/) - Join the Golem Network community on Discord and chat directly with the team.
* [Reddit](https://reddit.com/r/GolemProject) - Golem Network discussion on the Reddit platform.
* [Twitter](https://twitter.com/golemproject) - The Golem Project Twitter.
* [Blog](http://blog.golemproject.net/) - The official blog where you can find the most reliable information on announcements, summaries and updates.

## Network Statistics

* [Golem Network Stats](https://stats.golem.network) - Statistics tracking tasks and provider resource utilization in the Golem Network.
* [Golem Stats backend](https://github.com/cryptobench/golem-stats-backend) ⭐ 2 | 🐛 10 | 🌐 Python | 📅 2026-08-12 - Backend of the Golem Network Statistics page including API endpoint URLs.
* [Stats API Documentation](https://docs.stats.golem.network/) - API endpoints that the Golem Network Stats page uses to display its data.

## Golem Projects

### GPU Provider

We want to extend the capabilities of Golem Network for GPU workloads. Project status is available on the pinned messages of the dedicated GPU Provider channel on our [Discord](https://chat.golem.network/). You can find it under #golem-projects.

### Ray on Golem

[Ray on Golem](https://github.com/golemfactory/ray-on-golem) ⭐ 8 | 🐛 18 | 🌐 Python | 📅 2024-10-22 is an exciting integration with Ray, a distributed computing framework, to provide an easier way of accessing the Golem Network for Python developers.

### golem-js - the JS SDK from Golem

[golem-js](https://github.com/golemfactory/golem-js) ⭐ 42 | 🐛 15 | 🌐 TypeScript | 📅 2026-02-14 is a library and set of developer tools and docs that are aimed to enable developers to create Golem applications running in Node.js or browser context.

### Jupyter on Golem

[Jupyter on Golem](https://github.com/golemfactory/golem-kernel-python) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-07-18 is a JupyterLab Python kernel that empowers you to run your Python Notebooks using the decentralized resources available on the Golem Network.

### Rendering on Golem

In close collaboration with Reality Games, we've developed a service that activates Golem's providers for rendering personalized building animations as a (web2) proof-of-ownership for ERC-1155 tokens. Learn more [here](https://reality.golem.network/)

### Reputation System

The Reputation System goal is to address the challenges of trust and reliability in the network where anyone can participate as a provider or requestor without any sort of identification. The system aims to establish a framework of trust, ensuring secure and reliable interactions between participants on the network.

## Ecosystem

### Blockchain Automations (aka Emeth.xyz)

Emeth specializes in DeFi (Decentralized Finance) portfolio management and blockchain automations. It leverages Golem's technology to offer tools for  automation and simplification of managing DeFi investments. The platform focuses on enhancing the ease and efficiency of operating within the DeFi space. It combines user-friendly interfaces with sophisticated analytics, catering to the needs of both novice and experienced DeFi users.

## Developer and Requestor Resources

* [Golem Docs](https://docs.golem.network/) - A manual for Golem (both for Requestors and Providers).
* [Python API Reference](https://yapapi.readthedocs.io/) - Yapapi API Reference.
* [Releases List](https://github.com/golemfactory/yagna/releases) - GitHub releases of Yagna.
* [JS Requestor Quickstart](https://docs.golem.network/docs/quickstarts/js-quickstart) - Get started quickly and create your first tasks/request on Golem.
* [Yagna tag on Stack Overflow](https://stackoverflow.com/questions/tagged/yagna) - Use the Yagna tag if you have an interesting question you'd like answered.

## Provider Resources

* [Yagna-binaries for aarch64](https://github.com/MarijnStevens/yagna-binaries) ⚠️ Archived - Build for 64 bit arm architecture to be able to run as a provider on a system such as a Raspberry Pi.
* [Golem Price Updater](https://github.com/jedbrooke/golem-price-updater) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2024-03-06 - Automatically adjust the price for your Golem node based on the current price of GLM.
* [Provider Tutorial](https://docs.golem.network/docs/providers/provider-installation) - Get started as a Provider on Golem Network using the handbook.
* [Automatically update provider node prices](https://gist.github.com/sv3t0sl4v/28f896752edc9e20347ffc6d8cefe74c) - Script that checks the median of the prices on stats.golem.network and updates all 3 values on the provider node related to price.

### Monitoring

* [Golem Provider dashboard](https://github.com/vciancio/golem-dashboard) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2021-05-24 - ReactJS dashboard made to quickly gather status from your provider nodes without having to SSH into them.
* [Golem Provider dashboard backend / GolemBar](https://github.com/vciancio/golem-node-server) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2021-06-13 - Flask backend that collects the data from the provider that's then used with the dashboard project above.

### Provisioning

* [Golem Provider Node](https://github.com/alexandre-abrioux/golem-node) ⭐ 22 | 🐛 0 | 🌐 Dockerfile | 📅 2026-08-07 - Docker version of a node to help you get started running as a provider in a Docker container quick.
* [Automatic Golem](https://github.com/r34x/Automatic-Golem) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2021-04-18 - Setup a Golem Provider with simple instructions and logs guiding you through the process.
* [Golem Provider node](https://github.com/blue-notes-robot/golem-node) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2022-04-09 - Fork of Alxexandre-abrioux project above that allows to dynamically generate config files from ENV variables and specify how many replicas you'd like to spawn.
* [Golem Provider Terraform](https://github.com/nemani/golem-provider-terraform) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2021-01-06 - Terraform script to automatically deploy a Golem Provider on a cloud provider and setup monitoring using prometheus.
* [Ansible ya\_provider](https://galaxy.ansible.com/golemfactory/ya_provider) - Ansible role that deploys a Golem provider automatically with minimal configuration required.

## Learning Resources

### Presentations and Workshop Material

* [Golem: Distributed parallel computing with JavaScript](https://www.youtube.com/watch?v=2iUhqOJUsoI) - Presentation from Grzegorz Godlewski on Distributed Parallel Computing with JavaScript, based on Golem Network (meet.js Summit 2023).
* [Golem: Architecture, SDKs and tips with Jakub Mazurek at 0xHack](https://youtu.be/1UoZWC9XI2g) - Live workshop diving into how any developer with Python or JS coding experience can start build applications running on Golem.

### Unraveling Golem's The Next Milestone Blog Series

* [Unraveling Golem's The Next Milestone](https://blog.golemproject.net/next-milestone) - Introduction to the Yagna implementation of Golem.
* [Unraveling Golem's The Next Milestone, Part II](https://blog.golemproject.net/next-milestone-part-ii/) - Fundamental architectural concepts which constitute the foundations of the new implemenation of Golem, Yagna.
* [Unraveling Golem's The Next Milestone, Part III](https://blog.golemproject.net/next-milestone-part-iii/) - The elements of Golem's reference architecture, and illustrates how they interact to form a working ecosystem, being the Golem Network.

### GitHub Digest Blog Series

* [Golem GitHub Digest #1](https://blog.golemproject.net/golem-github-digest-1/) - Understanding the Golem Repositories.
* [Golem GitHub Digest #2](https://blog.golemproject.net/golem-github-digest-2/) - Diving into the Golem Repositories.
* [Golem GitHub Digest #3](https://blog.golemproject.net/golem-github-digest-3/) - Diving into Pull Requests of the Golem repositories.
* [Golem GitHub Digest #4](https://blog.golemproject.net/golem-github-digest-4/) - Diving into latest releases in the Golem repositories.
* [Golem GitHub Digest #5](https://blog.golemproject.net/golem-github-digest-5/) - Diving into the Golem alpha testnet.
* [Golem GitHub Digest #6](https://blog.golemproject.net/golem-github-digest-6/) - SGX proof-of-concept for Golem.
* [Golem GitHub Digest #7](https://blog.golemproject.net/golem-github-digest-7/) - Decentralization of the Golem marketplace.
* [Golem GitHub Digest #8](https://blog.golemproject.net/golem-github-digest-8/) - Awesome Golem and next steps to Alpha 3.
* [Golem GitHub Digest #9](https://blog.golemproject.net/golem-github-digest-9/) - AMD provider support, network metrics and improved proposal handling.
* [Golem GitHub Digest #10](https://blog.golemproject.net/golem-github-digest-10/) - Improvements from community feedback.
* [Golem GitHub Digest #11](https://blog.golemproject.net/golem-github-digest-11/) - Easy log collection.
* [Golem GitHub Digest #12](https://blog.golemproject.net/golem-github-digest-12/) - We are on MAINNET and gathering feedback.
* [Golem GitHub Digest #13](https://blog.golemproject.net/golem-github-digest-13/) - Progressing faster with the help of the Golem community.
* [Golem GitHub Digest #14](https://blog.golemproject.net/golem-github-digest-14/) - Towards the next major release.
* [Golem GitHub Digest #15](https://blog.golemproject.net/golem-github-digest-15/) - Awesome, Goth improvements and towards Beta 3.
* [Golem GitHub Digest #16](https://blog.golemproject.net/golem-github-digest-16/) - VPN, ARM binaries for requestors, and custom usage counters.

## Contributing

Pull requests and issues with suggestions to Awesome Golem are welcome! Please read the [contributing](contributing.md) guidelines before submitting a PR.

## Archive

### Apps

* [Chess On Golem](https://chessongolem.app/) - Hosted Chess app to play against the providers of the network utilizing the Stockfish open source Chess engine.
* [Go le' Machin](https://github.com/DEUTSCHKLUB/go-le-m) ⚠️ Archived - Web based bulk image editor that allows users to upload multiple images and apply bulk actions to them.

#### Docker

* [Golem Requestor Node](https://github.com/DerekJarvis/general-golem) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2020-11-24 - Dockerized requestor environment. Pass in the py script, it sets up the daemon and runs it.

#### Testing

* [Golem Test Harness (Goth)](https://github.com/golemfactory/goth) ⭐ 11 | 🐛 92 | 🌐 Python | 📅 2026-01-08 - Tool with the purpose of speeding up your development process and making it more enjoyable for application creators.
* [Golem SLATE](https://github.com/deutschklub/golem-slate) ⚠️ Archived - Open source repository for Golem SLATE described in the above Apps section.
* [Golem CI](https://github.com/hhio618/golem-ci) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-01-07 - Decentralized task pipeline.
* [ThorgPress](https://github.com/figurestudios/thorgpress) ⭐ 1 | 🐛 4 | 🌐 Shell | 📅 2022-06-19 - A tool to benchmark providers and unveil their true capabilities beyond what can be seen through the marketplace.
* [Golem-afl](https://github.com/sladecek/golem-afl) - An experimental test-fuzzing framework. Assists in finding security holes.
* [Golem Cargo Test](https://github.com/sladecek/golem_cargo_test) - An adaptive distributed test executor for Rust projects.

#### VPN

* [Yagna httpx client](https://github.com/golemfactory/ya-httpx-client/tree/johny-b/vpn) ⭐ 1 | 🐛 7 | 🌐 Python | 📅 2021-10-06 - VPN usage on Yagna demonstrating communication with a provider-based HTTP server the way you communicate with any other HTTP server.
* [Golem Provider with network access](https://github.com/jedbrooke/golem-network-requestor) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-11-28 - A requstor that acts as a http proxy for running providers, allowing them to access the wider internet.

#### Games

* [ChessOnGolem](https://github.com/broadcastmonkey/ChessOnGolem) ⭐ 11 | 🐛 2 | 🌐 JavaScript | 📅 2021-03-29 - Open source repository for Chess described in first Apps section. Includes React frontend for the 2 AI's playing against each other through the Golem backend.
* [Golem Fleet Battle Simulator](https://github.com/UnfortuN8/Golem-Fleet-Battle-Simulator) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-06-29 - System for calculating the results of a battle between two opposing starship fleets. Used in the iOS game Rock Paper Frigate to determine the result of PvP fleet battles.
* [Golem Sudoku](https://github.com/Dodecane/golem-sudoku) ⭐ 1 | 🐛 2 | 🌐 JavaScript | 📅 2021-01-12 - Game of Sudoku with size variants.
* [HSOG-requester](https://github.com/ChrisHelmsC/hsog-requestor) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2022-01-07 - Helps the HearthStone community in the design and building of decks by running a large number of simulated games.

#### CLI Tools

* [Golocity](https://github.com/davidstyers/golocity) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2021-07-30 - Build and deploy your dockerized applications on the Golem Network in just two commands.
* [Golem Completion Engine](https://github.com/krunch3r76/gc__enhanced_completion) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-02-12 - Enhanced bash completion engine that extends built-in completions by providing contextual help for golemsp and yagna.
* [gc\_\_push\_image](https://github.com/figurestudios/gc__push_image) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2022-06-30 - A CLI tool that publishes the GVMI image to Skynet, making users able to change the image\_url without self-hosting/giving up control.

#### Video Transcoding and Editing

* [Golem Transcoding requestor](https://github.com/Edhendil/golem-transcoding) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2020-11-25 - React + Spring based webapp accepting video files as input and transcoding these files into different formats.
* [Golem Auto Editor](https://github.com/jedbrooke/golem-auto-editor) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-06-25 - Run Auto-Editor to automatically perform some video editing functions, offload the video processing to Golem.
* [Golem Network Video Transcoder](https://github.com/Doc-Saintly/golem-video) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2020-10-19 - Sample app to transcode videos. Select your transcoding profile and then upload your videos.

#### Data Analysis

* [Flan](https://github.com/nestorbonilla/flan) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2021-01-06 - Tool for entrepreneurs that provide customized analysis of millions of worldwide trade value records giving them a bold guideline about what sectors they would need to take more attention to.
* [Full-Text Search Engine](https://github.com/niklr/golem-fulltext-search) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-08-22 - A search engine service that goes through text files.
* [Golem COVID](https://github.com/iRhonin/golem-covid) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-10-23 - Creates images of new deaths per million related to COVID. After all images generated, it will gather them and create a gif.
* [Golem Parallel Matplotlib](https://github.com/CoeJoder/golem-parallel-matplotlib) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-10-24 - Various statistical analyses are performed on circadian rhythm measurements in human test subjects.
* [Golem Lorenz-attractor](https://github.com/hhio618/golem-lorenz-attractor) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-11-06 - A system of three coupled, first-order, nonlinear differential equations which describe the trajectory of a particle through time.
* [Golem Geomandel](https://github.com/Edhendil/golem-geomandel) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-10-31 - Python script for generating sequences of Mandelbrot images centered on a single point and with zoom increasing in each image.
* [Coacervate](https://github.com/pryce-turner/coacervate/) - Coacervate is a free and open-source public good that lets you easily run genomic analyses on an extremely low-cost global supercomputer; democratizing access to the knowledge and infrastructure required to carry out groundbreaking research.

#### Data Simulation

* [Golem Array](https://github.com/johngrantuk/golem-array) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2020-12-29 - Antenna array design and simulation.
* [cadCAD Golem](https://github.com/rogervs/cadcadgolem) ⚠️ Archived - Package wrapper for cadCAD to dispatch the simulation workload to multiple Golem nodes. Supports Jupyter Notebook.
* [Limit visualization](https://github.com/vporton/limit-visualization) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-01-24 - Plots graphs with various limits. Supports discontinous graphs.
* [GolemGraphWavePair](https://github.com/smiley1983/golemGraphWavePair) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-10-20 - Generates graph frames, then combine them into an animation.
* [Golemized strong-gravitational-lense](https://github.com/rezahsnz/golemized-strong-gravitational-lense) ⚠️ Archived - Simple distributed computing hack that simulates a physical phenomena called gravitional lensing.

#### Data Optimization

* [Golem or-tools](https://github.com/Doc-Saintly/golem-ortools) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-10-08 - Uses the or-tools Constraint Programming library to solve problems.
* [Mutta Puffs](https://github.com/DeveloperInProgress/Mutta-Puffs) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-09-27 - Sports league scheduler that solves the Travelling Tournament Problem for a given set of teams using Population-based Simulated Annealing.
* [No more COFUD](https://github.com/DEUTSCHKLUB/no-more-COFUD) ⚠️ Archived - Calculates how to fit the most people into a space while keeping 2 meters distance between each other.

#### Machine Learning

* [DeML-Golem](https://github.com/anshuman73/DeML-Golem) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2021-01-08 - Decentralised Machine Learning using Federated Learning to combine the sub-step models, it trains on different provider nodes into a full fleged model.
* [Golem Image Classifier](https://github.com/ControlCplusControlV/Golem-Image-Classifier) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2021-09-19 - Train and classify images through an active service.

#### Deep Learning

* [Deepart Golem](https://github.com/echinocacti/deepart_golem) ⭐ 3 | 🐛 4 | 🌐 CSS | 📅 2021-01-06 - Makes art using distributed computing by running a tensorflow app, uploading your content and style picture.
* [Mlg](https://github.com/rezahsnz/mlg) ⚠️ Archived - CNN predict services, a deep learning application that distributes popular CNNs pre-trained with ImageNet datasets.

#### RNG

* [Entropythief](https://github.com/krunch3r76/entropythief) ⭐ 5 | 🐛 6 | 🌐 Python | 📅 2025-10-27 - Get random entropy at a steal of a rate from multiple providers utilizing the linux entropy source or Intel's RDRAND cpu instruction (inspired by Gandom).
* [Gandom](https://github.com/rezahsnz/gandom) ⚠️ Archived - Extract random streams from providers. Supports two PRNGs, one based on Chaos machines and the other that makes use of Sodium.

#### Password Recovery

* [Golem-JTR](https://github.com/hhio618/golem-jtr) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-01-11 - Run John The Ripper to recover a password.
* [Yacat](https://docs.golem.network/docs/creators/python/tutorials/task-example-2-hashcat) - Hashcat password-recovery step-by-step.

#### DeFi

* [Golem Staking Pool incentivize system for GLM holders](https://github.com/masaun/GLM-stake-pool) ⭐ 9 | 🐛 0 | 🌐 Solidity | 📅 2021-01-19 - A smart contract in order to provide the opportunity of yield farming for GLM token holders.
* [Magic-doll](https://github.com/bakaoh/magic-doll) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2021-01-07 - Sumer is a DeFi application that people may delegate their Splinterland card to earn passive income. Its core is `Kyle`, a Golem app that does all the computation to pick the best team to play for each match.

#### User Interfaces

* [Golem UI](https://github.com/shri4net/golem-hackathon-2020) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2021-01-14 - Electron user interface for Yagna.

#### Miscellaneous

* [Gc\_\_ListOffers](https://github.com/krunch3r76/gc__listoffers) ⭐ 3 | 🐛 7 | 🌐 Python | 📅 2023-09-17 - List offers by providers on the Golem Network with a GUI.
* [Filterms](https://github.com/krunch3r76/filterms) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2025-10-28 - Market-strategy for whitelisting or blacklisting as a Golem requestor (yapapi).
* [gvm-vim](https://github.com/canokaue/gvm-vim) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2020-10-17 - Golemized docker image for compiling the VIM editor.
* [Golem Image Sharpening](https://github.com/visualNext/golem) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2021-01-05 - A tool to sharpen images.
* [golem-bulk-image-handler](https://github.com/figurestudios/golem-bulk-image-handler) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-12-18 - Takes an input image and processes it in many different ways using the Pillow library.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
