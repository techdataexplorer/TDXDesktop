Examples

George Kizer
27 Feb 2021

These Examples refer to examples contained in the following folders:

<Step 1 Distance Programs>

<Step 2 Profile Programs>

<Step 3 Path Availability>

Step 1

Place a copy of <ExampleS1> in the root directory (C:\ExampleS1)

Launch <HowFarB.exe>.
Enter the following:
	ExampleS1
	221
	n
View the results as <Output.csv>.

Compare results with <ExampleStep1>.

 
Step 2A

Place a copy of <ExampleS2A> in the root directory (C:\ExampleS2A)

Launch <1 AllPathA.exe>.
Enter the following:
	c
	ExampleS2A
	sites
	y
	n
	30
	m
View the results as <Paths1.CSV>.

Launch <2 ScriptA.exe>.
Enter the following:
	c
	ExampleS2A
	E (or whatever is the drive letter of the USB hard disk with the terrain data)
	1
	y
	y
View the results as <GMscript.gms> and <Maps.csv>.

Use Global Mapper to run the <GMscript.gms> script.
The results are the P00000X.csv profiles in the TempFile folder.
If Global Mapper is not available, copy those profiles from <ExampleStep2A> into the TempFile folder.

Launch <3 PathsA.exe>.
Enter the following:
	c
	ExampleS2A
	y
	1
The results are the PA00000X.csv, PB00000X.csv and PC00000X.csv profiles in the TempFile folder.

Launch <4 GudPathA.exe>.
Enter the following:
	c
	ExampleS2A
	y
	1
	y
View the results in the <Passed>, <Optimize> and <Failed> folders.

Launch <5 ProfileA.exe>.
Enter the following:
	c
	ExampleS2A
The results are in <ProfPass>, <ProfOpt> and <ProfFail>.

Go into each folder and double click on <Plot.CMD>.
After the profiles are created, double click on <CleanUp.CMD>.
After the files are cleared, delete <Plot.CMD> and <CleanUp.CMD>.
View the profiles PR00000X.png in the folders.

Launch <6 KML3DA.exe>.
Enter the following:
	c
	ExampleS2A
	Paths1
	3
	2
	y
	y
	n
The result is <Paths1.KML>.

Compare results with <ExampleStep2A>.

/home/alan/miniconda3/bin/python
/home/alan/miniconda3/bin/python  
Step 2B

Place a copy of <ExampleS2B> in the root directory (C:\ExampleS2A)

Launch <1 AllPathA.exe>.
Enter the following:
	c
	ExampleS2B
	sites
	y
	n
	30
	m
View the results as <Paths1.CSV>.

Launch <2 ScriptA.exe>.
Enter the following:
	c
	ExampleS2B
	E (or whatever is the drive letter of the USB hard disk with the terrain data)
	1
	y
	y
View the results as <GMscript.gms> and <Maps.csv>.

Use Global Mapper to run the <GMscript.gms> script.
The results are the P00000X.csv profiles in the TempFile folder.
If Global Mapper is not available, copy those profiles from <ExampleStep2A> into the TempFile folder.

Launch <3 PathsA.exe>.
Enter the following:
	c
	ExampleS2B
	y
	2
	0.01
The results are the PA00000X.csv, PB00000X.csv and PC00000X.csv profiles in the TempFile folder.

Launch <4 GudPathA.exe>.
Enter the following:
	c
	ExampleS2B
	y
	1
	y
View the results in the <Passed>, <Optimize> and <Failed> folders.

Launch <5 ProfileA.exe>.
Enter the following:
	c
	ExampleS2B
The results are in <ProfPass>, <ProfOpt> and <ProfFail>.

Go into each folder and double click on <Plot.CMD>.
After the profiles are created, double click on <CleanUp.CMD>.
After the files are cleared, delete <Plot.CMD> and <CleanUp.CMD>.
View the profiles PR00000X.png in the folders.

Launch <6 KML3DA.exe>.
Enter the following:
	c
	ExampleS2B
	Paths1
	3
	2
	y
	y
	n
The result is <Paths1.KML>.

Compare results with <ExampleStep2B>.

 
Step 3

Place a copy of <ExampleS3> in the root directory (C:\ExampleS3)

Launch <1 Profile Script A.exe>.
Enter the following:
	c
	ExampleS3
	E (or whatever is the drive letter of the USB hard disk with the terrain data)
	1
View the results as <GMscript.gms> and <Maps.csv>.

Use Global Mapper to run the <GMscript.gms> script.
The results are the P00000X.csv profiles in the Profiles folder.
If Global Mapper is not available, copy those profiles from <ExampleStep3> into the TempFile folder.

Launch <2 Roughness A.exe>.
Enter the following:
	c
	ExampleS3
	6
See the results Roughness00000X.CSV in the Profiles folder.

Launch <3 Parameter B.exe>.
Enter the following:
	c
	ExampleS3
View the results in <Data\PathParameters.csv>.

Launch <4 Data A.exe>.
Enter the following:
	c
	ExampleS3
View the results in <Data\PathDataPass2.csv>.

Launch <5 Performance A.exe>.
Enter the following:
	c
	ExampleS3
View the results in <Data\PathDataPass3.csv>.

Launch <6 Final Report A.exe> Enter the following:
	c
	ExampleS3
View the results in <Data\Report.rtf>.  Open in MS Word and format as desired.

Compare results with <ExampleStep3>.


# TDXDesktop
