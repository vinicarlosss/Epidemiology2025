# Modelo SIR Aplicado aos Dados de Dengue em São Paulo

## 📌 Descrição do Projeto
Este projeto tem como objetivo modelar a disseminação da dengue na cidade de São Paulo utilizando o modelo SIR (Sucetíveis, Infectados e Recuperados). O código processa os dados reais da doença e ajusta os parâmetros epidemiológicos para simular sua propagação ao longo do tempo.

## 📊 Sobre o Modelo SIR
O modelo SIR é amplamente utilizado para estudar a dinâmica de doenças infecciosas e é baseado em três grupos populacionais:
- **S (Sucetíveis):** Indivíduos que podem contrair a doença.
- **I (Infectados):** Indivíduos atualmente infectados e capazes de transmitir a doença.
- **R (Recuperados):** Indivíduos que se recuperaram e não podem mais ser infectados.

Neste projeto, utilizamos os dados da cidade de São Paulo para calcular a taxa de infecção (β) e modelar o comportamento da epidemia.

## 🛠 Tecnologias Utilizadas
- Python 3
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- mplcursors

## 📁 Estrutura do Projeto
```
📂 Projeto_SIR_Dengue
│-- 📂 data
│   ├── data.xlsx  # Base de dados contendo os registros semanais de casos de dengue
│-- 📜 main.py      # Código principal para processamento e visualização dos dados
│-- 📜 README.md    # Documentação do projeto
```

## 🔧 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/projeto_SIR_Dengue.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd projeto_SIR_Dengue
   ```
3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute o script principal:
   ```bash
   python main.py
   ```

## 📈 Visualização dos Dados
O código gera um gráfico que mostram a evolução das três populações (Sucetíveis, Infectados e Recuperados) ao longo das semanas. Os dados são normalizados para facilitar a comparação entre os grupos.

## 📑 Fontes de Dados
Os dados utilizados foram extraídos de registros epidemiológicos e processados para aplicação no modelo SIR. O arquivo `data.xlsx` contém as informações semanais de casos de dengue na cidade de São Paulo.

