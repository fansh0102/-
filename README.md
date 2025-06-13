## ck-test 
检测网卡性能，并打包性能报告到 clusterkit_results/YYYYMMDD_HHMMSS.tar.gz
测试所有hca设备  ./ck-test.sh
测试特定hca设备（通过索引）  ./ck-test.sh 0,1,2,3
测试单个HCA设备   ./ck-test.sh 0

## core_to_hca_hgx100.sh
将MPI进程绑定到特定的CPU核心，并为每个进程分配对应的ConnectX-7网卡，以优化NUMA（Non-Uniform Memory Access）性能。

## daemon
docker的守护进程配置文件

## docker_install_online
在线安装docker的脚本

## drbd
文件同步系统，用于ufm上ha

## install-pip-offline
在线安装python包管理器

## netplan_config_tool
ubuntu22.04系统网络配置工具

## network_tool rocky9.5
系统网络配置工具


