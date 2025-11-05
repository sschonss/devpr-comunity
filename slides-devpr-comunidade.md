---
marp: true
theme: gaia
paginate: true
size: 16:9
class: lead
---

<style>
/* Tema customizado: branco com verde DevParaná */
section {
  --color-background: #ffffff;
  --color-foreground: #1a1a1a;
  --color-dimmed: #666666;
  --color-highlight: #1fbf74;
  background-color: var(--color-background);
  color: var(--color-foreground);
  background-image: none;
}

h1, h2, h3, h4, h5, h6 {
  color: var(--color-highlight);
}

h1 strong, h2 strong, h3 strong, h4 strong, h5 strong, h6 strong {
  color: var(--color-highlight);
}

a, mark {
  color: var(--color-highlight);
}

code {
  background: #f5f5f5;
  color: var(--color-foreground);
}

pre {
  background: #1a1a1a;
  color: #ffffff;
}

pre code {
  background: transparent;
  color: #ffffff;
}

blockquote {
  border-left-color: var(--color-highlight);
  color: var(--color-dimmed);
}

blockquote:before,
blockquote:after {
  color: var(--color-highlight);
}

footer, header, section:after {
  color: var(--color-dimmed);
}

section::before {
  content: '';
  position: absolute;
  top: 20px;
  left: 20px;
  width: 150px;
  height: 75px;
  background-image: url('logo-dev-parana.png');
  background-size: contain;
  background-repeat: no-repeat;
  background-position: left center;
  z-index: 10;
}

/* Remover logo na primeira página (capa) */
section:first-child::before {
  display: none;
}

section:first-child header {
  display: none;
}

table thead th {
  background: var(--color-highlight);
  color: #ffffff;
}

table td, table th {
  border-color: #e0e0e0;
}
</style>

<!-- _header: ![w:120px](logo-dev-parana.png) -->

<!-- Slide 1: Capa -->
![w:300px](logo-dev-parana.png)

# Apresentação da Comunidade

---

<!-- Slide 2: Apresentação Pessoal -->

![bg left:35% 90%](esse-sou-eu.jpg)

**Luiz Schons**

23 anos

Senior Software Engineer — PicPay

Community Manager — DevParaná

---

<!-- Slide 3: História da Comunidade -->

## O que é a comunidade?

O DevParaná surgiu em **2015** e desde então tem conectado pessoas desenvolvedoras, entusiastas e empresas no ecossistema de tecnologia do Paraná.

Nossa missão é fomentar aprendizado contínuo, colaboração e oportunidades através de eventos presenciais, conteúdo e networking.

---

<!-- Slide 4: Cidades 2025 -->

![bg 100%](cidades-2025.png)

---

<!-- Slide 5: Eventos Promovidos -->

## Eventos que já promovemos

- **DevParaná Conf**
- **DevParaná na Estrada**
- **Meetups mensais nas cidades**
- **Rodas de conversa**

---

<!-- Slide 6: Fotos dos Eventos -->

![bg contain](nossos-eventos.png)

---

<!-- Slide 7: Fotos dos Palestrantes -->

![bg 90%](palestrantes.png)

---

<!-- Slide 8: Quem faz a comunidade? -->

## Quem faz a comunidade?

---

<!-- Slide 9: Foto do Público -->

![bg 90%](nosso-publico.png)

---

<!-- Slide 10: Como posso ajudar? -->

## Como eu posso ajudar?

- **Palestrando**
- **Projetos Open Source** (devMX e Baas)
- **Disponibilizando espaços** (auditórios e etc)
- **Participando dos eventos**

---

<!-- Slide 11: Empresas Apoiadoras -->

## Empresas que já apoiaram o DevParaná:

- Grupo 3C
- DAM System
- Cilla Tech Park
- Michelc
- UTFPR
- Campo Real / Centro de Inovação
- Secretaria de Ciência, Tecnologia e Inovação
- ACT Tecnologia

<style scoped>
section {
  font-size: 32px;
}
ul {
  margin-top: 20px;
}
li {
  margin: 8px 0;
}
</style>

---

<!-- Slide 12: Contato -->

## Contato

**WhatsApp:** 42 999146456

**Email:** luiz.schons@devpr.org

