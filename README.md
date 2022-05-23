# EOS 源码分析

区块链的概念首次在2008年末由中本聪（Satoshi Nakamoto）在比特币论文《Bitcoin： A Peer-to-Peer Eletronic Cash Sytem》中提出，论文中区块链技术是构建比特币数据结构与交易信息加密传输的基础技术，该技术实现了比特币的挖矿与交易。  

随着电子货币的概念被更多的人所接受，其背后的区块链技术也进一步被更多的技术人员和商业人员充分发掘，他们认为区块链技术在很多领域中都将有广泛的应用，这种去中心化的可信网络将重构现有的商业逻辑。

但是完整的开发和部署一套去中心化的区块链网络并不是一件容易的事情，这需要投入巨大的研发精力和经费。于是有很多团队开始尝试开发一套底层区块链系统，从而能够方便更多的应用开发者在其基础上构建分布式应用。大家比较熟悉的以太坊正是这样一套区块链公链系统。但这些系统也有自身的问题，例如性能太低，确认延迟太长，需要用户付费等。  

为了能够解决这些问题，Block.One 公司启动了EOS项目，这是一套基于区块链底层的公链系统，简单的说就是一套去中心化的操作系统，当EOS完成系统目标之后，任何团队都可以在EOS 上以比较快的速度开发出所需要的Dapp（基于区块链的分布式应用），这些应用可以让普通人无需任何手续费就可以方便的使用，而EOS的高性能（100w+tps，可以在一秒之内进行100W次打包记账）也可以承载数量众多的Dapp应用，相信今后在此系统上将会诞生很多独角兽级别的分布式应用。  

为了能够在此系统上建构高效的分布式应用，对于EOS系统的深入理解和分析必不可少，而源码的阅读是深入理解EOS系统最有效的方式，本书就是从源码入手来分析EOS背后的概念和机制，从而让大家对于区块链技术有一个更加深入的了解。书中主要会涉及以下内容：

1.  对白皮书的解读。EOS白皮书有中文版，但很多地方的翻译非常晦涩，完全不通顺，我根据自己对项目的理解进行了重新解读  
2.  EOS 中涉及到的一些区块链概念，在文中也给出了详细介绍
3.  对于某些概念的现实意义，给出了自己的理解。从源码级别理解项目固然重要，但更重要的是对区块链本身的认知升级，不断的探索这些概念在现实世界中的使用场景，这才能更大程度的推进区块链的发展。
4.  源码阅读；源码之下，了无密码。做技术的人往往更喜欢从源码级了解一个项目，这使得很多概念能够对应到底层的算法，对于理解这些概念将会很有帮助。理解了源码层，才能够说真正理解了一个项目，你不仅知道他能干什么，更能知道他为什么能够这么用，并且能够深刻的理解它下一步的演进方向。


目前EOS还处于开发阶段，源代码还在不断的迭代中，但整体流程和框架已经基本成型，目前已经发布到Dawn3.0 版本了，本书也会根据系统的迭代不断进行完善，欢迎对EOS 项目感兴趣的朋友一起交流。

微信：

