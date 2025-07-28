```mermaid
graph TB
    A[Fábrica Universitária de Insumos Farmacêuticos]
    
    A --> B1[🔹 Pilar 1: Administração e Gestão]
    A --> B2[🔹 Pilar 2: Produção e Operações]
    A --> B3[🔹 Pilar 3: Pesquisa, Inovação e Desenvolvimento]

    B1 --> C1[📊 Planejamento e Finanças]
    B1 --> C2[⚖️ Contratos e Compliance]
    B1 --> C3[👥 Gestão de Pessoas]

    B2 --> D1[🏭 Produção Farmacêutica]
    B2 --> D2[🧪 Controle de Qualidade]
    B2 --> D3[🚚 Logística e Estoques]

    B3 --> E1[🔬 P&D de Medicamentos]
    B3 --> E2[📚 Documentação Técnica]
    B3 --> E3[🏥 Testes Clínicos e Avaliação Social]

    B1 -- integração --> B2
    B2 -- feedback técnico --> B3
    B3 -- inovação orientada --> B2
    B3 -- apoio estratégico --> B1
