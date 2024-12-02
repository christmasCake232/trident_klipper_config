
CAN Bus Speed: 1000000

## main

[Ocotpus_Max_EZ](https://github.com/bigtreetech/Octopus-Max-EZ)




## toolhead


[EBB SB2209 RP2040](https://github.com/bigtreetech/EBB/tree/master/EBB%20SB2209%20CAN%20(RP2040))




## Old


### EBB36 1.0
can bus 500000

[github](https://github.com/bigtreetech/EBB)


#### Fan

1. FAN0: PA1, hot end fan
2. FAN1: PA2, part cooling fan

#### Hot end

1. hotend0: PB1, hot end

#### End stop

1. PC13: probe
2. PC14: x end stop; using gnd from I2C

#### THx

1. TH0: PA0

---

### ERB 1.0

[github](https://github.com/FYSETC/FYSETC-ERB)

---

### M8P 1.1

[github](https://github.com/bigtreetech/Manta-M8P)

#### CAN

- H: PD13, L: PD12

#### End Stop

1. M1: PF3, E-Stop
2. M2: PF4, Y end stop
3. M3: PF5
4. M4: PC0
5. M5: PC1
6. M6

#### FANx

1. FAN0: PE6, A/B driver fan (5v)
2. FAN1: PE0, cabinet fan (24v)
3. FAN2: PC12
4. FAN3: PE5
5. FAN4:
6. FAN5:
7. FAN6:

#### HEx

1. HE0: PE3, bed heater
2. HE1: PB5, chamber heater
3. HE2: PB6, chamber lights front
4. HE3: PE1, chamber fans (nevermore)

#### Mx

1. M1: stepper x/b Back Left
2. M2: stepper y/a Back Right
3. M3: stepper z1 Front Left
4. M4: stepper z2 Back Center
5. M5: stepper z3 Front Right 
6. M6: 
7. M7:
8. M8:

#### THx

1. THB: PA0, heater bed sensor (heater)
2. TH0: PA1, bed sensor (bed)
3. TH1: PA2, heater chamber sensor (heater)
4. TH2: PA3, chamber0 (ambient left)
5. TH3: PA4, chamber1 (ambient right)

TODO: [Dual Loop PID PR](https://github.com/Klipper3d/klipper/pull/5972)

---

### SB2240

[github](https://github.com/bigtreetech/EBB)


---
