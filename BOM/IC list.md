List of IC availability (taking SEEEDstudio and LCSC as providers)
falling back to digikey
Prices rounded to one decimal

## IC's

### U1:
   * PN: ESP-32S
   * desc: Main microcontroller
   * www: https://learn.adafruit.com/adafruit-huzzah32-esp32-feather/pinouts
   * Options:
      * 0:
         * Store: LCSC
         * pkg: n/a
         * moq: 1
         * price: 3.2
   * kicad status:
      * footprint selected: yes
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
### U2:
   * PN: 74HC595
   * desc: Shift register for digital pins expansion
   * www: http://www.ti.com/lit/ds/symlink/sn74hc595.pdf
   * Options:
      * 0:
         * Store: LCSC
         * pkg: 16-SOIC (SOT109-1)
         * moq: 5
         * price: 0.1
         * www: https://lcsc.com/product-detail/74-Series_Nexperia_74HC595D-118_74HC595D-118_C5947.html
      * 1:
         * Store: LCSC
         * pkg: 16-SOP
         * moq: 10
         * price: 0
      ... 
      * 3:
         * Options: SEEED
         * pkg: 16-SOIC
         * moq: 5
         * price: 0.1
      * 4:
         * Options: SEEED
         * pkg: 16-TSSOP
         * moq: 5
         * price: 0.1
   * Kicad status:
      * footprint selected: yes
      * selected option: 0
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
### U3:
   * PN: CP2104
   * desc: Microcontroller for USB to serial conversion (HUZZAH)
   * www: https://www.silabs.com/Support%20Documents/TechnicalDocs/cp2104.pdf
   * Options: 
      * 0:
         * Store: LCSC (Discontinued)
         * pkg: QFN-24_4x4x05P
         * moq: 1
         * price: 1.4
   * Replacement Options:
      * 1:
         * Store: LCSC
         * pkg: QFN-20 
         * moq: 1
         * price: 2.2
         * www: https://lcsc.com/search?q=CP2102N
         * note: QFN 20 doesn't have RTS pin
      * 2:
         * Store: LCSC
         * pkg: QFN-28_5x5x05P
         * moq: 1
         * price: 1.6
         * www: https://lcsc.com/product-detail/USB_SILICON-LABS_CP2102-GMR_CP2102-GMR_C6568.html
   * Kicad status:
      * footprint selected: yes
      * selected option: 2
      * size check: checked
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct

### U4:
   * PN: AP2112K-3.3
   * desc: Power regulator for 3.3v
   * www: https://www.diodes.com/assets/Datasheets/AP2112.pdf
   * Options: 
      * 0:
         * Store: LCSC
         * pkg: SOT-25
         * moq: 1
         * price: 0.1
   * Kicad status:
      * footprint selected: yes
      * selected option: 0  (SOT23-5)
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
### U5:
   * PN: LP2985-5.0
   * desc: Power regulator for 5v
   * www: http://www.ti.com/lit/ds/symlink/lp2985.pdf
   * Options: 
      * 0:
         * Store: LCSC
         * pkg: SOT-23-5
         * moq: 1
         * price: 0.2
         * www: https://lcsc.com/product-detail/Others_Texas-Instruments_LP2985AIM5X-5-0-NOPB_Texas-Instruments-TI-LP2985AIM5X-5-0-NOPB_C311788.html
      * 1:
         * Store: SEEED
         * pkg: SOT7523
         * moq: 1
         * price: 0.3
   * Kicad status:
      * footprint selected: yes
      * selected option: 0  (SOT23-5)
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
### Q1,Q2(NPN):
   * PN: MMBT2222
   * desc: Autoreset circuit (HUZZAH)
   * www: https://www.onsemi.com/pub/Collateral/MMBT2222LT1-D.PDF
   * Options:
      * 0:
         * Store: LCSC
         * pkg: SOT-523
         * moq: 1
         * price: 0.1
      * 1: 
         * Store: LCSC
         * pkg: SOT-523
         * moq: 10
         * price: 0
      * 2: 
         * Store: LCSC
         * pkg: SOT-23
         * moq: 20
         * price: 0
         * www:https://lcsc.com/product-detail/Transistors-NPN-PNP_ON-Semicon_MMBT2222ALT1G_ON-Semicon-ON-MMBT2222ALT1G_C82460.html
      ...
      * 2:
         * Store: SEEED
         * pkg: SOR-23
         * moq: 5
         * price: 0
      ...
   * Kicad status:
      * footprint selected: yes
      * selected option: 2  (SOT23)
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: unchecked
### K1:
   * PN: vn920b5
   * desc: Contactor for pump PWM control
   * www: https://lcsc.com/product-detail/Others_STMicroelectronics_VN920B5-E_STMicroelectronics-VN920B5-E_C99316.html
   * Options:
      * 0:
         * Store: LCSC
         * pkg: P2PAK
         * moq: 1
         * price: 2.9
   
   * Kicad status:
      * footprint selected: yes
      * selected option: 0
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
### J17
   * found one that matches kicad's drawing:
      * https://datasheet.lcsc.com/szlcsc/SOFNG-TF-002-H18_C125814.pdf
      * https://lcsc.com/product-detail/Connector-Card-Sockets_SOFNG-TF-002-H18_C125814.html

   * Kicad status:
      * footprint selected: yes
      * size check: correct
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
## Actuators
### S1-S5
   * packaging: 6*6
   * www: https://lcsc.com/product-detail/Tactile-Switches_Korean-Hroparts-Elec-K2-1102SP-C4SC-04_C127509.html
   * Kicad status:
      * footprint selected: yes
      * size check: imperfect fit
      * datasheet-footprint correlation: correct
      * schematic-footprint correlation: correct
   


## Definitive SMD passives
(other passives will be tested, hence need be THT)

|Resistor, val     |available packagings         |kicad: size checked   |kicad: pin check  |
|------------------|-----------------------------|----------------------|------------------|
|100K              |0603,0402,0805,12006,0201,...|unchecked             |ok                |
|10K               |0603,0402,0805,12006,0201,...|unchecked             |ok                |
|1K                |0603,0402,0805,12006,0201,...|unchecked             |ok                |
|Capacitor, val    |                             |                      |                  |
|10uF              |0603,...                     |unchecked             |ok                |
|1uF               |0603,...                     |unchecked             |ok                |
|Schottky diode    |SOD123, DO41                 |unchecked             |unchecked         |
