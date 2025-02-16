---
title: 可扩展性
status: Completed
category: 属性
---

可扩展性指的是一个系统能有多大的发展。这就是增加做任何系统应该做的事情的能力。 例如，[Kubernetes](/zh-cn/kubernetes/) [集群](/zh-cn/cluster/) 通过增加或减少 [容器化](/zh-cn/containerization/) 应用程序的数量来进行扩展，但这种可扩展性取决于几个因素。 它有多少[节点](/nodes/)，每个节点可以处理多少个[容器](/zh-cn/container/)，控制平面可以支持多少条记录和操作？

可扩展的系统使添加更多容量更容易。 主要有两种缩放方法。 一方面，有 [水平扩展](/horizontal-scaling/) 添加更多节点来处理增加的负载。 相比之下，在 [垂直扩展](/vertical-scaling/) 中，单个节点的功能更强大，可以执行更多事务（例如，通过向单个机器添加更多内存或 CPU）。 可扩展的系统能够轻松更改并满足用户需求。
