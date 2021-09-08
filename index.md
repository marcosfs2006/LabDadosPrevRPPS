# **O que é e qual o objetivo do >LabDadosPrev("RPPS")?**

O **`>LabDadosPrev("RPPS")`** (Laboratório de Análise de Dados Previdenciários dos RPPS) é um "projeto" que tem por objetivo difundir o uso dos dados previdenciários dos RPPS, explorando o potencial de informações que os mesmos podem oferecer mediante exemplos de aplicações que façam uso dos mesmos e possam servir de inspiração para novos usos.

A SPREV disponibiliza os dados na página [Estatísticas e Informações dos RPPS](https://www.gov.br/previdencia/pt-br/assuntos/previdencia-no-servico-publico). Estes dados são atualizados de forma esporádica e irregular.

Recentemente a SPREV disponibilizou uma API para acesso aos dados previdenciários dos RPPS cuja documentação pode ser consultada na seguinte URL: https://apicadprev.economia.gov.br/api-docs/

A API ainda está em desenvolvimento e não se encontra completamente operacional. Além disso, alguns dados disponibilizados na página ainda não estão contemplados na API. 

A estratégia adotada fundamenta-se na adoção de **software livre** (utilizamos o [R](https://www.r-project.org/)) para que seja acessível a todos, bem como o compartilhamento de dados em formato aberto ou facilmente acessíveis. 

Também compartilhamos os _scripts_ utilizados nas análises realizadas, as quais preferencialmente serão disponibilizadas em [notebooks do Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). 

Para quem tiver curiosidade de saber o que é o R elencamos a seguir três fontes de informação lembrando que existe muita coisa disponível na internet de forma gratuita.

* [Análise de Dados em Linguagem R - Curso na EVG/ENAP](https://www.escolavirtual.gov.br/curso/325)    
* [Introdução ao R - Prof. Vinícius A. Vale NEDUR/UFPR](https://viniciusavale.com/IntroR/Intro-R.html)
* [Manipulação e Visualização de Dados: A abordagem _tidyverse_ - Prof.  Walmes Marques Zeviani - UFPR](http://leg.ufpr.br/~walmes/cursoR/data-vis/)    

Diversos órgãos públicos utilizam o R para realizar a análise de seus dados, entre os quais podemos citar a SPREV o Tesouro Nacional e o Ministério da Saúde, para citar apenas alguns.

À medida que as análises forem amadurecendo, nosso objetivo é incluí-las em um "livro" que chamamos de [`Análise de Dados Previdenciários - ADPrev`](https://marcosfs2006.github.io/ADPrevBook/) disponível _online_ para quem quiser consultar. 

Com essa estratégia esperamos que o conteúdo possa ser acessivel a uma maior quantidade de interessados e que a reprodutibilidade das análises seja a maior possível, possibilitando inclusive a verificação das análises de forma independente.

Chamamos a atenção para a questão da **reprodutibilidade das análises realizadas**. A ideia é que qualquer pessoa com os dados e scripts utilizados consigam chegar aos mesmos  resultados apresentados nas análises. Alguns _softwares_ utilizados para realizar análise de dados tornam a reprodutibilidade mais difícil de ser alcançada. Nessa categoria podemos citar o Excel, aplicativo largamente utilizado para análise de dados.

Este repositório destina-se ao armazenamento e disponibilização dos dados utilizados no "Projeto", cujos notebooks serão aqui elencados e disponibilizados à medida que forem concluídos.

Críticas e sugestões são sempre bem-vindos. 

**NOTA:** Os tutoriais estão, em sua maioria, em elaboração. Consulte o _status_ no notebook. 

Os links para acesso aos notebooks no Google Colab serão disponibilizados à medida que os mesmos forem ficando prontos.


# Tutoriais com o objetivo de explicar/documentar as bases de dados

Os "tutoriais" a seguir elencados tem por objetivo apenas mostrar como os dados "brutos" disponibilizados pela SPREV podem ser importados usando o R. Também apresentamos  "dicionárioS de dados" com o objetivo de documentar minimamente os dados, ou seja, explicar o conteúdo de cada coluna, já que a SPREV não disponibiliza essa documentação ao público.

* [Regime Previdenciário Atual dos Entes Federativos](https://colab.research.google.com/drive/1hITNSJKR_ujKjz31Y0tr2zkv84gtVHXL?usp=sharing)  
* [Alíquota de Contrituição](https://colab.research.google.com/drive/1OSLxjS4yyrcKqrgkiqQAzSWzO5noUSyU?usp=sharing)
* [CRP - Certificado de Regularidade Previdenciária](https://colab.research.google.com/drive/1UVovo2YxM3FWkmgqXKV6iTAs2T_Ge36r?usp=sharing)
* [DAIR - Carteira](https://colab.research.google.com/drive/1a51PriNhzo_liFnfLzwECCwjOIF9bhI9?usp=sharing)   
* Enquadramento dos Fundos de Investimento pela SPREV    
* Fundos Vedados    
* Instituições Financeiras Elegíveis a Atuar como Administradores e Gestoras de Fundos de Investimento para RPPS 
* DIPR - Demonstrativo de Informações Previdenciárias e Repasses<!--(https://colab.research.google.com/drive/1kaPJ6nT3zZCHCxYzkPTfTwurSgQMUeHl?usp=sharing)-->
* Fluxo Atuarial<!--(https://colab.research.google.com/drive/1Hhsuq1u6kxMuvo3y8jghBVm9gNfLwXOH?usp=sharing)-->   
* DRAA - Encaminhamento    
* DRAA - Valores Compromissos    
* Parcelamentos de Débitos   
* ISP - Indicador de Situação Previdenciária   


# Tutoriais com o objetivo de ilustrar possibilidades de análise com os dados previdenciários

Enquanto os tutoriais acima tem por objetivo principal "apresentar" as bases de dados, os tutoriais abaixo vão um pouco além e, **partindo da base de dados já tratada** cujo passo-a-passo estão explicitados nos notebooks anteriores, apresentam exemplos de análises possíveis com os referidos conjuntos de dados com o objetivo de motivar os leitores a fazerem suas próprias análises.  

* [Quais RPPS negam informação à sociedade?](https://colab.research.google.com/drive/1wdskC1W_CSgl2T3P6tkUKrjBjBO6xWM4?usp=sharing)
* [Municípios com menos de 50 mil habitantes e as transferências voluntárias](https://colab.research.google.com/drive/1BZfmZbVt24-DbXXLSXAqm35puUB2V17R?usp=sharing)
* [Quem são os atuários no segmento de RPPS?](https://colab.research.google.com/drive/1GBat-DP1ZNv4Oms8F3_tYEqaOwql81RJ?usp=sharing)
* [Quais são os RPPS com superavit atuarial?](https://colab.research.google.com/drive/1N-A7p_Cp8lwx0k1a_Gv9JT2E4CwIgBWz?usp=sharing)
* Análise Exploratória Preliminar dos Fundos de Investimentos
* [Perfil da Carteira de Ativos](https://colab.research.google.com/drive/1ZFmjCiMY91EAeIS4lw1afFRBVDnRSGyd?usp=sharing)
* Fundos de Investimento nas Carteiras dos RPPS que não Atendem ao Art. 15, par.2o,I, da Resolução CMN 3922/10
* Enquadramento de Fundos de Investimento
* [Análise do Perfil da Carteira de Ativos](https://colab.research.google.com/drive/1ZFmjCiMY91EAeIS4lw1afFRBVDnRSGyd?usp=sharing)
* [Pró-Gestão, Investidores Qualificados e Fundos de Investimento](https://colab.research.google.com/drive/1Nmy2hZyJGS-x_Mz5uNJfibpT1CKkXYuG?usp=sharing)
* Rudimentos de Análise de Investimentos para RPPS: Aplicações Usando R
* Termos de Acordos de Parcelamento de Débitos e Deficit Atuarial
* (...)

# Tutorial para a realização de testes na API e documentação dos resultados 

* [API CADPREV-SPREV](https://colab.research.google.com/drive/1FpeX9lWIVEOvyvEdWpd61PQhdMz_xPTw?usp=sharing)   

