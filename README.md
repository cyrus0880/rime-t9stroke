# rime-t9stroke
T9 / G6IME 筆劃輸入法 JKLUIO （一丨丿丶フ*）版本 (OSX 筆劃排位)

碼庫使用了G6IME六碼輸入法windows版的sqlite db 

用python 寫code提取同轉碼到rime碼表

增加* 萬用字測試 最多頭4-5碼 可用*

tnine.schema.ymal          #輪入法主config

tnine.extended.dict.yaml   #碼庫 config

tnine.g6tc.dict.yaml       #六碼字庫

tnine.g6tcf.dict.yaml      #全碼字庫

tnine.enn.dict.yaml        #自定議字庫

tnine.symbol.dict.yaml     #symbol字庫

setup 方法

```
#windows 
go to C:\Program Files (x86)\Rime\weasel-0.14.3
Copy all tnine.* to data folder
edit data\default.yaml
在 schema_list: 加入 - schema: tnine
在rime輸入法 icon 右click 搵 重新部署按下後即可使用
```

```
#linux
go to /usr/share/rime-data /
Copy all tnine.* to data folder
edit data/default.yaml
在 schema_list: 加入 - schema: tnine
在ibus icon 揀 rime輸入法 系ibus輸入法menu 搵 重新部署 按下後即可使用
```

遲小小會提供uiojkl碼表的config同字庫上來

作者:cyrus0880

如有任何問題可以在github上查詢
