API
=====

Component: core
-----

###Action

####saveSession


#####パラメータ1: apikey

#####パラメータ2: name：

- セッションを保存するディレクトリへの絶対パス + 保存するファイルの接頭文字列
- （例）"/Users/yuki/tmp/zap_session_save_test/foo" を渡すと、/Users/yuki/tmp/zap_session_save_test/ 内に、以下のファイルとディレクトリが生成される。
    - foo.session
    - foo.session.data
    - foo.session.lck
    - foo.session.log
    - foo.session.properties
    - foo.session.script
    - foo.session.tmp/

#####パラメータ3: overwrite

- "true" or "false"

#####戻り値:

- 成功時：{"Result":"OK"}

