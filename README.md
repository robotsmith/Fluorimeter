# OpenFluorimeter
### Note sur version 1.6b: ETAT: fonctionnel, a tester avant prod
Ajout du fluorimetre sur un module d'extension I2C vers UART
(FLUORIMETRE =[RS232]=> MAX232 =[UART]=> DFR0627 =[I2C]=> ESP32) \
Lien interface: [DFROBOT DFR0627](https://wiki.dfrobot.com/Gravity%3A%20IIC%20to%20Dual%20UART%20Module%20SKU%3A%20DFR0627)

### NOTES concernant le module DFR0627 : 
ATTENTION A L'ADRESSAGE :
- IA1=0 IA0=1 software. Un autre adressage peut venir en conflit avec les autres devices I2C
- Changer les interrupteurs DIP sur la carte DFROBOT
