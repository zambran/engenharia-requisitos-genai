# Sistema de Gestão de Eventos — Especificação de Requisitos

## 1. Sobre o projeto

Este repositório contém os artefatos de especificação de requisitos elaborados para o **Sistema de Gestão de Eventos da Eventus**.

O sistema tem como objetivo centralizar o gerenciamento de eventos, inscrições, vagas, pagamentos, cancelamentos, reembolsos, listas de espera e certificados, proporcionando maior controle aos organizadores e uma melhor experiência aos participantes.

A partir das informações obtidas nas entrevistas com os stakeholders, foram identificados requisitos funcionais, requisitos não funcionais, regras de negócio e diversas questões que ainda precisam ser esclarecidas.

---

## 2. Artefatos selecionados

Após a análise dos requisitos e das sugestões obtidas com o uso de Inteligência Artificial, foi escolhido **casos de uso** como o principal artefato de especificação.

A pasta `especificacao/` contém:

* [`casos-de-uso.md`](./especificacao/casos-de-uso.md) — contém a especificação textual dos principais casos de uso, seus atores, objetivos, fluxos, regras relacionadas e pendências.
* [`diagrama-casos-de-uso.md`](./especificacao/diagrama-casos-de-uso.md) — contém o diagrama visual dos casos de uso utilizando Mermaid, além da relação entre atores e funcionalidades.

O diagrama foi mantido em um arquivo separado para facilitar a leitura e a manutenção da documentação, mas faz parte da representação dos casos de uso selecionados.

---

## 3. Uso de Inteligência Artificial

### Ferramenta utilizada

Foi utilizada a **ChatGPT**, da OpenAI, como ferramenta de Inteligência Artificial Generativa (GenAI) para apoiar a análise e a elaboração dos artefatos de requisitos.

### Como a IA apoiou a atividade

A IA foi utilizada em diferentes etapas da atividade:

1. **Análise dos requisitos levantados**

   A partir das informações das entrevistas, requisitos funcionais, requisitos não funcionais e regras de negócio, a IA auxiliou na organização e interpretação das informações.

2. **Sugestão de artefatos**

   Foram solicitadas sugestões sobre quais artefatos seriam mais adequados para representar os requisitos do sistema.

   Entre as sugestões apresentadas estavam:

   * casos de uso;
   * diagramas de casos de uso;
   * especificações textuais de casos de uso;
   * diagramas de atividades;
   * diagramas de estados;
   * modelo de domínio/diagrama de classes;
   * matriz de rastreabilidade;
   * protótipos de interface;
   * especificações de requisitos não funcionais.

3. **Análise crítica das sugestões**

   As sugestões não foram aceitas automaticamente. Foi realizada uma análise considerando a complexidade do projeto, a quantidade de requisitos, os diferentes stakeholders e, principalmente, a necessidade de evitar uma documentação excessivamente complexa.

4. **Elaboração dos casos de uso**

   A IA auxiliou na organização dos atores, na identificação dos casos de uso e na elaboração dos fluxos principais e alternativos.

5. **Elaboração do diagrama**

   A IA também apoiou a representação visual dos casos de uso por meio da linguagem Mermaid, permitindo que o diagrama fosse mantido diretamente no repositório.

6. **Identificação de pendências**

   Durante a elaboração, foram preservadas as ambiguidades existentes nos requisitos. A IA ajudou a identificar questões que ainda precisam ser validadas com os stakeholders, evitando assumir regras que não haviam sido definidas.

7. **Refinamento do README.md**
   Após a redação do esboço do README.md, a IA auxiliou no processo de refinamento para garantir que todas as informações relevantes estivessem documentadas.
---

## 4. Sugestões aceitas

A principal recomendação aceita foi a utilização de **casos de uso** como artefato central da especificação.

Também foi aceita a utilização de um **diagrama de casos de uso** como representação visual complementar.

A escolha foi considerada adequada porque o sistema possui diferentes tipos de usuários e diversas funcionalidades relacionadas diretamente às interações desses usuários com o sistema.

Entre os casos de uso identificados estão:

* consultar eventos disponíveis;
* realizar inscrição;
* consultar inscrições;
* cancelar inscrição;
* entrar na lista de espera;
* confirmar pagamento;
* gerenciar reembolso;
* gerenciar eventos e atividades;
* gerenciar participantes;
* consultar participantes de uma atividade;
* emitir/obter certificado;
* enviar comprovante de inscrição.

---

## 5. Sugestões modificadas ou descartadas

A IA sugeriu a utilização de diversos outros artefatos, como diagramas de atividades, diagramas de estados, modelo de domínio/diagrama de classes, matriz de rastreabilidade e protótipos de interface.

Esses artefatos foram **descartados para esta etapa**, não porque sejam inadequados em termos gerais, mas porque sua utilização simultânea aumentaria a complexidade da especificação.

A proposta da atividade permitia selecionar os artefatos considerados mais adequados ao projeto. Dessa forma, optou-se por não produzir artefatos adicionais enquanto ainda existem decisões importantes em aberto.

Também foram feitas adaptações nas sugestões da IA para evitar que informações não definidas pelos stakeholders fossem tratadas como regras definitivas.

Por exemplo, ainda não estão definidos:

* os prazos e condições para cancelamento;
* as regras de reembolso;
* o funcionamento detalhado da lista de espera;
* os critérios para emissão dos certificados;
* o meio e o momento de envio das notificações;
* o tratamento de conflitos de horário;
* as informações dos participantes que poderão ser visualizadas pelos palestrantes.

Esses pontos foram mantidos como **pendências de validação**, em vez de serem preenchidos com suposições.

---

## 6. Justificativa dos artefatos escolhidos

Os **casos de uso** foram considerados os artefatos mais adequados para este projeto porque permitem representar as principais funcionalidades a partir da perspectiva dos usuários e dos demais atores envolvidos.

O sistema possui quatro grupos principais de atores diretamente relacionados às funcionalidades:

* Participante;
* Organizador;
* Equipe Financeira;
* Palestrante.

Os casos de uso permitem relacionar esses atores às funcionalidades que cada um desempenha, além de possibilitar a descrição dos fluxos principais e alternativos.

A escolha também contribui para a **redução da complexidade da especificação**. Em vez de produzir diversos modelos diferentes neste momento, foi priorizado um artefato capaz de representar grande parte dos requisitos funcionais de maneira organizada e compreensível.

O **diagrama de casos de uso** complementa essa especificação ao apresentar visualmente os atores e suas interações com o sistema.

Outros artefatos poderão ser elaborados futuramente caso o projeto evolua e exista necessidade de maior detalhamento. Entretanto, para esta etapa, a combinação de **especificação textual de casos de uso + diagrama de casos de uso** foi considerada suficiente para representar os requisitos selecionados.

---

## 7. Considerações sobre a utilização da IA

A Inteligência Artificial foi utilizada como **ferramenta de apoio**, e não como substituta da análise dos requisitos.

As sugestões geradas foram analisadas criticamente e ajustadas de acordo com as informações fornecidas pelos stakeholders. Quando uma informação não estava definida, optou-se por registrar a questão como pendência em vez de criar uma regra sem fundamento.

Dessa forma, a versão final dos artefatos representa uma combinação entre as sugestões fornecidas pela IA e as decisões tomadas durante a análise do projeto.

---

## 8. Estrutura do repositório

```text
/
├── README.md
└── especificacao/
    ├── casos-de-uso.md
    └── diagrama-casos-de-uso.md
└── analise/
    ├── duvidas-e-lacunas.md
    ├── regras-de-negocio.md
    ├── requisitos-funcionais.md
    └── requisitos-nao-funcionais.md
```

