# SGPD - Sistema de Gestão de Processos Dashboard

Sistema web moderno para gestão e monitoramento de processos corporativos, construído com React, TypeScript e Tailwind CSS.

## 🎯 Funcionalidades

- **Dashboard Interativo**: Visualização em tempo real de processos com cards de KPI coloridos
- **Gestão de Tarefas**: Tabela de tarefas urgentes com filtros e ordenação
- **Detalhes do Processo**: Histórico completo, documentos anexados e timeline de atividades
- **Navegação Intuitiva**: Sidebar responsiva com menu (Dashboard, Processos, Novo)
- **Design Profissional**: Paleta de cores consistente (#1A365D sidebar, #F7FAFC background)

## 📊 KPIs Monitorados

- **Em Andamento** (Azul): Processos atualmente em execução
- **Atrasados** (Vermelho): Processos que ultrapassaram o prazo
- **Concluídos** (Verde): Processos finalizados com sucesso
- **Pendentes** (Amarelo): Processos aguardando ação

## 🚀 Tecnologias

- React 18
- TypeScript
- Tailwind CSS v4
- Vite
- Lucide React (ícones)
- Recharts (gráficos)

## 📦 Instalação

```bash
# Instalar dependências
pnpm install

# Executar em desenvolvimento
pnpm dev

# Build para produção
pnpm build
```

## 🎨 Estrutura do Projeto

```
src/
├── app/
│   ├── App.tsx                    # Componente principal
│   ├── components/
│   │   ├── Layout.tsx             # Layout principal com sidebar
│   │   ├── Sidebar.tsx            # Menu lateral de navegação
│   │   ├── Dashboard.tsx          # Dashboard principal
│   │   └── sgpd/
│   │       ├── KPICard.tsx        # Cards de indicadores
│   │       ├── TasksTable.tsx     # Tabela de tarefas
│   │       └── ProcessDetails.tsx # Detalhes do processo
│   └── styles/
│       └── globals.css            # Estilos globais
```

## 🔧 Customização

### Cores do Sistema
As cores principais podem ser ajustadas no código:
- Sidebar: `#1A365D`
- Background: `#F7FAFC`
- Ações/Links: `#3182CE`

### Adicionar Novos KPIs
Edite o array `kpiData` em `Dashboard.tsx` para adicionar novos indicadores.

## 📝 Licença

Projeto desenvolvido para fins educacionais e demonstração.

---

Desenvolvido com ❤️ usando Figma Make
