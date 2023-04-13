# MIB-translate
Convert MIBs Files to Zabbix Templates
FORMULA TO CONVERT:

snpmtranslate -Tz -m ./A3COM-HUAWEI-E1T1VI-MIB.mib (nome do arquivo a ser convertido) | ./mib2zabbix -o .1.3.6.1.4.1 -f mib-translated-a3com-huawei-e1t1vi-mib.xml (nome do novo arquivo) -N a3com-huawei-e1t1vi-mib (nome do arquivo em minisculo).

snpmtranslate -Tz -m ./A100-R1-MIB.mib | ./mib2zabbix -o .1.3.6.1.4.1 -f mib-translate-a100-r1-mib.xml -N a3com-huawei-e1t1vi-mib
