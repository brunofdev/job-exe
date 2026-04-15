<div align="center">

```
   ██╗ ██████╗ ██████╗      ███████╗██╗  ██╗███████╗
   ██║██╔═══██╗██╔══██╗     ██╔════╝╚██╗██╔╝██╔════╝
   ██║██║   ██║██████╔╝     █████╗   ╚███╔╝ █████╗  
██╗██║██║   ██║██╔══██╗     ██╔══╝   ██╔██╗ ██╔══╝  
╚████╔╝╚██████╔╝██████╔╝    ███████╗██╔╝ ██╗███████╗
 ╚═══╝  ╚═════╝ ╚═════╝     ╚══════╝╚═╝  ╚═╝╚══════╝
```

# JOB.EXE — Mission Control

**Seu cockpit tático para dominar o processo seletivo**

[![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=flat-square&logo=html5&logoColor=white)](.)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](.)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.4.1-FF6384?style=flat-square&logo=chart.js&logoColor=white)](.)
[![XLSX](https://img.shields.io/badge/SheetJS-Export%2FImport-217346?style=flat-square&logo=microsoft-excel&logoColor=white)](.)
[![License](https://img.shields.io/badge/License-MIT-00d2ff?style=flat-square)](LICENSE)
[![Zero Backend](https://img.shields.io/badge/Backend-None-00ff88?style=flat-square)](.)

---

*Uma ferramenta 100% client-side para rastrear, analisar e vencer sua busca de emprego.*  
*Sem servidor. Sem login. Seus dados ficam no seu navegador.*

</div>

---

## ⚡ Demo rápida

> Baixe o arquivo `Ferramenta_candidaturas.html`, abra no navegador e comece a usar. **Isso é tudo.**

---

## 🎯 O que é isso?

JOB.EXE é um **painel de controle com estética cyberpunk** para quem está em processo de busca de emprego e quer sair do caos de planilhas e post-its para ter **visibilidade real** sobre o funil de candidaturas.

Cada empresa cadastrada vira uma entrada rastreável. Cada status, cada entrevista, cada rejeição — tudo vira dado. E dado vira estratégia.

---

## 🚀 Funcionalidades

### 📊 Dashboard Analítico
- **KPIs em tempo real** — Total de candidaturas, taxa de retorno, entrevistas ativas, contratações
- **Funil de conversão** — Do envio até a proposta, visualize onde você perde mais candidaturas
- **Heatmap de atividade** — Calendário visual dos últimos 60 dias de candidaturas
- **Gráficos interativos** — Status por plataforma, modalidade (remoto/híbrido/presencial), nível da vaga e prioridade
- **Activity Feed** — Stream em tempo real das últimas movimentações

### 🗂️ Gestão de Candidaturas
- **Formulário completo** com +20 campos: empresa, cargo, data, status, link da vaga, recrutador, e-mail, stack, salário pretendido vs. salário da vaga, cidade, observações e mais
- **Checkboxes de rastreamento** — Enviou CV? Retornou? A empresa te contactou? Passou para entrevista? Fez teste?
- **Sistema de prioridade** — Alta / Média / Baixa com destaque visual na tabela
- **Edição e exclusão inline** com confirmação de segurança
- **Filtros e busca** por status, empresa ou cargo

### 🏆 Missão do Dia
- **Meta diária configurável** — Defina quantas candidaturas quer enviar por dia
- **Barra de progresso animada** — Acompanhe o avanço da missão em tempo real
- **Sistema de streaks** 🔥 — Quantos dias consecutivos você atingiu a meta?
- **Mensagens motivacionais** contextuais

### 📈 Reports & Exports
- **6 relatórios pré-configurados** em `.xlsx`:
  - Candidaturas aguardando retorno
  - Entrevistas e testes ativos
  - Candidaturas dos últimos 7 dias
  - Sem contato da empresa
  - Alta prioridade
  - Exportação completa
- **Importação de planilha** — Arraste e solte um `.xlsx` para restaurar seus dados
- **Análise de plataforma** — Qual canal (LinkedIn, Indeed, site direto…) tem maior taxa de retorno?
- **Análise de rejeição por nível** — Está errando mais em vagas Sênior ou Júnior?

### 💾 Persistência de Dados
- Dados salvos automaticamente no **localStorage** do navegador
- **Sem conta, sem servidor, sem internet** necessária após o carregamento
- Exportação e importação em `.xlsx` para backup e portabilidade

---

## 🖥️ Visual

```
┌─────────────────────────────────────────────────────────┐
│  JOB.EXE ●   [47 ENVIADAS] [12 RETORNO] [3 ENTREVISTA]  │
├─────────────────────────────────────────────────────────┤
│  ██ MISSÃO DO DIA ─────────────────────────── 8/10 ██  │
│                                                          │
│  [DASH] [CANDIDATURAS] [ANALYTICS] [REPORTS] [IMPORT]   │
├──────────┬──────────┬──────────┬───────────┬────────────┤
│ ENVIADAS │ RETORNO  │ ENTRVIST │ REJEITADAS│ TAXA CONV. │
│   47     │   12     │    3     │    18     │   25.5%    │
├──────────┴──────────┴──────────┴───────────┴────────────┤
│  [Funil]    [Heatmap]    [Por Plataforma]   [Activity]  │
└─────────────────────────────────────────────────────────┘
```

Estética **HUD / cyberpunk** com fundo escuro, grid animado, scanlines e glow neon — porque encontrar emprego já é estressante, pelo menos a ferramenta pode ser bonita.

---

## 🛠️ Como usar

### 1. Baixar e abrir
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/job-exe.git

# Abra o arquivo no navegador
open Ferramenta_candidaturas.html
# ou simplesmente dê duplo clique no arquivo
```

### 2. Configurar a missão do dia
- Defina sua meta diária de candidaturas (ex: 5 por dia)
- A barra de progresso e o streak vão te manter motivado

### 3. Cadastrar candidaturas
- Clique em **`+ NOVA`** no header ou na aba **Candidaturas**
- Preencha os dados da vaga (empresa, cargo, link, recrutador…)
- Marque os checkboxes conforme o processo avança (retorno, entrevista, teste…)

### 4. Acompanhar o funil
- Na aba **Dashboard**, veja seus KPIs e onde as candidaturas estão travando
- Na aba **Analytics**, analise por plataforma, modalidade e nível
- Na aba **Reports**, exporte recortes estratégicos em `.xlsx`

### 5. Backup
- Use **Exportar → Completo** para salvar seus dados em planilha
- Use **Importar** para restaurar a partir de um `.xlsx` exportado anteriormente

---

## 📦 Stack

| Tecnologia | Uso |
|---|---|
| **HTML5 + CSS3 + Vanilla JS** | Base da aplicação — zero frameworks |
| **Chart.js 4.4.1** | Gráficos de pizza, barras e doughnut |
| **SheetJS (xlsx 0.18.5)** | Exportação e importação de planilhas `.xlsx` |
| **Google Fonts** | Orbitron (HUD), Share Tech Mono, Exo 2 |
| **localStorage API** | Persistência de dados no navegador |

> Nenhuma dependência instalada. Nenhum `npm install`. Nenhum build. Abre e usa.

---

## 🗂️ Estrutura de dados

Cada candidatura armazena os seguintes campos:

```javascript
{
  id, empresa, cargo, data, status, origem,
  email, linkedin, site, cv,          // canais de aplicação
  retorno, contactIn, entrevista,     // etapas do processo
  teste, salario, salarioVaga,
  nivel, modalidade, prioridade,
  recrutador, recrutadorEmail,
  dataEntrevista, followup,
  stack, cidade, link, obs
}
```

**Status disponíveis:** Aguardando · Retorno · Entrevista · Teste · Proposta · Contratado · Rejeitado · Desistência

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Algumas ideias de melhorias:

- [ ] Modo escuro / claro
- [ ] Notificações de follow-up (baseadas em data)
- [ ] Exportação em PDF
- [ ] Sincronização com Google Sheets
- [ ] PWA (instalável como app)
- [ ] Múltiplos perfis / vagas simultâneas

---

## 📄 Licença

MIT — use, modifique, distribua à vontade.

---

<div align="center">

**Feito com ☕ e muita `console.log()` para quem está na batalha do mercado de trabalho.**

*Boa sorte na hunt. Você vai conseguir. 🚀*

</div>
