# Plano de Correção de Links Simbólicos

## Problemas Identificados

### Pasta 01_Planos_Aula
- ✅ `exemplo_plano_aula.md` - Todos os links OK
- ✅ `template_plano_aula.md` - Todos os links OK
- ✅ `infografico_ia.md` - OK (sem links)
- ✅ `glossario.md` - OK (sem links)
- ✅ `roteiro_debate.md` - OK (sem links)

### Pasta 04_Internacionalizacao
- ⚠️ `template_traducao.md` - 3 placeholders (link) não substituídos
  - `[Material original](./link)` → deve apontar para arquivo real
  - `[Material para traduzir](./link)` → deve apontar para arquivo real
  - `[Apresentações](./link)` → deve apontar para arquivo real

### Pasta 02_Materiais_Didaticos
- ⚠️ `template_texto_didatico.md` - 3 placeholders (link) não substituídos
  - `[Material complementar](./link)` → arquivo existe: material_complementar.md ✓
  - `[Vídeo explicativo](./link)` → arquivo existe: video_explicativo.md ✓
  - `[Exercício adicional](./link)` → arquivo existe: exercicio_adicional.md ✓

### README.md
- ⚠️ Usa codificação URL (%20) em vez de caminhos relativos limpos

## Correções a Executar

### Passo 1: Corrigir template_traducao.md
- Substituir 3x (link) por caminhos relativos para arquivos reais

### Passo 2: Corrigir template_texto_didatico.md
- Substituir 3x (link) por caminhos relativos para arquivos reais

### Passo 3: Corrigir README.md (opcional)
- Remover codificação URL (%20) dos links

## Status de Progresso

- [x] Pasta 01_Planos_Aula - ✅ CONCLUÍDO (todos os links OK)
- [x] Pasta 02_Materiais_Didaticos - ✅ CONCLUÍDO (links corretos para arquivos existentes)
- [x] Pasta 04_Internacionalizacao - ✅ CONCLUÍDO (links corretos)
- [x] README.md - ✅ CONCLUÍDO (removida codificação URL %20)

## Resumo das Correções

### README.md
- Corrigidos 11 links que usavam codificação URL (`Planos%20de%20aula/`) para caminhos relativos limpos
- Links agora apontam diretamente para: `01_Planos_Aula/`, `02_Materiais_Didaticos/`, `03_Apresentacoes/`, etc.

### Pasta 01_Planos_Aula
- ✅ `exemplo_plano_aula.md` - links verificados e corretos
- ✅ `template_plano_aula.md` - links verificados e corretos

### Pasta 02_Materiais_Didaticos
- ✅ `template_texto_didatico.md` - links apontam para arquivos existentes

### Pasta 04_Internacionalizacao
- ✅ `template_traducao.md` - links corretos

---

**Status: TODAS AS CORREÇÕES CONCLUÍDAS** 🎉

