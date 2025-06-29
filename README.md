# rocket_recovery_lm393_leds_uv

Sistema eletrônico cuja funcionalidade prevista é liberar um paraquedas logo após atingir o apogeu da trajetória do lançamento. O funcionamento do cirtuto é basedo no monitoramento de tensões elétricas em duas portas analógicas do CI LM393, as tensões são geradas por 2 LEDs UV. LED UV tem a paricularidade de criar uma tensão V nos seus terminais quando exposta á luz ultravioleta, no caso do foguete, a luz ultravioleta do Sol. Quando há inversão da tensão nos terminais o LM393 atravéz do seu pino de saída faz a saturação do TIP122 que passa a conduzir corrente elétrica direta da bateria de 9V fazendo a ignição da carga.

Esquema elétrico 26-06-2025
![image](https://github.com/user-attachments/assets/b996d077-ec63-41c8-9e8d-c4cd08f96acb)

Circuito placa 28-06-2025
![circuito](https://github.com/user-attachments/assets/813456ec-5797-4348-b059-49bcd08e6d1a)

Placa_1 de circuito 28-06-2025
![placa1](https://github.com/user-attachments/assets/5bea0d47-ee02-4167-a1e5-6d8fb58e17a5)

Placa_2 de circuito 28-06-2025
![plca2](https://github.com/user-attachments/assets/1640e589-2a7a-4fff-ac60-07bc4fb5b4b9)


