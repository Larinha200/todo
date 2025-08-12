### 1-Open CV

### O que é?

As bibliotecas Open sources são bibliotecas de código aberto, ou seja, o usuário pode alterar, utilizar e distribuir o código sem precisar comprar licença

### Criador do Open CV

O open CV  foi desenvolvido pelo programador Gary Bradski da empesa intel em 1999, ele atuava também como engenheiro e pesquisador de IA. 

### História

- De 1999/2000  Intel lança o projeto para uso interno.
- Em 2006 a Versão 1.0 chega ao público.
- Em 2009 foi lançado Open CV 2 com APIs C++ modernizadas, oferecendo melhoria de desempenho e portabilidade.
- 2015 Open CV 3.0 adiciona suporte C++11, melhores bindings para Python e mais algoritmos de Machine Learning.
- 2023/2024  Open CV 4.8.0 traz backend Vulkan (até 4× desempenho), suporte a AVIF/HEVC, OpenVINO e melhorias para JS/Python.
- 2025 Versão 4.12.0 liberada com suporte ao C++20, quantização DNN, HALs para RISC-V e Qualcomm, entre outros.
- OpenCV 5 Alpha (preview) já disponível.

### Linguagens e Plataformas

O OpenCV foi projetado para ser multiplataforma. Ele foi escrito nativamente na biblioteca C++, e a biblioteca do OpenCV suporta Windows, Linux, Android, IOS, MacOS, e possui interfaces C++, Python, Java, MATLAB.

### Como Funciona

### Parte Conceitual:

- Pega imagens e vídeos como matrizes de pixels.

- Aplica operações matemáticas e lógicas para extrair informações visuais.

### Entrada dos Dados:

- Carrega dados de várias fontes.

### Processamento da imagem ou vídeo:

Após ler a imagem ou vídeo, possibilita aplicar operações como: Formas geométricas, Cores, Filtros, Reconhecimentos, Desenhos

### Exibição ou salvamento do resultado:

 Possibilta: Mostrar em janelas (cv2.imshow), Salvar em disco (cv2.imwrite),  Exportar como vídeo (cv2.VideoWriter)

### Principais Recursos:

- CORE: Funções básicas para lidar com imagens.
- IMGPROC: Ajusta e transforma imagens.
- Objdetect / Tracking: Detecção de faces.
- Features2D: Encontra pontos importantes em imagens.
- Calib3D: Trabalha com visão e medições em 3D.
- ML interno: Conjunto de métodos de aprendizado de máquina para analisar e classificar dados.
- DNN: Usa redes neurais para reconhecer e identificar objetos em imagens e vídeos.
- G-API: Ferramenta do OpenCV para criar e acelerar o processamento de imagens de forma mais rápida e organizada.

### Aplicações reais:

- Automação e robótica
- Detecção de obstáculos
- Fluxo óptico
- Reconhecimento de sinais de trânsito
- **Medicina**
- Segmentação de tumores
- Registro de imagem
- Pré-processamento DICOM
- Análise de contraste
- **Segurança e vigilância**
- Detecção de movimento
- Reconhecimento facial
- Alertas automáticos
- AR/VR
- Interface humano-computador
- Reconstrução 3D
- Aplicações em drones
- Aplicações em veículos autônomos.

### Pontos positivos

- O OpenCV tem código aberto no GitHub, permitindo uso, estudo, modificação e contribuição por qualquer pessoa.
- Conta com uma grande comunidade, muitos tutoriais, fóruns e documentação oficial detalhada que facilitam o aprendizado e solução de problemas.
- Suporta várias linguagens e sistemas operacionais, além de integração com frameworks como TensorFlow, PyTorch e outros.
- Oferece milhares de funções, indo de filtros simples até redes neurais avançadas.

### Concorrentes:

| Concorrente | Vantagens | Desvantagens |
| --- | --- | --- |
| **1. Pillow (PIL Fork)** | Simples de usar, ótima para manipulação básica de imagens (corte, redimensionamento, filtros), boa integração com Python puro. | Pouco voltada para visão computacional avançada, não possui recursos nativos para detecção de objetos, faces, etc. |
| **2. scikit-image** | Baseada em NumPy/SciPy, fácil integração com bibliotecas científicas, boa para processamento e análise de imagens, código limpo. | Mais lenta em operações pesadas, não é ideal para aplicações em tempo real, menos suporte para hardware acelerado. |
| **3. Dlib** | Excelente para detecção e reconhecimento facial, suporte a Machine Learning integrado, bem otimizada em C++. | Pouco flexível fora de aplicações de faces, comunidade menor que a do OpenCV. |

### Funções para serem testadas:

- Visão Computacional
- Detecção de objetos em Tempo Real
- Segmentação de imagens
- Reconhecimentos de movimentos e gestos
- Reconhecimento facial
- Realidade aumentada
- Execução de várias operações na imagem

### 2- NumPy

O NumPy é uma biblioteca essencial em Python projetada para manipulação de matrizes (*arrays*). Desenvolvido em 2005 por Travis Oliphant, seu nome deriva de Numerical **Python**.

### **Funcionalidades Principais**

- Suporte a operações avançadas de **álgebra linear** e **transformada de Fourier**.
- Manipulação de **matrizes N-dimensionais** de alto desempenho.
- Base para outras bibliotecas populares como **Pandas, Scikit-Learn, SciPy e TensorFlow.**

### **Principais Características**

- Estrutura de dados central: **`ndarray`** (*N-dimensional array*).
- **Desempenho superior** em comparação a listas padrão do Python.
- Otimizado para **dados complexos** (processamento de imagens, vídeos e *machine learning*).
- Armazenamento em **memória contígua**, melhorando a eficiência (*Localidade de Referência*).

### Ponto positivos

- **Alta velocidade** em operações numéricas.
- **Operações vetorizadas** simplificadas e eficazes.
- Integração perfeita com outras ferramentas científicas.
- Excelente para lidar com **grandes conjuntos de dados**.

### Pontos negativos

- **Dados homogêneos**: não permite misturar tipos em um mesmo *array*.
- **Suporte limitado** a operações com strings.
- Requer um **conhecimento mais avançado** para uso pleno.

## **3- Pandas**

O Pandas é uma biblioteca *open source* essencial para **ciência de dados** em Python, especializada em **manipulação e análise de dados**. Seus principais usos incluem:

- **Limpeza** de dados
- **Transformação** e preparação de dados
- **Análise exploratória** (EDA)

### Pontos positivos

- Sintaxe intuitiva :Fácil de aprender e usar
- Documentação completa :Tutoriais e exemplos abundantes
- Integração perfeita :Compatível com NumPy, Matplotlib e outras bibliotecas
- Comunidade ativa :Grande suporte no GitHub e fóruns

### Pontos negativos

- **Consumo de memória** :Pode ser ineficiente com **datasets muito grandes**
- Não otimizado para Big Data :Pode travar em volumes massivos de dados
- Alternativas recomendadas :Para grandes conjuntos, use **Spark** ou **Dask**

### **Estruturas Principais**

- Series – Array unidimensional com rótulos (índices) para cada elemento
- DataFrame – Tabela bidimensional (linhas × colunas), similar a uma planilha ou banco de dados

## **4- Matplotlib & Seaborn: Visualização de Dados em Python**

### **Matplotlib**

Biblioteca para visualização de dados em Python, responsável pela criação de gráficos e figuras.

- Funciona como base para outras bibliotecas de visualização
- Permite construir desde gráficos simples até visualizações complexas
- Oferece **controle detalhado** sobre cada elemento do gráfico

### **Seaborn**

Biblioteca construída sobre o Matplotlib que simplifica e aprimora a criação de visualizações estatísticas.

- Proporciona estilos visuais mais elegantes por padrão
- Facilita a criação de gráficos complexos com poucas linhas de código
- Ideal para **análise exploratória de dados**

### **Comparação**

| **Característica** | **Matplotlib** | **Seaborn** |
| --- | --- | --- |
| **Complexidade** | Mais detalhado, maior curva de aprendizado | Mais intuitivo e fácil de usar |
| **Personalização** | Altamente customizável | Menos flexível, mas com estilos prontos |
| **Aplicação** | Gráficos simples e complexos | Focado em visualização estatística |
| **Estética** | Requer ajustes para melhor aparência | Visual elegante por padrão |
| **Integração** | Base para outras bibliotecas | Construído sobre o Matplotlib |

### **Quando Usar Cada Uma**

- **Matplotlib:** Quando precisar de **controle total** sobre a visualização ou criar gráficos não convencionais
- Seaborn : Para **análise rápida** de dados, especialmente em estatística, com visual profissional

### **5 - Tkinter**

### **Criador**

John Ousterhout (década de 1980).

### **Pontos Positivos**:

- Facilidade de aprendizado e compatibilidade multiplataforma.
- Widgets básicos prontos e suporte a temas.
- Comunidade ativa e documentação extensa.

### **Pontos Negativos**:

- Visual desatualizado e widgets limitados para aplicações avançadas.
- Layouts pouco flexíveis e ferramentas de design não muito intuitivas.

### **Fundamentos Básicos**:

- Exemplo de código: Criação de janela, botões, labels e uso de gerenciadores de layout (**`pack`**, **`grid`**, **`place`**).

## **6 - PyQt**

### **Criador:**

Phil Thompson e Riverbank Computing (1998).

### **Pontos Positivos:**

- Interfaces modernas e multiplataforma :Adequado para aplicações profissionais.
- Qt Designer :Ferramenta visual para criação de interfaces gráficas.
- Widgets avançados :Suporte a tabelas, gráficos e integração com C++.

### **Pontos Negativos:**

- Curva de aprendizado acentuada : Mais complexo que outras bibliotecas.
- **Licenciamento:** Requer licença comercial para uso não aberto.
- Documentação voltada para C++ : Pode ser menos acessível para iniciantes em Python.

### **Funcionamento:**

- Sistema de sinais e slots :Comunicação eficiente entre componentes.
- Layouts automáticos : Facilita o dimensionamento responsivo.
- Suporte a temas :Personalização da aparência das aplicações.
