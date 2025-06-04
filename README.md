
🎵 Spotify Top 50 Brasil Analysis

Análise exploratória e visual dos dados das 50 músicas mais populares do Brasil segundo o Spotify. O projeto visa entender padrões musicais, identificar artistas e gêneros predominantes e construir um modelo preditivo leve com base em características como danceabilidade, energia e popularidade.

---

 📁 Estrutura do Projeto

```
spotify-top-brasil-analysis/
│
├── data/                       # Arquivo CSV com dados do Spotify
│   └── top50.csv
│
├── notebooks/                 # Análise em Jupyter Notebook
│   └── spotify_top50_analysis.ipynb
│
├── requirements.txt           # Bibliotecas necessárias
└── README.md                  # Este arquivo
```

---

🔧 Tecnologias Utilizadas

- Python 3.10+
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- Scikit-Learn

---

 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/TeuzB/spotify-top-brasil-analysis.git
   ```

2. Acesse o diretório:
   ```bash
   cd spotify-top-brasil-analysis
   ```

3. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   venv\Scripts\activate  # no Windows
   ```

4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

5. Execute o notebook:
   ```bash
   jupyter notebook notebooks/spotify_top50_analysis.ipynb
   ```

🔍 Principais Insights

- Gêneros como Pop, Funk e Sertanejo são predominantes nas 50 músicas mais tocadas.
- Artistas como **Anitta**, **MC Ryan SP** e **Jorge & Mateus** aparecem mais de uma vez.
- A **popularidade** tem correlação moderada com atributos como **energia** e **danceabilidade**.
- Utilizando **regressão linear**, conseguimos prever a popularidade de uma música com base em seus atributos musicais.

---

📦 Modelo Preditivo

O modelo de regressão linear foi treinado para prever a popularidade com base nos seguintes atributos:

- bpm
- danceabilidade
- energia

Embora simples, o modelo mostrou uma relação razoável entre os dados e o valor previsto, sendo útil como ponto de partida para futuras versões mais robustas.

---

👤 Autor

**Mateus Barbosa. (TeuzB)**  
📍 Belo Horizonte, Brasil  
🔗 [GitHub](https://github.com/TeuzB)
🔗 [LinkedIn](https://www.linkedin.com/in/mateus-oliveira-535ba2245/)

---

📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar, modificar e distribuir com os devidos créditos.

---

⭐ Considerações finais

Este projeto foi desenvolvido com foco em aprendizado de análise de dados, visualização e modelagem preditiva simples. A base de dados limitada em relação ao número totais e fixos de músicas traz restrições estatísticas, mas permite explorar conceitos fundamentais de **Data Science com música** de forma acessível.
