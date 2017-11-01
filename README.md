# jenkins-tool-nuwa

用于上传初始插件任务

在上传之前，请配置归档服务信息在arg.properties文件中。

```bash
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-asl
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-customtask
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-ftpartifact
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-semver
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-opspkg
./tools/asl/tools/ant/bin/ant -f nuwa.xml upload-cloudartifact
```
