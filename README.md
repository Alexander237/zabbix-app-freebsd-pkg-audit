# zabbix-app-freebsd-pkg-audit
zabbix template for monitoring vulnerabilities using % pkg audit

Template includes the following Zabbix items:
- Number of vulnerabilities reported by pkg audit;
- Number of vulnerable applications;
- List of vulnerable software.

Installation procedure:
- import zabbix template;
- include fbsd-pkg-audit.conf in FreeBSD zabbix agent configuration (also enable active checks).
