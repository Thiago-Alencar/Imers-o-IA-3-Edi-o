# Sistema Inteligente de Divulgação de Campanhas de Doação no LinkedIn - Uma Imersão Alura

Este projeto é o resultado prático do conhecimento e das habilidades adquiridas durante a **Imersão IA com Google Gemini  ** oferecida pela **Alura** ([https://cursos.alura.com.br/](https://cursos.alura.com.br/)). Ele demonstra a aplicação de agentes inteligentes, impulsionados pela tecnologia Google AI, para otimizar a divulgação de campanhas de doação na plataforma profissional LinkedIn.

## Fruto da Imersão Alura em IA com Google Gemini  

A arquitetura e a implementação deste sistema de quatro agentes refletem o aprendizado e a exploração das capacidades do Google Gemini   e do framework de agentes da Google AI Platform, conforme ensinado na Imersão Alura. Este projeto visa ilustrar como a inteligência artificial pode ser utilizada para automatizar tarefas complexas e gerar valor em contextos específicos, como o apoio a causas sociais.

## Arquitetura do Sistema

O sistema é composto por quatro agentes distintos, cada um com uma responsabilidade especializada, trabalhando em sinergia para alcançar o objetivo de divulgação eficaz:

1.  **Agente Buscador de Doações (`agente_buscador_doacoes`):**
    * **Aprendizado Alura Aplicado:** Utiliza a busca inteligente através da ferramenta `google_search` para identificar até 10 campanhas de doação relevantes e atuais, com base em um tópico definido pelo usuário. A priorização de fontes confiáveis e a análise da recência da informação são conceitos chave explorados na Imersão.
    * **Responsabilidade:** Descoberta inicial de oportunidades de doação.
    * **Saída:** Uma lista de campanhas com informações básicas.

2.  **Agente Analista e Filtrador de Campanhas (`agente_analista_doacoes`):**
    * **Aprendizado Alura Aplicado:** Aplica técnicas de análise e avaliação para refinar a lista inicial. A verificação de credibilidade (com uso estratégico do `google_search`) e a avaliação do potencial de impacto refletem a importância da curadoria inteligente de informações, um tema abordado na Imersão.
    * **Responsabilidade:** Seleção das 5 campanhas mais adequadas e extração de informações chave.
    * **Saída:** Uma lista das 5 melhores campanhas com detalhes relevantes para a divulgação.

3.  **Agente Planejador de Conteúdo para LinkedIn (`agente_planejador_linkedin`):**
    * **Aprendizado Alura Aplicado:** Demonstra a capacidade de planejar estratégias de conteúdo direcionadas para uma plataforma específica (LinkedIn), considerando o público e os objetivos de engajamento, conceitos discutidos na Imersão em relação à criação de prompts eficazes e design de agentes.
    * **Responsabilidade:** Desenvolvimento de um plano de divulgação para cada campanha, incluindo ângulos de mensagem, formatos de post e sugestões de conteúdo.
    * **Saída:** Um plano detalhado de divulgação para cada uma das 5 campanhas.

4.  **Agente Criador de Posts para LinkedIn (`agente_criador_posts_linkedin`):**
    * **Aprendizado Alura Aplicado:** Utiliza as informações e o planejamento dos agentes anteriores para gerar conteúdo textual persuasivo e otimizado para o LinkedIn. A ênfase na clareza, concisão e chamada para ação reflete as melhores práticas de comunicação ensinadas na Imersão.
    * **Responsabilidade:** Criação dos posts finais, prontos para publicação.
    * **Saída:** Uma lista de posts completos para o LinkedIn.

## Como Utilizar

Para experimentar este sistema, siga estas etapas:

1.  **Clone o Repositório:** Faça um clone deste repositório para o seu ambiente local.
2.  **Instale as Dependências:** Certifique-se de ter as bibliotecas necessárias instaladas (incluindo `google-genai` e `google-adk`). 
3.  **Configure a API Key:** Siga as instruções no código para configurar sua Google Gemini API Key, utilizando o `userdata` do Google Colab ou definindo a variável de ambiente `GOOGLE_API_KEY`.
4.  **Execute o Script Principal:** 
5.  **Forneça o Tópico de Doação:** Responda à solicitação no console, digitando o tema da campanha que deseja divulgar.
6.  **Analise os Resultados:** Observe a saída de cada agente, que demonstrará o processo de busca, análise, planejamento e criação dos posts.
7.  **Revise e Publique:** Examine os posts gerados e publique-os em sua conta do LinkedIn.

## Para a Comunidade Profissional

Este projeto serve como um exemplo prático do poder da inteligência artificial, especificamente do Google Gemini  e do framework de agentes, para resolver problemas reais e otimizar fluxos de trabalho. Ele demonstra como os conhecimentos adquiridos em plataformas de aprendizado como a Alura podem ser aplicados para criar soluções inovadoras e impactantes.

## Contribuições e Aprendizado Contínuo

Assim como a jornada de aprendizado na Alura é contínua, este projeto também pode evoluir. Contribuições para aprimorar a funcionalidade, otimizar o código ou adicionar novos recursos são bem-vindas. Sinta-se à vontade para compartilhar suas ideias e sugestões através de issues e pull requests.

## Licença

 MIT License

## Autor


Este projeto foi desenvolvido por Thiago Alencar como uma demonstração prática dos conhecimentos adquiridos na **Imersão IA com Google Gemini   da Alura** ([https://cursos.alura.com.br/(https://cursos.alura.com.br/)).
