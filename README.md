# azureNLP
trains for azure NLP

# Passo 1: Acessar o Azure AI Language Studio
- Acesse o Azure AI Language Studio.
- Faça login com sua conta da Microsoft.

# Passo 2: Criar um recurso de Análise de Texto
- No painel do Azure AI Language Studio, clique em Create a resource.
- Selecione Text Analytics.
- Preencha os detalhes necessários, como nome do recurso, região e grupo de recursos.
- Clique em Review + create e depois em Create.

# Passo 3: Configurar a Análise de Sentimento e Opinião
- Após criar o recurso, vá para a seção Language Studio.
- Selecione Analyze text e depois Sentiment analysis.

# Passo 4: Insira os textos que você deseja analisar, como os meus de exemplo:

![languageCog](https://github.com/user-attachments/assets/0934f15f-38ad-462b-8060-813cec762aa2)

- Texto 1: "I had such a smooth experience opening my account! The onboarding process was straightforward, quick, and user-friendly. Everything was explained clearly, and I was able to complete the entire process without any issues. Kudos to the team for creating such an efficient flow!"
- Texto 2: "Opening an account was such a hassle. The process was confusing and took way longer than I expected. There were too many unnecessary steps, and I had to contact support multiple times to figure things out. This really needs improvement!"
Clique em Analyze.

# Passo 5: Interpretar os Resultados
## O Azure AI Language Studio fornecerá uma análise detalhada dos sentimentos e opiniões presentes nos textos.
- Para o Texto 1, você verá uma análise de sentimento positiva com opiniões destacando a experiência suave, o processo de onboarding eficiente e a clareza das explicações.
- Para o Texto 2, a análise de sentimento será negativa, com opiniões destacando a confusão, a demora no processo e a necessidade de melhorias.

# Exemplos de Resultados Esperados:

![analytics](https://github.com/user-attachments/assets/a969bfd5-9258-4ed4-8c32-f4fb285900cd)

![analyze](https://github.com/user-attachments/assets/ed4abd27-1d8b-4dc4-9be3-bb559293547b)


## Texto 1:

### Sentimento: Positivo
#### Opiniões:
- Experiência suave
- Processo de onboarding eficiente
- Clareza nas explicações
- Processo sem problemas
- Elogios à equipe

## Texto 2:

### Sentimento: Negativo
#### Opiniões:
- Processo confuso e demorado
- Passos desnecessários
- Necessidade de suporte
- Necessidade de melhorias
