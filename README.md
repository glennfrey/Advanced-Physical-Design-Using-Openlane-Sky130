# Advanced Physical Design using Openlane Sky130
![](advanced_physical_design.png)
### ABOUT THE WORKSHOP
The Workshop is a 5-day basic to advance program that is design for fresher who wants to build a career in VLSI industry. It is a cloud based workshop that comprises of training courses that covers RTL to GDS topics, labs, intelligent assessment program, and documentation to be presented in github which may serve as a resume.
### AUTHOR OF THE WORKSHOP
#### Mr. Kunal Ghosh
Co-founder of VLSI System Design (VSD) Corporation Private Limited
### AGENDA
  - ##### Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
    - SKY130_D1_SK1 - How to talk to computers
      - SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs
      - SKY_L2 - Introduction to RISC-V
      - SKY_L3 - From Software Applications to Hardware
    - SKY130_D1_SK2 - SoC design and OpenLANE
      - SKY_L1 - Introduction to all components of open-source digital asic design
      - SKY_L2 - Simplified RTL2GDS flow
      - SKY_L3 - Introduction to OpenLANE and Strive chipsets
      - SKY_L4 - Introduction to OpenLANE detailed ASIC design flow
    - SKY130_D1_SK3 - Get familiar to open-source EDA tools
      - SKY_L1 - OpenLANE Directory structure in detail
      - SKY_L2 - Design Preparation Step
      - SKY_L3 - Review files after design prep and run synthesis
      - SKY_L4 - OpenLANE Project Git Link Description
      - SKY_L5 - Steps to characterize synthesis results
 - ##### Sky130 Day 2 - Good floorplan vs bad floorplan and introduction to library cells
    - SKY130_D2_SK1 - Chip Floor planning considerations
      - SKY_L1 - Utilization factor and aspect ratio
      - SKY_L2 - Concept of pre-placed cells
      - SKY_L3 - De-coupling capacitors
      - SKY_L4 - Power planning
      - SKY_L5 - Pin placement and logical cell placement blockage
      - SKY_L6 - Steps to run floorplan using OpenLANE
      - SKY_L7 - Review floorplan files and steps to view floorplan
      - SKY_L8 - Review floorplan layout in Magic
    - SKY130_D2_SK2 - Library Binding and Placement
      - SKY_L1 - Netlist binding and initial place design
      - SKY_L2 - Optimize placement using estimated wire-length and capacitance
      - SKY_L3 - Final placement optimization
      - SKY_L4 - Need for libraries and characterization
      - SKY_L5 - Congestion aware placement using RePlAce
    - SKY130_D2_SK3 - Cell design and characterization flows
      - SKY_L1 - Inputs for cell design flow
      - SKY_L2 - Circuit design step
      - SKY_L3 - Layout design step
      - SKY_L4 - Typical characterization flow
    - SKY130_D2_SK4 - General timing characterization parameters
      - SKY_L1 - Timing threshold definitions
      - SKY_L2 - Propagation delay and transition time
 - ##### Sky130 Day 3 - Design library cell using Magic Layout and ngspice characterization
    - SKY130_D3_SK1 - Labs for CMOS inverter ngspice simulations
      - SKY_L0 - IO placer revision
      - SKY_L1 - SPICE deck creation for CMOS inverter
      - SKY_L2 - SPICE simulation lab for CMOS inverter
      - SKY_L3 - Switching Threshold Vm
      - SKY_L4 - Static and dynamic simulation of CMOS inverter
      - SKY_L5 - Lab steps to git clone vsdstdcelldesign
    - SKY130_D3_SK2 - Inception of Layout  CMOS fabrication process
      - SKY_L1 - Create Active regions
      - SKY_L2 - Formation of N-well and P-well
      - SKY_L3 - Formation of gate terminal
      - SKY_L4 - Lightly doped drain (LDD) formation
      - SKY_L5 - Source  drain formation
      - SKY_L6 - Local interconnect formation
      - SKY_L7 - Higher level metal formation
      - SKY_L8 - Lab introduction to Sky130 basic layers layout and LEF using inverter
      - SKY_L9 - Lab steps to create std cell layout and extract spice netlist
    - SKY130_D3_SK3 - Sky130 Tech File Labs
      - SKY_L1 - Lab steps to create final SPICE deck using Sky130 tech
      - SKY_L2 - Lab steps to characterize inverter using sky130 model files
      - SKY_L3 - Lab introduction to Magic tool options and DRC rules
      - SKY_L4 - Lab introduction to Sky130 pdk's and steps to download labs
      - SKY_L5 - Lab introduction to Magic and steps to load Sky130 tech-rules
      - SKY_L6 - Lab exercise to fix poly.9 error in Sky130 tech-file
      - SKY_L7 - Lab exercise to implement poly resistor spacing to diff and tap
      - SKY_L8 - Lab challenge exercise to describe DRC error as geometrical construct
      - SKY_L9 - Lab challenge to find missing or incorrect rules and fix them
## Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK
### SKY130_D1_SK1 - How to talk to computers
##### SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs
![](imagesday1lec/vlcsnap-2021-10-28-15h04m27s930.png)
##### SKY_L2 - Introduction to RISC-V
![](imagesday1lec/vlcsnap-2021-10-28-15h05m47s611.png)
##### SKY_L3 - From Software Applications to Hardware
![](imagesday1lec/vlcsnap-2021-10-28-15h05m16s685.png)
### SKY130_D1_SK2 - SoC design and OpenLANE
##### SKY_L1 - Introduction to all components of open-source digital asic design
![](imagesday1lec/vlcsnap-2021-10-28-15h09m40s547.png)
##### SKY_L2 - Simplified RTL2GDS flow
![](imagesday1lec/vlcsnap-2021-10-28-15h08m09s395.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m14s103.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m26s065.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m31s233.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m33s122.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m42s506.png)
![](imagesday1lec/vlcsnap-2021-10-28-15h08m55s841.png)
##### SKY_L3 - Introduction to OpenLANE and Strive chipsets
![](imagesday1lec/vlcsnap-2021-10-28-15h09m17s372.png)
##### SKY_L4 - Introduction to OpenLANE detailed ASIC design flow
![](imagesday1lec/vlcsnap-2021-10-28-15h11m06s069.png)
### SKY130_D1_SK3 - Get familiar to open-source EDA tools
##### SKY_L1 - OpenLANE Directory structure in detail
![](imagesday1lab/ref_and_tech_libs.png)
![](imagesday1lab/ref_and_tech_2.png)
![](imagesday1lab/inside_sky130_fd_sc_hd.png)
![](imagesday1lab/openlane_designs.png)
##### SKY_L2 - Design Preparation Step
![](imagesday1lab/openlane_working.png)
##### SKY_L3 - Review files after design prep and run synthesis
![](imagesday1lab/file_created_after_executing_prep_design.png)
![](imagesday1lab/merged.lef.png)
##### SKY_L4 - OpenLANE Project Git Link Description
##### SKY_L5 - Steps to characterize synthesis results
![](imagesday1lab/run_synthesis.png)
![](imagesday1lab/yosys_stat_report.png)
![](imagesday1lab/synthesis_openstarpt.png)
![](imagesday1lab/synthesis_openstatimingrpt.png)
![](imagesday1lab/end_day1.png)
## Sky130 Day 2 - Good floorplan vs bad floorplan and introduction to library cells
### SKY130_D2_SK1 - Chip Floor planning considerations
##### SKY_L1 - Utilization factor and aspect ratio
![](imagesday2lec/vlcsnap-2021-10-28-20h25m37s780.png)
![](imagesday2lec/vlcsnap-2021-10-28-20h26m06s027.png)
##### SKY_L2 - Concept of pre-placed cells
![](imagesday2lec/vlcsnap-2021-10-28-20h26m42s607.png)
![](imagesday2lec/vlcsnap-2021-10-28-20h26m51s889.png)
##### SKY_L3 - De-coupling capacitors
![](imagesday2lec/vlcsnap-2021-10-28-20h27m16s914.png)
##### SKY_L4 - Power planning
![](imagesday2lec/vlcsnap-2021-10-28-20h27m41s770.png)
##### SKY_L5 - Pin placement and logical cell placement blockage
![](imagesday2lec/vlcsnap-2021-10-28-20h30m10s913.png)
##### SKY_L6 - Steps to run floorplan using OpenLANE
![](run_floorplan_command.png)
##### SKY_L7 - Review floorplan files and steps to view floorplan
![](imagesday2lab/results_floorplan.png)
![](imagesday2lab/magic_opening.png)
##### SKY_L8 - Review floorplan layout in Magic
![](imagesday2lab/tkcon_window_what.png)
### SKY130_D2_SK2 - Library Binding and Placement
##### SKY_L1 - Netlist binding and initial place design
![](imagesday2lec/vlcsnap-2021-10-28-20h34m36s183.png)
##### SKY_L2 - Optimize placement using estimated wire-length and capacitance
![](imagesday2lec/vlcsnap-2021-10-28-20h35m05s657.png)
##### SKY_L3 - Final placement optimization
![](imagesday2lec/vlcsnap-2021-10-28-20h35m05s657.png)
##### SKY_L4 - Need for libraries and characterization
![](imagesday2lec/vlcsnap-2021-10-28-20h35m30s378.png)
##### SKY_L5 - Congestion aware placement using RePlAce
![](imagesday2lab/placement_command.png)
![](imagesday2lab/placement_layout.png)
### SKY130_D2_SK3 - Cell design and characterization flows
##### SKY_L1 - Inputs for cell design flow
![](imagesday2lec/vlcsnap-2021-10-28-20h37m22s819.png)
##### SKY_L2 - Circuit design step
![](imagesday2lec/vlcsnap-2021-10-28-20h38m00s301.png)
##### SKY_L3 - Layout design step
![](imagesday2lec/vlcsnap-2021-10-28-20h38m04s188.png)
##### SKY_L4 - Typical characterization flow
![](imagesday2lec/vlcsnap-2021-10-28-20h38m31s469.png)
### SKY130_D2_SK4 - General timing characterization parameters
##### SKY_L1 - Timing threshold definitions
![](transition_time.png)
##### SKY_L2 - Propagation delay and transition time
![](imagesday2lec/vlcsnap-2021-10-28-20h39m33s995.png)
![](imagesday2lec/vlcsnap-2021-10-28-20h39m52s302.png)
##### Day 4
![](imagesday4/open_inv_via+magic.png)

![](imagesday4/tracks.info.png)

![](imagesday4/layoutinvcloser.png)

![](imagesday4/tracks.png)

![](imagesday4/grid.png)

![](imagesday4/checkalongthegrid.png)

![](imagesday4/layout.png)

- label the port with associated pin number.

![](imagesday4/layout2.png)

- assign each port as input or output port as in vtcon window.
- 
![](imagesday4/save_skyinmag.png)

- generate a mag file for the inverter using the vtcon window as shown
- 
![](imagesday4/generate_lef_file_from_inv_mag_file.png)

-generate a lef file from the mag file in the vtcon window with the command shown.

![](imagesday4/pinsequenceletfile.png)

-inside the lef file is the pin sequence you assign using magic.

![](imagesday4/copyassociatedfiles.png)

-copy the lef file and inv standard lib fle as highlighted into the picorv32/src folder.

![](imagesday4/includeinconfigtcl.png)

-add the modify the config.tcl file as shown.

![](imagesday4/rundockercommands.png)
-

