# Academic Domains Whitelist

Lista de filtros para uBlock Origin que permite funcionalidade completa em domínios acadêmicos e de pesquisa, mantendo proteção contra rastreamento predatório.

---

## 📋 Sobre

Esta whitelist preserva a relacionalidade epistêmica em espaços de produção de conhecimento, permitindo:

- ✅ Plataformas de rede acadêmica (ResearchGate, Academia.edu, ORCID)
- ✅ Repositórios e preprints (arXiv, bioRxiv, SSRN, Zenodo)
- ✅ Bases de dados e indexadores (Google Scholar, PubMed, Scopus, Web of Science)
- ✅ Editoras científicas (Nature, Science, JSTOR, Springer, Elsevier, Wiley)
- ✅ Domínios institucionais (.edu, .ac.uk, .edu.br)

Simultaneamente, **bloqueia analytics predatórios** mesmo em contextos acadêmicos (Google Analytics, Facebook Pixel, DoubleClick).

---

## 🚀 Instalação

### 1. Importar no uBlock Origin

1. Abra o **Dashboard do uBlock Origin** (clique no ícone → ⚙️)
2. Vá para a aba **"Listas de filtros"**
3. Role até **"Importar..."**
4. Cole a URL abaixo:

https://raw.githubusercontent.com/donatoniii/ublock/main/academic-whitelist.txt#Academic Domains Whitelist

5. Clique em **"Aplicar mudanças"** → **"Atualizar agora"**

### 2. Validar

- Acesse `researchgate.net` ou `arxiv.org`
- Clique no ícone do uBlock → 🪵 **Logger**
- Verifique se requisições aparecem como **"allowed"** (verde)

---

## 📁 Arquivos

| Arquivo | Descrição |
|---------|-----------|
| `academic-whitelist.txt` | Lista principal de filtros (importar no uBlock) |
| `README.md` | Esta documentação |
| `LICENSE` | CC0-1.0 (Domínio Público) |

---

## 🔄 Atualização

A lista é atualizada periodicamente. O uBlock Origin busca atualizações automaticamente a cada **12-24 horas**.

Para forçar atualização manual:
1. Dashboard → **"Listas de filtros"**
2. Clique em **"Limpar cache"**
3. Clique em **"Atualizar agora"**

---

## 🛠️ Validação

Este repositório usa **GitHub Actions** com AGLint para validação automática de sintaxe em cada commit.

![Validate](https://github.com/donatoniii/ublock/actions/workflows/validate.yml/badge.svg)

---

## 📄 Licença

[CC0-1.0](LICENSE) — Domínio Público. Use, modifique e redistribua sem restrições.

---

## 🤝 Contribuições

Sugestões de novos domínios acadêmicos são bem-vindas via **Issues** ou **Pull Requests**.

**Critérios para inclusão:**
- Domínio deve ser primariamente acadêmico/científico
- Deve ter processo de revisão por pares ou ser repositório institucional
- Não serão incluídos domínios com rastreamento predatório não-essencial

---

## 📊 Estatísticas

| Métrica | Valor |
|---------|-------|
| Versão atual | 2026.02.28.1 |
| Total de regras | ~80 |
| Última atualização | 2026-02-28 |
| Validação automática | ✅ Ativo |

---

## ⚠️ Aviso de Uso

Esta lista é fornecida "como está". Teste em seu ambiente antes de usar em produção. Regras muito permissivas podem reduzir a proteção de privacidade.

---

## 🔗 Links Relacionados

- [uBlock Origin — Documentação Oficial](https://github.com/gorhill/uBlock/wiki)
- [Sintaxe de Filtros ABP](https://help.adblockplus.org/hc/en-us/articles/360062733293)
- [AGLint — Validador de Filtros](https://github.com/AdguardTeam/AGlint)

---

*Última revisão: 2026-02-28*
