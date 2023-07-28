# CUC-2023

本项目为CUC-2023 漏洞环境构建及漏洞复现报告。

> https://github.com/Shenkongyin/CUC-2023



## 技术与实现

1.[Python_CVE_2022_28347_Django](https://github.com/Shenkongyin/CUC-2023/tree/Python_CVE-2022-28347_Django)

该漏洞使用本地IDE自建项目并结合 docker-compose.yml 和 Dockerfile构建漏洞集成环境。使用Python编写POC完成漏洞复现。

2.[PHP_CVE-2019-7580_ThinkCMF](https://github.com/Shenkongyin/CUC-2023/tree/PHP_CVE-2019-7580_ThinkCMF)

该漏洞使用 docker-compose.yml 拉取 vulfocus 现有 docker 镜像构建漏洞环境。使用Python编写POC完成漏洞复现。

3.[MariaDB_CVE-2021-27928_Bash](https://github.com/Shenkongyin/CUC-2023/tree/MariaDB_CVE-2021-27928_Bash)

该漏洞使用 Bash 脚本搭配 Dockerfile 完成自动生成反弹 shell载荷并复制到至 docker 容器完成漏洞环境构建。使用Bash脚本完成漏洞复现。



## 快速使用

共三个分支，三个漏洞，克隆对应分支，参考漏洞复现报告即可。

1. [CVE-2021-27928 漏洞复现报告.md](MariaDB_CVE-2021-27928_Bash/漏洞复现报告.md)

   ```sh
   git clone -b MariaDB_CVE-2021-27928_Bash --single-branch https://github.com/Shenkongyin/CUC-2023
   ```

2. [CVE-2019-7580 漏洞复现报告.md](PHP_CVE-2019-7580_ThinkCMF/漏洞复现报告.md)

   ```sh
   git clone -b PHP_CVE-2019-7580_ThinkCMF --single-branch https://github.com/Shenkongyin/CUC-2023
   ```

3. [CVE-2022-28347 漏洞复现报告.md](Python_CVE-2022-28347_Django/漏洞复现报告.md)

   ```sh
   git clone -b Python_CVE-2022-28347_Django --single-branch https://github.com/Shenkongyin/CUC-2023
   ```
