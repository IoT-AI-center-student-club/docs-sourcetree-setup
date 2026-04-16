# SourceTree セットアップガイド

この手順に従えば、GitとSourceTreeを使った開発環境を構築できます。

---

## 🔗 使用するツール

* Git
  https://git-scm.com/install/windows

* SourceTree
  https://www.sourcetreeapp.com/

---

## 🧰 1. Gitのインストール

### 💻 Windows

1. 上記GitのURLにアクセス
2. 「Git for Windows / x64 Setup」をクリック
3. インストーラーをダウンロード
4. ダウンロードしたファイルを起動し、インストール

---

### 🍎 Mac

1. ターミナルを開く
2. 以下コマンドで確認

```
git --version
```

3. バージョンが表示されない場合、以下を実行

```
brew install git
```

4. 再度確認

```
git --version
```

---

## 🌳 2. SourceTreeのインストール

1. SourceTreeのURLにアクセス
2. OSに応じたバージョンをダウンロード

   * Windows → Windows版
   * Mac → Mac版
3. ダウンロードしたファイルを起動

---

## 🔑 3. SourceTree 初期設定

### Bitbucketアカウント作成

1. インストール中にアカウント作成を求められる
2. 「登録」をクリック
3. 画面に従ってアカウントを作成
4. 作成後、インストーラーに戻る
5. 「Bitbucket」ボタンを押し、ブラウザでログイン

---

### Gitの設定

* 「既存のGitを使用」を選択
  （デフォルトで選択されているものを使用）

---

### ユーザー情報入力

* ユーザーネームを入力
* メールアドレスを入力

---

### SSHキー設定

* 「SSHキーを読み込む」→ **いいえ** を選択

---

## 🐈‍⬛ 4. GitHubアカウント登録（OAuth連携）

SourceTreeの初期画面から、以下の手順でGitHub連携を行います。

1. 「リモート」を開く
2. 「OAuthトークン再読み込み」をクリック
3. ブラウザが自動起動する
4. GitHubにログインする
5. 「Authorize」をクリック
6. 「github.com が SourceTree を開こうとしています」と表示されたら「許可」をクリック

---

## ✅ 5. セットアップ完了

以上でセットアップは完了です。

---

## ✔ チェックリスト

* Gitがインストールされている
* SourceTreeが起動できる
* Bitbucketアカウントでログインできる
* GitHubアカウント連携（OAuth）が完了している
* ユーザー情報が設定されている

---

不明点があれば先輩やチームメンバーに相談してください。
