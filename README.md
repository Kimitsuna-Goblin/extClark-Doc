# 小児薬用量計算ツール（拡張Clark式）関連ドキュメント

[小児薬用量計算ツール（拡張Clark式）](https://github.com/Kimitsuna-Goblin/extClark/) に関する公開ドキュメント類です。
<BR>
This repository contanints published documents about the [extClark](https://github.com/Kimitsuna-Goblin/extClark/) tool.

## 説明 - Description

ここでは、[小児薬用量計算ツール（拡張Clark式）](https://github.com/Kimitsuna-Goblin/extClark/) のドキュメント(仕様書、解決済み不具合一覧等)を公開しています。
<BR>
Here documents (specification, fixed bugs list and etc.) about the [extClark](https://github.com/Kimitsuna-Goblin/extClark/) tool are published.
<BR>
<BR>
[ツール本体のリポジトリ](https://github.com/Kimitsuna-Goblin/extClark/)と異なる、[ドキュメント専用のリポジトリ](https://github.com/Kimitsuna-Goblin/extClark-Doc/)を作成している理由は、ソースとドキュメントのライセンス管理を分けることで、
ドキュメントの品質を保ち、なおかつソースコードの改変をより柔軟にできるようにするためです。
<BR>
The reason why the [repository for the documents](https://github.com/Kimitsuna-Goblin/extClark-Doc/) is separated from the [main repository](https://github.com/Kimitsuna-Goblin/extClark/) of the tool
is to separate the licenses for the sources and for the documents in order to keep qualities of the documents and to make more flexible to update sources.

## 内容構成 - Contents

### マニュアル - Manual

マニュアル置き場です。
<BR>
The directory for the manuals.

### 仕様書 - Specification

[外部設計書](https://github.com/Kimitsuna-Goblin/extClark-Doc/blob/master/%E4%BB%95%E6%A7%98%E6%9B%B8/%E5%B0%8F%E5%85%90%E8%96%AC%E7%94%A8%E9%87%8F%E8%A8%88%E7%AE%97%E3%83%84%E3%83%BC%E3%83%AB(%E6%8B%A1%E5%BC%B5Clark%E5%BC%8F)_%E5%A4%96%E9%83%A8%E8%A8%AD%E8%A8%88%E6%9B%B8.pdf)等の置き場です。
<BR>
The directory for publiched documents like the [specification](https://github.com/Kimitsuna-Goblin/extClark-Doc/blob/master/%E4%BB%95%E6%A7%98%E6%9B%B8/%E5%B0%8F%E5%85%90%E8%96%AC%E7%94%A8%E9%87%8F%E8%A8%88%E7%AE%97%E3%83%84%E3%83%BC%E3%83%AB(%E6%8B%A1%E5%BC%B5Clark%E5%BC%8F)_%E5%A4%96%E9%83%A8%E8%A8%AD%E8%A8%88%E6%9B%B8.pdf).

### 品質保証 - Quality Assurance

解決済みの不具合一覧等の置き場です。
<BR>
The directory for the fixed bugs list and so on.
<BR>
<BR>
ツールの開発者は過去の不具合を確認し、デグレードを起こさないように注意して開発してください。
<BR>
Each of all developers of the [tool](https://github.com/Kimitsuna-Goblin/extClark/) should check fixed bugs and develop with care not to cause degradations.

## ドキュメントへの貢献 - Contribution

ドキュメントを改変するには、改変したいドキュメントの原本のWordファイルやExcelファイルをダウンロードして改変し、
印刷可能なPDFファイルを作成して、原本のファイルとPDFファイルの両方をコミットしてください。
<BR>
To update the document, download the original Word file or Excel file which you want to update,
then update it, create printable PDF file, and commit both the original file and the PDF file.

----

### 注意

ドキュメントを改変してリリースする場合、以下のルールを遵守してください。

+ ドキュメントのバージョン番号は、メジャー番号とマイナー番号は[ツール本体](https://github.com/Kimitsuna-Goblin/extClark/)の番号と一致させてください。
パッチ番号は[ツール本体](https://github.com/Kimitsuna-Goblin/extClark/)の番号と異なっていても構いません。

+ ドキュメントの表紙または先頭に、[ツール本体](https://github.com/Kimitsuna-Goblin/extClark/)のメジャー番号とマイナー番号を記載してください。
パッチ番号は記載しないでください (例: 正: v1.0, v1.1 誤: v1.0.0, v1.1.3 )。
また、ドキュメント自身のパッチ番号はドキュメント上のどこにも記載しないでください。

+ ドキュメントの表紙または先頭に、ドキュメントの最終改変日付を記載してください。

+ ドキュメントの表紙に改変前の著作者の記名がある場合は、その次に改変者の記名を追記してください。
ただし、既に自分の名前が表紙に記載されていれば、新たにそこに追記する必要はありません。

+ ドキュメントの著作権表示の欄に、改変者の著作権表示を記載してください。
なお、改変前の著作権表示は削除せず、改変者の著作権表示を追記する形で記載してください。
既に著作権表示をしたことがある場合でも、直前の改変者が自分自身でない場合は、追記してください。
ただし、全く新しいドキュメントを[リポジトリ](https://github.com/Kimitsuna-Goblin/extClark-Doc/)に追加する場合は、この限りではありません。

+ フッターなどを利用して、印刷可能なPDFファイルのすべてのページに「CC BY-SA」のアイコン表示を入れてください。

以上のルールから外れたドキュメントファイルをコミットしてしまった場合は、可及的速やかに修正してください。

----

### Remark

When you update the document and release it, please observe following rules.

* You must set the main version number and sub version number of the document as same as ones of the [tool](https://github.com/Kimitsuna-Goblin/extClark/).
You can set the patch number of the document as different as of the [tool](https://github.com/Kimitsuna-Goblin/extClark/).

* Write the main version number and the sub version number of the [tool](https://github.com/Kimitsuna-Goblin/extClark/)
on the top page or the top line of the document.
Don't write the patch number there (ex. good: v1.0, v1.1; wrong: v1.0.0, v1.1.3).
And you must not write the patch number of the document itself on any page of the document.

* Write the last update date on the top page or the top line of the document.

* If there is/are the name(s) of creator or changer on the top page of the document, add your name there.
If your name has been already written there, don't add there again.

* Add your copyright into the copyright list of the document.
You must not delete the copyright(s) already written in the list.
Although you have witten your copyright into the list once,
if the last copyright isn't yours, add your copyright again next of it.
But when you create a brand-new document and add it into the [repository](https://github.com/Kimitsuna-Goblin/extClark-Doc/),
you can ignore this rule.

* Using footer and so on, show the "CC BY-SA" icon in the each of all pages of the document.

If you commit a document file out of rules above, correct it as soon as possible.

## ライセンス - Licence

[CC BY-SA 4.0](https://github.com/Kimitsuna-Goblin/extClark-Doc/blob/master/LICENSE)

## 著作者 - Author

[Kimitsuna-Goblin](https://github.com/Kimitsuna-Goblin) (浦 公統; Ura Kimitsuna)
