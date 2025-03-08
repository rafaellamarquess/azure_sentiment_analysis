Este projeto utiliza o serviço de IA do Azure para analisar sentimentos em sentenças sobre um estabelecimento. A seguir, descrevemos o processo, insights e possibilidades observadas.

## Documentação do projeto

1. **Criando a pasta de entradas**
   - Foi criado uma pasta chamada `inputs` e adicionado um arquivo `sentencas.txt` contendo as seguintes frases sobre um estabelecimento de *Pet Shop*.
    ![Screenshot_20250308_110142](https://github.com/user-attachments/assets/0721d45c-34fe-4a67-9ee2-22352925b0ba)


2. **Utilizando o Azure AI para análise de sentimentos**
   - O serviço de IA do Azure foi utilizado para processar as frases e classificar os sentimentos como positivos, neutros ou negativos.

3. **Resultados e insights**
   - **Sentimento geral:** `mixed`
   - **Pontuações:**
     - Positivo: **75%**
     - Neutro: **4%**
     - Negativo: **21%**
   
### Análise de Frases
   - Após a análise, observamos que frases com palavras-chave positivas foram corretamente classificadas como "positivas".
   - Frases contendo críticas foram marcadas como "negativas".
   - Algumas frases neutras ou ambíguas tiveram classificações variadas, mostrando a importância do contexto na análise.

| Frase | Sentimento | Positivo | Neutro | Negativo |
|-------|-----------|----------|--------|----------|
| 1 | Positive | 100% | 0% | 0% |
| 2 | Neutral | 6% | 93% | 1% |
| 3 | Positive | 100% | 0% | 0% |
| 4 | Positive | 100% | 0% | 0% |
| 5 | Negative | 3% | 17% | 81% |
| 6 | Positive | 100% | 0% | 0% |
| 7 | Positive | 100% | 0% | 0% |
| 8 | Negative | 23% | 9% | 68% |

![Screenshot_20250308_110301](https://github.com/user-attachments/assets/a06e7bec-4386-4e83-942c-8c2333bf0ccb)
![Screenshot_20250308_110353](https://github.com/user-attachments/assets/aedd7623-0a80-4e7d-a1d6-de874976eaa7)




## Possibilidades de Aplicação

- **Monitoramento de feedback de clientes**: Empresas podem utilizar essa tecnologia para acompanhar a satisfação dos clientes em redes sociais e avaliações.
- **Automação de respostas**: Bots podem responder automaticamente a avaliações com base no sentimento identificado.
- **Aprimoramento de produtos e serviços**: A análise contínua de sentimentos pode ajudar negócios a identificar tendências e pontos de melhoria.
