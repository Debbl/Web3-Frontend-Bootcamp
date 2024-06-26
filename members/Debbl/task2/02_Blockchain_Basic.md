# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可



## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！



## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [ ] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [x] 多个私钥对应多个地址

 ## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266
      
## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
区块链的网络结构是一种去中心化的对等网络（P2P网络），每个节点都保存着一份完整的区块链数据。网络中的节点通过共识算法（如PoW, PoS等）来验证和记录交易，确保数据的一致性和安全性。每个区块包含若干条交易信息，并通过加密技术链接到前一个区块，形成一个不可篡改的链式结构。这样的结构确保了数据的透明性、不可篡改性和高容错性。
```



## [简答题] 智能合约是什么，有何作用？

```
智能合约是一种运行在区块链上的自执行代码，其执行结果由区块链网络上的共识机制保证。智能合约可以自动执行预设的条款和条件，无需第三方中介。其作用包括：自动化交易过程、提高效率、降低成本、增强透明度和安全性。例如，在以太坊区块链上，智能合约被广泛应用于去中心化金融（DeFi）应用中，实现贷款、交易、保险等金融服务。
```



## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM（以太坊虚拟机）是以太坊的核心组件，它提供了在以太坊区块链上执行智能合约的运行环境。EVM是一个图灵完备的虚拟机，可以执行任何计算任务。它将智能合约编译成字节码并在以太坊节点上运行。EVM的设计确保了所有节点能够在相同的输入下获得相同的输出，保证了智能合约执行的确定性和一致性。
```



## [分析题] 你对去中心化的理解

```
去中心化是指在系统中没有单一的控制中心，所有节点都具有平等的权利和义务。去中心化的系统通过共识机制和分布式账本技术来保证数据的一致性和安全性。它的优势包括提高系统的抗审查能力和容错性，减少对中介的依赖，提高透明度和信任度。以区块链为例，去中心化确保了交易的公开透明、不可篡改，同时避免了单点故障和中心化机构的控制。然而，去中心化也面临着如扩展性、效率和监管等方面的挑战。
```



## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链与传统数据库在结构、功能和应用上存在显著差异。

1. **数据结构**：区块链是一个分布式账本，由一系列按时间顺序连接的区块组成，每个区块包含若干条交易记录。传统数据库通常是集中式的，数据存储在表格和记录中，通过关系或非关系模型进行组织。

2. **去中心化 vs. 中心化**：区块链是去中心化的，数据分布在网络中的所有节点上，每个节点都有一份完整的账本。传统数据库通常是中心化的，由单一机构控制和管理数据。

3. **不可篡改性**：区块链上的数据一旦记录，几乎不可能被篡改或删除，确保了数据的完整性和透明性。传统数据库的数据可以被修改或删除，需要依赖访问控制和审计机制来确保数据的安全性。

4. **共识机制**：区块链依赖于共识机制（如PoW, PoS）来验证和记录交易，确保数据的一致性。传统数据库使用事务处理和锁机制来确保数据的一致性。

5. **性能**：区块链的性能通常较低，交易处理速度和吞吐量受到共识机制的限制。传统数据库的性能较高，可以处理大量的并发请求和复杂查询。

6. **应用场景**：区块链适用于需要高信任、高透明度和防篡改的应用场景，如加密货币、智能合约、供应链管理等。传统数据库广泛应用于各类信息系统，如企业管理、电子商务、社交网络等。

总的来说，区块链和传统数据库各有优劣，具体选择应根据应用需求和场景来决定。
```



## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.
