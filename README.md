# canales
采用canal-adapter，mysql同步数据到es。
提交代码，准备修改以下bug：
1 子表在查询结果中为数组，最后一项删除时，canal-apdpter删除不掉；
2 json数据支持不好，json嵌套json时，字段删除，无法感知。
