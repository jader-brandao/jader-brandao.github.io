# 🔧 Oficina Mecânica Amarela

Sistema completo de gestão para oficinas mecânicas, desenvolvido com IA, tecnologias web modernas e armazenamento local.

## 📋 Funcionalidades

### 🏠 Dashboard
- Visão geral com estatísticas em tempo real
- Alertas de estoque baixo
- Ordens de serviço recentes
- Métricas mensais (receita, serviços concluídos, peças utilizadas)

### 👥 Gestão de Clientes
- Cadastro completo de clientes
- Busca e filtros avançados
- Histórico de veículos por cliente

### 🚗 Controle de Veículos
- Registro detalhado de veículos
- Vinculação com proprietários
- Histórico de manutenções

### 🔩 Estoque de Peças
- Controle de estoque com alertas automáticos
- Gestão de preços e fornecedores
- Sistema de estoque mínimo

### ⚙️ Catálogo de Serviços
- Biblioteca de serviços oferecidos
- Preços e tempo estimado
- Descrições detalhadas

### 📝 Ordens de Serviço
- Criação e acompanhamento de OS
- Controle de status (Aberta, Em Andamento, Concluída, Cancelada)
- Cálculo automático de valores
- Sistema de compartilhamento

## 🚀 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Icons**: Lucide Icons
- **Database**: IndexedDB (armazenamento local)
- **PWA**: Service Workers (opcional)

## 💾 Características Técnicas

- ✅ **100% Offline** - Funciona sem conexão com internet
- ✅ **Responsivo** - Interface adaptável para desktop, tablet e mobile
- ✅ **Backup/Restore** - Sistema completo de backup em JSON
- ✅ **Busca Avançada** - Filtros em tempo real
- ✅ **Ordenação** - Tabelas ordenáveis por qualquer coluna
- ✅ **Dados Demo** - Carregamento de dados de exemplo

## 🛠️ Como Usar

### Instalação
1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. O sistema funcionará imediatamente (sem necessidade de servidor)

### Primeiro Acesso
1. Acesse o sistema pelo navegador
2. Use "Carregar Dados Demo" para popular o sistema com exemplos
3. Ou comece criando seus próprios dados

### Backup e Restauração
- **Exportar**: Menu lateral → Exportar Backup
- **Importar**: Menu lateral → Importar Backup
- **Limpar**: Menu lateral → Limpar Banco (cuidado!)

### Navegação
- **Desktop**: Use o menu lateral fixo
- **Mobile**: Toque no ícone ☰ para abrir o menu

## 📱 Compatibilidade

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers

## 🎯 Funcionalidades em Destaque

### Sistema de Estoque Inteligente
- Controle automático de estoque ao criar/editar ordens
- Alertas visuais para peças com estoque baixo
- Validação para evitar uso de peças indisponíveis

### Interface Responsiva
- Design mobile-first
- Tabelas com scroll horizontal em dispositivos pequenos
- Modais otimizados para diferentes tamanhos de tela

### Experiência do Usuário
- Feedback instantâneo com toasts informativos
- Confirmações para ações destrutivas
- Loading states para operações assíncronas

## 📊 Estrutura de Dados

O sistema utiliza 5 entidades principais:
- **Clientes**: Nome, email, telefone, endereço
- **Veículos**: Placa, marca, modelo, ano, cor, observações
- **Peças**: Código, nome, marca, preço, estoque, estoque mínimo
- **Serviços**: Nome, descrição, preço, duração estimada
- **Ordens**: Cliente, veículo, status, serviços, peças, valores, datas

## 🔒 Privacidade

- Todos os dados são armazenados localmente no navegador
- Nenhuma informação é enviada para servidores externos
- Controle total sobre backup e restauração

## 📞 Suporte

Este é um projeto de código aberto. Para dúvidas ou sugestões:
- Abra uma issue no repositório
- Faça um fork e contribua com melhorias

## 📄 Licença

Projeto de uso livre para fins educacionais e comerciais.

---

**Oficina Mecânica Amarela** - Sistema completo de gestão automotiva 🚗⚡
