# ITC bot 2023
- このbotはITC Bot ver.1.1.0を移植したものです。
- 今後機能を追加予定です。
- `BOT使用`のロールが付与されていないと使用できません。

# 目次

- [コマンド一覧](https://github.com/kariumi/ITCBot/edit/master/Readme.md#コマンド一覧)
  - [/shuffle](https://github.com/kariumi/ITCBot/edit/master/Readme.md#shuffle) - メンバーをボイスチャンネルに均等に振り分ける
- [更新履歴](https://github.com/kariumi/ITCBot/edit/master/Readme.md#%E6%9B%B4%E6%96%B0%E5%B1%A5%E6%AD%B4)

# コマンド一覧

## \/shuffle

- 自分が入っているボイスチャンネルの人を指定したボイスチャンネルにランダムに振り分け、*自動的に移動させる*コマンドです。
```Python
/shuffle [ボイスチャンネルID 1] [ボイスチャンネルID 2] ...

例：
/shuffle 123456789012345678 123456789012345679
```
- 上記のように指定すると、指定したボイスチャンネルにランダムに振り分けることができます。
```Python
/shuffle [ロール 1] [ロール 2] ... [ボイスチャンネルID 1] [ボイスチャンネルID 2] ...

例：
/shuffle @部長 @部員 123456789012345678 123456789012345679
```
- 上記のようにロールを指定すると、指定したロールのメンバーは均等に振り分けられます。
- 尚、ロールは4つまで指定することができます。


  
# 更新履歴
### 2022/12/**
- ITC bot ver1.1.0から移植しました。

### 2023/2/2
- voteコマンドを削除しました。
- Readmeを書きました。