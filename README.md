# rocket_recovery_lm393_leds_uv

Sistema eletrônico cuja funcionalidade prevista é liberar um paraquedas logo após atingir o apogeu da trajetória do lançamento. O funcionamento do cirtuto é basedo no monitoramento de tensões elétricas em duas portas analógicas do CI LM393, as tensões são geradas por 2 LEDs UV. LED UV tem a paricularidade de criar uma tensão V nos seus terminais quando exposta á luz ultravioleta, no caso do foguete, a luz ultravioleta do Sol. Quando há inversão da tensão nos terminais o LM393 atravéz do seu pino de saída faz a saturação do TIP122 que passa a conduzir corrente elétrica direta da bateria de 9V fazendo a ignição da carga.

Esquema elétrico 26-06-2025
<img width="735" height="309" alt="image" src="https://github.com/user-attachments/assets/e9b1741d-a7ff-4a2c-9a9b-a437d68bd099" />


Circuito placa 11/07/2025
<img width="498" height="554" alt="image" src="https://github.com/user-attachments/assets/b958ce45-b74a-4547-b67f-ce9d05b6415a" />
<img width="639" height="690" alt="image" src="https://github.com/user-attachments/assets/99ac7345-8f9c-4d5c-9c22-e042893526a0" />
<img width="612" height="680" alt="image" src="https://github.com/user-attachments/assets/ecbd5b1c-14df-4352-896d-d7548f219cc6" />
