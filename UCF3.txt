

# Banck 15 : 1.8 v   ,   Banck 14 : 3.3 v    ,    Banck 34 ; 1.8 v



# Clock(Bank 15 : 1.8V)_______________________________________________________________
set_property -dict {PACKAGE_PIN B13 IOSTANDARD LVCMOS18} [get_ports Clock_100MHz]

create_clock -period 10.000 -name sys_clk_pin -waveform {0.000 5.000} -add [get_ports Clock_100MHz]

##   Input Port(Bank 15 : 1.8V)_________________________________________________________
#set_property -dict {PACKAGE_PIN A5 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[0]}]
#set_property -dict {PACKAGE_PIN B6 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[1]}]
#set_property -dict {PACKAGE_PIN A6 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[2]}]
#set_property -dict {PACKAGE_PIN A7 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[3]}]
#set_property -dict {PACKAGE_PIN C8 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[4]}]
#set_property -dict {PACKAGE_PIN A8 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[5]}]
#set_property -dict {PACKAGE_PIN C9 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[6]}]
#set_property -dict {PACKAGE_PIN B9 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[7]}]
#set_property -dict {PACKAGE_PIN A9 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[8]}]
#set_property -dict {PACKAGE_PIN A10 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[10]}]
#set_property -dict {PACKAGE_PIN B11 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[11]}]
#set_property -dict {PACKAGE_PIN D10 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[12]}]
#set_property -dict {PACKAGE_PIN C10 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[13]}]
#set_property -dict {PACKAGE_PIN D11 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[14]}]
#set_property -dict {PACKAGE_PIN E11 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[15]}]
#set_property -dict {PACKAGE_PIN D12 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[16]}]
#set_property -dict {PACKAGE_PIN C13 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[17]}]
#set_property -dict {PACKAGE_PIN B12 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[18]}]
#set_property -dict {PACKAGE_PIN A11 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[19]}]




#set_property -dict {PACKAGE_PIN B10 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[9]}]



#set_property -dict {PACKAGE_PIN A14 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[20]}]



#set_property -dict {PACKAGE_PIN B14 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[21]}]
#set_property -dict {PACKAGE_PIN A13 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[22]}]
#set_property -dict {PACKAGE_PIN A12 IOSTANDARD LVCMOS18} [get_ports {Input_Signal[23]}]


## Output Port(Bank 14 : 3.3 V)_________________________________________________________
#set_property -dict {PACKAGE_PIN M13 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[0]}]
#set_property -dict {PACKAGE_PIN R4 IOSTANDARD LVCMOS18} [get_ports {Output_Signal[21]}]
#set_property -dict {PACKAGE_PIN P1 IOSTANDARD LVCMOS18} [get_ports {Output_Signal[18]}]
#set_property -dict {PACKAGE_PIN R2 IOSTANDARD LVCMOS18} [get_ports {Output_Signal[19]}]
#set_property -dict {PACKAGE_PIN R3 IOSTANDARD LVCMOS18} [get_ports {Output_Signal[20]}]





#set_property -dict {PACKAGE_PIN N14 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[1]}]
#set_property -dict {PACKAGE_PIN N15 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[2]}]
#set_property -dict {PACKAGE_PIN P15 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[3]}]
#set_property -dict {PACKAGE_PIN P14 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[4]}]
#set_property -dict {PACKAGE_PIN R14 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[5]}]
#set_property -dict {PACKAGE_PIN N13 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[6]}]
#set_property -dict {PACKAGE_PIN L13 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[7]}]
#set_property -dict {PACKAGE_PIN N12 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[8]}]
#set_property -dict {PACKAGE_PIN L12 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[9]}]
#set_property -dict {PACKAGE_PIN N11 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[10]}]


#set_property -dict {PACKAGE_PIN L10 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[11]}]
#set_property -dict {PACKAGE_PIN R13 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[12]}]
#set_property -dict {PACKAGE_PIN P12 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[13]}]
#set_property -dict {PACKAGE_PIN R12 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[14]}]
#set_property -dict {PACKAGE_PIN R11 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[16]}]
#set_property -dict {PACKAGE_PIN P10 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[17]}]



#set_property -dict {PACKAGE_PIN N6 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[22]}]
#set_property -dict {PACKAGE_PIN M7 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[23]}]
#set_property -dict {PACKAGE_PIN M8 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[24]}]
#set_property -dict {PACKAGE_PIN N7 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[25]}]
#set_property -dict {PACKAGE_PIN N8 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[26]}]
#set_property -dict {PACKAGE_PIN N9 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[27]}]
#set_property -dict {PACKAGE_PIN R9 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[28]}]
#set_property -dict {PACKAGE_PIN R10 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[29]}]
#set_property -dict {PACKAGE_PIN M10 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[30]}]


#set_property -dict {PACKAGE_PIN N10 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[31]}]
#set_property -dict {PACKAGE_PIN R7 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[32]}]
#set_property -dict {PACKAGE_PIN R8 IOSTANDARD LVCMOS33} [get_ports {Output_Signal[33]}]




##  Attenustor 1
set_property -dict {PACKAGE_PIN N13 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[0]}]
set_property -dict {PACKAGE_PIN L13 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[1]}]
set_property -dict {PACKAGE_PIN N12 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[2]}]
set_property -dict {PACKAGE_PIN P15 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[3]}]
set_property -dict {PACKAGE_PIN P14 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[4]}]
set_property -dict {PACKAGE_PIN R14 IOSTANDARD LVCMOS33} [get_ports {Attenuator_1[5]}]


##  Attenustor 2

set_property -dict {PACKAGE_PIN N8  IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[0]}]
set_property -dict {PACKAGE_PIN N7  IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[1]}]
set_property -dict {PACKAGE_PIN M8  IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[2]}]
set_property -dict {PACKAGE_PIN R10 IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[3]}]
set_property -dict {PACKAGE_PIN R9  IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[4]}]
set_property -dict {PACKAGE_PIN N9  IOSTANDARD LVCMOS33} [get_ports {Attenuator_2[5]}]

##  Attenustor IF

set_property -dict {PACKAGE_PIN R13 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[0]}]
set_property -dict {PACKAGE_PIN P12 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[1]}]
set_property -dict {PACKAGE_PIN R12 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[2]}]
set_property -dict {PACKAGE_PIN L10 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[3]}]
set_property -dict {PACKAGE_PIN N11 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[4]}]
set_property -dict {PACKAGE_PIN L12 IOSTANDARD LVCMOS33} [get_ports {Attenuator_IF[5]}]

##  Attenustor E.P

set_property -dict {PACKAGE_PIN A12 IOSTANDARD LVCMOS18} [get_ports {E_P[0]}]
set_property -dict {PACKAGE_PIN A13 IOSTANDARD LVCMOS18} [get_ports {E_P[1]}]
set_property -dict {PACKAGE_PIN B14 IOSTANDARD LVCMOS18} [get_ports {E_P[2]}]
set_property -dict {PACKAGE_PIN A14 IOSTANDARD LVCMOS18} [get_ports {E_P[3]}]


##  Feed Back
set_property -dict {PACKAGE_PIN B10 IOSTANDARD LVCMOS18} [get_ports Feed_Back]
set_property -dict {PACKAGE_PIN N14 IOSTANDARD LVCMOS33} [get_ports T_R_Command]
#   D.F Path
set_property -dict {PACKAGE_PIN N15 IOSTANDARD LVCMOS33} [get_ports DF_Path]
#   Switch14-A
set_property -dict {PACKAGE_PIN R8  IOSTANDARD LVCMOS33} [get_ports {Switch_14A[0]}]
set_property -dict {PACKAGE_PIN R7  IOSTANDARD LVCMOS33} [get_ports {Switch_14A[1]}]
#   Switch14-B
set_property -dict {PACKAGE_PIN N10 IOSTANDARD LVCMOS33} [get_ports {Switch_14B[0]}]
set_property -dict {PACKAGE_PIN M10 IOSTANDARD LVCMOS33} [get_ports {Switch_14B[1]}]
#   Switch1
set_property -dict {PACKAGE_PIN M7  IOSTANDARD LVCMOS33} [get_ports {Switch_1[0]}]
set_property -dict {PACKAGE_PIN N6  IOSTANDARD LVCMOS33} [get_ports {Switch_1[1]}]
set_property -dict {PACKAGE_PIN P10 IOSTANDARD LVCMOS33} [get_ports {Switch_1[2]}]
set_property -dict {PACKAGE_PIN R11 IOSTANDARD LVCMOS33} [get_ports {Switch_1[3]}]

##   ID(Bank 15 :1.8V)__________________________________________________________________

#set_property -dict { PACKAGE_PIN C6   IOSTANDARD LVCMOSS18 } [get_ports { ID[0] }]
#set_property -dict { PACKAGE_PIN C7   IOSTANDARD LVCMOSS18 } [get_ports { ID[1] }]
#set_property -dict { PACKAGE_PIN D7   IOSTANDARD LVCMOSS18 } [get_ports { ID[2] }]
#set_property -dict { PACKAGE_PIN D8   IOSTANDARD LVCMOSS18 } [get_ports { ID[3] }]
#set_property -dict { PACKAGE_PIN D9   IOSTANDARD LVCMOSS18 } [get_ports { ID[4] }]


##   AD7386(4Channel,4MSPS,16bit/14bit/12bit)______________________________
set_property -dict { PACKAGE_PIN H13   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SCLK[0] }]
set_property -dict { PACKAGE_PIN H12   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDI[0] }]
set_property -dict { PACKAGE_PIN G11   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOA[0] }]
set_property -dict { PACKAGE_PIN H11   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOB[0] }]
set_property -dict { PACKAGE_PIN G13   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_CS[0] }]

set_property -dict { PACKAGE_PIN G12   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SCLK[1] }]
set_property -dict { PACKAGE_PIN F11   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDI[1] }]
set_property -dict { PACKAGE_PIN E12   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOA[1] }]
set_property -dict { PACKAGE_PIN E13   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOB[1] }]
set_property -dict { PACKAGE_PIN D13   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_CS[1] }]


set_property -dict { PACKAGE_PIN G15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SCLK[2] }]
set_property -dict { PACKAGE_PIN G14   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDI[2] }]
set_property -dict { PACKAGE_PIN F14   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOA[2] }]
set_property -dict { PACKAGE_PIN F15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOB[2] }]
set_property -dict { PACKAGE_PIN E15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_CS[2] }]

set_property -dict { PACKAGE_PIN E14   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SCLK[3] }]
set_property -dict { PACKAGE_PIN D15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDI[3] }]
set_property -dict { PACKAGE_PIN C14   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOA[3] }]
set_property -dict { PACKAGE_PIN C15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_SDOB[3] }]
set_property -dict { PACKAGE_PIN B15   IOSTANDARD LVCMOSS18 } [get_ports { AD7386_CS[3] }]



##   AD7490(16Channel,1MSPS,12bit) (Bank 14 : 3.3v)________________________________
#set_property -dict { PACKAGE_PIN P6   IOSTANDARD LVCMOSS33 } [get_ports { AD7490_DIN }]
#set_property -dict { PACKAGE_PIN P7   IOSTANDARD LVCMOSS33 } [get_ports { AD7490_DOUT }]
#set_property -dict { PACKAGE_PIN R5   IOSTANDARD LVCMOSS33 } [get_ports { AD7490_CS }]
#set_property -dict { PACKAGE_PIN R6   IOSTANDARD LVCMOSS33 } [get_ports { AD7490_SCLK }]



###   Rs485(Bank 14)_________________________________________________________
set_property -dict { PACKAGE_PIN J11   IOSTANDARD LVCMOSS33 } [get_ports { RS485_1_RXD }]
set_property -dict { PACKAGE_PIN K11   IOSTANDARD LVCMOSS33 } [get_ports { RS485_1_TXD }]
set_property -dict { PACKAGE_PIN K12   IOSTANDARD LVCMOSS33 } [get_ports { RS485_1_DE }]
set_property -dict { PACKAGE_PIN J15   IOSTANDARD LVCMOSS33 } [get_ports { RS485_2_RXD }]


##   CAN-______________________________________________________
##set_property PACKAGE_PIN K14 [get_ports CAN_SCLK]
##set_property PACKAGE_PIN K15 [get_ports CAN_RST]
##set_property PACKAGE_PIN L14 [get_ports CAN_SDO]
##set_property PACKAGE_PIN L15 [get_ports CAN_SDI]
##set_property PACKAGE_PIN M14 [get_ports CAN_INT]
##set_property PACKAGE_PIN M15 [get_ports CAN_CS]


##   Flash(Banck 34 ; 1.8 v)_____________________________________________________
#set_property -dict { PACKAGE_PIN  D2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[0] }]
#set_property -dict { PACKAGE_PIN  B1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[1] }]
#set_property -dict { PACKAGE_PIN  A2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[2] }]
#set_property -dict { PACKAGE_PIN  A4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[3] }]
#set_property -dict { PACKAGE_PIN  B4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[4] }]
#set_property -dict { PACKAGE_PIN  C5   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[5] }]
#set_property -dict { PACKAGE_PIN  D3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[6] }]
#set_property -dict { PACKAGE_PIN  E3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[7] }]
#set_property -dict { PACKAGE_PIN  C1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[8] }]
#set_property -dict { PACKAGE_PIN  B2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[9] }]
#set_property -dict { PACKAGE_PIN  A3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[10] }]


#set_property -dict { PACKAGE_PIN  B5   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[11] }]
#set_property -dict { PACKAGE_PIN  B3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[12] }]
#set_property -dict { PACKAGE_PIN  C4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[13] }]
#set_property -dict { PACKAGE_PIN  D4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[14] }]
#set_property -dict { PACKAGE_PIN  G4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_DQ[15] }]



#set_property -dict { PACKAGE_PIN  D1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[0] }]
#set_property -dict { PACKAGE_PIN  P2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[1] }]
#set_property -dict { PACKAGE_PIN  P3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[2] }]
#set_property -dict { PACKAGE_PIN  N3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[3] }]
#set_property -dict { PACKAGE_PIN  N4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[4] }]
#set_property -dict { PACKAGE_PIN  M3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[5] }]
#set_property -dict { PACKAGE_PIN  M4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[6] }]
#set_property -dict { PACKAGE_PIN  N2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[7] }]
#set_property -dict { PACKAGE_PIN  H2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[8] }]
#set_property -dict { PACKAGE_PIN  H1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[9] }]
#set_property -dict { PACKAGE_PIN  G1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[10] }]

#set_property -dict { PACKAGE_PIN  F1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[11] }]
#set_property -dict { PACKAGE_PIN  F2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[12] }]
#set_property -dict { PACKAGE_PIN  K3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[13] }]
#set_property -dict { PACKAGE_PIN  J3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[14] }]
#set_property -dict { PACKAGE_PIN  J4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[15] }]
#set_property -dict { PACKAGE_PIN  F3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[16] }]
#set_property -dict { PACKAGE_PIN  N1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[17] }]
#set_property -dict { PACKAGE_PIN  M2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[18] }]
#set_property -dict { PACKAGE_PIN  J1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[19] }]
#set_property -dict { PACKAGE_PIN  J2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[20] }]


#set_property -dict { PACKAGE_PIN  L1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[21] }];
#set_property -dict { PACKAGE_PIN  H3   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[22] }];
#set_property -dict { PACKAGE_PIN  H4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[23] }];
#set_property -dict { PACKAGE_PIN  F4   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_A[24] }];

#set_property -dict { PACKAGE_PIN  E1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_OE }];
#set_property -dict { PACKAGE_PIN  E2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_CE] }];
#set_property -dict { PACKAGE_PIN  K1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_WE }];
#set_property -dict { PACKAGE_PIN  K2   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_RST }];
#set_property -dict { PACKAGE_PIN  M1   IOSTANDARD LVCMOSS18 } [get_ports { NORFlash_RY_BY }];







