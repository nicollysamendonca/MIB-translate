# MIB-translate
Convert MIBs Files to Zabbix Templates

Fórmula utilizada para converter arquivos .MIB para XML ou JSON:

snpmtranslate -Tz -m ./A3COM-HUAWEI-E1T1VI-MIB.mib (nome do arquivo a ser convertido) | ./mib2zabbix -o .1.3.6.1.4.1 -f mib-translated-a3com-huawei-e1t1vi-mib.xml (nome do novo arquivo) -N a3com-huawei-e1t1vi-mib (nome do arquivo em minisculo).
