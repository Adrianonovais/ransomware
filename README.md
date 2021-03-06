# Ransomware
Analise de Malwares Ransomware via Redes Neurais

## Limitações dos Antivirus Comerciais

Tecnicamente, o modus operandi para a identificação de arquivos e servidores maliciosos refere-se à consulta em bases de dados de listas negras nomeadas. A plataforma VirusTotal emite os diagnósticos de características malignas relacionadas a arquivos e servidores web.

Quando se trata de arquivos suspeitos, o VirusTotal emite os diagnósticos fornecidos pelos principais produtos antivírus comerciais do mundo. Em relação aos servidores web suspeitos, o VirusTotal utiliza o banco de dados responsável por detectar endereços virtuais com práticas maliciosas.

O VirusTotal possui Application Programming Interface (APIs) que permitem aos programadores consultar a plataforma de forma automatizada e sem o uso da interface gráfica da web. O artigo proposto emprega duas das APIs disponibilizadas pelo VirusTotal. O primeiro é responsável por enviar os arquivos investigados ao servidor da plataforma. A segunda API, por sua vez, disponibiliza diagnósticos antivírus comerciais para arquivos enviados à plataforma pela primeira API.

Inicialmente, os malwares executáveis ​​são enviados ao servidor pertencente à plataforma VirusTotal. Depois disso, os executáveis ​​são analisados ​​pelos 86 antivírus comerciais vinculados ao VirusTotal. Portanto, o antivírus fornece seu diagnóstico para os executáveis ​​submetidos à plataforma. O VirusTotal permite a emissão de três tipos diferentes de diagnósticos: malware, benigno e omissão.

Em seguida, através da plataforma VirusTotal, o trabalho proposto investiga 68 antivírus comerciais com seus respectivos resultados apresentados na Tabela 2. Utilizamos 1000 executáveis ​​maliciosos para ARM obtidos de nosso banco de dados. O objetivo do trabalho é verificar o número de pragas virtuais catalogadas por antivírus. A motivação é que a aquisição de novas pragas virtuais desempenha um papel importante no combate a aplicativos maliciosos. Portanto, quanto maior o banco de dados de malwares na lista negra, melhor tende a ser a defesa fornecida pelo antivírus.

Quanto à primeira possibilidade do VirusTotal, o antivírus detecta a malignidade do arquivo suspeito. No ambiente experimental proposto, todos os executáveis ​​enviados são malwares de domínio público. Portanto, no estudo proposto, o antivírus acerta quando detecta a malignidade do executável investigado. A detecção de malware indica que o antivírus fornece um serviço robusto contra invasões cibernéticas. Quanto maior o banco de dados da lista negra, melhor tende a ser a defesa fornecida pelo antivírus.

Na segunda possibilidade, o antivírus atesta a benignidade do arquivo investigado. Portanto, no estudo proposto, quando o antivírus atesta a benignidade do arquivo, trata-se de um falso negativo – já que todas as amostras são maliciosas. Ou seja, o executável investigado é um malware; no entanto, o antivírus atesta a benignidade da maneira errada.

Na terceira possibilidade, o antivírus não emite opinião sobre o executável suspeito. A omissão indica que o arquivo investigado nunca foi avaliado pelo antivírus nem tem robustez para avaliá-lo em tempo real. A omissão do diagnóstico pelo antivírus aponta para sua limitação em serviços de grande porte.

Na terceira possibilidade, o antivírus não emite opinião sobre o executável suspeito. A omissão indica que o arquivo investigado nunca foi avaliado pelo antivírus nem tem robustez para avaliá-lo em tempo real. A omissão do diagnóstico pelo antivírus aponta para sua limitação em serviços de grande porte.

A Tabela 2 mostra os resultados dos 68 produtos antivírus avaliados. Apenas um desses antivírus obteve pontuação acima de 82,6%. Este antivírus é: ESET-NOD32. A detecção de malware indica que esses programas antivírus fornecem um serviço eficiente contra invasões cibernéticas.

Uma grande adversidade no combate a aplicativos maliciosos é o fato de os fabricantes de antivírus não compartilharem suas listas negras de malware devido a disputas comerciais. Por meio da análise da Tabela 2, o trabalho proposto aponta para um agravante dessa adversidade: o mesmo fornecedor de antivírus nem sequer compartilha seus bancos de dados entre seus diferentes programas antivírus. Observe, por exemplo, que os antivírus McAfee e McAfee-GW-Edition pertencem à mesma empresa. Suas listas negras, embora robustas, não são compartilhadas entre si. Portanto, as estratégias comerciais da mesma empresa dificultam o confronto com malware. Complementa que os fornecedores de antivírus não estão necessariamente preocupados em evitar invasões cibernéticas, mas em otimizar sua receita comercial.

A detecção de malware variou de 0% a 82,6%, dependendo do antivírus que está sendo investigado. Em média, os 68 antivírus foram capazes de detectar 46,08% das pragas virtuais avaliadas, com desvio padrão de 35,61. O alto desvio padrão indica que a detecção de executáveis ​​maliciosos pode sofrer variações abruptas dependendo do antivírus escolhido. Fica determinado que a proteção, contra invasões cibernéticas, se deve à escolha de um antivírus robusto com uma lista negra grande e atualizada.

Quanto aos falsos negativos, os antivírus Malwarebytes, Baidu e Panda, afirmaram erroneamente que o malware era benigno em mais de 95% dos casos. Em média, os antivírus atestaram falsos negativos em 44,85% dos casos, com desvio padrão de 36,26. Lidar com a benignidade do malware pode levar a danos irrecuperáveis. Uma pessoa ou instituição, por exemplo, confiaria em um determinado aplicativo malicioso quando, na verdade, é um malware.

As empresas de antivírus Invincea, CrowdStrike, eGambit e F-Prot dificilmente retiveram opiniões sobre qualquer uma das 1.000 amostras maliciosas. Portanto, cerca de 7,35% dos softwares antivírus não foram capazes de diagnosticar um número mínimo significativo de amostras maliciosas. Em média, os antivírus estavam ausentes em 8,92% dos casos, com desvio padrão de 25,76. A omissão do diagnóstico aponta para a limitação desses antivírus que possuem listas negras limitadas para detecção de malware em tempo real.

Inclui-se como adversidade, no combate às aplicações maliciosas, o fato dos antivírus comerciais não possuírem um padrão na classificação dos malwares como visto na Tabela 3. Escolhemos 3 de 1.000 amostras de malwares para exemplificar as classificações diversas de antivírus comerciais. Os malwares escolhidos são VirusShare_001627d61a1bde3478ca4965e738dc1e, VirusShare_075efef8c9ca2f675be296d5f56406fa e VirusShare_0dab86f850fd3dafc98d0f2b401377d5. Dessa forma, o tempo em que os fabricantes reagem a uma nova praga virtual é afetado drasticamente. Como não há um padrão, os antivírus dão os nomes que quiserem, por exemplo, uma empresa pode identificar um malware como "Trojan.Linux.Generic.69575" e uma segunda empresa o identifica como "ELF:DDoS-S [Trj] ". Portanto, a falta de um padrão, além do não compartilhamento de informações entre os fabricantes de antivírus, dificulta a detecção rápida e eficaz de um aplicativo malicioso.

###### Table 1 Results of 77 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
Alibaba |	99,45|	0,55|	0|
MicroWorld-eScan	|99,36|	0,64|	0|
Webroot	|99,36|	0,36|	0,27|
FireEye	|99,18|	0,18|	0,64|
Fortinet|	99,18|	0,73|	0,09|
MAX|	98,91|	0,64|	0,45|
BitDefender|	98,91|	0,91|	0,18|
Panda	98,45|	1,36|	0,18|
VIPRE|	98,36|	0,82|	0,82|
McAfee|	98,27|	0,45|	1,27|
Comodo|	98,27|	1,36|	0,36|
Microsoft|	98,18|	1|	0,82|
Emsisoft|	98|	0,91|	1,09|
GData|	97,91|	0,64|	1,46|
NANO-Antivirus|	97,73|	2,09|	0,18|
VBA32|	97,54|	2,27|	0,18|
Symantec	|97,27|	0,27|	2,46|
CrowdStrike	|97,27|	2,64|	0,09|
ESET-NOD32	|97,18|	2,73|	0,09|
Kaspersky	|97,18|	1,82|	1|
APEX|	97,09|	2,91|	0|
AVG|	96,72|	0,09|	3,18|
Jiangmin|	96,54|	3,28|	0,18|
Avast|	96,09|	2,37|	1,55|
SentinelOne|	95,91|	3,82|	0,27|
DrWeb|	95,27|	4,55|	0,18|
Rising|	95,18|	4,09|	0,73|
Tencent|	94,72|	4,91|	0,36|
TrendMicro-HouseCall|	93,9|	5,55|	0,55|
McAfee-GW-Edition	|93,18|	0,91|	5,91|
Sophos	|93,18|	1,73|	5,1|
ALYac	|92,9|	3,82|	3,28|
K7GW	92,63|	7,37|	0|
K7AntiVirus|	92,54|	7,28|	0,18|
AhnLab-V3|	92,54|	7,46|	0|
TrendMicro|	92,54|	6,1|	1,36|
Cylance	92,45|	3,82|	3,73|
Avira|	92,45|	7,46|	0,09|
Ad-Aware|	91,63|	3,91|	4,46|
Sangfor	|91,63|	2|	6,37|
Antiy-AVL|	90,81|	5,55|	3,64|
Zillya	|90,72	|6,28|	3|
Cynet	|90,35|	0,36|	9,28|
Elastic	|85,99|	4|	10,01|
Cyren	|85,9|	14,01|	0,09|
Yandex	|85,44	|14,56|	0|
Ikarus	|85,26|	7,01|	7,73|
Malwarebytes|	84,53|	15,1|	0,36|
Paloalto|	82,98|	16,92|	0,09|
Acronis|	82,89|	12,56|	4,55|
Lionic|	77,62|	19,38|	3|
Cybereason|	74,16|	0,36|	25,48|
BitDefenderTheta|	72,25|	24,39|	3,37|
MaxSecure|	70,79|	26,66|	2,55|
CAT-QuickHeal|	70,52|	29,21|	0,27|
SUPERAntiSpyware|	66,61|	33,39|	0|
ClamAV|	66,61|	30,03|	3,37|
Bkav|	63,42|	33,76|	2,82|
ZoneAlarm|	55,32|	40,22|	4,46|
VirIT|	55,23|	21,84|	22,93|
Kingsoft|	55,14|	43,86|	1|
ViRobot|	49,04|	50,96|	0|
Arcabit|	45,77|	49,77|	4,46|
TACHYON|	43,31|	56,69|	0|
Baidu|	40,58|	58,6|	0,82|
Gridinsoft|	37,4|	53,05|	9,55|
eGambit	30,03|	14,83|	55,14|
F-Secure|	10,56|	89,08|	0,36|
Qihoo-360|	9,83|	11,37|	78,8|
Invincea|	8,83|	0,45|	90,72|
Endgame|	7,46|	0,55|	91,99|
F-Prot|	6,19	1,73|	92,08|
Trapmine|	5,28|	2,09|	92,63|
Zoner	|2,82|	96,54|	0,64|
TotalDefense	|1,36|	7,1|	91,54|
CMC	|1	|98,73|	|0,27|
Avast-Mobile	|0	|8,1	|91,9|

###### Table 2 Miscellaneous classifications of commercial antiviruses:

Antivírus |	VirusShare_001627d61a1bde3478ca4965e738dc1e |	VirusShare_075efef8c9ca2f675be296d5f56406fa |	VirusShare_0dab86f850fd3dafc98d0f2b401377d5
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
ALYac|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
AVG|ELF:DDoS-S [Trj]|ELF:Gafgyt-DO [Trj]|ELF:DDoS-S [Trj]|
Acronis|Undetected|Undetected|Undetected| 
Ad-Aware|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
AhnLab-V3|Linux/Mirai.Gen6|Linux/Tsunami.Gen|Linux/Gafgyt.Gen|
Antiy-AVL|Trojan[Backdoor]/Linux.Gafgyt.a|GrayWare/Linux.Generic|Trojan[Backdoor]/Linux.Gafgyt.ac|
Arcabit|Trojan.Linux.Generic.D10FC7|Trojan.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.D11EEB|
Avast|ELF:DDoS-S [Trj]|ELF:Gafgyt-DO [Trj]|ELF:DDoS-S [Trj]|
Avast-Mobile|ELF:DDoS-S [Trj]|ELF:Tsunami-CR [Trj]|ELF:DDoS-S [Trj]|
Avira|LINUX/Gafgyt.opnd|LINUX/Tsunami.wkuvt|LINUX/Gafgyt.opnd|
Baidu|Undetected|Undetected|Undetected| 
BitDefender|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
BitDefenderTheta|Gen:NN.Mirai.34608|Gen:NN.Mirai.34608|Gen:NN.Mirai.34608|
Bkav|Undetected|Undetected|Undetected| 
CAT-QuickHeal|Undetected|Elf.Trojan.A1198970|Undetected| 
CMC|Undetected|Undetected|Undetected| 
ClamAV|Unix.Malware.Agent-6769357-0|Unix.Trojan.Mirai-5607483-0|Unix.Trojan.Gafgyt-111|
Comodo|Malware@#3o8smwc385jui|Malware@#3j0a9lm761bhc|Malware@#1vbephabp2pmb|
Cynet|Malicious (score: 85)|Malicious (score: 85)|Malicious (score: 85)|
Cyren|E32/Gafgyt.C.gen!Camelot|E32/Gafgyt.C.gen!Camelot|E32/Gafgyt.C.gen!Camelot|
DrWeb|Linux.BackDoor.Fgt.1755|Linux.BackDoor.Tsunami.485|Linux.BackDoor.Fgt.9|
ESET-NOD32|a variant of Linux/Mirai.AE|a variant of Linux/Tsunami.NBV|a variant of Linux/Gafgyt.C|
Emsisoft|Trojan.Linux.Generic.69575 (B)|Gen:Variant.Backdoor.Linux.Tsunami.1 (B)|Trojan.Linux.GenericA.73451 (B)
F-Secure|Malware.LINUX/Gafgyt.opnd|Malware.LINUX/Tsunami.wkuvt|Malware.LINUX/Gafgyt.opnd|
FireEye|Trojan.Linux.Generic.69575|Gen:Variant.Backdoor.Linux.Tsunami.1|Trojan.Linux.GenericA.73451|
Fortinet|ELF/Mirai.AE!tr|ELF/Tsunami.NDJ!tr|ELF/Gafgyt.UN!tr.bdr|
GData|Linux.Trojan.Gafgyt.A|Linux.Trojan.Gafgyt.A|Linux.Trojan.Gafgyt.B|
Gridinsoft|Undetected|Undetected|Undetected| 
Ikarus|Trojan.Linux.Mirai|Trojan.Linux.Fgt|Trojan.Linux.Fgt|
Jiangmin|Backdoor.Linux.cbip|Backdoor.Linux.ksj|Backdoor.Linux.gmy|
K7AntiVirus|Undetected|Undetected|Undetected| 
K7GW|Undetected|Undetected|Undetected| 
Kaspersky|HEUR:Backdoor.Linux.Gafgyt.a|HEUR:Backdoor.Linux.Tsunami.bh|HEUR:Backdoor.Linux.Gafgyt.ac|
Kingsoft|Undetected|Undetected|Undetected| 
Lionic|Trojan.Linux.Gafgyt.4!c|malware (ai score=99)|Undetected| 
MAX|malware (ai score=99)|Undetected|malware (ai score=98)
Malwarebytes|Undetected|Trojan.Malware.121218.susgen|Undetected| 
MaxSecure|Trojan.Malware.121218.susgen|Linux/Gafgyt.h|Trojan.Malware.121218.susgen|
McAfee|Linux/Mirai.g|Linux/Gafgyt.h|Linux/Gafgyt.r|
McAfee-GW-Edition|Linux/Mirai.g|Gen:Variant.Backdoor.Linux.Tsunami.1|Linux/Gafgyt.r|
MicroWorld-eScan|Trojan.Linux.Generic.69575|Backdoor:Linux/Gafgyt.AF!MTB|Trojan.Linux.GenericA.73451|
Microsoft|DDoS:Linux/Gafgyt.YA!MTB|Trojan.ElfArm32.Tsunami.ejtrus|Backdoor:Linux/Gafgyt.AF!MTB|
NANO-Antivirus|Trojan.ElfArm32.Mirai.fkvjsm|Undetected|Trojan.ElfArm32.Gafgyt.emzwvw|
Panda|Undetected|Linux/Backdoor.9d5|Undetected| 
Qihoo-360|Linux/Backdoor.812|Trojan.Gafgyt/Linux!1.A480 (CLASSIC)|Linux/Trojan.DDoS.adc|
Rising|Backdoor.Mirai/Linux!1.BAF6 (CLASSIC)|Undetected|Backdoor.Gafgyt/Linux!1.A512 (CLASSIC)|
SUPERAntiSpyware|Undetected|Undetected|Undetected| 
Sangfor|Undetected|Linux/Tsunami-A|Malware.ELF-Script.Save.07a8c2d7|
Sophos|Linux/DDoS-CIA|Trojan.Gen.NPE|Linux/DDoS-BI|
Symantec|Trojan.Gen.NPE|Undetected|Linux.Lightaidra|
TACHYON|Undetected|Backdoor.Linux.Gafgyt.ya|Undetected| 
Tencent|Backdoor.Linux.Gafgyt.ff|Undetected|Backdoor.Linux.Gafgyt.ym|
TotalDefense|Undetected|Backdoor.Linux.BASHLITE.SMJC|Undetected| 
TrendMicro|Backdoor.Linux.BASHLITE.SMJC|Backdoor.Linux.BASHLITE.SMJC|Backdoor.Linux.BASHLITE.SMJC|
TrendMicro-HouseCall|Backdoor.Linux.BASHLITE.SMJC|Undetected|Backdoor.Linux.BASHLITE.SMJC|
VBA32|Undetected|Undetected|Undetected| 
VIPRE|Undetected|Undetected|Undetected| 
ViRobot|Undetected|Undetected|Undetected| 
Yandex|Undetected|Backdoor.Tsunami.Linux.379|Undetected| 
Zillya|Backdoor.Mirai.Linux.38039|HEUR:Backdoor.Linux.Tsunami.bh|Undetected| 
ZoneAlarm|HEUR:Backdoor.Linux.Gafgyt.a|Undetected|HEUR:Backdoor.Linux.Gafgyt.ac|
Zoner|Undetected|Undetected|Undetected| 


## Metodos e Materiais

This paper proposes a database aiming at the classification of Android benign and malware executables. There are 1,000 malicious executables, and 1,000 other benign executables. Therefore, our datasaet is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

For the construction of a pattern recognition AI (artificial intelligence), the conventional method used for its training is the use of classes and counter classes of a certain filetype. The designation chosen to refer to the categories was "benign files" for serious and safe applications and "malignant files" for applications that can be a threat to the user. The malwares samples are executables files for ARM. The virtual plages were extracted from databases made avaiable by enthusiastic groups about the study of malwares through the digital plataform VirusShare. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The construction of the test environment for the experiment was performed using the free software emulator QEMU[https://www.qemu.org/]. Unlike other more popular virtualization solutions, such as VirtualBox[https://www.virtualbox.org/], the emulator is able to install operating systems, such as the IoT ARM and RISC-V architectures, on machines with divergent host processors , such as the desktop-oriented architectures. The guest system, 32-bit ARM architecture, was configured and the GNU/Linux Debian and Fedora distributions installed on it for compilation and obtaining samples for analysis in sandbox.

The benign samples were extracted from GNU/Linux Fedora for ARM architecture, on website official Fedora for linux devices. In addition, databases from others plataforms of benign executables were also used: GNU/Linux Debian for ARM and compiled samples. To avoid repeat the samples, were used authoral scripts coded in python. The script read the files fetched and delete its copies.


## Extração Dinamica de caracteristicas

The features of 32-bit ARM files originate through the dynamic analysis of suspicious files. Therefore, in our methodology, the malware is executed in order to infect, intentionally, the GNU/Linux audited, in real time (dynamic), by the Cuckoo Sandbox. In total, 2,793 features are generated of each 32-bit ARM file, regarding the monitoring of the suspect file in the proposed controlled environment. Next, the groups of features are detailed.

######	Features related to Code Injection, a technique used by an attacker to introduce code into vulnerable programs and change their behavior. The auditory checks whether the tested file try to:
-	execute a process and inject code while it is uncompressed;
-	injecting code into a remote process using one of the following functions: CreateRemoteThread or NtQueueApcThread.
	
######	Features related to Keyloggers, programs that record all user-entered keyboard entries, for the primary purpose of illegally capturing passwords and other confidential information. Checks whether the file being investigated tries to:
-	create mutexes of Ardamax or Jintor keyloggers.
	
######	Features related to the search for other possibly installed programs. The goal is to verify that the audited file searches for:
-	discover where the browser is installed, if there is one in the system.
-	discover if there is any sniffer or a installed network packet analyzer.

######	Features related to disable GNU/Linux components.

######	Features related to packing and obfuscation. The proposed digital forensic verifies if the suspect file:
-	has packet or encrypted information indicative of packing
-	creates a slightly modified copy of itself (polymorphic packing);
-	is compressed using UPX (Ultimate Packer for Executables) or VMProtect (software used in order to obfuscate code and virtualize programs).
-	
######	Features related to persistence, functionality of backup information in a system, without the need to register them before. Our Sandbox audit if suspicious file tries to:
-	create an ADS (Alternate Data Stream), NTFS feature that contains information to locate a specific file by author or title, used maliciously because as the information that is present in it does not change the characteristics of the file associated with it, transform them into an ideal option for building rootkits, because they are hidden (steganography);
-	install a self-executing in startup (autorun);
-	install a native executable to run at the beginning of GNU/Linux boot.

######	Features related to native GNU/Linux programs. It is audited, during its execution, if the suspicious file tries to:
-	allocate write and read memory for execution, usually for unpacking;
-	identify analysis tools installed by the location of the installation of said tool;
-	check for known devices or GNU/Linux from forensic tools and debuggers;
-	detect the presence of the Wine emulator;
-	install yourself on AppInit to inject into new processes;

######	Features related to GNU/Linux boot. Audit if suspicious file tries to:

-	modify boot configurations;
-	install a bootkit (malicious files for the purpose of changing and infecting the master boot record of the computer) through modifications to the hard disk;
-	create a executable file on the system;
-	create or configure registry with a long string of bytes, most likely to store a binary file or configure a malware;
-	create a service;
-	use the APIs to generate a cryptographic key;
-	erase your original disk binary;
-	load a device driver;
-	release and execute a binary file;
-	remove evidence that a file has been downloaded from the Internet without the user being aware of it;
-	create files related to Fakerean Fraudtool malware;
-	connect to an IP BitTorrent Bleepchat (encrypted chat service and P2P from BitTorrent);
-	connect to IP's related to Chinese instant messaging services, such as QQ, used by hackers maliciously;
-	access Bitcoin/ALTCoin portfolios, which can be used to transfer funds into illegal transactions.

######	Features that seek to disable features of GNU/Linux and other utilities. The audit checks to see if the file can:

-	modify system policies to prevent the launch of specific applications or executables;
-	disable browser security warnings;
-	disable GNU/Linux security features and properties;
-	disable google SPDY network protocol support in Mozilla Firefox browsers to increase the ability of an internet malware to gain access to sensitive information;
-	disable system restore;

######	Features related to executable files. The proposed digital forensic verifies that the suspect file tries to:

-	use the BITSAdmin tool (command line tool originally used to download and upload files, as well as track the progress of this transfer, but which malicious hackers use) to download any file;
-	halt at least one process during its execution;
-	execute the WaitFor statement (it has originally the function of synchronizing events between networked computers, but which evildoers use in harmful ways), possibly to synchronize malicious activities.

######	Features related to memory dump, process in which the contents of RAM memory is copied for diagnostic purposes. The proposed digital forensics audits if the application tries to:
-	find malicious URL’s in memory dump processing;
-	find evidence of the presence and use of the yara program, used to perform memory dump's.

######	Features related to crypto-coin mining:
-	It is audited if the suspect application tries to connect to mining pools, the goal is to generate virtual currencies without the cognition (and not benefiting) the computer owner.

######	Features related to system modifications:
-	It is audited if the suspect application tries to create or modify system certificates, security center warnings, user account control behaviors, desktop wallpaper, or ZoneTransfer.ZoneID values in the ADS(Alternate Data Stream).

######	Feature related to POS (point of sale), type of attack that aims to obtain the information of credit and debit cards of victims. It is investigated if the audited file tries to:
-	create files related to malware POS Alina;
-	contact servers related to malware POS Alina;
-	contact botnets related to malware POS blackpos;
-	create mutexes related to malware POS decebel;
-	create mutexes and registry keys related to POS Dexter malware;
-	create mutexes and registry keys related to malware POS jackpos;
-	contact botnets related to malware POS jackpos;
-	contact servers related to POS poscardstealer malware.

######	Features related to shell code injectors. Our Sandbox checks if the tested file:
-	is a shell malware of powerfun type;
-	is a shell malware powerworm type;
-	attempts to create a suspicious shell process;
-	attempts to create log entries via shell scripts.

######	Features related to processes. Checks if the tested file:
-	is interested in some specific process in execution;
-	repeatedly searches for a process not found;
-	tries to fail some process.

######	Features related to ransomwares, cyber-attacks that turn the computer data inaccessible, requiring payment in order to restore the user access. Our Sandbox verifies that the audited server tries to:
-	create mutexes of ransomware named chanitor;
-	execute commands in bcdedit (command-line tool that manages boot configuration data) related to ransomware;
-	add extensions of files known to be ransomwares related to files that have been encrypted;
-	perform drives on files, which may be indicative of the data encryption process seen in an ransomware attack;
-	create instructions on how to reverse encryption made in an ransomware attack or attempt to generate a key file;
-	write a rescue message to disk, probably associated with an ransomware attack;
-	empty the trash;
-	remove or disable shadow copy, which is intended to speed up data restoration in order to avoid system recovery.

######	Features related to the use of sandboxes. The digital forensics examines if the tested file tries to:
-	detect if the sandboxes: Cuckoo, Joe, Anubis, Sunbelt, ThreatTrack/GFI/CW or Fortinet are being used, through the presence of own files used by them;
-	search for known directories where a sandbox can run samples;
-	check if any human activity is being performed;
-	install a procedure that monitors mouse events;
-	disconnect or restart the system to bypass the sandbox;
-	delay analysis tasks;
-	shut down GNU/Linux functions monitored by the cuckoo sandbox.

######	Features related to Trojans (malicious program that enters a computer masked as another program, legitimate) of remote access, or RAT (Remote Access Trojans). Our Sandbox verifies if the tested server tries to create files, registry keys, and/or mutexes related to RATs: 
- Adzok, bandook, beastdoor, beebus, bifrose, blackhole/schwarzesonne, blackice, blackshades, bladabindi, bottilda, bozokrat, buzus, comrat, cybergate, darkcloud, darkshell, delf trojan, dibik/shark, evilbot, farfli, fexel, flystudio, fynloski/darkcomet, ghostbot, hesperbot, hkit backdoor, hupigon, icepoint, jewdo backdoor, jorik trojan, karakum/saharabot, koutodoor, aspxor/kuluoz, likseput, madness, madness, magania, minerbot, mybot, naid backdoor, nakbot, netobserve spyware, netshadow, netwire, nitol/servstart, njrat, pasta trojan, pcclient, plugx, poebot/zorenium, poison ivy, pincav/qakbot, rbot, renos trojan, sadbot, senna spy, shadowbot, siggen, spynet, spyrecorder, staser, swrort, travnet, tr0gbot bifrose, turkojan, urlspy, urx botnet, vertexnet, wakbot, xtreme, zegost.

######	Features related to the banking threats (Trojan horses):

-	Find out if the test file tries to create registry keys, Mutexes or Trojan files, and/or try to contact HTTP servers of the known threats. Banking Banking, Banking, Prinyalka Banking, SpyEye, Tinba Banking, Zeus, Zeus P2P, Dridex, Emotet and Online Banking.

######	Features related to payload in network. Checks if the server tested tries to:
-	verify if the network activity contains more than one unique useragent;
-	create Remote Desktop Connection Protocol (RDP) mutexes;
-	check the presence of mIRC chat clients;
-	install Tor (the onion router, open source software with the ability to securely and anonymously create online connections in order to safeguard the user's right to privacy), or a hidden Tor service on the machine;
-	connect to a Chinese URL shorter with malicious history;
-	create mutexes related to remote administration tools VNC (Virtual Remote Computer).

######	Features associated with network traffic hint GNU/Linux 7 OS in PCAP format. Audit if suspicious document attempts to:
-	connect with an IP which is not responding to requests;
-	resolve a suspicious top domain;
-	start listening (socket) with some server;
-	connect to some dynamic DNS domain;
-	make HTTP requests;
-	generate ICMP traffic;
-	connect to some IRC server (possibly part of some BotNet);
-	make SMTP requests (possibly sending SPAM);
-	connect to some hidden TOR service through a TOR gateway;
-	generate IDS or IPS alerts with Snort and Suricata (network monitoring and management tools).

######	Features related to DNS servers (Domain Name System, servers responsible for the translation of URL addresses in IP). It is investigated the audited file tries to:
-	connect to DNS servers of dynamic DNS providers;
-	connect to the expired malicious site 3322.org, or its related domain, 125.77.199.30;
-	resolve some Free Hosting domain, possibly malicious.

######	Features related to file type.

-	It is audited if the suspect server the suspect file is a SSH, Telnet, SCP and / or FTP-style FTP client with its files, registry keys and mutexes;
-	It is investigated whether the suspect file is a suspect downloader (download manager);
-	It is investigated if the file has in it a path to a pdb extension file, which contains information given directly to the system compiler.

######	Features related to malware. Checks whether the audited file tries to:

-	create Mutexes (single name files, with a function to set a lock / unlock state, which ensures that only one process at a time uses the resources);
-	create Advanced Persistent Threat (APT) files, or connect to IP addresses and URLs of known threats: Carbunak/Anunak, CloudAtlas, Flame, Inception, Panda Putter, Sandworm, Turla Carbon and Turla/Uroboros.

######	Features related to Backdoors:

-	It is audited if the suspect file tries to create Backdoor files, registry keys or Mutexes of the known threats LolBot, SDBot, TDSS, Vanbot and Schwarzesonne.

######	Features related to bots (machines that perform automatic network tasks, malicious or not, without the knowledge of their owners):

-	It is audited if the suspect file tries to contact HTTP servers and / or tries to create Mutexes associated with Athena, Beta, DirtJumper, Drive2, Kelihos, Kotver, Madness, Pony, Ruskill, Solar, VNLoader, and Warbot Bots.

######	Features related to browsers. Checks if the suspect file tries to:

-	install a Browser Helper object (usually a DLL file that adds new functions to the browser) in order to let the navigation experience be impaired in some way;
-	modify browser security settings;
-	modify the browser home page;
-	acquire private information from locally installed internet browsers.

######	Features related to Bitcoin:

-	It is examined if the suspect file attempts to install the OpenCL library, Bitcoins mining tool.

######	Features related to Ransomware (type of malware that by means of encryption, leaves the victim's files unusable, then request a redemption in exchange for the normal use later of the user's files, a redemption usually paid in a non-traceable way, such as bitcoins) .

-	It is monitored if the suspect file tries to show, generate, or is an hta file (HTML Application), common extension type in situations involving ransomware.

######	Features related to exploit-related features which constitute malware attempting to exploit known or unackaged vulnerabilities, faults or defects in the system or one or more of its components in order to cause unforeseen instabilities and behavior on both your hardware and in your software. The proposed digital forensic verifies whether the audited file attempts to:

-	contact the HTTP server of the Blackhole Exploit Kit (a threat that had its peak of performance in 2012, aims to download malicious content on the victim's computer);
-	create mutexes of the Sweet Orange EK exploit;
-	create mutexes from other known exploits;
-	use the technique known as heapspray, where memory is completely filled, causing the computer to experience crashes.

######	Features related to Infostealers, malicious programs that collect confidential information from the affected computer. Digital forensics checks if suspicious file tries to:

-	create files related to infostealer Derusbi;
-	collect credentials and software information from locally installed FTP clients;
-	collect information and credentials related to locally installed Instant Messenger clients;
-	create a program that monitors keyboard inputs (possibly a keylogger);
-	collect credentials and information from locally installed e-mail clients.


######	Features related to virtual machines. The goal is to verify that the audited file searches for:

-	detect whether Bochs, Sandboxie, VirtualBox, VirtualPC, VMware, Xen or Parallels virtual machines are being used through the presence of registry keys (regedit), files, instructions, and device drivers used by them;
-	find the computer name;
-	find the disk size and other information about the disk, which may indicate the use of a virtual machine with small and fixed disk size, or dynamic allocation;
-	discover the BIOS version, which may indicate virtualization;
-	discover the CPU name in the registry, which may indicate virtualization;
-	detect a virtual machine through the firmware;
-	detect the presence of IDE drives in the registry, which may indicate virtualization;
-	detect the presence of SCSI disks;
-	enumerate services, which may indicate virtualization;
-	detect Hyper-V through registry keys (regedit);
-	check the amount of memory in the system in order to detect virtual machines with little available memory;
-	check adapter addresses that can be used to detect virtual network interfaces;
-	detect a virtual machine by using pseudo devices (parts of the kernel that act as device drivers but do not actually match any hardware present on the machine);
-	detect whether it is running in a GNU/Linux, indicative of VirtualBox usage.

######	Features related to Firewall. The proposed digital forensics audits if the file tries to:

-	modify local firewall policies and settings.

######	Features related to cloud computing. The file is audited when you try to:

-	connect to storage services and / or files from Dropbox, Google, MediaFire, MegaUpload, RapidShare, Cloudflare and Wetransfer.

######	Features related to DDoS (Dynamic Danial of Service) attacks:

-	It is audited if the suspect file create mutexes, other files and bots known as DDoS of the IPKiller, Dark-DDoS, Eclipse and Blackrev types.

######	Features related to Infostealers, malicious programs that collect confidential information from the affected computer. Digital forensics checks if suspicious file tries to:

-	create files related to infostealer Derusbi;
-	collect credentials and software information from locally installed FTP clients;
-	collect information and credentials related to locally installed Instant Messenger clients;
-	create a program that monitors keyboard inputs (possibly a keylogger);
-	collect credentials and information from locally installed e-mail clients.
