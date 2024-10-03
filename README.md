
![image](https://github.com/user-attachments/assets/5d3b4e1e-f751-4e11-bd75-34a8f8a74aad)



# 🚀 Data Viking's Foundation

## 🌟 Descrição

O **Data Viking's Foundation** é um programa de analytics avançado projetado para auxiliar equipes de dados na seleção da melhor abordagem para resolver problemas de análise. Este projeto fornece uma árvore de decisão visual que guia os usuários através de diferentes metodologias, considerando a natureza específica do problema enfrentado. 

Nosso objetivo é estabelecer uma base sólida para as práticas de análise de dados, promovendo decisões informadas e eficientes. O programa foi criado tanto para iniciantes quanto para profissionais experientes que buscam otimizar suas abordagens analíticas.

## 💡 Motivação

Na era dos dados, as equipes enfrentam uma variedade crescente de desafios analíticos. Com tantas técnicas e modelos disponíveis, pode ser difícil determinar a melhor abordagem para um problema específico e de fato conseguir eliminar vieses e ter uma analise assertiva. O **Data Viking's Foundation** busca simplificar esse processo, oferecendo guias confiáveis na escolha de metodologias e trabalhando em casos práticos com o intuito de provar valor e resultado atraves do uso eficiente dos dados.

## 📋 Funcionalidades

- **🌳 Árvore de Decisão Interativa**: Visualização intuitiva das abordagens analíticas, organizadas em uma estrutura hierárquica.
- **🔍 Orientação de Métodos**: Sugestões detalhadas de modelos e técnicas específicas, adaptadas ao tipo de problema.
- **💾 Download de Imagem**: Geração e download da árvore de decisão em formato PNG.
- **🛠️ Exemplos de Aplicação**: Cenários práticos que ilustram como utilizar as recomendações.
- **📖 Documentação**: Descrições abrangentes das abordagens e suas aplicações, incluindo vantagens e desvantagens.

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal para o desenvolvimento do projeto.
- **Graphviz**: Biblioteca para a criação de gráficos direcionados e visualizações.
- **Google Colab**: Ambiente de desenvolvimento colaborativo para execução do código.

## 🌐 Estrutura da Árvore de Decisão

A árvore de decisão é dividida em várias seções, cada uma representando um tipo de problema de análise. Aqui estão algumas categorias principais:

### 1. 📈 Previsão
- **Métodos**: Modelos de Regressão, Séries Temporais.
- **Uso**: Previsão de métricas como vendas, demanda ou preços.

### 2. 📊 Classificação
- **Métodos**: Regressão Logística, Árvores de Decisão, Random Forests.
- **Uso**: Problemas como detecção de fraude, classificação de feedback e segmentação de clientes.

### 3. 📝 Análise de Sentimentos
- **Métodos**: Técnicas de Processamento de Linguagem Natural (NLP) como TF-IDF, BERT.
- **Uso**: Análise de opiniões e sentimentos em dados textuais.

### 4. 📊 Causalidade
- **Métodos**: Inferência Causal, A/B Testing.
- **Uso**: Entender relações de causa e efeito entre variáveis.

### 5. 📊 Estimativa Probabilística
- **Métodos**: Inferência Bayesiana, Modelos Estatísticos Tradicionais.
- **Uso**: Incorporar conhecimento prévio ou estimar incertezas.

### 6. 🏷️ Outros Problemas
- **Métodos**: Análise de Variância (ANOVA), Modelagem de Elasticidade de Preço.
- **Uso**: Análise da eficácia de campanhas de marketing e otimização de preços.

## 🚀 Como Usar

### Passo a Passo

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/diegoborgeszup/data-vikings-foundation.git
   cd data-vikings-foundation

2. **Execute o Código no Google Colab**:
   - Abra o Google Colab e faça upload do arquivo `.ipynb` presente no repositório.
   - Execute as células do código para gerar a árvore de decisão.

3. **Visualize e Faça Download**:
   - A árvore de decisão será exibida após a execução.
   - O arquivo PNG gerado será baixado automaticamente.


### Exemplos de Aplicação

---

#### Cenário 1: Prever Vendas
- **Problema**: Sua equipe precisa prever as vendas para o próximo trimestre.
- **Recomendação**: Utilize **Modelos de Regressão** ou **Séries Temporais**.
- **Aplicação**: Aplique um modelo de regressão linear com dados históricos de vendas, considerando variáveis como sazonalidade, promoções e eventos especiais. Utilize métricas como RMSE (Root Mean Square Error) para validar o modelo.

---

#### Cenário 2: Classificar Feedback de Clientes
- **Problema**: Analisar feedback de clientes para melhorar produtos.
- **Recomendação**: Empregue **Árvores de Decisão** ou **Random Forests**.
- **Aplicação**: Colete feedback textual através de formulários e redes sociais. Aplique técnicas de pré-processamento de texto (como tokenização e remoção de stop words) e um modelo de classificação para identificar sentimentos (positivo, negativo, neutro) e temas recorrentes.

---

#### Cenário 3: Prever Churn de Clientes
- **Problema**: Sua empresa deseja entender a taxa de churn de seus clientes.
- **Recomendação**: Utilize **Modelos de Classificação**.
- **Aplicação**: Aplique um modelo de Regressão Logística, usando dados como histórico de compras, interações com o atendimento e uso do produto. Identifique variáveis preditoras e utilize validação cruzada para otimizar o modelo.

---

#### Cenário 4: Detecção de Fraude em Transações
- **Problema**: Sua equipe precisa identificar transações fraudulentas em tempo real.
- **Recomendação**: Utilize **Detecção de Anomalias** (ex: Isolation Forest).
- **Aplicação**: Analise transações financeiras em tempo real, identificando padrões normais de comportamento. Use métricas como a taxa de falsos positivos e a precisão do modelo para ajustar a sensibilidade da detecção.

---

#### Cenário 5: Análise de Sentimentos em Redes Sociais
- **Problema**: Analisar a percepção dos consumidores em relação a um novo produto nas redes sociais.
- **Recomendação**: Utilize **Técnicas de NLP** (ex: TF-IDF, BERT).
- **Aplicação**: Extraia dados textuais de comentários e postagens em redes sociais. Aplique técnicas de análise de sentimentos para classificar opiniões e identifique temas predominantes usando métodos de clustering para agrupar sentimentos semelhantes.

---

#### Cenário 6: Estimativa de Tempo de Resposta em Serviços
- **Problema**: Sua equipe quer melhorar o tempo de resposta de um serviço ao cliente.
- **Recomendação**: Utilize **Modelos de Séries Temporais**.
- **Aplicação**: Analise dados históricos de atendimento ao cliente, levando em conta variáveis como horários de pico e tipos de solicitações. Utilize modelos como ARIMA ou Holt-Winters para prever e otimizar os tempos de resposta.

---

#### Cenário 7: Segmentação de Clientes para Marketing
- **Problema**: Deseja segmentar clientes para campanhas de marketing mais eficazes.
- **Recomendação**: Utilize **Clustering** (ex: K-means).
- **Aplicação**: Agrupe clientes com base em características demográficas, comportamentais e transacionais. Utilize a técnica do "cotovelo" para determinar o número ideal de clusters e analise cada grupo para direcionar campanhas específicas.

---

#### Cenário 8: Análise de Eficácia de Campanhas de Marketing
- **Problema**: Avaliar o impacto de diferentes campanhas de marketing sobre as vendas.
- **Recomendação**: Utilize **Análise de Variância (ANOVA)**.
- **Aplicação**: Compare as vendas entre grupos que participaram de diferentes campanhas. Utilize testes estatísticos para validar se as diferenças observadas nas vendas são significativas e identifique quais campanhas foram mais eficazes.

---

#### Cenário 9: Modelagem de Preços
- **Problema**: Precificar produtos de forma a maximizar a receita.
- **Recomendação**: Utilize **Modelagem de Elasticidade de Preço**.
- **Aplicação**: Analise como as variações de preço afetam a demanda, utilizando dados históricos de vendas e preços. Realize experimentos A/B para testar diferentes preços e determine o ponto de preço ideal para maximizar a receita.

---

#### Cenário 10: Análise de Tendências de Vendas
- **Problema**: Identificar tendências de vendas ao longo do tempo.
- **Recomendação**: Utilize **Análise de Tendências**.
- **Aplicação**: Examine dados históricos de vendas para identificar padrões e tendências sazonais. Utilize gráficos de séries temporais e decomposição para visualizar tendências e prever vendas futuras com base em padrões identificados.


---

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tem sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou um pull request. Para contribuir:

1. Faça um fork do projeto.
2. Crie sua branch de funcionalidade (`git checkout -b feature/nome-da-funcionalidade`).
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`).
4. Faça push para sua branch (`git push origin feature/nome-da-funcionalidade`).
5. Abra um Pull Request.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 🌍 Comunidade

Participe da discussão! Sinta-se à vontade para abrir uma issue para discutir melhorias ou compartilhar experiências com o projeto. Acompanhe as atualizações no repositório.

## 📫 Contato

Para mais informações, entre em contato com:

- Diego Alberone / diego.borges@zup.com.br / [diegoborgeszup](https://github.com/diegoborgeszup)

- Leonardo Borges / user@zup.com.br / [seuusuario](https://github.com/user1)

- Renato Lotto / user@zup.com.br / [seuusuario](https://github.com/user1)

- Yago Luciano / user@zup.com.br / [seuusuario](https://github.com/user1)
  

Agradecemos seu interesse no **Data Viking's Foundation** e esperamos que este programa ajude você e sua equipe a otimizar suas análises de dados! 

---

                                             ![image](https://github.com/user-attachments/assets/ee2dddc9-abf7-4217-93a2-2b5f0a1e03c4)
