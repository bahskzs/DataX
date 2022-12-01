# Read me 

基于阿里开源框架datax,追加orale writeMode,支持增量更新模式
e.g. insert模式无改变，若需要增量则追加"writeMode" : "update('主键或组合主键')"