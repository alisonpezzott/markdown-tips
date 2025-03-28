# Markdown

Markdown é uma linguagem de marcação comumente usada para formatar arquivos readme, escrever mensagens em fóruns de discussão online e criar texto rico usando um editor de texto simples.

Benefícios do uso do Markdown incluem:

- Fácil de aprender e usar
- Fácil de ler em sua forma bruta
- Flexível e extensível
- Universalmente suportado em muitas plataformas e aplicações

Confira aqui a documentação sobre Markdown no GitHub: [Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)  

# Títulos  

> [!NOTE]  
> Use hashtags para alterar o nível de cada título.  

Entrada:  
`### Este é um título nível 3`  

Saída: 
### Este é um título nível 3 
<br> 

# Título Nível 1
## Título Nível 2
### Título Nível 3
#### Título Nível 4
##### Título Nível 5
###### Título Nível 6

<br>  

# Estilos
|Estilo            |Entrada                                               |Saída                                              |
|------------------|------------------------------------------------------|---------------------------------------------------|
|Negrito           |`Este é um texto **em negrito**`                      |Este é um texto **em negrito**                     |
|Itálico           |`Este é um texto *em itálico*`                        |Este é um texto *em itálico*                       |
|Negrito Itálico   |`Este é um texto ***em negrito e itálico***`          |Este é um texto ***em negrito e itálico***         |
|Tachado           |`Este é um texto ~~tachado~~`                         |Este é um texto ~~tachado~~                        |
|Subscrito         |`Este é um texto com <sub>subscrito</sub>`            |Este é um texto com <sub>subscrito</sub>           |
|Sobrescrito       |`Este é um texto com <sup>sobrescrito</sup>`          |Este é um texto com <sup>sobrescrito</sup>         |
|Sublinhado        |`Este é um texto <ins>sublinhado</ins>`               |Este é um texto <ins>sublinhado</ins>              |

# Citações

Entrada:  
`> Esta é uma citação`

Saída:  
> Esta é uma citação

# Links  

Entrada:  
`[Visite este README](https://github.com/alisonpezzott/markdown-tips/main/README.md)`  

Saída:  
[Visite este README](https://github.com/alisonpezzott/markdown-tips/main/README.md)  

# Imagens  

Entrada:  
`![Fabric](https://github.com/alisonpezzott/alisonpezzott/blob/main/assets/fabric.png?raw=true)`  

Saída:  
![Fabric](https://github.com/alisonpezzott/alisonpezzott/blob/main/assets/fabric.png?raw=true)

# Alertas

Entrada:  
```
> [!NOTE]  
> Informações úteis que os usuários devem saber, mesmo ao passar rapidamente pelo conteúdo.
```

Saída:  
> [!NOTE]  
> Informações úteis que os usuários devem saber, mesmo ao passar rapidamente pelo conteúdo.
<br>

Entrada:  
```
> [!TIP]  
> Conselhos úteis para fazer as coisas de forma melhor ou mais fácil.
```

Saída:  
> [!TIP]  
> Conselhos úteis para fazer as coisas de forma melhor ou mais fácil.
<br>
  
Entrada:  
```
> [!IMPORTANT]  
> Informações chave que os usuários precisam saber para alcançar seu objetivo.
```

Saída:  
> [!IMPORTANT]  
> Informações chave que os usuários precisam saber para alcançar seu objetivo.

<br>  

Entrada:  
```
> [!WARNING]  
> Informações urgentes que exigem atenção imediata do usuário para evitar problemas.
```

Saída:  
> [!WARNING]  
> Informações urgentes que exigem atenção imediata do usuário para evitar problemas.

<br>    

Entrada:  
```
> [!CAUTION]  
> Avisos sobre riscos ou resultados negativos de determinadas ações.
```

Saída:  
> [!CAUTION]  
> Avisos sobre riscos ou resultados negativos de determinadas ações.

<br>    

# Tabelas

|Projeto            |Status      |Percentual|
|:------------------|:----------:|---------:|
|Contrução do site  |Em andamento|85%       |
|Gravação do curso  |Congelado   |50%       |
|Revisão da mentoria|Concluído   |100%      |

# Badges  

Badges são cards que podem possuir ícones, textos, links e algumas estatísticas que são resultado de alguma API.  
Veja abaixo alguns badges de exemplo.  

Input:  
`![GitHub Repo stars](https://img.shields.io/github/stars/alisonpezzott/pbi-docs?style=flat&color=yellow&link=https%3A%2F%2Fgithub.com%2Falisonpezzott%2Fpbi-docs%2Fblob%2Fmain%2F)`  
Output:  
![GitHub Repo stars](https://img.shields.io/github/stars/alisonpezzott/pbi-docs?style=flat&color=yellow&link=https%3A%2F%2Fgithub.com%2Falisonpezzott%2Fpbi-docs%2Fblob%2Fmain%2F)

Input:  
`[GitHub forks](https://img.shields.io/github/forks/alisonpezzott/pbi-docs?style=flat&color=blue&link=https%3A%2F%2Fgithub.com%2Falisonpezzott%2Fpbi-docs%2Fedit%2Fmain%2F`     

Output:  
![GitHub forks](https://img.shields.io/github/forks/alisonpezzott/pbi-docs?style=flat&color=blue&link=https%3A%2F%2Fgithub.com%2Falisonpezzott%2Fpbi-docs%2Fedit%2Fmain%2F)  

Input:
`[![GitHub followers](https://img.shields.io/github/followers/alisonpezzott?style=flat&logo=github&logoColor=ffffff&colorA=2E3440&colorB=FFFFFF)](https://github.com/alisonpezzott)`  

Output:  
[![GitHub followers](https://img.shields.io/github/followers/alisonpezzott?style=flat&logo=github&logoColor=ffffff&colorA=2E3440&colorB=FFFFFF)](https://github.com/alisonpezzott)  


Input:  
`[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?&logo=discord&logoColor=white)](https://discord.gg/sJTDvWz9sM)`  
Output:  
[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?&logo=discord&logoColor=white)](https://discord.gg/sJTDvWz9sM)

Visit [https://img.shields.io/](https://img.shields.io/) for more examples.  


# Fluxogramas   

Podemos criar diagramas Mermaid para demonstrar o fluxo de algum processo como o exemplo abaixo:  

Input:  
```
```mermaid
flowchart TD
    A[Start] -->|Request access token| B[get_token]
    B -->|Fetch tenant metadata| C[get_tenant_metadata]
    C -->|Save JSON files| D[Save metadata to results/tenant_metadata]
    
    D -->|Extract dataset information| E[get_info_datasets]
    E -->|Run DAX queries| F[Generate CSV files for each dataset]
    F -->|Save to results/datasets_info| G[Save dataset info]
    
    D -->|Export dataflows JSON| H[get_dataflows]
    H -->|Save JSON files| I[Save to results/dataflows_json]
    
    D -->|Identify PRO datasets| J[get_pro_datasets]
    J -->|Export PBIX files| K[Save to results/exported_pbix]
    
    K -->|Extract dataset info from PBIX| L[get_info_pro_datasets]
    L -->|Run DAX Query locally| M[Generate CSV files for each dataset]
    M -->|Save to results/datasets_info| N[Save dataset info]
    
    G & N -->|Generate documentation| O[create_documentation]
    O -->|Save DOCX files| P[Save to results/documentation]
    
    P -->|Process completed| Q[End]
\```
```

Output:  
```mermaid
flowchart TD
    A[Start] -->|Request access token| B[get_token]
    B -->|Fetch tenant metadata| C[get_tenant_metadata]
    C -->|Save JSON files| D[Save metadata to results/tenant_metadata]
    
    D -->|Extract dataset information| E[get_info_datasets]
    E -->|Run DAX queries| F[Generate CSV files for each dataset]
    F -->|Save to results/datasets_info| G[Save dataset info]
    
    D -->|Export dataflows JSON| H[get_dataflows]
    H -->|Save JSON files| I[Save to results/dataflows_json]
    
    D -->|Identify PRO datasets| J[get_pro_datasets]
    J -->|Export PBIX files| K[Save to results/exported_pbix]
    
    K -->|Extract dataset info from PBIX| L[get_info_pro_datasets]
    L -->|Run DAX Query locally| M[Generate CSV files for each dataset]
    M -->|Save to results/datasets_info| N[Save dataset info]
    
    G & N -->|Generate documentation| O[create_documentation]
    O -->|Save DOCX files| P[Save to results/documentation]
    
    P -->|Process completed| Q[End]
```
