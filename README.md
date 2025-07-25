# 📊 Métricas de Avaliação de Classificadores

Este projeto demonstra como calcular as principais **métricas de avaliação** de modelos de classificação usando **Python**, baseado em uma **matriz de confusão arbitrária**.

O objetivo é compreender, de forma prática e clara, como funcionam as fórmulas e interpretações de métricas como:

- ✅ Acurácia
- 🎯 Precisão (Precision)
- 🔍 Sensibilidade (Recall)
- 🚫 Especificidade
- 📏 F1-Score

---

## 📘 Descrição

Dado um conjunto de valores da **matriz de confusão**:
- VP (Verdadeiros Positivos)
- VN (Verdadeiros Negativos)
- FP (Falsos Positivos)
- FN (Falsos Negativos)

O código realiza o cálculo das seguintes métricas:

| Métrica       | Fórmula                                                                 |
|---------------|-------------------------------------------------------------------------|
| Acurácia      | (VP + VN) / (VP + VN + FP + FN)                                         |
| Precisão      | VP / (VP + FP)                                                          |
| Sensibilidade (Recall) | VP / (VP + FN)                                                |
| Especificidade| VN / (VN + FP)                                                          |
| F1-Score      | 2 × (Precisão × Recall) / (Precisão + Recall)                          |

---

## 🧪 Exemplo de Uso (no Google Colab)

```python
VP = 70
VN = 50
FP = 10
FN = 20

# Executar a função
resultados = calcular_metricas(VP, VN, FP, FN)

for nome, valor in resultados.items():
    print(f"{nome}: {valor}")


🛠️ Tecnologias Utilizadas
Python 3.10+

Google Colab

GitHub

📂 Estrutura do Projeto
├── Metricas_Colab.ipynb   # Notebook principal
├── README.md              # Descrição do projeto
└── assets/
    └── ilustracao_metricas.png  # Imagem ilustrativa

👨‍💻 Autor
Desenvolvido por Ricardo Santos



---

## 🖼️ Imagem Ilustrativa

Vou agora gerar uma imagem no estilo tecnológico, com ícones ou representação gráfica de uma **matriz de confusão**, gráficos e as palavras-chave: *acurácia, precisão, recall, F1-score*.
Estilo nerd/moderno, cores azul e verde escuro.

Aguarde um instante enquanto gero a imagem... 🎨  
