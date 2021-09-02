# AE-to-Slack_renderingNotifier:grinning:

 レンダリング完了後にSlackの特定のリンクへ通知を送信するAfterEffects用のスクリプトです。<br> AfterEffectsScript for notify completed rendering to slack workspace.

## DEMO

## Development Environment

- Python 3.8.3
  
  2.xでの動作は確認してません:cry:
  
- AfterEffects 2021
  
- Mac OS X (Big Sur)
  

## Requirement

- python (3.x)
  
- AfterEffects CC
  
- slackweb
  
- Mac OS X
  

## Installation

- **Python 3** 
  
  Python3のインストールは[ここ](https://qiita.com/7110/items/1aa5968022373e99ae28)がわかりやすいです
  
- **slackweb**
  

**pipがインストールされていない場合**

terminalで

`$ pip -V`

として、pip x.x.xとバージョンが表示されない場合

`$ sudo easy_install pip`

**pipインストール後　slackwebをインストール**

`$ sudo pip install slackweb`

****

**確認**

terminalで

`$ python -V`

3.x.xが出てくればPythonはOK

`$ pip list`

として、listの中にslackwebが入っていればOK

# Usage(how to use)
