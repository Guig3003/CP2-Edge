# CP2-Edge 
# Descrição do projeto 📝
Introdução 🧾

Após a entrega do primeiro projeto, recebemos um feedback da Vinheria Agnello, no qual solicitaram novas funcionalidades para o dispositivo, que consistiam em mostrar os dados em um display (LCD) e captar, além da luminosidade, os valores de umidade e temperatura. Isso ocorre porque o sabor do vinho não é alterado apenas pela exposição à muita luminosidade, mas também pela umidade e temperatura. Com isso em mente, nesta segunda parte, implementamos essas funções e aprimoramos o projeto.

Inicialização 🎇

Ao ligar o dispositivo, o Buzzer tocará um som e todos os LED's piscarão. Implementamos isso pois isso verificará se os LED's e o Buzzer estão funcionando. Após isso, o logo da nossa empresa aparece no display (LCD). Em seguida, ele mostra os valores da luminosidade, temperatura e umidade 10 vezes cada. Depois, exibe a média desses valores.

Luminosidade 💡

Como discutido na primeira parte do projeto, a exposição à luminosidade excessiva e à penumbra pode causar danos à qualidade do vinho. Levando isso em consideração, além da indicação se o ambiente está escuro, com meia luz ou iluminado pelos LEDs, essa informação será visível no display (LCD), assim como a quantidade de luminosidade em lux. Por fim, a buzina (Buzzer) que emitia o alarme apenas por 3 segundos agora tocará continuamente.

Temperatura 🌡

O vinho, quando exposto ao calor excessivo, tem sua vida encurtada, além de que variações de temperatura superiores a 3°C podem resultar no aparecimento de aromas indesejáveis. Por essas razões, implementamos um sensor que captura a temperatura da adega, o DHT11, além de indicar se o local está com uma temperatura alta, baixa ou na faixa ideal, entre 10°C e 15°C. Essas informações são visíveis no display (LCD) do dispositivo. Quando a temperatura do ambiente estiver fora da situação ideal, o LED amarelo será aceso e a buzina (Buzzer) tocará continuamente.

Umidade ❄

Além da temperatura, a ausência de umidade pode resultar na secagem do vedante, ocasionando uma vedação inadequada da garrafa e aumentando o risco de oxidação do líquido. Enquanto isso, um excesso de umidade pode causar danos aos rótulos e favorecer o crescimento de fungos. Portanto, o nível ideal de umidade deve ser em torno de 70%, com uma margem de variação entre 50% e 70%.
# Link do CP 🔗
https://wokwi.com/projects/396159048683156481
#  Componentes 🧠
1 arduino;
3 resistores;
1 led vermelho;
1 led verde;
1 led amarelo;
1 buzzer;
1 Sensor digital de umidade e temperatura;
1 Módulo sensor fotoresistor;
1 Um LCD com 2 linhas, 16 caracteres por linha;
![image](https://github.com/Guig3003/CP2-Edge/assets/92872071/335c6860-7a98-4bfd-b77e-9ad9aae0a254)
# Empresa 💎 
![image](https://github.com/Guig3003/CP2-Edge/assets/92872071/24cf31eb-4e21-49ea-884a-7e3153affd72)

Paulo Poças - RM556080;
Guilherme Gomes - RM554606;
Pedro Gaspar Fernandes Ferrari - RM554887;
André Luiz Fernandes De Queiroz - Rm554503.
