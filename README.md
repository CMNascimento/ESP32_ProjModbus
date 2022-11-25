# ESP32_ProjModbus

Projeto realizado partindo do exemplo de comunicação do Modbus do ESP-IDF. Para o desenvolvimento do projeto foram utilizados uma ESP32, um LED vermelho, um fotoresistor, resistores do tipo PTH(220ohms em série com o LED, e 100k ohms e 10k ohms em série com o fotoresistor), e um supervisório desenvolvido no ScadaBR. 

O programa comportasse da seguinte maneira:

I) O LED pode ser acionado manualmento através do supervisório;

II) O acionamento pode ser realizado de forma automática através de um valor selecionado da tensão obtida no fotoresistor. 

Imagem do supervisório no ScadaBR:

![supervisorio](https://user-images.githubusercontent.com/89278224/203318462-56f15358-b1f5-4891-800e-13ee09660360.png)
