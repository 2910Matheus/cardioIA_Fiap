# 🫀 CardioIA – Base de Dados para IA em Saúde

Este repositório reúne diferentes tipos de dados (numéricos, textuais e visuais) que servirão como base para os módulos inteligentes do **CardioIA**.  
Os dados foram preparados de forma **simulada** ou coletados de **fontes públicas**, sempre respeitando a Governança de Dados e princípios éticos.

---

## 📊 Parte 1 – Dados Numéricos (IoT)

Foi gerado um dataset com **120 pacientes fictícios** contendo variáveis relevantes para análise de risco cardíaco.  

📂 [Acesse o CSV aqui](https://drive.google.com/drive/folders/1VSFq5e2YQxjvuB5MYGnulymHIon4ICaQ?usp=sharing)

### 🔑 Variáveis incluídas
- **Idade (anos)** → risco cardiovascular aumenta com a idade.  
- **Sexo (M/F)** → há diferenças de incidência entre homens e mulheres.  
- **Pressão arterial (sistólica e diastólica)** → hipertensão é um dos maiores fatores de risco.  
- **Colesterol (mg/dL)** → níveis elevados podem causar aterosclerose.  
- **Histórico familiar** → indica predisposição genética.  
- **Fumante (sim/não)** → aumenta chance de infarto.  
- **Diabetes (sim/não)** → fortemente associado a complicações cardiovasculares.  
- **Frequência cardíaca (bpm)** → bradicardia ou taquicardia são sinais de alerta.  
- **Sintomas relatados** → dor no peito, falta de ar, palpitação.  
- **Risco cardíaco (baixo/médio/alto)** → variável alvo para treinar modelos de predição.  

### 💡 Relevância
Esse conjunto de dados pode ser usado para **treinar modelos de Machine Learning** (classificação de risco), análises estatísticas e até simulação de sistemas IoT hospitalares.

---

## 📝 Parte 2 – Dados Textuais (NLP)

Adicionamos três textos em formato `.txt` na pasta [`docs/`](./docs/):

1. **cases_organic_heart.txt** – *“Cases of Organic Diseases of the Heart”*, John C. Warren (1809).  
2. **heart_disease_age.txt** – *“Heart Disease in Middle and Advanced Age”*, J. Mitchell Bruce (1902).  
3. **revisao_cardiovascular.txt** – revisão rápida sobre **doenças cardiovasculares, fatores de risco e desafios para controle na Atenção Primária à Saúde**, disponível via ResearchGate.

###  Possibilidades de uso em NLP
- **Extração de sintomas e fatores de risco**: identificar termos como “hipertensão”, “tabagismo”, “sedentarismo”, “diabetes”, “controle na atenção primária”.  
- **Classificação por temas**: separar seções sobre epidemiologia, prevenção, fatores de risco, estratégias de controle.  
- **Análise comparativa**: comparar linguagem e foco entre textos históricos (John C. Warren, J. Mitchell Bruce) e texto atual (atualidades em saúde pública).  
- **Modelagem de tópico**: identificar padrões como “orientação comunitária”, “prevenção primária”, “educação em saúde”, “impacto social”.

###  Relevância
- O texto moderno traz uma **perspectiva atual de saúde pública**, o que amplia o escopo de análise além de linguagem clínica, incluindo políticas de saúde e estratégias de controle.  
- Ajuda a desenvolver **modelos de NLP mais robustos**, capazes de lidar tanto com vocabulário médico clássico quanto com linguagem de saúde pública contemporânea.  
- Pode suportar a criação de **ferramentas de suporte à decisão em atenção primária**, identificando riscos e propondo diretrizes adaptadas ao contexto atual.



---

## 🖼️ Parte 3 – Dados Visuais (Visão Computacional)

Foi reunido um conjunto de **700 imagens médicas de raio-X de tórax (Chest X-ray Dataset for Tuberculosis Segmentation)**.  

📂 [Acesse as imagens aqui](https://drive.google.com/drive/folders/1bPiEVe0IoOlX0OOFPATql8eWJs-EgnU8?usp=sharing)

### 🔎 Possibilidades de uso em Visão Computacional
- **Detecção de padrões**: identificar alterações em exames.  
- **Reconhecimento de anomalias**: diferenciar exames normais de patológicos.  
- **Segmentação**: separar pulmões, costelas e área cardíaca.  
- **Treinamento de CNNs**: classificar exames e apoiar diagnóstico.  

### 💡 Relevância
Imagens médicas são fundamentais para IA na saúde. Com técnicas de Visão Computacional, é possível **detectar doenças precocemente**, apoiar médicos em triagens e aumentar a precisão de diagnósticos.

---

## ⚠️ Observações
- Nenhum dado pessoal real foi utilizado.  
- Dados **numéricos foram simulados**.  
- Textos e imagens foram obtidos de **fontes públicas de acesso livre**.  
- Todo material tem caráter **acadêmico e educacional**.  
