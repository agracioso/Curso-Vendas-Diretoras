# 📊 Matriz de Priorização - Trilha de Venda Consultiva Fadelito

Artefato interativo para facilitar a priorização de módulos de treinamento em vendas consultivas junto com a cliente.

## ✨ Funcionalidades

- **Seleção Interativa**: Marque/desmarque módulos com checkboxes
- **8 Cenários Pré-Calculados**: Mínimo, Recomendado, Robusto, Completo A + 3 novos (Visão Estratégica, Expansão, Autorregulação)
- **Botão "Todos"**: Seleciona os 12 módulos de uma vez
- **2 Gráficos Dinâmicos**:
  - Composição por cenário (Mínimo vs Adicional)
  - Distribuição por tema (8 temas com cores diferentes)
- **Análise de Impacto Real-Time**:
  - Vantagens da seleção
  - Lacunas por categoria (Essenciais, Importantes, Desejáveis)
  - Validação de pré-requisitos
- **Dashboard**: Total de horas + resumo de módulos selecionados
- **Exportação**:
  - JSON para compartilhamento estruturado
  - TXT para resumo legível

## 🎯 Como Usar

1. Abra `priorizacao-fadelito.html` em um navegador moderno
2. Clique em um dos botões de cenário OU selecione módulos manualmente
3. Veja os gráficos e análise de impacto se atualizarem em tempo real
4. Exporte a seleção para compartilhar com a cliente

## 📋 Estrutura dos 12 Módulos

### Camada A — Núcleo (8 módulos)
- Fundamentos da Venda Consultiva (1.5h)
- Diferenciais Institucionais (1.5h)
- Qualificação e Leitura de Perfil (2h)
- Top 5 Objeções e Decisão Multi-Decisor (2.5h)
- Protocolo de Pós-Venda e Follow-up (1.5h)
- Roleplay com IA + Diário Reflexivo (3h)
- Gatilhos Mentais (1h)
- PNL e Rapport (1.5h)

### Camada B — Protocolo de Virada (2 módulos)
- Leitura de KPIs Comerciais (2h)
- Mapeamento de Concorrência Local (1.5h)

### Camada C — Onboarding (1 módulo)
- Imersão Cultural para Novas Lideranças (2h)

### Extra (1 módulo)
- Gestão Emocional / Resiliência Comercial (1h)

## 🎨 8 Temas com Cores

Cada módulo é categorizado por tema para melhor visualização:
1. **Fundação** (#667eea) - Fundamentos
2. **Proposta de Valor** (#f093fb) - Diferenciais
3. **Relacionamento** (#4facfe) - Qualificação, Pós-Venda, PNL
4. **Objeções** (#fa709a) - Top 5 Objeções, Gatilhos
5. **Prática** (#30cfd0) - Roleplay
6. **Gestão Comercial** (#a8edea) - KPIs, Concorrência
7. **Cultura** (#fed6e3) - Imersão Cultural
8. **Desenvolvimento Pessoal** (#ffecd2) - Gestão Emocional

## 💡 Cenários

| Cenário | Módulos | Horas | Caso de Uso |
|---------|---------|-------|-----------|
| **Mínimo** | 4 | 8.5h | MVP com fundamentos |
| **Recomendado** | 5 | 10.5h | Balanced com prática |
| **Robusto** | 6 | 12h | Cobertura maior |
| **Completo A** | 8 | 15h | Núcleo completo (teto) |
| **Visão Estratégica** | 10 | 18.5h | + KPIs + Concorrência |
| **Expansão em Bases Sólidas** | 9 | 17h | + Imersão Cultural |
| **Autorregulação** | 9 | 16h | + Gestão Emocional |
| **Todos** | 12 | 21.5h | Pacote completo |

## 🚀 Deploy no GitHub Pages

Para compartilhar o link com a cliente:

```bash
# 1. Criar repositório no GitHub (ex: Curso-Vendas-Diretoras)
# 2. Criar pasta 'docs' e mover o arquivo HTML
mkdir docs
mv priorizacao-fadelito.html docs/index.html

# 3. Fazer commit
git add docs/
git commit -m "Adiciona interface interativa para docs/"

# 4. Fazer push
git push origin master

# 5. No GitHub: Settings > Pages > Source: main/docs → Save
# Link fica: https://seu-usuario.github.io/Curso-Vendas-Diretoras/
```

## 📱 Responsividade

- Desktop: 4 colunas de botões + 2 painéis lado a lado
- Tablet: 2 colunas de botões + 1 painel por vez
- Mobile: 1 coluna + scroll vertical

## 🔧 Tecnologia

- **HTML5** (semântica + accessibility)
- **CSS3** (Grid, Flexbox, gradientes)
- **JavaScript vanilla** (sem dependências externas além de Chart.js)
- **Chart.js 4.4.0** (gráficos dinâmicos)

## 📝 Notas de Desenvolvimento

- Todos os dados ficam no navegador (sem servidor)
- Exportação usa Clipboard API (copiar JSON) e Blob (download TXT)
- Validação de pré-requisitos em tempo real
- Sem necessidade de build/compilação

---

**Versão**: 1.0.0  
**Data**: 20/06/2026  
**Autor**: Claude Code + Agracioso
