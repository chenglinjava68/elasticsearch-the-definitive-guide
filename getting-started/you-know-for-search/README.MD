
你知道的，为了搜索
===============

* [安装Elasticsearch](installing-elasticsearch.md)
* [运行Elasticsearch](running-elasticsearch.md)
* [和Elasticsearch交流](talking-to-elasticsearch.md)
* [面向文档](document-oriented.md)
* [找找感觉](finding-your-feet.md)
* [索引员工文档](indexing-employee-documents.md)
* [检索一个文档](retrieving-a-document.md)
* [搜索精简版](search-lite.md)
* [使用查询DSL搜索](search-with-query-dsl.md)
* [复杂搜索](more-complicated-searches.md)
* [全文搜索](full-text-search.md)
* [短语搜索](phrase-search.md)
* [高亮搜索](highlighting-our-searches.md)
* [分析](analytics.md)
* [教程结论](tutorial-conclusion.md)
* [分布式特性](distributed-nature.md)
* [接下来](next-steps.md)

Elasticsearch是一个构建于全文搜索引擎库[Apache Lucene™](https://lucene.apache.org/core/)之上的开源搜索引擎。Lucene开源，且拥有专利，甚至可以说，它是当下最先进、高效、功能齐全的搜索引擎库。

但是，Lucene仅仅是一个库，要领略它的魅力，你需要使用Java，将它集成到到你的程序。更坏的是，你可能需要对它的检索机制有深入的了解。总之，它是很复杂的。

Elasticsearch使用java语言编写，索引和检索完全基于Lucene，目标在于通过简单、通用、REST化的接口，隐藏Lucene的高深莫测，让全文搜索变得简单。

但是，Elasticsearch不仅仅是Lucene，也不仅仅是全文搜索，它同时可以被描述成这样的：

* 分布式实时文档存储，所有字段可被索引和搜索。
* 带有实时分析功能的分布式搜索引擎。
* 极强伸缩性，轻松应对数以百计服务器，以及pb级别的数据（无论结构化或非结构化）

Elasticsearch把这些功能集中到单独的一台服务器，你的程序可以使用你最喜欢的语言、甚至命令行，通过简单的RESTfule接口和它进行交互。

开始Elasticsearch是很简单的事情，它的默认配置已经足够智能化，确保新手们可以远离那些复杂的搜索理论。你只需要掌握很少的一部分知识，就可以马上将其投入到实践中去。

Elasticsearch基于[Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0.html)（最灵活的开源许可之一），你可以免费地下载、使用和修改。

Elasticsearch是灵活可配置的，随着对Elasticsearch的不断了解，你可以掌握它更高级的功能，从里边挑选合适的解决掉你遇到问题的领域。

> 时间迷雾
  ------------------------

>  很多年以前，一个名叫Shay Banon的待业工程师，跟随新婚不久的妻子到了伦敦。妻子正在学习厨师，他边找工作，边着手帮妻子开发一款便捷的菜谱搜索引擎，便开始接触早期版本的Lucene。
  
> 直接使用Lucene是很棘手的事情，所以Shay开始抽象出一个层，使得java程序能更加简单地使用搜索引擎，他把这个项目开源了，取名Compass。
  
> 后来，Shay找到了一份构建高性能、分布式内存数据网格的工作，很明显，这需要一个高性能、实时、分布式的搜索引擎，于是乎，他决定重写Compass库，将其改造成一个独立的服务器，取名Elasticsearch。
  
> 2010年2月，Elasticsearch的第1个版本发布。之后，它成为Github上最受欢迎的项目之一，拥有300多名贡献者。一家公司想让Elasticsearch提供商业授权开发新功能，但是Elasticsearch现在、而且永远都将开放给所有人使用。
  
> Shay的妻子还在等着他的菜谱搜索引擎...


-------------------

[« 入门](../../getting-started/README.MD)   [安装Elasticsearch »](installing-elasticsearch.md)
