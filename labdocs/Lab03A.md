﻿# ラボ 3A: 実験の実行

実験はデータ サイエンティストの研究の中核です。Azure Machine Learning では、*実験*を使用してスクリプトまたはパイプラインを実行し、通常は出力を生成し、メトリックを記録します。

## 開始する前に

このラボを開始する前に、このラボで使用する Azure Machine Learning ワークスペースと他のリソースを作成するタスクを含む[ラボ 1A](Lab01A.md) と[ラボ 1B](Lab01B.md) を完了させてください。

## タスク 1: コンピューティング インスタンスで実験を実行する

Azure Machine Learning コンピューティング インスタンスは、ワークスペースで実験コードを実行するための便利な環境を提供します。

1. [Azure Machine Learning Studio](https://ml.azure.com) で、ワークスペースの**コンピューティング** ページを表示し、**コンピューティング インスタンス** タブでコンピューティング インスタンスを開始します。
2. コンピューティング インスタンスが実行されている場合は、ブラウザーで Azure Machine Learning Studio の Web ページを更新して、認証セッションの有効期限が切れていないことを確認します。次に、**Jupyter** リンクをクリックして、新しいブラウザー タブで Jupyter のホーム ページを開きます。
3. Jupyter のホーム ページの**Users/DP100** フォルダーで、**03A - Running Experiments.ipynb** Notebook を開きます。次に、Notebook 内の注意事項を読み、各コード セルを順番に実行します。
4. Notebook 内のコードの実行が終了したら、**ファイル(File)** メニューの**閉じて停止(Close and Halt)**をクリックして閉じ、Python カーネルをシャットダウンします。その後、すべての Jupyter ブラウザー タブを閉じます。
5. Azure Machine Learning Studio の**コンピューティング** ページで、コンピューティング インスタンスを選択し、**停止**をクリックしてシャットダウンします。
