# step-analyzer
Read the hierarchical assembly structure of a STEP file
Sample output:
Assembly structure of file: step/as1-oc-214.stp

1	as1 [0:1:1:1]	Number of labels at root = 9
2		rod-assembly_1 [0:1:1:1:1] => rod-assembly [0:1:1:2]
3			nut_1 [0:1:1:2:1] => nut [0:1:1:3]
4			nut_2 [0:1:1:2:2] => nut [0:1:1:3]
5			rod_1 [0:1:1:2:3] => rod [0:1:1:4]
6		l-bracket-assembly_1 [0:1:1:1:2] => l-bracket-assembly [0:1:1:5]
7			nut-bolt-assembly_1 [0:1:1:5:1] => nut-bolt-assembly [0:1:1:6]
8				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
9				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
10			nut-bolt-assembly_2 [0:1:1:5:2] => nut-bolt-assembly [0:1:1:6]
11				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
12				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
13			nut-bolt-assembly_3 [0:1:1:5:3] => nut-bolt-assembly [0:1:1:6]
14				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
15				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
16			l-bracket_1 [0:1:1:5:4] => l-bracket [0:1:1:8]
17		plate_1 [0:1:1:1:3] => plate [0:1:1:9]
18		l-bracket-assembly_2 [0:1:1:1:4] => l-bracket-assembly [0:1:1:5]
19			nut-bolt-assembly_1 [0:1:1:5:1] => nut-bolt-assembly [0:1:1:6]
20				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
21				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
22			nut-bolt-assembly_2 [0:1:1:5:2] => nut-bolt-assembly [0:1:1:6]
23				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
24				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
25			nut-bolt-assembly_3 [0:1:1:5:3] => nut-bolt-assembly [0:1:1:6]
26				bolt_1 [0:1:1:6:1] => bolt [0:1:1:7]
27				nut_3 [0:1:1:6:2] => nut [0:1:1:3]
28			l-bracket_1 [0:1:1:5:4] => l-bracket [0:1:1:8]
