# Vaja6-ADC-scan-mode-conversion-Nucleo

## Cilj naloge: S pomočjo programskega okolja STM32CubeIDE in HAL knjižnicami sprogramirajte mikroprocesor tako, da bo izvajal ADC pretvorbe na več kanalnih sočasno v scan mode način. Vrednosti treh zunanjih potenciometrov boste zajemali preko Nuclea-L476RG in jih prikazovali na STM Studio.

## Postopek inicializacije periferije

- vhodni pini so PC0 , PC1 , PC2.  
- Poleg pinov se izpiše ADC1_IN1,2,3.  
- Izbrana Vrednost je 4.  
- Number of Conversio je 1.  
- tvz = 61,87μs 
- DMA = Direct memory access (Direkten dostop spomina).

## Pinout
![Pinout](https://raw.githubusercontent.com/TomiHawky/Vaja6-ADC-scan-mode-conversion-Nucleo/main/IMG_20221115_085853.jpg)

## Slika Vezja
![SlikaVezja]([media/FF69ECB8-AD37-4267-8AE3-73734B376573.jpeg](https://raw.githubusercontent.com/TomiHawky/Vaja6-ADC-scan-mode-conversion-Nucleo/main/Screenshot%20from%202022-11-21%2011-52-01.png))

## Komentar
 -koda ne deluje, saj so sve 3 vrednosti enako
