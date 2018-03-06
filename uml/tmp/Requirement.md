### 仕様

汎用性のあるボードゲームシミュレータ。  
ここでのボードゲームとは、升目状の盤面と2つの駒を使用するものに限定する。
2つ駒は、2つのプレイヤに1つずつ属する。  
また、駒はプレイヤ交互に打たれるものとする。  
  
ユーザはゲームの実行を行うことができる。  
ゲームは予め設定されたルール(勝利条件、禁じ手)に従い進行される。
ゲーム終了後は、戦績を出力する。  
  
ユーザはゲームを行うプレイヤを選択することができる。
戦略+指定した識別文字列でプレイヤとする。
プレイヤは2つで固定とする。  
なお、選択はゲーム前・プレイ中どちらでも可能とする。
選択可能な戦略は、予め設定しておく。  

ユーザは特定のゲームの盤面を作成することができる。  
なお、盤面作成はゲーム前・プレイ中どちらでも可能とする。  
また、作成した盤面は、ファイル形式により保存できる。  
盤面ファイルを読み込むことで、保存した盤面を再現することができる。  

ユーザは戦略を登録することができる。  
戦略の登録では、戦略が記述されたjavaファイルを指定する。  
登録された戦略は、前記したプレイヤ選択で使用される。  

