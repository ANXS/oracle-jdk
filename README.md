## ANXS - OracleJDK [![Build Status](https://travis-ci.org/ANXS/oracle-jdk.png)](https://travis-ci.org/ANXS/oracle-jdk)

Ansible role to install the latest update of Oracle/Sun JDK version(s).


#### Requirements & Dependencies
- Tested on Ansible 1.4 or higher


#### Variables

```yaml
oracle_jdk_java_versions: [7]             # A list of java versions you want to have installed (6, 7 and/or 8)
oracle_jdk_java_version_default: 7        # The java version you want to be the system default
```


#### In operation

To switch between different Java versions, you could use the following terminal command:
```bash
sudo update-alternatives --config java
```


#### License

Licensed under the MIT License. See the LICENSE file for details.


#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/ANXS/oracle-jdk/issues)!
