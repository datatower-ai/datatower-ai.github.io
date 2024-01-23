---
layout: default
github:
  is_project_page: true
  repository_url: "https://github.com/datatower-ai/"
---

# DTOSP

Datatower open source project

## About

DataTower.ai is an innovative technology company that focuses on leveraging powerful big data analytics platforms and AI technologies to help businesses achieve user and revenue growth in global markets. We offer a comprehensive suite of products including accurate attribution, real-time ROI tracking, user behavior analysis, ad campaign management, and marketing automation. Our goal is to provide data-driven decision-making solutions that enhance companies' capabilities in product optimization, digital marketing, and precision operations.

The Datatower open source initiative includes the parts that we consider mature, stable, and secure. It consists of a system composed of a series of open source software and our proprietary modules, including but not limited to libraries and open source projects such as Java, Python, HDFS, Hadoop, Flink, Sanic, etc. This system allows users to build and operate it on their own.

## Get Started

### Components
* SDKs: Collect data from end-user with various types of clients or directly from third-party servers.
* API server: Gateway of DT system, receiving data from SDKs and third-party.
* BI System: Provide you with visual reports and management dashboard.
    * Frontend
    * Backend
* Jobs and Schedules: ETL and runnable scheduled task programs.
* BigData Extension: Underlying architecture of big data and scalability features.

<img src="./diagrams/dt.typefromweb.app.diagrams.net.drawio.png" alt="drawing" width="800"/>


### Try SaaS

Trying out Datatower is a straightforward process.

Just visit [DataTower.ai](https://datatower.ai/) and follow the instructions step by step.

You can connect your data and get insights within **10 minutes**.

### Using, Building and Contribute Guide

1. Rent a server from AWS, Google or any other Iaas.
2. Install bigdata toolkit.
3. Load codes into server.
4. Test your service for your self.
5. Start coding.
6. Pull requests.

Setting up the machine, taking Debian 12 as an example, let's go through the deployment process.

1. Install Docker following this [doc](https://docs.docker.com/engine/install/debian/).
2. Set up the big data infrastructure based on the configuration files from the [Bigdata Initial](https://github.com/datatower-ai/bigdata-initial) repository.
3. Deploy the API Server service.
4. Deploy nginx as a traffic forwarding service.
5. Deploy the backend service for the Web Server.
6. Deploy the Web Frontend.
7. Congratulations! Your dedicated environment is now ready, and you can actively participate in the development of DataTower.ai.

## Documentation

For full documentations, please visit our websites:
[Datatower.ai Home Page](https://datatower.ai/)

To contact us or chat with other users, please visit:
[Discord Community](https://discord.gg/bRVZ64EVVV)

## Plugin

## Roadmap

* 2024-01 API server open source.
* 2024-02 BI Frontend open source.
* 2024-04 BI Backend open source.
* 2024-05 BigData Initial open source.
* 2024-07 Finish core repositories open source.

## Changes

* 2024-01 BigData Initial released.

## Thanks to

*Join us and you would be here.*

## License

[DTOSP License 1](https://datatower-ai.github.io/license)

This document is copyrighted by DATATOWER AI LIMITED (HongKong Registered) and can be disseminated. Reproduction and plagiarism in commercial activities are strictly prohibited.

In addition, each open-source code repository has its own copyright agreement and usage instructions. We primarily utilize DTOSP License 1 which is similar to Elv2 license as our code-sharing agreement.
Please refer to the specific repository's documentation for the applicable terms, if other open-source licenses apply.
Any source code not identified with a shared open-source license is prohibited for third-party use with commercial intentions.

If you have any copyright concerns, please contact: contact@datatower.ai.

