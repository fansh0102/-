1.ck-test 检测网卡性能，并打包性能报告到 clusterkit_results/YYYYMMDD_HHMMSS.tar.gz
测试所有hca设备  ./ck-test.sh
测试特定hca设备（通过索引）  ./ck-test.sh 0,1,2,3
测试单个HCA设备   ./ck-test.sh 0

2.core_to_hca_hgx100.sh将MPI进程绑定到特定的CPU核心，并为每个进程分配对应的ConnectX-7网卡，以优化NUMA（Non-Uniform Memory Access）性能。

3.daemon是docker的守护进程。

4.docker_install_online是在线安装docker的脚本

5.drbd是文件同步系统，用于ufm上ha

6.install-pip-offline,在线安装python包管理器

7.netplan_config_tool，ubuntu22。04系统网络配置工具

8.network_tool rocky9.5系统网络配置工具


