## 鸡腿保卫战-EOS概念入门文章

---

### **百科登场**

简介

> *EOS，可以理解为Enterprise Operation System，即为商用分布式应用设计的一款区块链操作系统。EOS是引入的一种新的区块链架构，旨在实现分布式应用的性能扩展。注意，它并不是像比特币和以太坊那样的货币，而是基于EOS软件项目之上发布的代币，被称为区块链3.0。*

特点

>*1. EOS有点类似于微软的windows平台，通过创建一个对开发者友好的区块链底层平台，支持多个应用同时运行，为开发dAPP提供底层的模板。*

>*2. EOS通过并行链和DPOS的方式解决了延迟和数据吞吐量的难题，EOS是每秒可以上千级别的处理量，而比特币每秒7笔左右，以太坊是每秒30-40笔；*

>*3. EOS是没有手续费的，普通受众群体更广泛。EOS上开发dApp，需要用到的网络和计算资源是按照开发者拥有的EOS的比例分配的。当你拥有了EOS的话，就相当于拥有了计算机资源，随着DAPP的开发，你可以将手里的EOS租赁给别人使用，单从这一点来说EOS也具有广泛的价值。简单来说，就是你拥有了EOS，就相当于拥有了一套房租给别人收房租，或者说拥有了一块地租给别人建房。*

---

### **EOS中文社区的wiki列表(有点老了，但啃起来还是香)**

<li><a class="page" href="/wiki/api-serializer">EOSFans API 数据类型</a></li>
<li><a class="page" href="/wiki/api-index">EOSFans API 目录</a></li>
<li><a class="page" href="/wiki/api">EOSFans API 快速开始</a></li>
<li><a class="page" href="/wiki/index">EOS技术开发资料汇总</a></li>
<li><a class="page" href="/wiki/development-tools">EOS效率工具</a></li>
<li><a class="page" href="/wiki/eos-releases">EOS版本计划</a></li>
<li><a class="page" href="/wiki/tutorials">EOS开发新手教程</a></li>
<li><a class="page" href="/wiki/glossary">EOS词汇表</a></li>
<li><a class="page" href="/wiki/hello-word-contracts">EOS Hello Word 智能合约</a></li>
<li><a class="page" href="/wiki/eosio-token-contract">Eosio.token，Exchange和Eosio.msig合约</a></li>
<li><a class="page" href="/wiki/introduction-to-eosio-smart-contract">EOS智能合约入门</a></li>
<li><a class="page" href="/wiki/smart-contracts">EOS智能合约</a></li>
<li><a class="page" href="/wiki/persistence-api">EOS持久化API</a></li>
<li><a class="page" href="/wiki/cli-wallet">EOS命令行钱包</a></li>
<li><a class="page" href="/wiki/programs-tools">程序和工具</a></li>
<li><a class="page" href="/wiki/local-environment">设置本地环境</a></li>
<li><a class="page" href="/wiki/account-permission">EOS账户权限</a></li>
<li><a class="page" href="/wiki/cleos-command-reference">Cleos命令使用指南</a></li>
<li><a class="page" href="/wiki/eosiodb">EOSIO 3.0 数据库使用指南</a></li>
<li><a class="page" href="/wiki/contributors">EOS中文社区贡献者名单</a></li>
<li><a class="page" href="/wiki/eos-party-testnet">EOS Party 测试网络</a></li>
<li><a class="page" href="/wiki/eos3-smart-contract">EOS3.0-智能合约</a></li>
<li><a class="page" href="/wiki/emergency">应急方案</a></li>
<li><a class="page" href="/wiki/contact">联系我们</a></li>
<li><a class="page" href="/wiki/about">关于我们</a></li>

---

### **EOS系列导航**
<p><a href="https://github.com/EOSIO/eos">Github</a>    <a href="https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md">白皮书</a>    <a href="https://github.com/EOSIO/eos/releases">版本列表</a></p>
<p><span id="more-2"></span></p>
<p><strong>#开发文档</strong></p>
<p><a href="https://developers.eos.io/">EOS Developer</a>    <a href="https://github.com/superoneio/awesome-eos">Awesome-EOS</a>    <a href="https://developers.eos.io/eosio-nodeos/reference">HTTP API</a>    <a href="https://github.com/slowmist/eos-smart-contract-security-best-practices">慢雾安全指南</a></p>
<p><!--more--></p>
<p><strong>#测试网</strong></p>
<p><a href="http://blog.eosdata.io/index.php/2018/11/05/jungle-eos-testnet/">Jungle 测试网</a>    <a href="http://blog.eosdata.io/index.php/2018/09/25/cryptokylin-eos-testnet/">麒麟测试网</a>    <a href="http://blog.eosdata.io/index.php/2020/01/17/eosio-guan-fang-testnet/">官方Testnet</a></p>
<p><!--more--></p>
<p><strong>#环境配置</strong></p>
<p><a href="https://github.com/eoshackathon/eos_dapp_development_cn">开发配置（中文）</a>    <a href="https://dev4eos.com/#/">部署工具Dev4eos</a>    <a href="https://beosin.com/EOS-IDE/index.html#/">部署工具Beosin</a>    <a href="http://app.eosstudio.io/">部署工具EOSstudio</a>    <a href="https://validate.eosnation.io/mainnet/reports/endpoints.html">RPC Endpoint</a></p>
<p><!--more--></p>
<p><strong>#Scatter 接口开发</strong></p>
<p><a href="https://github.com/MediShares/scatter-eos-sample">ScatterSample</a>    <a href="https://github.com/eoshackathon/eos_dapp_development_cn/blob/master/docs/eosjs_manual.md">eosjs 说明文档</a>    <a href="https://www.youtube.com/playlist?list=PLyM_BB-jMJPrj79ykPNQPgJ5kinwLi8W_">EOS应用开发视频教程</a></p>
<p><!--more--></p>
<p><strong>#ÐApps 排行</strong></p>
<p><a href="https://dapp.review/explore/eos">DAppReview</a>    <a href="https://dappradar.com/eos-dapps">DAppRadar</a>    <a href="https://www.spider.store/">SpiderStore</a></p>
<p><!--more--></p>
<p><strong>#区块浏览器</strong></p>
<p><a href="http://eosflare.io">EOS Flare</a>    <a href="https://www.myeoskit.com/">MyEOSKit</a>    <a href="https://eospark.com/">EOSPark</a>    <a href="https://www.bloks.io/">Bloks</a></p>
<p><!--more--></p>
<p><strong>#开发社区</strong></p>
<p><a href="https://steemit.com/trending/eosdev">Steem EOS频道</a>    <a href="http://blog.eosdata.io/index.php/xiaomq/">EOS开发微信群</a>    <a href="https://eoshackathon.io/">EOSHackathon</a>   <a href="https://eosio.stackexchange.com/">Stack Exchange</a></p>
<p><!--more--></p>
<p><strong>#侧链</strong></p>
<p><a href="https://www.eosforce.io/">EOS原力</a>    <a href="https://boscore.io/">BOS</a>    <a href="https://enumivo.org/">ENU</a>    <a href="https://telosfoundation.io/">Telos</a>    <a href="https://worbli.io/">Worbli</a>    <a href="https://meet.one">MEETONE</a></p>
<p><!--more--></p>
<p>#其它相关网站</p>
<p><a href="https://eos.io/">EOS.io</a>   <a href="https://medium.com/eosio">EOS Blog</a>    <a href="http://block.one/">BlockONE</a>    <a href="https://ecaf.io/">ECAF</a></p>
<p><a href="https://steemit.com/@dan">Dan@Steem</a>    <a href="https://medium.com/@bytemaster">Dan@Medium</a>    <a href="https://github.com/bytemaster">ByteMaster</a>    <a href="https://www.reddit.com/r/eos/">Reddit</a></p>
	</div>