# Challenge Telecom X: Análise de Evasão de Clientes-Parte-2

# 📊 Pipeline de Modelagem Preditiva em Telecom  

## 📌 Descrição  
O notebook **TelecomX_2_.ipynb** apresenta um fluxo completo de **análise exploratória** e **modelagem preditiva** aplicado a dados do setor de telecomunicações.  
O objetivo principal é construir modelos capazes de **prever churn (evasão de clientes)** ou situações de **inadimplência**, utilizando ferramentas de ciência de dados.  
Cada etapa foi documentada com comentários explicativos, permitindo fácil compreensão, replicação e adaptação para outros cenários.  

---

## 🗂️ Estrutura do Notebook  

1. **Importação de pacotes essenciais**  
2. **Carregamento e inspeção inicial dos dados**  
3. **Análise exploratória (EDA):** distribuição de variáveis, relações entre atributos e churn.  
4. **Pré-processamento:**  
   - Conversão de tipos de variáveis  
   - Tratamento de valores faltantes  
   - Criação de variáveis dummy (OneHotEncoder, get_dummies)  
   - Balanceamento de classes (SMOTE, NearMiss)  
5. **Divisão em dados de treino e teste**  
6. **Modelagem:**  
   - DummyClassifier (baseline)  
   - DecisionTreeClassifier  
   - RandomForestClassifier  
   - Regressão Logística  
   - KNeighborsClassifier  
   - Validação cruzada (KFold e StratifiedKFold)  
7. **Avaliação dos modelos:**  
   - Métricas: Acurácia, Recall, Precisão, F1-score  
   - Matriz de confusão e Curva ROC  
   - Importância das variáveis  
8. **Conclusão e recomendações**  

---

## ▶️ Como Executar  

1. **Pré-requisitos:** Python 3.8 ou superior.  
2. Instale as dependências:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
