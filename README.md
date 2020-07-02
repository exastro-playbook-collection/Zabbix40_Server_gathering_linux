# Zabbix パラメータ生成Role

# Trademarks
-----------
* Linuxは、Linus Torvalds氏の米国およびその他の国における登録商標または商標です。
* RedHat、RHEL、CentOSは、Red Hat, Inc.の米国およびその他の国における登録商標または商標です。
* Windows、PowerShellは、Microsoft Corporation の米国およびその他の国における登録商標または商標です。
* Ansibleは、Red Hat, Inc.の米国およびその他の国における登録商標または商標です。
* pythonは、Python Software Foundationの登録商標または商標です。
* Zabbixは、ラトビア共和国にあるZabbix LLCの商標です。
* Oracleは、Oracle International Corporation の米国およびその他の国における登録商標または商標です。
* NECは、日本電気株式会社の登録商標または商標です。
* その他、本ロールのコード、ファイルに記載されている会社名および製品名は、各社の登録商標または商標です。

## Description
本Roleは、Zabbix構築済の実環境（サーバ）からソフトウェアの動作に必要となる設定情報を収集し、収集データからAnsible Playbookへ投入するパラメータ値（extra_vars）を生成します。

現在対象となる、ZabbixのRoleは以下となります。
* Zabbix v4.0
  * Zabbix Agent Windows版
  * Zabbix Agent Linux版
  * Zabbix Server Linux版

詳細は、各ディレクトリのREADME_role.mdを参照ください。

# Copyright
Copyright (c) 2019 NEC Corporation

# Author Information
NEC Corporation
