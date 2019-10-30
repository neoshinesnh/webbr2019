

## Desenvolvendo Chatbots usando Python e Processamento de Linguagem Natural
### Jefferson Oliveira Pesquisador do Centro de Estudos sobre Tecnologias Web - Ceweb.br e Professor na PUC-SP (github.com/j3ffsilva)
_30 de OUT 11:00 - 12:30_

* Framework [RASA](https://rasa.com/)
    * O RASA uniu o RASA NLU + RASA CORE
* Concorrente
    * Dialog Flow
* Arquivos importantes
    * config.yml
        * pipeline: (qual das duas utilizar vai depender do contexto)
            * supervised_embeddings -> considera sua base
            * pretrained_embeddings_spacy -> 
        * policies: (determina a próxima ação)
    * stories.yml
    * domain.yml
* Comandos
    * Treine o modelo (terminal 1): rasa train
    * Inicia servidor: rasa run actions (em outro terminal , terminal 2)
    * Inicia rasa shell: rasa shell