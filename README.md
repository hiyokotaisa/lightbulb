# Ansible Lightbulb

Ansible Lightbulbプロジェクトは、Ansibleの教育およびコミュニケーションにおいて、効率的なツールキットおよびリファレンスを提供することを目的としています。

Lightbulbは、Linuxサーバーの自動化に特化したAnsibleのトレーニングプログラムとして、AnsibleがRed Hatファミリーに参加する前に誕生しました。

現在では、Ansibleのデモンストレーションや多種多様な非公式トレーニング(インストラクターによる指導、ハンズオン、自己学習)向けの多目的なツールキットとして生まれ変わっています。

Lightbulbは、従来のLinuxサーバーの自動化だけに留まらず、Windowsやネットワークの自動化も含めた発展的で開発者向けのトピックも扱います。

これらの目的を達成するために、本プロジェクトではLightbulbのコンテンツを実行する環境構築のためのlab provisioner toolを提供しています。

## 提供されるもの

Ansible Lightbulbプロジェクトは、Ansibleの自己学習やハンズオンでのデモまで、Ansibleのプレゼンテーション向けにツールキットとベストプラクティスを提供します。

* Examples
* Workshops
* Presentation Decks
* Lab Provisioner
* Facilitator Guide

### Examples

`examples/` に含まれるコンテンツは、Lightbulbの中心となるものです。代表的な機能および使用例のデモンストレーションを行う完結したAnsible Playbooksです。

これらはAnsibleの動作を説明、理解する教育向けのリファレンスとして非常に優れており、明解、集中的で一貫したベストプラクティスです。

このコンテンツはAnsibleでの自動化の概要説明やデモの有用なソースとなります。いくつかの例はワークショップへのソリューションを提供します。

### Workshops

`workshops/` に含まれるコンテンツは、Markdownドキュメントと、どのようにAnsibleでの自動化するかを学ぶハンズオンに使うことができるリソースです。 

インストラクターのノートと全ワークショップのソリューションは、`facilitator/solutions/`にあります。

## Presentation Decks

The content of `decks/` are collection of presentation decks using the [reveal.js framework](http://lab.hakim.se/reveal-js/) for delivering instructor-led or hands-on instruction.

## Lab Provisioner

Lightbulb provides a lab provisioner utility for creating a personal lab environment for each student. Currently only Amazon Web Services (AWS) is supported in us-east-1 and us-west-1 with the foundation to support other regions in place.

**Coming Soon.** Vagrant support for self-paced learning is planned. Legacy support from the previous generation of Lightbulb remains, but is in need of an overhaul.

## Facilitator Guide

`facilitator/` includes documentation on recommended ways Lightbulb content can be assembled and used for a wide range of purposes and scenarios.

If you are planning on using Lightbulb for some sort of informal training on automating with Ansible [this documentation](facilitator/README.md) should be your next stop.

### Requirements

True to its philosophy and The Ansible Way, Lightbulb has been developed so that using Lightbulb is as simple and low-overhead as possible. Requirements depend on the format and delivery of the Lightbulb content.

* Modern HTML5 Standard Compliant Web Browser
* A recent stable version of Python 2.7 and the latest stable version of the boto libraries.
* The latest stable versions of Ansible.
* A SSH client such as PuTTY or Mac OSX Terminal.
* An AWS account or local Vagrant setup.

### Assumed Knowledge

For hands-on or self-paced training, students should have working knowledge of using SSH and command line shell (BASH). The ability to SSH from their personal laptop to a lab environment hosted in a public cloud can also be required based on the format and presentation of the context.

For demos and instructor-led exercises, conceptual understanding of linux system admin, DevOps and distributed application architecture is all that is required.

### Reference

* [Ansible Documentation](http://docs.ansible.com)
* [Ansible Best Practices: The Essentials](https://www.ansible.com/blog/ansible-best-practices-essentials)

### License

Red Hat, the Shadowman logo, Ansible, and Ansible Tower are trademarks or registered trademarks of Red Hat, Inc. or its subsidiaries in the United States and other countries.

All other parts of Ansible Lightbulb are made available under the terms of the [MIT License](LICENSE).
