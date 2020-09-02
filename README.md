你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
[![Travis](https://travis-ci.org/elastic/beats.svg?branch=master)](https://travis-ci.org/elastic/beats)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/p7y92i6pp2v7vnrd/branch/master?svg=true)](https://ci.appveyor.com/project/elastic-beats/beats/branch/master)
[![GoReportCard](http://goreportcard.com/badge/elastic/beats)](http://goreportcard.com/report/elastic/beats)
[![codecov.io](https://codecov.io/github/elastic/beats/coverage.svg?branch=master)](https://codecov.io/github/elastic/beats?branch=master)

# Beats - Lightweight shippers for Elasticsearch & Logstash

The [Beats](https://www.elastic.co/products/beats) are lightweight processes,
written in Go, that you install on your servers to capture all sorts of
operational data like logs, operating system metrics or network packet data,
and to send it to Elasticsearch, either directly or via Logstash, so it can be
visualized with Kibana.

This repository contains libbeat and all the officially supported Beats, in the
following folders:

Folder  | Description
--- | ---
[libbeat](https://github.com/elastic/beats/tree/master/libbeat) | The Go framework for creating new Beats
[Packetbeat](https://github.com/elastic/beats/tree/master/packetbeat) | Tap into your wire data
[Filebeat](https://github.com/elastic/beats/tree/master/filebeat) | Lightweight log forwarder to Logstash & Elasticsearch
[Winlogbeat](https://github.com/elastic/beats/tree/master/winlogbeat) | Sends Windows Event logs

In addition to the above Beats, which are officially supported by
[Elastic](elastic.co), the
community has created a set of other Beats that make use of libbeat but live
outside of this Github repository. We maintain a list of community Beats
[here](https://www.elastic.co/guide/en/beats/libbeat/master/community-beats.html).

## Documentation and Getting Help

You can find the documentation on the [elastic.co
site](https://www.elastic.co/guide/en/beats/libbeat/current/index.html). If you
need help, you can open a topic on our [discuss
forums](https://discuss.elastic.co/c/beats).

## Contributing

We'd love working with you! You can help making the Beats better in many ways:
report issues, help us reproduce issues, fix bugs, add functionality, or even
create your own Beat.

Please start by reading our [CONTRIBUTING](CONTRIBUTING.md) file.

If you are creating a new Beat, you don't need to submit the code to this
repository. You can simply start working in a new repository and make use of
the libbeat packages, by following our [developer
guide](https://www.elastic.co/guide/en/beats/libbeat/current/new-beat.html).
After you have a working prototype, open a pull request to add your Beat to the
list of [community
Beats](https://github.com/elastic/beats/blob/master/libbeat/docs/communitybeats.asciidoc).

## Building Beats from the Source

See our [CONTRIBUTING](CONTRIBUTING.md) file for information about setting up your dev
environment to build Beats from the source.
