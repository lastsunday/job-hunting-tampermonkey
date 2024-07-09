# job-hunting-tampermonkey

协助找工作，方便职位浏览的油猴脚本

## 源码地址

https://github.com/lastsunday/job-hunting-tampermonkey

### 加强版插件(推荐使用)

> 项目为浏览器插件，可安装在Chrome,Edge和Firefox(数据持久化未实现)

> 采用了数据本地存储(Sqlite技术)，如职位信息（可在后台页面浏览历史职位），公司信息（加速了公司信息的查询，减少人机验证）

1. 加强版插件源码地址

    https://github.com/lastsunday/job-hunting

2. 加强版插件功能列表

    1. 显示职位发布时间与自动排序(按职位发布时间,hr 活跃时间（只支持 BOSS）)。
    2. 快捷查询公司信息 🔎（互联网渠道，政府渠道）。
    3. 自动检测公司风评 📡，当前支持：若比邻黑名单。
    4. 自动快速查询公司信息并保存到数据库（BOSS 直聘和猎聘网需手动点击查询）。
    5. 自动查询官网可达性，建站时间和备案信息。
    6. 本地显示职位初次浏览时间，历史浏览次数，职位详情查看次数。
    7. 本地职位记录统计，查询，查询结果导出。
    8. 数据备份，数据恢复。
    9. 职位评论，公司评论。（当前采用 ECHO 作为评论平台，请遵守相关法律法规合法留言）
    10. 数据统计图表
        1. 根据指定搜索条件统计薪酬区间职位数（薪酬计算方式：(最低薪资+最高薪资)/2）
    11. 公司自定义标签（可添加，修改，拖拽排序），内置外包公司标签数据。
    12. 公司标签数据管理页面，公司标签数据导出，导入。
    13. 公司数据管理页面，公司数据导出，导入。

## 运行截图

<img src="https://raw.githubusercontent.com/lastsunday/job-hunting-tampermonkey/main/docs/introduction/tampermonkey-51job.png" alt="chrome_extension_sidepanel_open" width="600px"/>

## 招聘平台支持列表

| 招聘平台  | 访问地址                            | 备注                   |
| --------- | ----------------------------------- | ---------------------- |
| BOSS直聘  | https://www.zhipin.com/web/geek/job |                        |
| 前程无忧  | https://we.51job.com/pc/search      |                        |
| 智联招聘  | https://sou.zhaopin.com/            |                        |
| 拉钩网    | https://www.lagou.com/wn/zhaopin    |                        |
| 猎聘网 | https://www.liepin.com/zhaopin              | 需点击搜索按钮才有效果 |

## 功能列表

1. 显示职位发布时间与自动排序(按职位发布时间,hr活跃时间（只支持BOSS）)。
2. 快捷查询公司信息🔎（互联网渠道，政府渠道）。
3. 自动检测公司风评📡，当前支持：若比邻黑名单。
4. 自动快速查询公司信息（BOSS直聘需手动点击查询）。
5. 自动查询官网可达性，建站时间和备案信息。

## Thanks

1. https://github.com/tangzhiyao/boss-show-time ***boss 直聘时间展示插件***
2. https://github.com/iibeibei/tampermonkey_scripts ***BOSS 直聘 跨境黑名单***
3. https://kjxb.org/ ***【跨境小白网】，跨境电商人的职场交流社区，互助网站。***
4. https://maimai.cn/article/detail?fid=1662335089&efid=I0IjMo8A_37C2pHoqU2HjA ***求职必备技能：教你如何扒了公司的底裤***