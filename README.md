```mermaid
gantt
    title Sistema de Cadastro de Empresas Parceiras - TechConnect Solutions
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Planejamento
    Levantamento de Requisitos          :a1, 2025-10-01, 2025-10-07
    Documentação Funcional              :a2, after a1, 7d
    Design de Interface (Protótipos)    :a3, after a2, 5d

    section Desenvolvimento
    Configuração do Ambiente            :b1, after a3, 3d
    Criação do Banco de Dados           :b2, after b1, 6d
    Módulo de Login e Autenticação      :b3, after b2, 14d
    CRUD de Empresas                    :b4, after b3, 20d
    Upload de Logotipo                  :b5, after b4, 14d
    Relatórios PDF/Excel                :b6, after b5, 20d
    Painel Administrativo               :b7, after b6, 20d

    section Testes e Validação
    Testes Unitários e Integração       :c1, after b7, 15d
    Testes de Usabilidade               :c2, after c1, 15d

    section Entrega
    Implantação no Servidor             :d1, after c2, 10d
    Validação Final com o Cliente       :d2, after d1, 10d
