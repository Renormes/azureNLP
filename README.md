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

# Insights:
## Experiência do Usuário:

- Texto 1: O usuário teve uma experiência positiva, destacando a facilidade e eficiência do processo de abertura de conta.
- Texto 2: O usuário teve uma experiência negativa, mencionando a confusão e a demora no processo.

## Clareza e Simplicidade:

- Texto 1: A clareza das instruções e a simplicidade do processo foram pontos positivos.
- Texto 2: A falta de clareza e a complexidade do processo foram pontos negativos.

## Suporte ao Cliente:

- Texto 1: Não houve necessidade de suporte, indicando um processo bem estruturado.
- Texto 2: O usuário precisou contatar o suporte várias vezes, sugerindo que o processo pode ser melhorado.

# Possibilidades
## Melhoria do Processo:

- Simplificar o processo de abertura de conta para reduzir a confusão e o tempo necessário.
Remover etapas desnecessárias para tornar o processo mais eficiente.
Aprimoramento da Comunicação:

- Melhorar a clareza das instruções fornecidas aos usuários.
Garantir que todas as etapas sejam explicadas de forma clara e concisa.
Suporte ao Cliente:

- Implementar um sistema de suporte mais eficiente para ajudar os usuários que encontram dificuldades.
Fornecer guias ou tutoriais adicionais para ajudar os usuários a completar o processo sem problemas.
Feedback Contínuo:

- Coletar feedback dos usuários regularmente para identificar áreas de melhoria.
Usar análises de sentimento para monitorar a satisfação do usuário e ajustar o processo conforme necessário.
