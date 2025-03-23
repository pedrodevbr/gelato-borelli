
# GelatoBorelli - Sistema de Gestão de Estoque para Sorveteria

![GelatoBorelli Logo](https://i.imgur.com/yfYLKAl.jpg)

## Sobre o Projeto

GelatoBorelli é um sistema completo de gestão de estoque, vendas e pedidos desenvolvido especificamente para sorveterias. Com uma interface elegante inspirada na cultura italiana, o sistema oferece todas as ferramentas necessárias para o controle eficiente da sua gelateria.

## Funcionalidades

- **Dashboard**: Visualize métricas importantes como vendas do dia, produtos em estoque baixo e próximos do vencimento.
- **Gestão de Estoque**: Controle o estoque de produtos, registre entradas e saídas, e acompanhe movimentações.
- **Vendas**: Processe vendas rapidamente, com suporte para scanner de código de barras.
- **Pedidos Automáticos**: O sistema gera pedidos automáticos quando o estoque está baixo.
- **Fornecedores**: Gerencie seus fornecedores e seus respectivos produtos.
- **Relatórios**: Gere relatórios de vendas, movimentações de estoque e validades de produtos.
- **Alertas**: Receba notificações sobre produtos com estoque baixo ou próximos do vencimento.

## Tecnologias Utilizadas

- **Frontend**: React.js, CSS personalizado baseado no tema GelatoBorelli
- **Estado**: React Hooks e Context API
- **Persistência**: JSON Server (API REST simulada)
- **Gráficos**: Recharts

## Instalação e Uso

### Pré-requisitos
- Node.js (versão 14 ou superior)
- npm ou yarn

### Passos para Instalação

1. Clone o repositório
```bash
git clone https://github.com/pedrodevbr/gelato-borelli.git
cd gelato-borelli
```

2. Instale as dependências
```bash
npm install
# ou
yarn install
```

3. Inicie o servidor de banco de dados
```bash
npm run server
# ou
yarn server
```

4. Em um novo terminal, inicie o aplicativo React
```bash
npm start
# ou
yarn start
```

5. Acesse a aplicação em seu navegador
```
http://localhost:3000
```

### Credenciais para Teste
- **Email**: admin@gelatoborelli.com
- **Senha**: admin123

## Estrutura do Projeto

```
/src
  /components
    /alertas      - Componentes de alertas de estoque e validade
    /auth         - Componentes de autenticação
    /configuracoes - Configurações do sistema
    /dashboard    - Dashboard com métricas e gráficos
    /estoque      - Gestão do estoque
    /fornecedores - Cadastro e gestão de fornecedores
    /layout       - Componentes estruturais (header, sidebar, etc)
    /pedidos      - Gerenciamento de pedidos automáticos
    /relatorios   - Relatórios diversos
    /ui           - Componentes de UI reutilizáveis
    /vendas       - Processamento de vendas
  /context        - Context API para gerenciamento global
  /data           - Dados iniciais e constantes
  /hooks          - Hooks personalizados
  /services       - Serviços para comunicação com a API
  /styles         - Estilos e tema GelatoBorelli
  /utils          - Funções utilitárias
```

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.

## Agradecimentos

- Inspiração na identidade visual GelatoBorelli
- Ícones fornecidos por Lucide React
