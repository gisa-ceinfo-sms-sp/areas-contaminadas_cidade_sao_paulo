# areas-contaminadas_cidade_sao_paulo
<strong>Mapa dinâmico com as áreas contaminadas recuperadas, limites vigentes das áreas de abrangência de UBS e outros territórios de interesse da SMS-SP</strong>

<strong>1. Utilizando dados dinâmicos (geowebservice)</strong>
# GEOSampa
Link para acessar: http://wms.geosampa.prefeitura.sp.gov.br/geoserver/geoportal/wms?service=WMS&version=1.1.0&request=GetMap&layers=MapaBase_Politico,area_contaminada_reabilitada_svma,equipamento_saude_coordenadoria_regional,equipamento_saude_supervisao_tecnica,equipamento_saude_abrangencia_ubs,equipamento_saude_cobertura_familia,equipamento_saude_ubs_posto_centro&styles=&bbox=341000,7390000,345000,7400000&width=1820&height=820&srs=EPSG:31983&format=application/openlayers#toggle

Fontes:

Todas as camadas são obtidas a partir de conexões do tipo <i>WebFeatureService (WFS)</i>, estabelecidas com a Infraestrutura Municipal de Dados de São Paulo (IMDE-SP), que refletem os dados mais recentes disponibilizado na infraestrutura oficial pelos órgãos produtores primários. O catálogo de metadados na íntegra pode ser acessado em: https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search;jsessionid=DFEC77321EE2B48CE4A2F2219EDABA2B#/home

- MapaBase Politico - GEOSampa/GEOInfo/SMUL-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search#/metadata/cb23313b-a613-4ee6-b2ba-cda7ecfb05cc/formatters/xsl-view?root=div&view=advanced&approved=true">metadados</a>) 
- Área Contaminada Reabilitada - CLA/CTGEO/SVMA-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search#/metadata/ca351b78-bbd3-423d-97a8-ae9b3345d390/formatters/xsl-view?root=div&view=advanced&approved=true">metadados</a>) 
- Coordenadoria Regional de Saúde - CEInfo/CAB/SMS-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search;jsessionid=97985C810436B3A08D34D132D47895C7#/metadata/2a4add4b-9247-45f7-aa86-351046774909">metadados</a>)  
- Supervisão Técnica de Saúde - CEInfo/CAB/SMS-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search;jsessionid=97985C810436B3A08D34D132D47895C7#/metadata/34114468-f478-4cf2-a44d-b0a80242edca">metadados</a>)  
- Àrea de abrangência de UBS - CEInfo/CAB/SMS-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search;jsessionid=97985C810436B3A08D34D132D47895C7#/metadata/d35eff25-51f2-442e-963f-222e872c6deb">metadados</a>)  
- Àrea de cobertura de Estratégia Saúde da Familia (SMS-SP) - CEInfo/CAB/SMS-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search#/metadata/f5125c75-5d28-4b0f-88ee-79e630e49c6c/formatters/xsl-view?root=div&view=advanced&approved=true">metadados</a>) 
- Equipamento - Unidade Básica de Saúde (SMS-SP) - CEInfo/CAB/SMS-SP (<a href="https://metadados.geosampa.prefeitura.sp.gov.br/geonetwork/srv/por/catalog.search#/metadata/bc44ee6c-e973-4670-b912-9ac8d64b9f56/formatters/xsl-view?root=div&view=advanced&approved=true">metadados</a>) 

Aparência de exibição da tela: ![image](https://github.com/gisa-ceinfo-sms-sp/areas-contaminadas_cidade_sao_paulo/assets/75272641/744a6d2c-4ae7-42cf-a313-4ff6a31d9adb)




