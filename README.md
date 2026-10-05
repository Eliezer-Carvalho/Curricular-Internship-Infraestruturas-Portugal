<h1> <a href = "https://github.com/Eliezer-Carvalho/IP/blob/master/A%20Three-Dimensional%20Analysis%20for%20LLM%20Deployment/A%20Three-Dimensional%20Analysis%20for%20LLM%20Deployment.pdf"> A Three-Dimensional Analysis for LLM Deployment </a> </h1>

Apresento uma abordagem para a análise da hospedagem de Large Language Models.

<h1> <a href = "https://github.com/Eliezer-Carvalho/IP/blob/master/Context%20Engineering/Context%20Engineering.pdf"> Context Engineering </a> </h1>

Como fornecer um bom contexto a um modelo ? Porque devemos ter atenção ao contexto ? 

<h1> <a href = "https://github.com/Eliezer-Carvalho/IP/blob/master/Synthetic%20Data/Synthetic%20Data.pdf"> Synthetic Data </a> </h1>

Os dados são o novo petróleo, saber criá-los é muito importante.

<h1> <a href = "https://github.com/Eliezer-Carvalho/IP/blob/master/How%20To%20RAG/How%20To%20RAG.pdf"> How To RAG </a> </h1>

RAG e as suas abordagens. Porque é importante e técnicas de implementação.

<h1> <a href = "https://github.com/Eliezer-Carvalho/IP/blob/master/Automatic%20Speech%20Recognition/Automatic%20Speech%20Recognition.pdf"> Automatic Speech Recognition </a> </h1>

Análise e estudo de modelos ASR. Construção do sistema <b> <a href = "https://github.com/Eliezer-Carvalho/IP/tree/master/Automatic%20Speech%20Recognition/v1"> Assobio</b></a>. 

<h1> TL:DR </h1>

```mermaid
flowchart LR
    n1["A Three-Dimensional Analysis for LLM Deployment"] <--> n2["Ínicio do estágio. \nComo principal objetivo compreender como hospedar de maneira local modelos de Inteligência Artificial e como avaliar a performance dos mesmos."]
    n3["Context Engineering"] <--> n4["Temos os modelos do nosso lado, como os instruir a tomar as decisões que nós queremos ? \n O segredo está na construção de um bom e conciso contexto."]
    n1 --> n3 & n9["Temas base para:"]
    n5["Synthetic Data"] <--> n6["Os dados são o novo pretróleo. \n Os modelos de linguagem trouxeram uma revolução brutal à area de Dados Sintéticos e ter em posse ferramentas e técnicas para construir dados é muito importante na hora de Avaliar e Construir modelos. \n Abordagem a técnicas como Constraint Decoding."]
    n3 --> n5 & n9
    n5 --> n9
    n9 --> n8["Assobio"] & n7["How To RAG"]

    style n2 stroke-width:1px,stroke-dasharray: 0,fill:#C8E6C9,color:#000000
    style n4 stroke-width:1px,stroke-dasharray: 0,fill:#C8E6C9,color:#000000
    style n6 stroke-width:1px,stroke-dasharray: 0,fill:#C8E6C9,color:#000000
```

<h1> Links Interessantes </h1>

https://huggingnews.com/ <br>
https://paperswithcode.co/ <br>
https://www.openresearch.sh/compute <br>
https://deepwiki.com/ <br>
https://www.tensortonic.com/ <br>
https://www.deep-ml.com/projects 
