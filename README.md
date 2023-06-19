# MIB-translate
Convert MIBs Files to Zabbix Templates

Fórmula utilizada para converter arquivos .MIB para XML ou JSON:

snmptranslate -Tz -m ./A100-R1-MIB.mib | ./mib2zabbix -o .1.3.6.1.4.1 -f template-a100-r1-mib.xml -N a100-r1-mib
