# TOPPERS Contributed Software (GitHub版)

本ページは、[TOPPERSプロジェクト](https://toppers.jp/)から公式リリースされているもの以外で、TOPPERSプロジェクトに関するオープンソースソフトウェアを共有するためのものです。   

本ページにソフトウェアを登録することで、会員の開発成果物をひろくアピールすることができます。  
特にGitHubで管理されている成果物がありましたら、ぜひ登録をご検討ください。  
[Trac/SVN版はこちらのページ](https://dev.toppers.jp/trac_user/contrib)をご参照ください。

ソフトウェアの登録は、TOPPERSプロジェクトの会員のみが可能です。

## ソフトウェア一覧

|略称・リンク|開発者（ハンドルネーム可）|概要|備考|
|:--|:--|:--|:--|
| [asp3_in_zig](https://github.com/toppers/asp3_in_zig) | hiroakitakada | TOPPERS/ASP3 Kernel written in Zig Programming Language |   |
| [asp3_wo_tecs](https://github.com/ertlnagoya/asp3_wo_tecs) | HONDA | TOPPERS/ASP3カーネルを，TECSなしで使えるように変更したもの |  |
| [mROS](https://github.com/tlk-emb/mROS) | 京都大学 高木研究室 | 組込みデバイス向けROS 1ノード軽量実行環境 | [asp-gr_peach_gcc-mbed](https://github.com/ncesnagoya/asp-gr_peach_gcc-mbed)を利用 |
<!--下記をコピペして追加してください
|略称・リンク|開発者（ハンドルネーム可）|概要|備考|
-->

## 利用上の注意

- ソフトウェアの登録について
  - 登録できるソフトウェアは、TOPPERSプロジェクトの会員以外の方にも配布可能な、**オープンソースソフトウェア**のみとさせていただきます。
  - ソフトウェアの登録は、TOPPERSプロジェクトの会員のみが可能となっております。
  - **登録するソフトウェアには、利用条件を明記してください。**
  - 利用条件がTOPPERSライセンスでないソフトウェアも登録可能です。
  - ソフトウェア／リポジトリの管理者が明確であれば、GitHub以外で管理されているものでも登録できます。
  - Tracによるチケット管理システムやSVNによるバージョン管理を利用したい場合は、[こちらのページ](https://dev.toppers.jp/trac_user/contrib)をご利用ください。

- ソフトウェアの利用について
  - **各ソフトウェアの利用条件を遵守し、開発者の著作権を侵害しないようにご注意ください。**
  
- TOPPERS Contributed Software (GitHub版)の運用方針についての質問や全般的な提案がある場合は、[本リポジトリIssueのinquiryテンプレート](https://github.com/toppers/contrib/issues/new?template=inquiry.md)にてお知らせください。

## ソフトウェア・リポジトリの登録方法

### 「ソフトウェア一覧」に自身の管理リポジトリを追加したい

リポジトリの管理権限を保持したまま、ソフトウェアの管理リポジトリを一覧に追加する場合です。

本リポジトリをForkし、このファイル（README.md）の「`## ソフトウェア一覧`」の表を編集してください。  
その後、Pull Requestを作成し、下記の情報をお知らせください。

- 略称
- リポジトリのURL
- リポジトリの管理者（および組織）
- TOPPERSの会員区分
- リポジトリ・ソフトウェアの説明
- 補足事項・連絡事項

問題ないと判断しましたら、該当するPull RequestをMergeし、ソフトウェア一覧に追加されます。

### TOPPERSのGitHub Organizationに移譲したい

[TOPPERSプロジェクトのGitHub Organization](https://github.com/toppers)を取得・運用しています。このOrganizationに[リポジトリを移譲したい](https://docs.github.com/ja/github/administering-a-repository/transferring-a-repository)場合を想定しています。

移譲を希望される場合は、[本リポジトリIssueのorganization_requestテンプレート](https://github.com/toppers/contrib/issues/new?template=organization_request.md)にて、下記の情報をお知らせください。

- 略称
- リポジトリのURL
- リポジトリの管理者（および組織）
- TOPPERSの会員区分
- リポジトリ・ソフトウェアの説明
- 補足事項・連絡事項

問題ないと判断しましたら、Issueを作成されたアカウントをOrganizationのメンバに招待します。その後、リポジトリを移譲いただき、本ファイルの「ソフトウェア一覧」を編集してください。
