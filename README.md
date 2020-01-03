##学习社区

##资料

[spring 文档](https://spring.io/guides)
[github 社区项目](https://github.com/zuokun300/community)
[BootStrap组件](https://v3.bootcss.com/components/)
[GitHubAPP登陆API  OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

##工具
git
visual-paradigm

##脚本
`sql`
create table USER
(
  ID           INTEGER default NEXT VALUE FOR "PUBLIC"."SYSTEM_SEQUENCE_2D351212_B8BD_4C79_9D9E_00EC3B30F511"
    primary key,
  ACCOUNT_ID   VARCHAR(100),
  NAME         VARCHAR(50),
  TOKEN        CHAR(36),
  GMT_CREATE   BIGINT,
  GMT_MODIFIED BIGINT
);


