# 📊 Análise de dados dos indicadores de vendas do varejo brasileiro

Projeto desenvolvido para a disciplina extensionista **Tópicos de Big Data com Python**.

## 📖 Sobre o projeto

O objetivo deste projeto foi realizar a extração, tratamento e análise de dados referentes aos **Indicadores de Volume de Vendas do Comércio Varejista**, disponibilizados pelo **Instituto Brasileiro de Geografia e Estatística (IBGE)**.

O foco da análise foi a categoria:

- Artigos farmacêuticos, médicos, ortopédicos, de perfumaria e cosméticos.

Os dados foram obtidos a partir de diversos relatórios em PDF publicados pelo IBGE, referentes aos anos de 2020 à 2025. Após a extração das informações, os dados foram organizados em tabelas e utilizados para a geração de gráficos que permitem visualizar a evolução dos indicadores ao longo do tempo.

---

## 🎯 Objetivos

- Extrair informações de documentos PDF do IBGE;
- Automatizar a leitura de dados utilizando Python;
- Tratar e organizar os dados coletados;
- Construir visualizações gráficas para análise dos indicadores;
- Aplicar conceitos de Big Data e Ciência de Dados estudados na disciplina.

---

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- pdfplumber
- pytesseract (OCR)
- OpenCV
- Pillow
- pdf2image
- NumPy
- Expressões Regulares (Regex)

---

## 📚 Bibliotecas

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import pdfplumber
import pytesseract
from PIL import Image
from pdf2image import convert_from_path
import cv2
import numpy as np
import re
import os
import unicodedata
```

---

## 📂 Estrutura do projeto

```
.
├── Pesquisa-Comercio/
│   ├── PDFs do IBGE
│   └── Dados utilizados
├── Projeto_Final_TopicosBigData.ipynb
└── README.md
```

---

## 📈 Etapas do projeto

1. Coleta dos relatórios do IBGE em formato PDF;
2. Extração automática dos dados utilizando Python;
3. Aplicação de OCR quando necessário;
4. Tratamento e organização dos dados;
5. Construção de tabelas;
6. Geração de gráficos para análise dos indicadores.

---

## ▶️ Como executar

1. Clone este repositório.

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
```

2. Instale as dependências.

```bash
pip install pandas matplotlib seaborn pdfplumber pytesseract pillow pdf2image opencv-python numpy
```

3. Instale também:

- Tesseract OCR
- Poppler

4. Abra o notebook `Projeto_Final_TopicosBigData.ipynb` em Jupyter Notebook ou Google Colab.

---

## 👩‍💻 Autora

**Bárbara Gabriela**

## 👥 Equipe
-Bianca Rafaela
-Wesley Augusto
-Gabriel Auvarenga

Projeto desenvolvido como atividade extensionista da disciplina **Tópicos de Big Data com Python**.
