<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=4db5c4&height=120&section=header"/>

# Resenha do Artigo: Big Ball Of Mud

## Introdução

O artigo "Big Ball of Mud" de Brian Foote e Joseph Yoder apresenta uma análise profunda sobre um dos padrões de arquitetura mais comuns e menos discutidos em software: o Big Ball of Mud (BBM). Essa resenha busca aprofundar a discussão, explorando as consequências do BBM, comparando-o com outros padrões e portanto, propondo estratégias para lidar com essa complexidade.

## O que é um Big Ball of Mud?

O BBM descreve sistemas sem uma arquitetura clara, construídos de forma desordenada e mantidos de maneira improvisada. Essa falta de estrutura, muitas vezes comparada a um "bolo de lama", dificulta a manutenção, a evolução e a compreensão do sistema.

## Quais as Consequências do BBM?

**Custos de desenvolvimento:** A falta de organização aumenta o tempo e os recursos necessários para adicionar novas funcionalidades ou corrigir bugs.
**Qualidade do software:** A arquitetura desordenada contribui para a ocorrência de falhas e instabilidades.
**Dificuldade de onboarding:** A complexidade de um BBM torna o processo de aprendizado de novos membros da equipe mais demorado e sujeito a erros.

## Padrões 

Foote e Yoder discutem seis padrões principais que contribuem para a formação de um Big Ball of Mud:

**Big Ball of Mud** – O padrão central que se refere à arquitetura desorganizada, resultado de modificações apressadas e falta de planejamento.
**Throwaway Code** – Código "descartável" que acaba sendo mantido devido à sua funcionalidade imediata.
**Piecemeal Growth** – O crescimento incremental e descontrolado que, com o tempo, compromete a estrutura do sistema.
**Keep it Working** – A prática de manter o sistema em funcionamento a qualquer custo, mesmo que isso signifique ignorar problemas arquiteturais.
**Sweeping it Under the Rug** – Esconder a complexidade ou a bagunça arquitetônica sem realmente resolvê-la.
**Reconstruction** – A reconstrução total de sistemas que se tornam insustentáveis, o que envolve um reinício do zero.

## Comparando o BBM com Outros Padrões

Ao contrário do BBM, padrões como **PIPELINE** e **LAYERED ARCHITECTURE** promovem a modularidade e a reutilização de código, facilitando a manutenção e a evolução do sistema. No entanto, a adoção desses padrões pode ser desafiadora em projetos com prazos apertados e requisitos em constante mudança.

## Fatores que Contribuem para o BBM

**Falta de tempo:** A pressão por entregas rápidas muitas vezes leva a decisões que comprometem a arquitetura a longo prazo.
**Inexperiência:** A falta de conhecimento sobre princípios de design de software pode levar à criação de sistemas mal estruturados.
**Complexidade:** Problemas complexos podem exigir soluções complexas, que, se não forem bem gerenciadas, podem resultar em um BBM.
**Mudanças constantes:** Requisitos em constante evolução podem dificultar a manutenção de uma arquitetura consistente.

## Estratégias para Lidar com o BBM

**Refatoração gradual:** Realizar pequenas mudanças incrementas para melhorar a estrutura do código sem interromper a operação do sistema.
**Introdução de testes:** Utilizar testes automatizados para identificar e corrigir problemas em um código legado.
**Uso de ferramentas de análise de código:** Empregar ferramentas para identificar gargalos, duplicidade de código e outras questões relacionadas à qualidade do software.
**Reconstrução:** Em casos extremos, a reconstrução total do sistema pode ser a única solução viável.

## Conclusão

Foote e Yoder argumentam que o **Big Ball of Mud** (BBM) não deve ser visto como um "anti-padrão", mas como um padrão real devido à sua prevalência e eficácia em muitos contextos. Embora o ideal seja evitar essa arquitetura desordenada, as pressões práticas do desenvolvimento frequentemente tornam inevitável a adoção desse modelo. A chave para enfrentar essas situações é compreender as forças que levam ao BBM e buscar formas de mitigar seus efeitos, com o objetivo de eventualmente alcançar uma arquitetura mais robusta e duradoura.

O artigo é relevante tanto no contexto acadêmico quanto prático, especialmente para desenvolvedores que enfrentam o dilema entre a criação de uma arquitetura sustentável e a necessidade de entrega rápida. Ele oferece uma visão realista dos desafios inerentes ao desenvolvimento de software, proporcionando insights valiosos sobre como lidar com a complexidade e a desorganização em projetos de grande escala.

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=4db5c4&height=120&section=footer"/>
