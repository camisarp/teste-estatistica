<h1 align="center">
  <img src="assets/reprograma-fundos-claros.png" alt="logo reprograma" width="500">
</h1>

<h1 align="center">  Estatística com Python: Probabilidade e Amostragem 📊 </h1>
<h3 align="center">  Turma ON29 | Python | Semana 12 | 2024 | Professora Camila Ribeiro  </h3>

<br>

### Instruções

Antes de começar, vamos organizar nosso setup.


    1. Fork esse repositório

    2. Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)

    3. Entre na pasta do seu repositório (Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`)


<br>

# Índice

- [1. Introdução à Estatística](./1-introducao-a-estatistica.md)
    - [1.1 Estatística: Definição e Importância](./1-introducao-a-estatistica.md#11-estatistica-definicao-e-importancia)
        - [1.1.1 Importância de Estudar Estatística](./1-introducao-a-estatistica.md#111-importancia-de-estudar-estatistica)
        - [1.1.2 Vantagens de Estudar Estatística](./1-introducao-a-estatistica.md#112-vantagens-de-estudar-estatistica)
        - [1.1.3 Desvantagens de Estudar Estatística](./1-introducao-a-estatistica.md#113-desvantagens-de-estudar-estatistica)
        - [1.1.4 Preconceitos](./1-introducao-a-estatistica.md#114-preconceitos)
        - [1.1.5 Estatística em Tecnologia](./1-introducao-a-estatistica.md#115-estatistica-em-tecnologia)
    - [1.2 Tipos de Dados](./1-introducao-a-estatistica.md#12-tipos-de-dados)
        - [1.2.1 Dados Qualitativos (Categóricos)](#121-dados-qualitativos-categoricos)
        - [1.2.2 Dados Quantitativos (Numéricos)](#122-dados-quantitativos-numericos)
            - [1.2.2.1 Dados Quantitativos Discretos](#1221-dados-quantitativos-discretos)
            - [1.2.2.2 Dados Quantitativos Contínuos](#1222-dados-quantitativos-continuos)
    - [1.3 Medidas Descritivas](./1-introducao-a-estatistica.md#13-medidas-descritivas)
        - [1.3.1 Média](./1-introducao-a-estatistica.md#131-media)
        - [1.3.2 Mediana](./1-introducao-a-estatistica.md#132-mediana)
        - [1.3.3 Moda](./1-introducao-a-estatistica.md#133-moda)
        - [1.3.4 Variância](./1-introducao-a-estatistica.md#134-variancia)
        - [1.3.5 Desvio Padrão](./1-introducao-a-estatistica.md#135-desvio-padrao)
    - [1.4 Em Resumo](./1-introducao-a-estatistica.md#14-em-resumo)
- [2. Python para Estatística](./2-python-para-estatistica.md)
    - [2.1 Instalação e Configuração do Ambiente Python](./2-python-para-estatistica.md#21-instalacao-e-configuracao-do-ambiente-python)
    - [2.2 Bibliotecas Essenciais](./2-python-para-estatistica.md#22-bibliotecas-essenciais)
        - [2.2.1 NumPy](./2-python-para-estatistica.md#221-numpy)
        - [2.2.2 Pandas](./2-python-para-estatistica.md#222-pandas)
    - [2.3 Demonstração Prática de Manipulação de Dados com NumPy e Pandas](./2-python-para-estatistica.md#23-demonstracao-pratica-de-manipulacao-de-dados-com-numpy-e-pandas)
    - [2.4 Em Resumo](./2-python-para-estatistica.md#24-em-resumo)
- [3. Probabilidade](./3-probabilidade.md)
    - [3.1 Definição de Probabilidade e Eventos](./3-probabilidade.md#31-definicao-de-probabilidade-e-eventos)
    - [3.2 Espaço Amostral](./3-probabilidade.md#32-espaco-amostral)
    - [3.3 Tipos de Probabilidade](./3-probabilidade.md#33-tipos-de-probabilidade)
        - [3.3.1 Probabilidade Clássica](./3-probabilidade.md#331-probabilidade-classica)
        - [3.3.2 Probabilidade Frequentista](./3-probabilidade.md#332-probabilidade-frequentista)
        - [3.3.3 Probabilidade Subjetiva](./3-probabilidade.md#333-probabilidade-subjetiva)
    - [3.4 Regras de Probabilidade](./3-probabilidade.md#34-regras-de-probabilidade)
        - [3.4.1 Regra da Soma](./3-probabilidade.md#341-regra-da-soma)
        - [3.4.2 Regra da Multiplicação](./3-probabilidade.md#342-regra-da-multiplicacao)
        - [3.4.3 Probabilidade Condicional](./3-probabilidade.md#343-probabilidade-condicional)
- [4. Probabilidade com Python](./4-probabilidade-com-python.md)
    - [4.1 Simulação de Eventos Aleatórios com Python](./4-probabilidade-com-python.md#41-simulacao-de-eventos-aleatorios-com-python)
    - [4.2 Cálculo de Probabilidade com Funções da Biblioteca NumPy](./4-probabilidade-com-python.md#42-calculo-de-probabilidade-com-funcoes-da-biblioteca-numpy)
    - [4.3 Criação de Gráficos de Probabilidade com Matplotlib](./4-probabilidade-com-python.md#43-criacao-de-graficos-de-probabilidade-com-matplotlib)
- [5. Amostragem](./5-amostragem.md)
    - [5.1 Métodos de Amostragem](./5-amostragem.md#51-metodos-de-amostragem)
        - [5.1.1 Amostragem Aleatória Simples](./5-amostragem.md#511-amostragem-aleatoria-simples)
        - [5.1.2 Amostragem Estratificada](./5-amostragem.md#512-amostragem-estratificada)
        - [5.1.3 Amostragem por Conglomerados](./5-amostragem.md#513-amostragem-por-conglomerados)
        - [5.1.4 Amostragem Sistemática](./5-amostragem.md#514-amostragem-sistematica)
        - [5.1.5 Erros Amostrais e Intervalos de Confiança](./5-amostragem.md#515-erros-amostrais-e-intervalos-de-confianca)
- [6. Amostragem com Python](./6-amostragem-com-python.md)
    - [6.1 Implementação de Métodos de Amostragem com Pandas e NumPy](./6-amostragem-com-python.md#61-implementacao-de-metodos-de-amostragem-com-pandas-e-numpy)
    - [6.2 Cálculo de Estatísticas Descritivas e Intervalos de Confiança](./6-amostragem-com-python.md#62-calculo-de-estatisticas-descritivas-e-intervalos-de-confianca)
    - [6.3 Visualização de Dados com Matplotlib](./6-amostragem-com-python.md#63-visualizacao-de-dados-com-matplotlib)

<p align="center">
Desenvolvido com :purple_heart:  
</p>
