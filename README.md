# ansible-graalvm

## Useage:

```bash
$ ansible-playbook -i hosts deploy-graalvm.yml
```

請自行將remote server的 IP 填入 sensible-graalvm/hosts

## Result:

```bash
[root@localhost ~]# java -version
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment (build 11.0.5+10-jvmci-19.3-b05-LTS)
OpenJDK 64-Bit GraalVM CE 19.3.0 (build 11.0.5+10-jvmci-19.3-b05-LTS, mixed mode, sharing)
```

