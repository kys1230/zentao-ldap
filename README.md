# ZENTAO-LDAP 开源版 LDAP 插件 PLUS

## 简介

这个插件是在 “[shynome/zentao-ldap](https://github.com/shynome/zentao-ldap)” 上基础进行的修正，使其可以在 禅道开源版 12.5 上正常运行

## 配置示例

| 选项 | 示例值 |
| ---- | ---- |
| LDAP服务器 | ldap://192.168.32.203:389 |
| 协议版本 | 3 |
| BindDN | cn=admin,dc=mylitboy,dc=com |
| BindDN 密码 | ou=users,dc=mylitboy,dc=com |
| Search filter | (objectClass=person) |
| 账号字段 | uid |
| EMail 字段 | mail |
| 姓名字段 | cn |

> [参考](https://blog.mylitboy.com/article/operation/zentao-config-ldap.html)

### 从钉钉同步信息到ldap

> [参考](https://github.com/anjia0532/virtual-ldap)
