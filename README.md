# **>LabDadosPrev("RPPS")**  

O **>LabDadosPrev("RPPS")** - Laboratório de Análise de Dados Previdenciários dos RPPS é um "projeto" que tem por objetivo difundir o uso dos dados previdenciários dos RPPS, explorando o potencial de informações que os mesmos podem gerar mediante exemplos de aplicações que façam uso dos mesmos e possam servir de inspiração para novos usos. 

A estratégia a ser adotada fundamenta-se na adoção de software livre ([R](https://www.r-project.org/)) para que seja acessível a todos, bem como o compartilhamento de dados em formato aberto e compartilhamento de análises, as quais preferencialmente serão disponibilizadas em notebooks do [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb).  

Com essa estratégia espera-se que o conteúdo possa ser acessivel a uma maior quantidade de pessoas e que a reprodutibilidade das análises seja a maior possível.

Assim, este é o repositório para armazenamento e disponibilização dos dados utilizados no "Projeto", cujos notebooks serão aqui elencados à medida que forem sendo concluídos. Críticas e sugestões são sempre bem-vindos.

Até o momento já elaboramos alguns tutoriais:

**NOTA: A MAIORIA DOS TUTORIAIS AINDA ESTÁ EM ELABORAÇÃO**

## Tutoriais com objetivo de explicar as bases de dados
* CRP - Certificado de Regularidade Previdenciária<!--(https://colab.research.google.com/drive/1UVovo2YxM3FWkmgqXKV6iTAs2T_Ge36r?usp=sharing)-->
* DIPR - Demonstrativo de Informações Previdenciárias e Repasses<!--(https://colab.research.google.com/drive/1kaPJ6nT3zZCHCxYzkPTfTwurSgQMUeHl?usp=sharing)-->
* Fluxo Atuarial<!--(https://colab.research.google.com/drive/1Hhsuq1u6kxMuvo3y8jghBVm9gNfLwXOH?usp=sharing)-->   
* Alíquota de Contrituição<!--(https://colab.research.google.com/drive/1OSLxjS4yyrcKqrgkiqQAzSWzO5noUSyU?usp=sharing)-->
* Parcelamentos   
* ISP - Indicador de Situação Previdenciária   
* Regime Previdenciário Atual dos Entes Federativos   
* DAIR - Carteira   


## Tutoriais com objetivo de ilustrar possibilidades de análise com os dados previdenciários
* [Municípios com menos de 50 mil habitantes e as transferências voluntárias](https://colab.research.google.com/drive/1BZfmZbVt24-DbXXLSXAqm35puUB2V17R?usp=sharing)
* [Quem são os atuários no segmento de RPPS?](https://colab.research.google.com/drive/1GBat-DP1ZNv4Oms8F3_tYEqaOwql81RJ?usp=sharing)
* [Quais são os RPPS com superavit atuarial?](https://colab.research.google.com/drive/1N-A7p_Cp8lwx0k1a_Gv9JT2E4CwIgBWz?usp=sharing)
* Análise Exploratória Preliminar dos Fundos de Investimentos
* Fundos de Investimento nas Carteiras dos RPPS que não Atendem ao Art. 15, par.2o,I, da Resolução CMN 3922/10
* Enquadramento de Fundos de Investimento
* [Análise do Perfil da Carteira de Ativos](https://colab.research.google.com/drive/1ZFmjCiMY91EAeIS4lw1afFRBVDnRSGyd?usp=sharing)
* [Pró-Gestão, Investidores Qualificados e Fundos de Investimento](https://colab.research.google.com/drive/1Nmy2hZyJGS-x_Mz5uNJfibpT1CKkXYuG?usp=sharing)
* Rudimentos de Análise de Investimentos para RPPS: Aplicações Usando R
* Termos de Acordos de Parcelamento de Débitos e Deficit Atuarial
* (...)


# API do CADPREV

Recentemente a SPREV disponibilizou uma API para acesso aos dados previdenciários dos RPPS.

A API pode ser consultada na seguinte URL: https://apicadprev.economia.gov.br/api-docs/

Nos tutoriais acima elencados utilizamos os dados disponibilizados pela SPREV em seu site, os quais em boa parte do tempo estão muito desatualizados, o que dificulta bastante qualquer tentativa de acompanhamento que se queira fazer. Em breve disponibilizaremos tutoriais que ilustram como extrair os dados disponíveis na API disponibilizada e com isso, nossa expectativa é ter dados sempre atualizados, o que possibilitará um acompanhamento mais tempestivo dos RPPS.

Críticas e sugestões podem ser encaminhadas para meu email: `marcosfs2006@gmail.com`

* [API CADPREV-SPREV](https://colab.research.google.com/drive/1FpeX9lWIVEOvyvEdWpd61PQhdMz_xPTw?usp=sharing)   
