# Radar Chart no Power BI com SVG

Este projeto demonstra como é possível criar um **gráfico Radar** utilizando apenas **visuais nativos do Power BI**, combinados com **código SVG dinâmico**.

## 📊 Contexto do Projeto
Em um caso real de negócio, foi necessário avaliar o **SLA de entregas** considerando **8 etapas do processo** – algumas obrigatórias e outras situacionais.  

A solução encontrada foi gerar um **SVG customizado**, que:
- Cria a estrutura do gráfico Radar com 8 eixos.
- Atualiza dinamicamente de acordo com as medidas do modelo.
- Respeita os filtros aplicados no relatório do Power BI.

## 🛠️ Como funciona
1. Medidas em DAX alimentam os valores de cada etapa do processo.
2. O código SVG monta o desenho do Radar Chart.
3. O visual nativo de **Tabela** ou **Matriz** é usado para renderizar o SVG diretamente no Power BI.

## 🚀 Benefícios
- Nenhum visual customizado externo é necessário.
- Total flexibilidade no design via SVG.
- Compatível com filtros e segmentações do Power BI.

## 🔗 Post no LinkedIn
Confira mais detalhes na publicação que explica o caso de uso em **pt-BR** e **en-US**:  
👉 [LinkedIn Post](https://www.linkedin.com/posts/fsanfo_powerbi-dataviz-businessintelligence-activity-7371154074337091584-9oV_) <!-- substitua pelo link real -->

## 📥 Como usar
- Baixe este repositório.
- Importe o arquivo `.pbix` no Power BI Desktop.
- Explore as medidas e adapte o SVG para a sua realidade.
