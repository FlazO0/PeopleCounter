
# Contador de Pessoas

### Visão Geral do Projeto

O Contador de Pessoas é um projeto que utiliza a biblioteca OpenCV para contar o número de pessoas que passam por uma determinada região em um vídeo. Ele é capaz de detectar pessoas em movimento e realizar a contagem de forma precisa e eficiente.

### Funcionalidades

- Contagem automática do número de pessoas em um vídeo.
- Detecção de pessoas em movimento em uma área específica.
- Visualização da contagem em tempo real sobre o vídeo.

### Tecnologias Utilizadas

- **Python:** Linguagem de programação principal do projeto.
- **OpenCV:** Biblioteca para processamento de imagens e vídeo.
- **NumPy:** Biblioteca para manipulação de arrays e cálculos numéricos.

### Configuração e Instalação

### Requisitos

- Python 3.7 ou superior
- OpenCV
- NumPy

### Clone o Repositório

```bash
git clone https://github.com/FlazO0/PeopleCounter.git
cd PeopleCounter
```

### Instale as Dependências

Certifique-se de ter o Python instalado. Em seguida, instale os pacotes necessários:

```bash
pip install opencv-python numpy
```

### Uso

1. Baixe o vídeo que deseja analisar e coloque-o na pasta do projeto.
2. Abra o script Python `app.py`.
3. Altere o caminho do vídeo no código para o nome do seu arquivo de vídeo.
4. Execute o script Python:

```bash
python app.py
```

5. A aplicação iniciará a contagem de pessoas no vídeo e exibirá a contagem sobre o vídeo em tempo real.

