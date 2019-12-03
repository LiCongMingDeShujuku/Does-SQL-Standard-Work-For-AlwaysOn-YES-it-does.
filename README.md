![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# SQL Standard支持AlwaysOn吗？ 是的！
#### Does SQL Standard Work For AlwaysOn? YES it does.
**发布-日期: 2016年05月18日 (评论)**

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
一个常见问题是...... SQL Server 有支持AlwaysOn的版本么？ 答案是肯定的。 这个问题有些混乱，因为微软传统上将其集群（高可用性解决方案）保留为高级或“企业级”功能。但是SQL Server 2012 Standard是支持AlwaysOn配置的：
MSDN参考：https：//msdn.microsoft.com/en-us/library/cc645993（v = sql.110）.aspx

请看下图：

## English
A common question that comes up from time to time is… What SQL Server Edition supports AlwaysOn? The answer is YES IT DOES. There is some confusion around this topic as Microsoft has traditionally kept it’s Cluster (High Availability Solutions) reserved as a premium or ‘Enterprise Level’ feature. However; in this case SQL Server 2012 Standard does support the AlwaysOn configurations:
MSDN Reference: https://msdn.microsoft.com/en-us/library/cc645993(v=sql.110).aspx

See the image below:

![#](images/01-Does-SQL-Standard-Work-For-AlwaysOn-YES-it-does.png?raw=true "#")

Another common follow-up question to this is… What Windows Server Edition supports AlwaysOn? The answer to this is Server 2012 STANDARD. Yes. Thats right! I said Server 2012 Standard. Microsoft has included the Failover Cluster feature in Windows Standard editions.
Here’s some screenshot to further illustrate the point.


另一个常见的后续问题是，什么版本的Windows Server 支持AlwaysOn？ 答案是Server 2012 STANDARD。 是。 那就对了！ 我说的是Server 2012 Standard。 Microsoft已在Windows标准版中包含故障转移群集功能。
这里有一些截图来进一步说明这一点。
Here’s a garden variety Windows Server R2 installation.
这是一个garden variety Windows Server R2的安装示范。

![#](images/02-Does-SQL-Standard-Work-For-AlwaysOn-YES-it-does.png?raw=true "#")

If you go to features…
如果你点击「功能」（Add roles and features）


![#](images/03-Does-SQL-Standard-Work-For-AlwaysOn-YES-it-does.png?raw=true "#")

You’ll see the Failover feature exists, and has already been selected. I selected it and installed it to be sure it’s functional and it is.

你会看到Failover功能已经被选中。我已经选择并安装了这个功能，它现在能运作并发挥功能。


![#](images/04-Does-SQL-Standard-Work-For-AlwaysOn-YES-it-does.png?raw=true "#")

[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

