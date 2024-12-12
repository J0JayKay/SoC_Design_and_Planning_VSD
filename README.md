<h1> Digital VLSI SoC Design and Planning by VSD </h1>
<h2> Introduction </h2>

This is my repo for the VSD course [Digital VLSI SoC Design](https://vsdsquadron.vlsisystemdesign.com/digital-vlsi-soc-design-and-planning/) on PnR using OpenLANE and SkyWater PDK. The course covers floorplanning and standard cell design, designing and characterizing a library cell, pre-layout timing analysis and clock tree synthesis, all using opensource tools for the SkyWater 130nm process. This repo will contain the notes I take, and the screenshots and the files generated while doing the tasks assigned, both for my own and for anyone else's reference.

<details>
<summary> <h3>Notes</h3> </summary>
  
</details>

<details>
<summary> <h3>Labs</h3> </summary>
<details>
<summary> <h4>Section 1</h4> </summary>

1. The directory containing OpenLANE is cd'ed to, using the command: 

```bash
cd ~/Desktop/work/tools/openlane_working_dir/openlane
```

2. The script to enter the interactive shell of the docker container containing openLANE has been aliased to the alias given below. This has to be run next:

```
docker
```

3. Now that we have entered the shell of the container, we run openLANE. OpenLANE can be run in two modes: autonomous or interactive. we run openLANE flow in interactive mode by running the script:

```
./flow.tcl -interactive
```
  This opens a tcl shell that accepts tcl commands.

4. Required package is loaded with the tcl command:

```tcl
package require openlane 0.9
```
</details>

</details>


