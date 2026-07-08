# Miniguia-PPCI-notebooklm
Facilitando o desenvolvimento de projetos de prevenção e combate a incêndio (PPCI) para edifícios residenciais, com IA treinada especificamente com as principais instruções técnicas do corpo de bombeiros de São Paulo, permitindo tirar dúvidas de forma rápida e eficiente, sem riscos de alucinações por parte da IA.

Para os iniciantes no densenvolvimento de PPCI (assim como eu já fui) e até para os experientes, pois é inevitável esquecer algum detalhe com o tempo, esse recurso economiza horas e horas de pesquisas em mais de 50 instruções técnicas do corpo de bombeiros pra tirar pequenas dúvidas. A utilização da IA permite ao projetista focar no desenvolvimento do desenho feito no AutoCAD, Revit ou qualquer outro software relacionado. 

A IA recebeu como fonte as 47 principais instruções técnicas do corpo de bombeiros de SP para projetos de edifícios residenciais, além do decreto 69.118/24 para classificar a categoria da edificação.

[Notebooklm - Projeto de Combate a Incêndio em SP - Edifícios Residenciais](https://notebooklm.google.com/notebook/24ef1b89-c34d-4b6a-9b15-597333e9475d)  
  
# Utilização
Recomendo que comece passando o contexto da edificação, por exemplo: 

    Considerando um prédio com as seguintes características:
    
    Tipo: Residencial
    28m de altura
    Pavimentos com área de até 150m²
    Área total do terreno 600m²
  
    Qual seria a categoria dele e quais sistemas de combate a incêndio seriam exigidos nele?

Dessa forma a IA irá informar todas as características que deveram ser abordadas no projeto, além de entender especificamente qual é seu caso. No exemplo acima a resposta da IA foi a seguinte: 

    Com base nas características fornecidas e nos regulamentos de segurança contra incêndio do Estado de São Paulo, a classificação e as exigências para o edifício são as seguintes:
    
    1. Categoria e Classificação:
     
     Grupo e Divisão: O prédio é classificado como Grupo A (Residencial), Divisão A-2 (Habitação multifamiliar), que engloba edifícios de apartamentos em geral.
    
     Classificação quanto à Altura: Com 28 metros de altura, o edifício é enquadrado como Classe V – Edificação Mediamente Alta (para construções com altura entre 23 m e 30 m).
    
    Carga de Incêndio: A carga de incêndio específica para apartamentos (A-2) é de 300 MJ/m², considerada de potencial de risco baixo.
    
    2. Medidas de Segurança Contra Incêndio Exigidas
     
      Como o edifício possui altura superior a 12 metros, ele deve seguir as exigências da Tabela 6A do Decreto Estadual nº 69.118/24 para a faixa de altura entre 23 m e 30 m.
      
      Os sistemas e medidas obrigatórios são:
      
      Acesso de Viatura na Edificação: Facilita a aproximação e operação dos bombeiros em caso de emergência.
      
      Segurança Estrutural contra Incêndio: Garante a resistência ao fogo dos elementos de construção (TRRF), geralmente de 90 minutos para essa classe de altura (Classe P4).
      
      Compartimentação:
        Horizontal: Devem ser atendidas as regras de separação entre as unidades autônomas (apartamentos).
        
        Vertical: Exigida para evitar a propagação do fogo entre os pavimentos.
        
      Controle de Materiais de Acabamento e Revestimento (CMAR): Limita o uso de materiais combustíveis para restringir a propagação de chamas e fumaça.
      
      Saídas de Emergência: Inclui o dimensionamento de corredores e escadas. Para um edifício A-2 com menos de 50 metros de altura e pavimentos de até 750 m², a escada deve ser do tipo EP (Escada Enclausurada Protegida).
      
      Brigada de Incêndio: Grupo de ocupantes treinados para atuar na prevenção e no combate a princípios de incêndio.
      
      Iluminação de Emergência: Sistema que garante a visibilidade das rotas de fuga em caso de falta de energia.
      
      Alarme de Incêndio: Sistema de aviso sonoro que pode ser setorizado em uma central junto à portaria com vigilância 24 horas.
      
      Sinalização de Emergência: Placas indicativas de rotas de fuga, saídas e localização de equipamentos.
      
      Extintores: Proteção por equipamentos portáteis para combate a princípios de incêndio.
      
      Hidrantes e Mangotinhos: Sistema hidráulico fixo para combate ao fogo. Para essa área e ocupação, a reserva de incêndio mínima (RTI) é geralmente de 8 m³ (Sistema Tipo 2).
    
    3. Observações Relevantes
      Projeto Técnico: Devido à altura de 28m, a regularização deve ser feita via Projeto Técnico (PT), exigindo análise prévia de planta pelo Corpo de Bombeiros e posterior vistoria para emissão do AVCB.

      Subsolos: Caso o prédio possua subsolo ocupado (além de estacionamento), poderão ser exigidas medidas adicionais como chuveiros automáticos ou controle de fumaça, dependendo da área.
      
      Elevador de Emergência: Não é obrigatório para esta altura em edifícios residenciais A-2, sendo exigido apenas para alturas superiores a 80 metros.

Com essas informações seria possível afunilar dúvidas, por exemplo com o seguinte prompt: 

    Passe mais detalhe sobre o tipo de escada EP

A IA irá te apresentar todas as características desse tipo de de escada segundo as instruções técnicas:

    A Escada Enclausurada Protegida (EP) é um dos modelos fundamentais de saídas de emergência, projetada para oferecer um ambiente seguro de abandono em edificações de média altura.
  
    Abaixo, detalho os requisitos técnicos e as características exigidas para esse tipo de escada:
  
    1. Proteção Contra Fogo (Compartimentação)
       
      Enclausuramento: A escada deve ser situada em ambiente envolvido por paredes que garantam um Tempo de Resistência ao Fogo (TRRF) de, no mínimo, 120 minutos.
    
      Portas Corta-Fogo (PCF): O acesso à caixa de escada deve ser feito obrigatoriamente através de portas corta-fogo com resistência mínima de 90 minutos (P-90).
      
    2. Requisitos de Ventilação
       
      A ventilação é o ponto crítico da escada tipo EP para garantir a expulsão da fumaça:
      
      Janelas nos Pavimentos: Deve possuir janelas abrindo diretamente para o espaço livre exterior em todos os pavimentos (exceto na descarga, onde é facultativo).
      
        Área de ventilação: Cada janela deve ter uma área efetiva mínima de 0,80 m².
    
        Posicionamento: Devem estar situadas junto ao teto ou, no máximo, a 40 cm deste, com o peitoril a pelo menos 1,10 m do piso.
      
        Afastamentos: Devem manter distância mínima de 1,40 m de outras aberturas no mesmo plano e 2,00 m de aberturas em planos distintos para evitar a entrada de fumaça vinda de outros locais.
      
      Ventilação Superior: No topo da escada, deve haver uma janela ou alçapão para saída de fumaça com área mínima de 0,80 m².
      
      Ventilação Permanente Inferior: Exige-se uma entrada de ar puro no nível do solo ou patamar intermediário do térreo, com área mínima de 1,20 m².
      
    3. Dimensionamento e Acessibilidade
       
      Largura: Geralmente dimensionada em função da população, sendo o padrão mínimo de 1,20 m para a maioria das ocupações.
      
      Área de Resgate: É obrigatório prever, no patamar de acesso, uma área de resgate para pessoas com deficiência (PCD) com dimensões mínimas de 1,20 m x 0,80 m, sinalizada e sem obstruir o fluxo de saída.
      
      Degraus: Devem seguir a fórmula de Blondel (63 cm≤2h+b≤64 cm), com altura (h) entre 16 e 18 cm e largura (b) compatível.
      
    4. Materiais e Acabamentos
       
      Incombustibilidade: A estrutura da escada e os materiais de acabamento/revestimento devem ser obrigatoriamente incombustíveis (Classe I) ou de Classe II-A.
      
      Piso: Deve ser antiderrapante e permanecer nessa condição mesmo com o uso.
      
    5. Sinalização e Iluminação
       
      Deve ser dotada de iluminação de emergência em todos os patamares e sinalização de balizamento indicando o sentido da fuga e a numeração do pavimento.
      
      A sinalização de identificação deve ser instalada a uma altura de 1,80 m, visível tanto por quem sobe quanto por quem desce.
      
    Cenário de Aplicação (Exemplo do seu caso): Para edifícios residenciais (Divisão A-2), a escada EP é exigida para alturas entre 12 m e 30 m. 
    Caso o pavimento tenha até 750 m², ela pode ser utilizada em prédios de até 50 metros de altura, substituindo a exigência de escada à prova de fumaça (PF).

Esse é só um exemplo de funcionamento no caso de desenvolvimento de um projeto do 0, no cotidiano é possível tirar qualquer dúvida sobre qualquer tema relacionado a PPCI de edifícios residênciais, sem a necessidade de passar o contexto completo. Até mesmo para preencher legendas do projeto, é possível perguntar especificamente em qual instrução técnica, e até em qual tópico, é falado sobre determinado assunto. Por exemplo:  

    Em qual instrução técnica e em qual tópico é especificado os detalhes sobre a "Reserva Técnica de Incêndio"

Onde a IA respondeu: 

    Os detalhes específicos sobre a Reserva Técnica de Incêndio (RTI), também referida como "Reserva de Incêndio", são tratados principalmente na 
    Instrução Técnica nº 22/2025 (Sistemas de hidrantes e de mangotinhos), no tópico 4.9, intitulado "Reservatório e reserva técnica de incêndio".

