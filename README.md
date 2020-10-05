# Vaja3-ADC-trigger-timer-conversion-STM32F0

Glede na ploščico je bil izbran pin <b>PA0</b>

Glede na potenciometer je bil izbren pin <b>PC0 (In10)</b>

Aktivirana LED dioda na izhodu <b>pin9</b>

<i>Clock Configuration</i> se ob vnosu vrednosti <i>APB1 Timer clock</i> na 16Mhz clock spremeni še HCLK; HCLK to AHB bus, core, memory and DMA; to Cortex system timer, FCLK v 16 ter APB1 peripheral clocks v 8


Preskalirana vrednost <i>ABP1 Timer Clock</i> v polje <i>Prescaler<i> znaša 1000
  
Branje funkcije z zeleno LED diodo omogočimo z zapisom kode: HAL_GPIO_TogglePin(Zelena_led_GPIO_Port, GPIO_PIN_9);

<pre><strong>Komentar:</strong>
Program je zapisan po točnih navodilih. Zapis je bil izveden dvakrat zaradi napake, ki je bila posledica odpustnega cina. Posledično se program ni mogle primerno testirati ter ne deluje pravilno (ne izpisuje vrednosti). 
</pre>
