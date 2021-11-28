# Project_WorK
# project_task-
Hello,This is my repository.My self Sameer Munnavvar.pursuing my BE final year.
For my final year project .I started exploring the tools,by a few basic programs.which are below following.
Before we proceed do install:

1.icarus verilog (for windows download link:https://bleyer.org/icarus/ ).


Icarus Verilog is a free compiler implementation for the IEEE-1364 Verilog hardware description language. Icarus is maintained by Stephen Williams and it is released under the GNU GPL license.

In this page you will find easy to install Icarus Verilog packages compiled with the MinGW toolchain for the Windows environment. GTKWave for Win32 is also included in the latest releases. The installers have been created with Jordan Rusell's Inno Setup free installer utility.

2.vscode download link-https://code.visualstudio.com/download (also extentions i.Verilog-HDL/SystemVerilog/Bluespec SystemVerilog and ii.Graphviz Preview).


<p align="justify"> Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).</p> 

**1.HALF ADDER (combinational circuit)**

Steps to be followed to execute the above program.
=
 ![image](https://user-images.githubusercontent.com/93427617/140308328-bb34eda3-899b-4f86-8674-454ff5a54d1e.png)
**STEP1**:Click on the mark icon,Then make a new folder by naming it.

Again beside the mark icon click on it,
follow the same procedure to make new subfolders.

![image](https://user-images.githubusercontent.com/93427617/140309432-34269ade-2cb6-492b-bc46-bc6a6f3e80a8.png)

**STEP2**:Write the verilog program in the blank feild and Save it by pressing ctrl+s.
![image](https://user-images.githubusercontent.com/93427617/140310138-5425983c-7e51-4512-bef3-3e902208d5bf.png)

**STEP3**:Go to another sub-folder,write testbench for the above verilog program written.

![image](https://user-images.githubusercontent.com/93427617/140311791-fa2263c8-bcac-436a-88ec-931893d07749.png)

**STEP4**:Write the shown command,to be in working file.
Command syntax={cd  tabfoldername.v}

![image](https://user-images.githubusercontent.com/93427617/140312317-b491f1a1-be15-4d25-bad9-d19c16d3c32b.png)

**STEP5**:command written is for to check sub-folders

![image](https://user-images.githubusercontent.com/93427617/140312651-72ae04e6-e77f-44aa-b492-d731a33262aa.png)

**STEP6**:Further,to check for the codes to be errorfree.use the shown command.
By successful errorfree codes a file gets generated as (a.out).

command syntax={iverilog tabverilogcodesubfoldername.v tabtestbenchsubfolder.v}

![image](https://user-images.githubusercontent.com/93427617/140315939-dc2712ff-6d61-46a8-9063-90d137ea40ac.png)

**STEP7**:To run the simulation,have the following command

command syntax={vvp taba}

A new file will genterated with the processingfoldername.vcd.


![image](https://user-images.githubusercontent.com/93427617/141677602-8915961b-b495-486e-a42d-ff496c819a55.png)

**STEP8**: Now,to generate the waveform Enter the command (gtkwave tabprocessingfoldername.vcd).


Analyse,the result using waveform.


![image](https://user-images.githubusercontent.com/93427617/141677722-ea731862-5e9a-4fc5-bf1c-aa91fe7f3fe8.png)


**STEP9**:Attach the cmos (program) lib file or liberty file in the proccessing folder.

![image](https://user-images.githubusercontent.com/93427617/140318600-a296ef7f-61c1-427f-96af-a00ba94b7caf.png)

**STEP10**:Now,go to yosys.by giving the command {yosys}

![image](https://user-images.githubusercontent.com/93427617/140319345-036836c3-6ed0-44cd-8198-052c1b26fa50.png)

**STEP11**:To read the liberty file,Enter the command shown in demonstration image.

![image](https://user-images.githubusercontent.com/93427617/140320195-0685c449-3bfd-47e1-a505-00522e0aa587.png)

**STEP12**:For executing verilog frontend.
Enter read_verilog (processingfilename.v).

![image](https://user-images.githubusercontent.com/93427617/140320757-e8142913-c9c1-463a-8526-62b3c0695db0.png)

**STEP13**:To synthesize ,Enter synth -top modulename

![image](https://user-images.githubusercontent.com/93427617/140321225-bb62b1d7-53fc-4ef4-8147-c8664f03b4c0.png)

=>To execute ,Enter the shown command in demonstration image.

![image](https://user-images.githubusercontent.com/93427617/140321759-82259eaa-aa06-435c-a778-fb0f5aa3e1e0.png)

=>To genrate the show.dot file.Enter the command (show modulename).

![image](https://user-images.githubusercontent.com/93427617/140322599-fce3cf23-a6ed-43b5-bf7b-4c7ca7350dca.png)

After,successful generation of show.dot file 

Then click on show.dot file 

Go,to view  from the following list in view select (command palette) or PRESS ctrl+Shift+P.Furthere enter or select Graphviz:open preview to the slide.

![image](https://user-images.githubusercontent.com/93427617/140324132-a0393f06-57db-4f96-b131-ee09eb2a7f38.png)

Finally,Successful generation of output or preview to the slide.

**Lets,do the other program using skylibertyfile**
=

**2.D FLIP FLOP (SEQUENTIAL CIRCUIT)**

**steps to be followed same as previous a few steps differ.lets divide the procedure in 2 PARTS.**

**PART1**
=

**STEP1**:Download the files using https://drive.google.com/drive/folders/1CQvbm9vSEIKuPZCqJT04rVpkR61yKr-a

**STEP2**:![image](https://user-images.githubusercontent.com/93427617/140597247-36840016-3f75-4cae-aece-f947cab25e50.png)

From the downloaded files copy this files into a seprate file,by doing so our process gets hands down..!!

**STEP3**:
 ![image](https://user-images.githubusercontent.com/93427617/140308328-bb34eda3-899b-4f86-8674-454ff5a54d1e.png)

Click on the mark icon,Then make a new folder by naming it.Again beside the mark icon click on it, follow the same procedure to make new subfolders.

**STEP4**:


![image](https://user-images.githubusercontent.com/93427617/140597403-df40bc86-a66a-47fa-a2d9-029a62d47e4b.png)

Write the verilog program in the blank feild.and save it by PRESSING CTRL+S


**STEP5**:


![image](https://user-images.githubusercontent.com/93427617/140597452-d2853e0a-a427-4f13-af02-e670fa1cfc85.png)

write test bench for verilog program and save it 

**STEP6**:


![image](https://user-images.githubusercontent.com/93427617/141644129-9c275b8d-c717-4b6a-b4dd-73908eb4af0b.png)


Enter the given shown command to have errorfree codes,which is most important to moveon.

**STEP7**:


![image](https://user-images.githubusercontent.com/93427617/141644481-e633c5cc-df7f-4178-9d4a-cb3082b6c169.png)

Run Simulation . which gives out a new file  with the processingfoldername.vcd.

**STEP8**


Type command gtkwave"tab"filename.vcd 
which produce..


![image](https://user-images.githubusercontent.com/93427617/141677663-ccdbbea7-5c72-478c-9d6b-f4cfbab869d6.png)


**Now,we go to "denouement"**

**PART2**
=

**STEP1**:

![image](https://user-images.githubusercontent.com/93427617/141645006-2c2f8367-1eaa-4447-8439-63b91666c0fb.png)


In terminal,type yosys to move in yosys tools.

**STEP2**:


![image](https://user-images.githubusercontent.com/93427617/141645123-01b87ae9-dd3f-40c5-885b-b595333c36ae.png)

TO read liberty file enter :read_liberty -lib sky130_fd_sc_hd__tt_025C_1v80.lib

**STEP3**:

![image](https://user-images.githubusercontent.com/93427617/141645264-bad56e0d-5f7f-40f3-921e-8ff5c3d1f6e7.png)

commmand for raeding module :read_verilog filename.v

**STEP4**:

![image](https://user-images.githubusercontent.com/93427617/141645429-18d53c23-3e5d-4bb2-a9fc-940ec291daf5.png)

synthesis the work by the following command : synth -top modulename

**STEP5**:

![image](https://user-images.githubusercontent.com/93427617/141645532-90f5d448-9d28-45a7-8802-c385347621e5.png)

For mapping Dflip-flops to library use following command : dfflibmap -liberty sky130_fd_sc_hd__tt_025C_1v80.lib

**STEP6**:


![image](https://user-images.githubusercontent.com/93427617/141645606-9f5c076a-428d-49bb-97de-7d4f77d332d8.png)

For mapping logic to library file use following command : abc -liberty sky130_fd_sc_hd__tt_025C_1v80.lib

**STEP7**:


![image](https://user-images.githubusercontent.com/93427617/141645704-0591a078-8ce5-4aae-93ed-b0e4337c9bb5.png)

type show in terminal to access show.dot.

**STEP8**:


![image](https://user-images.githubusercontent.com/93427617/141677491-05d06f65-9ddd-43cf-a09d-00c647a25cad.png)



This the preview of graphviz.

**STEP9**:

![image](https://user-images.githubusercontent.com/93427617/141646093-7226ed6a-138b-465b-965a-e1b770dea466.png)

now using following command  tee -o report.txt stat -liberty sky130_fd_sc_hd__tt_025C_1v80.lib extract report file.

**STEP10**:


![image](https://user-images.githubusercontent.com/93427617/141646154-f9c666e6-5ec4-4524-9abb-efc077bfc2b6.png)

Use the following code shown in demonstration pic to get netlist.v file.

**STEP11**:


![image](https://user-images.githubusercontent.com/93427617/141646238-ffd98a8c-645a-431d-87d8-78b045cc29d9.png)

Now in terminal type exit to move out from yosys tools.

**STEP12**:


![image](https://user-images.githubusercontent.com/93427617/141646467-87607511-f931-438f-a782-ba5075156e98.png)


![image](https://user-images.githubusercontent.com/93427617/141646488-93ab833a-2697-460d-a257-a2b9bc22a90d.png)


After successfull extraction of required files.
we can check for information from each file report.txt file shows the statistical data of the design made and netlist.v file shows the all the detailed information which requred to make a intigrated Circuit. This is the file we give to foundry for making a physical copy.

**STEP13**:


![image](https://user-images.githubusercontent.com/93427617/141651822-54d725ec-31d4-4a7c-acab-6c8c181daca9.png)

By shown command ensure to be error free.




































