# ansible-graalvm

將GraalVM 安裝到/opt目錄下，並設定好環境變數

## Useage:

```bash
$ ansible-playbook -i hosts deploy-graalvm.yml
```

請自行將remote server的 IP 填入 ansible-graalvm/hosts

請將GraalVM的URL填入ansile-graalvm/vars/graalvm_var.yml中的download_path_url

## Result:

```bash
[root@localhost ~]# java -version
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment (build 11.0.5+10-jvmci-19.3-b05-LTS)
OpenJDK 64-Bit GraalVM CE 19.3.0 (build 11.0.5+10-jvmci-19.3-b05-LTS, mixed mode, sharing)
```

