# Ansible Role: Java

Installs Java on Centos 7

## Requirements

Tested CentOS 7

## Role Variables

Define the openJDK vesion

```
java_version: "1.8.0"
```

List of packages

```
java_packages:
  - java-{{ java_version }}-openjdk
```

## Dependencies

You need Java

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-java](https://github.com/tovletoglou/ansible-role-java)
