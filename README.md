# 🚢 Análise de Clusterização Não Supervisionada - Dataset Titanic

## 📋 Descrição do Projeto

Projeto acadêmico comparando algoritmos de clusterização não supervisionada (K-Means e K-Prototypes) 
aplicados ao dataset Titanic, com foco na segmentação de passageiros e extração de regras interpretáveis.

## 🎯 Objetivos

- Comparar K-Means e K-Prototypes em dados mistos (numéricos + categóricos)
- Identificar o número ótimo de clusters usando múltiplas métricas
- Extrair regras interpretáveis usando Árvores de Decisão
- Analisar perfis dos clusters identificados

## 🛠️ Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas & NumPy** - Manipulação de dados
- **Scikit-learn** - Machine Learning
- **KModes** - K-Prototypes
- **Matplotlib & Seaborn** - Visualização
- **Jupyter Notebook** - Desenvolvimento interativo

## 📦 Instalação

### 1. Clone o repositório
```bash
git clone https://github.com/jvictornobre27/titanic-clustering-project.git
cd titanic-clustering-project
```

### 2. Crie um ambiente virtual
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Execute o Jupyter Notebook
```bash
jupyter notebook notebooks/titanic_clustering.ipynb
```

## 📊 Estrutura do Notebook

1. **Setup & Configuração** - Importação de bibliotecas
2. **Carregamento de Dados** - Dataset Titanic
3. **Pré-processamento** - Limpeza e tratamento de nulos
4. **EDA** - Análise exploratória visual
5. **K-Means** - Implementação e otimização
6. **K-Prototypes** - Implementação e otimização
7. **Análise de Resultados** - Perfis dos clusters
8. **Extração de Regras** - Árvore de Decisão
9. **Conclusões** - Insights e recomendações

## 📚 Referências

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [K-Prototypes Paper](https://link.springer.com/article/10.1007/s001800050075)
- [Are You Still Using the Elbow Method?](https://github.com/smazzanti/are_you_still_using_elbow_method)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.