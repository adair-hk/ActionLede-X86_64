<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
    <h1>Action-x86_64 云Lede编译项目</h1>
    <h3>fork至自己的账户,Actions内运行<u>.config</u>即可云生成.config。本项目默认自带.config</h3>
    <h5>.config文件为在编译Openwrt完整操作系统前的生成的配置文件，根据个人需求修改。</h5>
    <h5>添加需要的插件源，按照格式填入diy-part1.sh或者Lede-CI.yaml页面进入编辑74行<br />格式：echo 'src-git <文件夹名称>  <源地址>' >>feeds.conf.default</h5>
    <h5>修改固件默认ip地址，请修改diy-part2.sh或者Lede-CI.yaml页面进入编辑87行，10.10.10.2换成需要的IP地址</h5>
    <h3>前往ACtions界面Build openwrt，点击Run workflow即可</h3>
    <hr size="1px" color="black"/>
    <h3>本项目基于Ubuntu-20.04（也可以使用Windows下子系统wsl2完成完整的操作编译）
    <br /><br />详细介绍页（本地操作或者云服务器操作）：<a href="http://www.huadao.art/">Jayha's blog</a></h3>
    <hr size="1px" color="black"/>
    <h3>本项目参考并基于Lede（by:coolsnowwolf）
        <br />项目地址：<a href="https://github.com/coolsnowwolf/lede">Lede</a></h3>
    <h3>Actions-Openwrt（by:P3TERX）
        <br />项目地址：<a href="https://github.com/P3TERX/Actions-OpenWrt">Actions-Openwrt</a></h3>
    <h3>如果好用请点一下FROK/STRA，谢谢！—— ~ ——</h3>
    <h3>本项目仅供本人学习使用，无任何商业价值。</h3>
</body>
</html>