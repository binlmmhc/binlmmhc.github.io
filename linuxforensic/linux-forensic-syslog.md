# Linux类系统日志取证分析

## 1、系统日志概述

## 2、系统日志涉及的文件与路径
    Linux类系统日志涉及的文件与路径如下：
    1.  /var/log/messages
        该文件记录了系统启动后的信息和错误日志，是查看Linux系统信息最常用的文件之一。
    2.  /var/log/secure
        该文件记录了用户登录和权限认证信息，包括密码错误日志、root用户的登录记录等。
    3.  /etc/rsyslog.conf
        该文件是系统日志配置文件，记录了各种日志的输出位置、日志类型以及日志级别等。
    4.  /var/log/cron.log

## 3、系统日志取证分析


## 4、附录-日志详述
    1、/var/log/auth.log日志详诉
        auth.log中记录了用户的登录信息，包括用户名、登录时间、登录IP地址等。通过分析auth.log，可以了解用户登录情况、异常登录行为等，其日志信息如下。
        ![日志图片](https://github.com/binlmmhc/binlmmhc.github.io/blob/master/linuxforensic/imgs/linux-forensic-syslog-authlog1.png)