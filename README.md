# Role: motd

Configure the message of the day

## Configuration
|Variable|Default vaule|Description|
|--------|-------------|-----------|
| `motd_infrastructure_manager` | `"ISG SOSETH <isg@sos.ethz.ch>"` | "Host contact", that is, whom to contact in case of problems |
| `motd_distribution_name` | `{{ ansible_distribution }}` | |
| `motd_distribution_version` | `{{ ansible_distribution_version }}` | |
| `motd_static` | `True` | Whether to enable motd replacement |

**Compatibility tested with:**
 * Debian 8
 * Debian 9
 * Fedora 25 Server

## License
GPLv3
