# DevParaná - Apresentação da Comunidade

Slides da apresentação da comunidade DevParaná criados com [Marp](https://marp.app/).

## 📦 Instalação

```bash
npm install
```

## 🚀 Desenvolvimento

Servir os slides localmente:

```bash
npm run serve
```

## 📄 Gerar Slides

Gerar HTML:

```bash
npm run build:html
```

Gerar PDF:

```bash
npm run build:pdf
```

Gerar todos os formatos:

```bash
npm run build
```

## 🌐 GitHub Pages

Os slides são automaticamente publicados no GitHub Pages através de GitHub Actions.

1. No repositório GitHub, vá em **Settings** > **Pages**
2. Configure a fonte como **GitHub Actions**
3. A cada push na branch `main` ou `master`, os slides serão gerados e publicados automaticamente

O workflow do GitHub Actions:
- Gera o HTML a partir do Markdown
- Copia as imagens necessárias
- Publica no GitHub Pages

## 📝 Editar Slides

Edite o arquivo `slides-devpr-comunidade.md` para modificar os slides. O arquivo usa a sintaxe Markdown do Marp.

## 🎨 Tema

Os slides usam um tema customizado branco e verde (#1fbf74), identidade visual do DevParaná.

---

**DevParaná** - Comunidade de Desenvolvedores do Paraná
