## Ansibles - OracleJDK [![Build Status](https://travis-ci.org/Ansibles/oracle-jdk.png)](https://travis-ci.org/Ansibles/oracle-jdk)

Ansible role to install the latest update of Oracle/Sun JDK version(s) on Ubuntu variants.


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher

#### Variables

```yaml
oracle_jdk_java_versions: [7]                  # List of versions to install (6, 7 and/or 8)
oracle_jdk_java_version_default: 7             # One of the versions installed above
```

#### In operation

To switch between different Java versions, you could use the following terminal command:
```bash
sudo update-alternatives --config java
```

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ansibles/oracle-jdk/issues)!
