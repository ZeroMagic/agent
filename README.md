我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

[![Build Status](https://travis-ci.org/kata-containers/agent.svg?branch=master)](https://travis-ci.org/kata-containers/agent)
[![codecov](https://codecov.io/gh/kata-containers/agent/branch/master/graph/badge.svg)](https://codecov.io/gh/kata-containers/agent)

# Kata Containers Agent

* [Debug mode](#debug-mode)
* [Developer mode](#developer-mode)
* [Enable trace support](#enable-trace-support)

This project implements an agent called `kata-agent` that runs inside a virtual machine (VM).

The agent manages container processes inside the VM, on behalf of the
[runtime](https://github.com/kata-containers/runtime) running on the host.

## Debug mode

To enable agent debug output, add the `agent.log=debug` option to the guest kernel command line.

See the [developer guide](https://github.com/kata-containers/documentation/blob/master/Developer-Guide.md#enable-full-debug) for further details.

## Developer mode

Add `agent.devmode` to the guest kernel command line to allow the agent
process to coredump (disabled by default). Specifying this option implicitly
enables [debug mode](#debug-mode).

## Enable trace support

See [the tracing guide](TRACING.md).
