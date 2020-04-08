# README 文档标准

在 UKUI 各项目开发的早期阶段，各个项目的 README 文档描述的内容或有或无，各有不同。部分项目缺失了一些至关重要的内容影响了新参与者的贡献与使用，所以我们决定有一个 README 文档规范，约束项目的 README。README 文件通常是 UKUI 项目的第一个入口点。它应该告诉访问者关于该项目的简介、如何安装以及如何使用。 标准化编写 README 文件的方式可使创建和 README 自述文件更加容易。 

UKUI README 标准将通过使本文符合 UKUI README 文档标准，用以介绍 README 规范的详细指导。

## Table of Contents

   * [README 文档标准](#readme-文档标准)
      * [项目背景](#项目背景)
      * [开始 (Getting Strated)](#开始-getting-strated)
      * [文档说明 (Document / Introduction)](#文档说明-document--introduction)
      * [贡献指南 （可选）](#贡献指南-可选)
      * [已知问题（可选）](#已知问题可选)
      * [Q&amp;A （可选）](#qa-可选)
      * [TODO list (可选)](#todo-list-可选)


## 项目背景

在 README 的开始部分，UKUI 项目应该介绍本项目的产生背景，预期的目标，实现的功能和主要的应用场景。正如本文内容一样，它应该位于一级标题  `# TITLE` 之后，位于 `TOC 目录` 之前。

## 开始 (Getting Strated)

在 `TOC` 之后，README 文档正文内容的开始应当是从 __Getting Started__ 开始，在这一部分提供项目构建与安装的快速指导。例如：

```bash
# Install something
apt install example-project
make install

# Run some build scripts
./autogen.sh
mkdir bulid & cd build
cmake ../
```

## 文档说明 (Document / Introduction)

在简短的安装与构建指导之后，应当提供一个必要的细节描述文档，需要对构建所需的必要依赖和项目的可选配置及设置进行详细的说明。

```markdown
## 说明

一些描述。

### 依赖

本项目依赖于一些必要的依赖，它们是：

* 依赖 1
* 依赖 2

在激活一些可选功能后，需要安装对应的依赖，它们有：

* 依赖 3 (可选，a 功能所需)
* 依赖 4 (可选，b 功能所需)

### 如何使 A 开启 B 支持

一些描述
```

## 贡献指南 （可选）

如果您作为 UKUI 的项目维护者，您可能想要其他参与者的贡献满足一些要求后再添加到项目之中。比如 Pull Request 需要通过 CI，Issue 需要按照指定模板， 代码需要遵循哪些规范等等。此时您需要编写一个贡献指南章节用以指导这部分行为，如果内容较长，应当抽离本节内容至 `CONTRIBUTING.md `。

## 已知问题（可选）

如果该项目具有一些影响较大，但尚未解决或需要用户手动修复的问题，编写已知问题小节是必要的。

## Q&A （可选）

如果该项目具有一些新的参与者经常寻求帮助或是维护者经常在 Issue 中解释的问题或是设计思路，通常可以编写适当的 Q&A 内容来节约您的精力。

## TODO list (可选)

如果作为项目的维护者，您有一些想要其他参与者获悉的 TODO 任务，或是想要分享项目的开发计划，可以利用 Markdown 支持的 checkbox 来编写一个 TODO list。例如：

* [ ] 计划完成任务 1
* [ ] 计划完成任务 2
* [ ] ~~计划完成任务 3~~
* [x] 计划完成任务 4

