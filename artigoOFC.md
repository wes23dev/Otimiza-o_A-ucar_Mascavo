# Otimização Açúcar Mascavo
## 1. Introdução

A produção de açúcar mascavo em pequena escala desempenha um papel econômico crucial no desenvolvimento do agronegócio regional e no fortalecimento de pequenas agroindústrias locais. Segundo Souza (2022), a cana-de-açúcar é uma matéria-prima fundamental para este setor, contribuindo significativamente para a economia nacional e possuindo um elevado valor social, especialmente quando se considera o impacto direto no bem-estar dos trabalhadores e das comunidades rurais envolvidas. Nessas unidades, a gestão é predominantemente familiar e o processo produtivo é fortemente influenciado pelas condições climáticas. Diferente das grandes indústrias do setor sucroenergético, as pequenas usinas enfrentam desafios específicos, nos quais a qualidade da matéria-prima e as variações sazonais das chuvas afetam diretamente a viabilidade do empreendimento.

O planejamento da produção de produtos derivados da cana-de-açúcar é um procedimento complexo que se inicia com pelo menos dois anos de antecedência em relação à colheita (PIEDADE, 1989). Entretanto, é nos períodos mais curtos que os gestores se deparam com o maior desafio: a produção ocorre apenas por cerca de sete meses anualmente, normalmente de maio a novembro. Nesse período, a maturação da cana oferece uma concentração ideal de sacarose. Segundo Tomiya (1994), há um momento ideal para a colheita relacionado a essa maturação, frequentemente acontecendo em setembro, embora limitações de recursos e mão de obra possam impedir a plena exploração desse potencial.

Por outro lado, na temporada de chuvas, a cana apresenta um aumento no teor de água, o que diminui a concentração de sacarose por unidade colhida. Além de afetar o rendimento, as chuvas dificultam as colheitas manuais e a carga nos caminhões. Como as vendas ocorrem ao longo do ano, é crucial que exista um sistema eficaz para gerenciar a distribuição e o armazenamento, dado que a perecibilidade e o ciclo biológico dos vegetais representam desafios significativos na elaboração do planejamento rural (SOUZA, 2022). Conforme Colin (2001), a falta de estoque disponível durante a entressafra pode resultar na perda de clientes para competidores.

Tradicionalmente, as decisões sobre estocagem e paradas operacionais nessas unidades são feitas de modo empírico. Contudo, a aplicação dos conceitos de Planejamento, Programação e Controle da Produção (PPCP) é essencial para que a empresa produza na quantidade e momentos certos, utilizando da melhor forma os seus recursos (SOUZA, 2022). Neste cenário, a Pesquisa Operacional se destaca como uma ferramenta estratégica fundamental, pois permite a criação de modelos matemáticos que ajudam a decidir quanto produzir e estocar antes do período crítico. A adoção desses modelos para organizar a produção em empresas agroindustriais já demonstrou ser eficaz em casos clássicos de integração de planejamento, reduzindo incertezas e custos operacionais (TAUBE-NETTO, 1996).

O principal objetivo deste trabalho consiste na otimização da gestão de estoques de antecipação integrada às variáveis críticas do campo, como o clima e a produtividade das variedades de cana-de-açúcar. Busca-se evidenciar que a eficiência logística não se baseia apenas na quantidade produzida, mas também na seleção estratégica das variedades plantadas, levando em consideração a pluviosidade sazonal. Assim, o intuito é aplicar modelos matemáticos acessíveis para reduzir perdas resultantes da diminuição do rendimento industrial, utilizando o estoque regulador como um amortecedor que assegura a continuidade das entregas e reforça as pequenas agroindústrias locais.

## 2. Fundamentação Teórica
   
### 2.1 A Cultura da Cana-de-Açúcar e a Sazonalidade
O sucesso da produção de açúcar mascavo está intrinsecamente ligado ao ciclo biológico da cana-de-açúcar. A maturação da planta é o processo de acúmulo de sacarose nos colmos, medido tecnicamente pelo teor de Açúcar Total Recuperável (ATR). Segundo Tomiya (1994), a maturação não é uniforme ao longo do ano; ela atinge seu pico em períodos de estiagem, quando a planta cessa o crescimento vegetativo e passa a estocar energia na forma de açúcar.

A sazonalidade impõe uma janela de colheita restrita, geralmente entre maio e novembro na região Sudeste. Nesse contexto, a pluviosidade atua como um fator crítico: o excesso de chuvas não apenas dificulta a logística de colheita e transporte, mas também aumenta o teor de água na planta, diluindo a concentração de sacarose e reduzindo o rendimento industrial por tonelada de cana processada.

As variedades de cana são classificadas em precoces, médias e tardias.O planejamento do mix de variedades é o que permite estender o período de safra com rendimentos economicamente viáveis. Piedade (1989) reforça que a escolha incorreta das variedades para cada período de colheita pode resultar em perdas drásticas, visto que colher uma variedade tardia no início da safra significa processar uma matéria-prima com baixo vigor tecnológico.

### 2.2 Gestão de Estoques de Antecipação e Realidade Familiar
Diferente de indústrias de manufatura comum, a agroindústria lida com a oferta sazonal de matéria-prima para uma demanda que costuma ser constante ao longo dos 12 meses do ano. Para garantir a continuidade das vendas durante a entressafra (dezembro a abril), utiliza-se o conceito de Estoque de Antecipação.

Conforme Souza (2022), o estoque de antecipação funciona como um "amortecedor" (buffer) que absorve a superprodução dos meses de safra para suprir a carência dos períodos onde a colheita é impossibilitada. Em unidades de gestão familiar, a posse de infraestrutura própria de armazenagem (galpões próprios) é um ativo estratégico fundamental. Embora elimine o custo direto de aluguel, a manutenção desse estoque envolve outros custos e riscos:

Custo de Oportunidade: Representa o capital investido em produto parado que poderia estar gerando liquidez para outros investimentos na propriedade.
Integridade do Produto: O açúcar mascavo é altamente higroscópico, exigindo rigoroso controle de umidade no galpão para evitar o empedramento ou perda de qualidade microbiológica.
Nível de Serviço e Fidelização: A principal função do estoque, neste cenário, é evitar a Ruptura de Estoque. Segundo Colin (2001), a incapacidade de entrega na entressafra força o cliente a buscar novos fornecedores, o que pode resultar na perda definitiva de mercado.

### 2.3 Pesquisa Operacional e Programação Linear
Para resolver o conflito entre a produção limitada pela safra e a necessidade de estoque para o ano todo, a Pesquisa Operacional (PO) oferece métodos quantitativos de suporte à decisão. A Programação Linear (PL) destaca-se como uma técnica de otimização que busca encontrar a melhor alocação de recursos escassos através de relações lineares.Um modelo de PL para o planejamento da produção é composto por:

Variáveis de Decisão: Representam as escolhas do gestor, como a quantidade de toneladas de cana a colher de cada variedade em cada mês $t$.
Função Objetivo: Define a meta do sistema (ex: minimizar custos totais de operação ou maximizar o aproveitamento da sacarose disponível).
Restrições: São os limites físicos e operacionais, como a capacidade de moagem da usina, a disponibilidade de cana no campo por variedade e o balanço de estoque mensal, garantindo que a quantidade vendida nunca supere a soma do que foi produzido e estocado.

A eficácia dessa técnica na agroindústria é documentada por Taube-Netto (1996), que demonstra que modelos matemáticos reduzem a subjetividade da gestão empírica e permitem a realização de análises de sensibilidade — fundamentais para prever o impacto de variações climáticas severas sobre o planejamento financeiro da agroindústria.

Referências Bibliográficas
COLIN, Emerson Carlos; CIPPARRONE, Flávio A. M.; SHIMIZU, Tamio. Otimização do Custo de Transporte na Distribuição-Armazenagem de Açúcar. Revista Produção, v. 11, n. 2, 2001.

PIEDADE, Rinaldo Vianna. Um modelo de planejamento do sequenciamento de corte da cana-de-açúcar. 1989. Dissertação (Mestrado em Engenharia de Produção) - Universidade Federal de Santa Catarina, Florianópolis, 1989.

SOUZA, Mariana Clemente de. Planejamento, Programação e Controle da Produção em uma agroindústria de cana-de-açúcar. 2022. Trabalho de Conclusão de Curso (Bacharelado em Engenharia de Produção) - Universidade Federal de Uberlândia, Ituiutaba, 2022.

TAUBE-NETTO, Miguel. Integrated planning for poultry production at Sadia. Interfaces, v. 26, n. 1, p. 38-53, 1996.

TOMIYA, Eduardo H. Modelo econômico de empresa sucroalcooleira. 1994. Dissertação (Mestrado) - Escola Politécnica da USP, São Paulo, 1994.



