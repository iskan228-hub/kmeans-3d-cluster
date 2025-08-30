# Clusterização em 3D com K-Means

Projeto desenvolvido para a disciplina **Aprendizado de Máquina Não Supervisionado** do **4º semestre do curso Tecnólogo em Ciência de Dados** da **Faculdade de Tecnologia e Inovação Senac DF**, sob orientação do **professor Rogério Gomes Lopes**.  

O trabalho consiste na aplicação do algoritmo **K-Means** a **três variáveis contínuas**, com foco em **aprendizado não supervisionado** e **visualização tridimensional dos clusters**.  

Entrega destinada à **obtenção de nota parcial no primeiro bimestre**.

---

## ✨ Objetivos
- Explorar um dataset real com três variáveis contínuas.  
- Aplicar técnicas de **clusterização não supervisionada**.  
- Gerar **visualizações 3D** para interpretação dos clusters.  
- Produzir relatório e código reprodutível.

---

## 🗂️ Dataset
- **Fonte oficial**: [Distribuição de Renda – dados.gov.br](https://dados.gov.br/dados/conjuntos-dados/distribuio-de-renda)  
- **Dataset bruto**: `data/raw/distribuicao-renda.csv`  
- **Dataset tratado (3 variáveis)**: `data/processed/distribuicao-renda-3vars.csv`  

Variáveis contínuas selecionadas:
1. **Rendimentos Tributáveis – Soma da RTB do Centil**  
   → Representa a renda declarada pelos grupos (capacidade econômica).  
2. **Bens e Direitos – Imóveis**  
   → Indica acumulação patrimonial em imóveis.  
3. **Dívidas e Ônus**  
   → Mostra o endividamento declarado, completando o perfil econômico.  

Essas variáveis permitem formar um espaço tridimensional (renda, patrimônio e dívida) para análise de clusters.

---

## 🛠️ Tecnologias
- Python 3.13  
- Pandas, NumPy, Scikit-learn  
- Seaborn, Matplotlib, Plotly  
- Jupyter Notebook (VS Code)  

---

## ▶️ Como executar
```bash
# Clonar o repositório
git clone https://github.com/PadawanXXVI/kmeans-3d-cluster.git
cd kmeans-3d-cluster
```

# Criar ambiente virtual (opcional)
python -m venv .venv
source .venv/Scripts/activate  # Windows (bash)
# ou
source .venv/bin/activate      # Linux/Mac

# Instalar dependências
pip install -r requirements.txt

# Rodar notebooks
jupyter notebook

## 📂 Estrutura do repositório
├── data/  
│   ├── raw/         # dataset original (CSV completo)  
│   └── processed/   # dataset tratado com 3 variáveis  
├── notebooks/       # exploração e clusterização  
├── src/             # scripts de preparação e modelo  
├── reports/         # figuras e relatórios  
├── requirements.txt  
├── README.md  
└── LICENSE

## 👥 Equipe
- Anderson de Matos Guimarães  
- Gustavo Stefano Thomazinho  
- Renan Ost  
