## notice

1. env

    - 默认 logstash 不会再 kibana 内显示
    - logstash 创建 es 的索引(库)只能再起权限内

2. wip

    - 现在 logstash 在 kibana 显示是通过将其配置给 es的， 但是使用的是username=kibana_system, 否则没权限
    - logstash 的pipeline使用 index 会重复出现字段.keyword
