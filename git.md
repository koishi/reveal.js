# Git講座 実習編
---
# 導入
* Gitのダウンロード、インストール<br>
https://git-for-windows.github.io
* SourceTreeのダウンロード・インストール<br>
https://ja.atlassian.com/software/sourcetree
---
# 導入後の動作確認
* Gitのバージョン確認して表示されたらOK<br>

<pre><code class="bash">$ git version</code></pre>
---
# 初期設定
* 名前を設定

<pre><code class="bash">$ git config --global user.name 'name'</code></pre>

* メールアドレスを設定

<pre><code class="bash">$ git config --global user.email 'email'</code></pre>

* 設定を確認

<pre><code class="bash">$ git config --list</code></pre>
---
# 準備
* バージョン管理するプロジェクトの作成
* フォルダを作ってHTMLファイルを作成<br>
sample.html
<pre><code class="html">&lt;html>
&lt;body>
  &lt;h1>Hello World!!&lt;/h1>
&lt;/body>
&lt;/html>
</code></pre>
---
# 初期化
* Gitリポジトリの作成

<pre><code class="bash">$ git init</code></pre>
---
# ステータス確認
* ファイルの編集状態、追加状態を確認する

<pre><code class="bash">$ git status</code></pre>
---
# コミット
ステージ、コミットの概念
---
# ファイルのステージ
* ファイルをコミット対象(ステージ)にする<br>

<pre><code class="bash">$ git add 'file'</code></pre>

* 全てのファイルをステージする<br>

<pre><code class="bash">$ git add .</code></pre>
---
# コミット
# 変更のコミット

<pre><code class="bash">$ git commit -m 'comment'</code></pre>
---
# コミットログを表示

<pre><code class="bash">$ git log</code></pre>
---
# ファイルの変更を元に戻す

* 全ての変更を元に戻す

<pre><code class="bash">$ git checkout .</code></pre>

* 特定のファイルのみ

<pre><code class="bash">$ git checkout 'file'</code></pre>
---
# ブランチ(branch)
* ブランチを表示

<pre><code class="bash">$ git branch</code></pre>

* ブランチの概念を説明(masterブランチ)
---
# ブランチの作成
* 別のブランチを作る(冒険の書のコピー)

<pre><code class="bash">$ git branch 'branch'</code></pre>

# ブランチの切り替え
* 別のブランチをチェックアウトする(冒険の書を選ぶ)

<pre><code class="bash">$ git checkout 'branch'</code></pre>
---
# ブランチの削除
<pre><code class="bash">$ git branch -d</code></pre>
---
# マージ
* マージの概念を説明
---
# マージ
* チェックアウトしているブランチへ別のブランチをマージする。

<pre><code class="bash">$ git merge 'branch'</code></pre>
---
# マージ スカッシュオプション
* 変更点を1つのコミットにまとめたい場合

<pre><code class="bash">$ git merge --squash 'branch'</code></pre>

* この後でコミットをする
---
# 追加コミット

* コメント修正
* 不足ファイルの追加
* 変更点の修正

<pre><code class="bash">$ git commit --amend</code></pre>
---
# コミットリズム
* 1タスクごとにコミット
* 最後にまとめて1コミット
---
# スタッシュ

* 編集中のファイルを一時退避する

<pre><code class="bash">$ git stash</code></pre>

* 一時退避したファイルを元に戻す

<pre><code class="bash">$ git stash pop</code></pre>
---
# コミットの打ち消し
* コミットした変更の逆のコミットを作成

<pre><code class="bash">$ git revert 'commit'</code></pre>
---
# リビジョンの移動
* コミットの位置を変更する

<pre><code class="bash">$ git reset 'commit'</code></pre>
---
# リベース
* 他ブランチからの変更の上にコミットを重ねる

※まだ書いてない
※ツール上で説明
---
# タグ
* 特定のコミットにタグをつけて管理する
* リリースバージョンごとにタグで管理

※ツール上で説明
---
# 無視ファイルの設定
* .gitignoreを編集する

※ツール上で説明
※サンプル使用