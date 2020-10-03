# Laboratório de Análise de Dados Previdenciários - **LabDadosRPPS()**

Repositório para armazenamento e disponibilização de dados dos RPPS em **formato Rds**, utilizados em análises realizadas no Google Colab. 

**Bases de dados dos CRP** - Essas bases de dados contém informações quanto a validade do CRP (Certificado de Regularidade Previdenciária) dos RPPS. Estes arquivos são identificados com o prefixo `crp` e contém as seguines variáveis:

variável      | descrição
--------------|-----------------------------------------------------------
uf            | sigla da unidade da federação
ente          | nome do ente 
num_crp       | número do CRP 
dt_emissao    | data de emissão do CRP
dt_validade   | data de validade do CRP  
judicial      | indica se o CRP foi obtido por via judicial     
tipo_regime   | tipo de regime ao qual o Ente está vinculado - RGPS ou RPPS
situacao      | situação do CRP - VÁLIDO ou INVÁLIDO    

<br>

**Bases de dados do DAIR** - Essas bases de dados contém informações quanto aos investimentos dos RPPS e são identificados pelo prefixo `dair` e contém as seguines variáveis:

variável      | descrição
--------------|-----------------------------------------------------------
cnpj          | CNPJ do Ente
uf            | Sigla da unidade da federação
ente          | Nome do ente
competencia   | Més de competência (mês de posicionamento dos dados)       
segmento      | Segmento em que se enquadra o ativo
tipo_ativo    | Tipo de ativo
limite_resol_cmn | Percentual máximo de recursos que o RPPS pode investir no ativo
ident_ativo   | Identificação do ativo       
nm_ativo      | Nome do ativo
qtd_quotas    | Quantidade de quotas que o RPPS possui do ativo
vlr_atual_ativo | Valor da fração unitária do ativo
vlr_total_atual | Valor que o RPPS possui investido no ativo   
perc_recursos_rpps | Percentual dos recursos do RPPS aplicados no ativo
pl_fundo      | Valor do patrimõnio líquido do Fundo de Investimentos
perc_pl_fundo | Percentual do Patrimônio Líquido do FI que os investimentos do RPPS no referido FI representam     

<br>

**Bases de dados do DIPR** - Essas bases de dados contém informações detalhadas sobre receitas e despesas do RPPS. O dicionário desse conjunto de dados está no arquivo `xxx`

<br>

**Bases de dados de parcelamentos** - Essa base de dados traz informações sobre os termos de parcelamento de débitos celebrados pelos RPPS.

<br>



# Análises já produzidas

Até o momento já foram produzidas as seguintes análises:

* Análise da Evolução de regularização de RPPS quanto ao CRP (a elaborar)    
* Indicador de Situação Previdenciária (em elaboração)
