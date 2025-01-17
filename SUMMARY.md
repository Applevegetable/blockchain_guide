# 区块链技术指南

* [前言](README.md)
* [修订记录](revision.md)
* [如何贡献](contribute.md)
* [区块链的诞生](01_history/README.md)
  * [记账科技的千年演化](01_history/ledger_history.md)
  * [分布式记账与区块链](01_history/dlt_problem.md)
  * [集大成者的比特币](01_history/bitcoin.md)
  * [区块链的商业价值](01_history/business.md)
  * [本章小结](01_history/summary.md)
* [核心技术概览](02_overview/README.md)
  * [定义与原理](02_overview/definition.md)
  * [技术的演化与分类](02_overview/classify.md)
  * [关键问题和挑战](02_overview/challenge.md)
  * [趋势与展望](02_overview/vision.md)
  * [认识上的误区](02_overview/misunderstand.md)
  * [本章小结](02_overview/summary.md)
* [典型应用场景](03_scenario/README.md)
  * [应用场景概览](03_scenario/glance.md)
  * [金融服务](03_scenario/finance.md)
  * [征信管理](03_scenario/trust.md)
  * [权属管理与溯源](03_scenario/ownership.md)
  * [资源共享](03_scenario/sharing.md)
  * [物流与供应链](03_scenario/logistics.md)
  * [物联网](03_scenario/iot.md)
  * [其它场景](03_scenario/others.md)
  * [本章小结](03_scenario/summary.md)
* [分布式系统核心技术](04_distributed_system/README.md)
  * [一致性问题](04_distributed_system/problem.md)
  * [共识算法](04_distributed_system/algorithms.md)
  * [FLP 不可能原理](04_distributed_system/flp.md)
  * [CAP 原理](04_distributed_system/cap.md)
  * [ACID 原则与多阶段提交](04_distributed_system/acid.md)
  * [Paxos 算法与 Raft 算法](04_distributed_system/paxos.md)
  * [拜占庭问题与算法](04_distributed_system/bft.md)
  * [可靠性指标](04_distributed_system/availability.md)
  * [本章小结](04_distributed_system/summary.md)
* [密码学与安全技术](05_crypto/README.md)
  * [密码学简史](05_crypto/history.md)
  * [Hash 算法与数字摘要](05_crypto/hash.md)
  * [加解密算法](05_crypto/algorithm.md)
  * [消息认证码与数字签名](05_crypto/signature.md)
  * [数字证书](05_crypto/cert.md)
  * [PKI 体系](05_crypto/pki.md)
  * [Merkle 树结构](05_crypto/merkle_trie.md)
  * [Bloom Filter 结构](05_crypto/bloom_filter.md)
  * [同态加密](05_crypto/homoencryption.md)
  * [其它技术](05_crypto/others.md)
  * [本章小结](05_crypto/summary.md)
* [比特币 —— 区块链思想诞生的摇篮](06_bitcoin/README.md)
  * [比特币项目简介](06_bitcoin/intro.md)
  * [实体货币到加密数字货币](06_bitcoin/currency.md)
  * [基本原理和设计](06_bitcoin/design.md)
  * [挖矿过程](06_bitcoin/mining.md)
  * [共识机制](06_bitcoin/consensus.md)
  * [闪电网络](06_bitcoin/lightning_network.md)
  * [侧链](06_bitcoin/sidechain.md)
  * [热点问题](06_bitcoin/hot_topics.md)
  * [相关工具](06_bitcoin/tools.md)
  * [本章小结](06_bitcoin/summary.md)
* [以太坊 —— 挣脱加密货币的枷锁](07_ethereum/README.md)
  * [以太坊项目简介](07_ethereum/intro.md)
  * [核心概念](07_ethereum/concept.md)
  * [主要设计](07_ethereum/design.md)
  * [相关工具](07_ethereum/tools.md)
  * [安装客户端](07_ethereum/install.md)
  * [使用智能合约](07_ethereum/smart_contract.md)
  * [智能合约案例：投票](07_ethereum/contract_example.md)
  * [本章小结](07_ethereum/summary.md)
* [超级账本 —— 面向企业的分布式账本](08_hyperledger/README.md)
  * [超级账本项目简介](08_hyperledger/intro.md)
  * [社区组织结构](08_hyperledger/community.md)
  * [顶级项目介绍](08_hyperledger/project.md)
  * [开发必备工具](08_hyperledger/tools.md)
  * [贡献代码](08_hyperledger/contribute.md)
  * [本章小结](08_hyperledger/summary.md)
* [Fabric 安装与部署](09_fabric_deploy/README.md)
  * [简介](09_fabric_deploy/intro.md)
  * [本地编译组件](09_fabric_deploy/install_local.md)
  * [容器方式获取](09_fabric_deploy/install_docker.md)
  * [本地方式启动 Fabric 网络](09_fabric_deploy/start_local.md)
  * [容器方式启动 Fabric 网络](09_fabric_deploy/start_docker.md)
  * [本章小结](09_fabric_deploy/summary.md)
  * [简介](fabric/intro.md)
  * [使用 Fabric 1.0 版本](fabric/1.0.md)
  * [使用 Fabric SDK Node](fabric/sdk-node.md)
  * [Fabric v0.6](fabric/v0.6/README.md)
    * [安装部署](fabric/v0.6/install.md)
    * [使用 chaincode](fabric/v0.6/usage.md)
    * [权限管理](fabric/v0.6/membersrcv-usage.md)
    * [Python 客户端](fabric/v0.6/hyperledger-py.md)
  * [小结](fabric/summary.md)
* [智能合约开发](11_app_dev/README.md)
  * [简介](11_app_dev/intro.md)
  * [链码概念与结构](11_app_dev/chaincode.md)
  * [示例一：信息公证](11_app_dev/chaincode_example01.md)
  * [示例二：交易资产](11_app_dev/chaincode_example02.md)
  * [示例三：数字货币发行与管理](11_app_dev/chaincode_example03.md)
  * [示例四：学历认证](11_app_dev/chaincode_example04.md)
  * [示例五：社区能源共享](11_app_dev/chaincode_example05.md)
  * [小结](11_app_dev/summary.md)
* [Fabric 架构与设计](13_fabric_design/README.md)
  * [简介](13_fabric_design/intro.md)
  * [架构设计](13_fabric_design/design.md)
  * [消息协议](13_fabric_design/protocol.md)
  * [小结](13_fabric_design/summary.md)
* [区块链服务平台设计](17_baas/README.md)
  * [简介](17_baas/intro.md)
  * [IBM Bluemix 云区块链服务](17_baas/bluemix.md)
  * [微软 Azure 云区块链服务](17_baas/azure.md)
  * [使用超级账本 Cello 搭建区块链服务](17_baas/cello.md)
  * [本章小结](17_baas/summary.md)
* [性能与评测](evaluation/README.md)
  * [简介](evaluation/intro.md)
  * [Hyperledger Fabric v0.6](evaluation/hyperledger.md)
  * [小结](evaluation/summary.md)
* [附录](appendix/README.md)
  * [术语](appendix/terms.md)
  * [常见问题](appendix/faq.md)
  * [Go 语言开发相关](appendix/golang/README.md)
    * [安装与配置 Golang 环境](appendix/golang/install.md)
    * [编辑器与 IDE](appendix/golang/ide.md)
    * [高效开发工具](appendix/golang/tools.md)
    * [依赖管理](appendix/golang/package.md)
  * [ProtoBuf 与 gRPC](appendix/grpc.md)
  * [参考资源链接](appendix/resources.md)
