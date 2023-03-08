# ProtectedApkSignerForVasDolly
一步解决加固未签名apk对齐再签名生成多渠道包的问题。

# 写在前面

python脚本，用于将加固完未签名的apk对齐再签名然后使用[VasDolly](https://github.com/Tencent/VasDolly)生成多渠道包。
----------

# 用法：

- 按照config.py文件中的注释改成自己项目配置，将protectedSourceApkName改成加固好的apk文件名【未签名的包，请不要使用加固客户端签名工具】
- 将已经加固好的包【未签名的包，请不要使用加固客户端签名工具】放到./\\channel\\reinforce-unsigned-apk中
- 各种渠道的定义是在channel这个文件中，请根据项目情况修改
- 运行命令执行ApkResignerVasDolly.py脚本,即可自动生成所有渠道包。
----------

# 支持平台：（需要python环境）
- Windows (Test)
- Mac OS (Test)
- Linux

注意：python2.x版本正常，python3.x待测试
----------
