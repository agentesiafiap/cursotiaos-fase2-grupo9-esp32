# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Iniciando a coleta de dados

## Agentes IA Fiap

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/daniel-baião-0b351049/">Daniel Emilio Baião</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 2</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 3</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 4</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Nome do integrante 5</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/sabrina-otoni-22525519b/">Sabrina Otoni</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">André Godoi Chiovato</a>


## 📜 Descrição

*Considerando como base a Fase anterior do projeto — que envolveu o cálculo de área plantada, monitoramento climático, entre outros —, a Fase 2 vai avançar no sistema de gestão agrícola da empresa FarmTech Solutions usando um dispositivo construído por você e seu grupo.

Agora, vamos imaginar em como podemos conectar os sensores físicos para otimizar a irrigação agrícola e criar um sistema de irrigação inteligente. Toda cultura agrícola depende, em maior ou menor proporção, de três elementos químicos: Nitrogênio (N), Fósforo (P) e Potássio (K) — o famoso NPK. Isso vai influenciar o pH da terra e, obviamente, a produtividade daquela planta. Além disso, é preciso considerar a umidade do solo, que indica o quanto choveu em um determinado período observado. Infelizmente, no Wokwi.com — plataforma onde simulamos projetos ESP32 — não há sensores exclusivamente agrícolas. Por isso, faremos simulações e algumas substituições didáticas.

No lugar dos sensores de nutrientes N, P e K, utilizaremos um botão verde em cada. Portanto, seu projeto precisa ter três botões simulando os níveis de cada elemento.

No lugar do sensor de pH, utilizaremos um sensor de intensidade de luz chamado LDR (Light Dependent Resistor) que trará dados analógicos da intensidade da luz, mas, para fins de simulação, vamos assumir que ele representa o pH da terra. Como referência, podemos comparar os dados analógicos do pH que variam de 0 a 14, sendo próximo de 7, pH neutro. Você também pode adotar outras escalas maiores que 0 a 14 para melhorar sua mecânica ao manipular o sensor LDR.

Quanto ao sensor de umidade, este possui um similar no Wokwi que mede a umidade do ar. Portanto, vamos adotar o DHT22 como medidor de umidade do solo (embora seja do ar na prática).
O objetivo do projeto na Fase 2 será desenvolver um sistema de irrigação automatizado e inteligente que monitore a umidade do solo em tempo real, os níveis dos nutrientes N, P e K representados por botões (que vão “medir” os níveis como tudo ou nada, isto é, “true” ou “false”, ou em outras palavras, como botão pressionado ou não pressionado). *


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.

- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

*Acrescentar as informações necessárias sobre pré-requisitos (IDEs, serviços, bibliotecas etc.) e instalação básica do projeto, descrevendo eventuais versões utilizadas. Colocar um passo a passo de como o leitor pode baixar o seu código e executá-lo a partir de sua máquina ou seu repositório. Considere a explicação organizada em fase.*


## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
    * 
* 0.4.0 - XX/XX/2024
    * 
* 0.3.0 - XX/XX/2024
    * 
* 0.2.0 - XX/XX/2024
    * 
* 0.1.0 - XX/XX/2024
    *

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>