Simulação do Movimento Browniano
Descrição
Este projeto contém um script em Python que simula o movimento browniano em duas dimensões utilizando as bibliotecas NumPy e Matplotlib. O movimento browniano é modelado como um passeio aleatório, onde a partícula se move em direções aleatórias com passos de tamanho fixo.
Requisitos
Para executar o script, você precisa ter as seguintes bibliotecas instaladas:

Python 3.x
NumPy
Matplotlib

Você pode instalá-las usando o pip:
pip install numpy matplotlib

Como Usar

Salve o script Python (por exemplo, como brownian_motion.py).
Execute o script em um ambiente Python com as bibliotecas necessárias instaladas:python brownian_motion.py


Um gráfico será gerado, exibindo a trajetória da partícula em um plano 2D.

Estrutura do Código
O script realiza as seguintes etapas:

Parâmetros da Simulação:
num_steps: Define o número de passos na simulação (padrão: 1000).
step_size: Define o tamanho de cada passo (padrão: 1.0).


Inicialização:
Cria arrays para armazenar as posições x e y da partícula, iniciando em (0,0).


Simulação do Movimento:
Para cada passo, um ângulo aleatório é gerado entre 0 e 2π.
As posições x e y são atualizadas com base em componentes trigonométricas (cosseno e seno).


Visualização:
Um gráfico é gerado com Matplotlib, mostrando a trajetória da partícula.



Exemplo de Saída
O script gera um gráfico com:

Eixos X e Y representando as posições da partícula.
Uma linha azul com pequenos marcadores circulares indicando a trajetória.
Um título e grade para facilitar a visualização.

Personalização
Você pode modificar os seguintes parâmetros no código para alterar a simulação:

num_steps: Aumente ou diminua para tornar a trajetória mais ou menos detalhada.
step_size: Ajuste para alterar a escala do movimento.
Cores, tamanhos de marcadores e estilos de linha no comando plt.plot podem ser personalizados.

Limitações

A simulação assume um movimento browniano idealizado com passos de tamanho fixo.
Não há tratamento de colisões ou limites espaciais.
Para simulações mais realistas, considere adicionar variações no tamanho do passo ou condições de contorno.

Licença
Este projeto é fornecido sob a licença MIT. Sinta-se à vontade para usar, modificar e distribuir conforme necessário.
Contato
Para dúvidas ou sugestões, entre em contato com [vitor.souza@ime.eb.br].
