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

`decks/` に含まれるコンテンツは[reveal.js framework](http://lab.hakim.se/reveal-js/) を使用した、インストラクターおよびハンズオン向けのスライド集です。

## Lab Provisioner

Lightbulbは、個人的なラボ環境の構築のためにlab provisioner utilityを提供しています。現在はAmazon Web Services (AWS)のus-east-1 と us-west-1 リージョンのみをサポートしています。

**【まもなく提供予定】** 自己学習用途向けにVagrantのサポートが計画中です。以前のバージョンのLightbulbに対してもレガシーなサポートは継続しますが、大規模改修が必要です。 

## Facilitator Guide

`facilitator/` には、さまざまな種類のシナリオや目的で構成された推奨ドキュメントが格納されています。

もしLightbulbをAnsibleの非公式なトレーニングなどで使用しようとしているのであれば、 [このドキュメント](facilitator/README.md) を次に読むことを推奨します。

### 必須要件

Ansible Wayとその哲学に基づき、Lightbulbは可能な限りシンプルでオーバーヘッドがないように開発されています。要件はLightbulbのコンテンツとフォーマットによって異なります。

* HTML5標準互換なモダンWebブラウザ
* 最新安定版のPython 2.7と、最新安定版のboto libraries
* 最新安定版のAnsible
* PuTTY や Mac OSX TerminalなどのSSHクライアント
* AWSアカウントもしくはローカルなVagrant環境

### Assumed Knowledge

For hands-on or self-paced training, students should have working knowledge of using SSH and command line shell (BASH). The ability to SSH from their personal laptop to a lab environment hosted in a public cloud can also be required based on the format and presentation of the context.

For demos and instructor-led exercises, conceptual understanding of linux system admin, DevOps and distributed application architecture is all that is required.

### Reference

* [Ansible Documentation](http://docs.ansible.com)
* [Ansible Best Practices: The Essentials](https://www.ansible.com/blog/ansible-best-practices-essentials)

### License

Red Hat, the Shadowman logo, Ansible, and Ansible Tower are trademarks or registered trademarks of Red Hat, Inc. or its subsidiaries in the United States and other countries.

All other parts of Ansible Lightbulb are made available under the terms of the [MIT License](LICENSE).
