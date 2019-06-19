# PocHubs

PocHubs是为了整合网上知名开源框架的漏洞详细和POC，目前计划完善的是ThinkPHP、WordPress等平台。

### ThinkPHP

使用方法：

```bash
# 进入网站根目录，如 /var/www/
cd /var/www
# 创建 thinkphp5 目录 tp5 ，拉取 thinkphp5 代码
git clone https://github.com/top-think/framework.git /var/www/tp5
# 创建 thinkphp3 目录 tp3 ，拉取 thinkphp3 代码
git clone https://github.com/top-think/thinkphp.git /var/www/tp3
```

详细漏洞列表可查看 [`ThinkPHP.md`](ThinkPHP.md)

目前已收录

| ThinkPHP3                                                    | ThinkPHP5                                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ThinkPHP3.2.3 缓存函数设计缺陷可导致Getshell](ThinkPHP.md#ThinkPHP3.2.3 缓存函数设计缺陷可导致Getshell) | [ThinkPHP5.0.9 SQL注入漏洞 && 敏感信息泄露](ThinkPHP.md#ThinkPHP5 SQL注入漏洞 && 敏感信息泄露) |
| [ThinkPHP3.2.3 最新版update注入漏洞](ThinkPHP.md#ThinkPHP3.2.3最新版update注入漏洞) | [ThinkPHP5.0.10-3.2.3 缓存函数设计缺陷可导致Getshell](ThinkPHP.md#ThinkPHP5.0.10-3.2.3 缓存函数设计缺陷可导致Getshell) |
| [ThinkPHP3.2.X find_select_delete注入](ThinkPHP.md#ThinkPHP3.2 find_select_delete注入) | [ThinkPHP框架 5.0.x sql注入漏洞分析](ThinkPHP.md#ThinkPHP框架 5.0.x sql注入漏洞分析) |
| [ThinkPHP 3.2.X order by注入漏洞](ThinkPHP.md#ThinkPHP 3.X order by注入漏洞) | [ThinkPHP 5.X order by注入漏洞](ThinkPHP.md#ThinkPHP 5.X order by注入漏洞) |
|                                                              | [ThinkPHP5.X 远程代码执行](ThinkPHP.md#ThinkPHP5.X 远程代码执行) |

### WordPress

使用方法：

```bash
# 进入网站根目录，如 /var/www/
cd /var/www
# 创建 wordpress 目录 wp ，并拉取 wordpress 代码
git clone https://github.com/WordPress/WordPress.git /var/www/wp
```

详细漏洞列表可查看 [`WordPress.md`](WordPress.md)

目前未整合

