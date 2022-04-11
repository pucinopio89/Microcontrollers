# Microcontrollers - inca lucrez la el
Conținut proiect:
Mi-am ales 2 senzori: de temperatură(analogic) și
umididate(digital)
Am convertit tensiunea analogică de la ieșirea senzorului
de temperatură, folosind un CAN, ADC0808, după ce am
folosit un circuit de condiționare cu un Amplificator Diferential.
Pentru senzorul de umiditate, am scris interfața I2C
Am interfațat ADC-ul cu un microcontroller din familia
8051
Am conectat un LCD pentru afișarea temperaturii, pe
care l-am programat în C , cât și în limbaj de asamblare
Am programat ADC-ul
Am proiectat/dimensionat un sistem de încălzire, pentru
un incubator/cameră, utilizând un triac, optocuplor și un
heater, pe care l-am controlat cu ajutorul
microcontrollerului.
În prezent, lucrez la un ventilator.
...
Toată schema proiectului a fost realizată în PROTEUS; codul
pentru controlul termostatului l-am scris în C și limbaj de
asamblare; am lucrat în mediul KEIL. Toate componentele
electronice le-am dimensionat, ținând cont de foile de catalog
specifice, iar în cazul componentelor pasive, de valorile
standarizate.
