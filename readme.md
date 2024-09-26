# Bebedouro Inteligente para Cães de Rua

## Descrição
Este projeto foi desenvolvido com intuito de diminuir os casos de dengue e melhorar a qualidade de vida dos cachorros de rua. O programa foi simulado em microPython e esp32 através do software Wokwi e modelado em 3D no software SolidWorks.

## Utilização
Para simular o bebedouro, você pode acessar esse [Link](https://wokwi.com/projects/399953734587806721) para ter acesso ao código em microPython no site oficial do Wokwi, onde o led mais escuro representa a bomba d'água que ativa o bebedouro, o led mais claro representa o refrigerador de água, o servo motor representa a abertura da pia do bebedouro, e os dois sensores ultrassônicos para medir a distância da água e do cachorro, que controlam a saída e entrada de água.

### Funcionamento
Quando o sensor do cachorro detecta que a distância é menor que 13 cm, o ralo fecha e a bomba d'agua é ativada, enchendo o pote. Quando o sensor da água detecta que a distância da água é menor do que 4,5 cm, a bomba é desativada. E quando o cachorro sai de perto o ralo abre e a água é descartada, não permitindo com que fique parada e diminuindo o risco de desenvolvimento de micro-organismos. Além disso, caso o sensor de temperatura detecte que a água está a mais de 25 graus Celcius, o motor de resfriamento é ativado

### Representação
O modelo 3D representa como seria a estrutura do bebedouro, contendo todos os componentes: sensores, servo-motor, bomba dágua e refrigerador. Caso você queira acessá-lo, basta baixar o arquivo .STL e executá-lo

## Aprendizado
Durante o desenvolvimento do projeto, foi possível aprender novas funções das bibliotecas de microPython, interação com componentes do Wokwi e simulação, além de desenvolver um projeto com intuito de ajudar a sociedade.