## ZTE (2015/7 - 2018/10)

- Android系统的定制化，主要包括对init子系统和service的裁减，使其满足容器化的运行环境（https://blog.totorow.xyz/posts/lxc_android/lxc_android/）。
- 在Android系统中添加对LXC容器化工具的支持，主要包括对LXC工具链的移植以及适配工作 （https://github.com/lxc/lxc/pull/743）。
- 对Android系统进行改造，使其具备容器化运行的功能，主要包括显示（framebuffer），
输入设备（touchpad），进程间通信机制（binder），声音（PCM），GPS（Location service），
网络（virtual ethernet）。
- 基于SPICE的远程桌面协议的改造，添加对声音和输入事件的支持（https://blog.totorow.xyz/posts/spice/）。
- 使用Go语言开发了针对用户事件的服务模块（https://github.com/tw4452852/servicemgr）。
- 基于Android容器化技术的系统调优（通过cgroup），主要包括系统进程调度，内存，文件系统方面。
- 嵌入式存储设备驱动的移植和适配，分析和解决针对flash的文件系统的问题（https://blog.totorow.xyz/posts/nand_flash_basics/）。