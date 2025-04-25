# 🎬 Documentário: NesquikDecompiler — O Raio-X dos Plugins de Minecraft
## 🍃 Website
Veja o site funcionando em: Breve...

## 🕹️ Introdução  
No coração da comunidade de Minecraft, onde criatividade e desenvolvimento se entrelaçam, surge uma ferramenta revolucionária. Seu nome? **NesquikDecompiler** — um site moderno, responsivo e poderoso, feito para um único propósito: **revelar o que está por trás dos arquivos `.jar` dos plugins de Minecraft**.

## 📦 O Problema  
Plugins são essenciais para personalizar servidores. Mas muitos vêm ofuscados, embaralhados, intocáveis... até agora. Com o NesquikDecompiler, isso muda. Agora é possível **enviar um plugin `.jar` diretamente pelo navegador** e, em segundos, **ver seu código-fonte descompilado**, de forma clara, rápida e segura.

## 🖥️ A Experiência do Usuário  
A interface foi pensada como um painel intuitivo, escuro e elegante. Com suporte a **drag & drop**, ou apenas um clique, o usuário envia seu arquivo `.jar`.  
O que acontece a seguir é quase mágico.

## ⚙️ Os Bastidores  
No backend, começa a engenharia:  
- O `.jar` é extraído, focando apenas em classes e arquivos relevantes.  
- Cada arquivo `.class` é descompilado utilizando ferramentas como **FernFlower**, **CFR** ou **Procyon**.  
- Os pacotes e classes aparecem organizados em uma estrutura navegável no frontend.  
- Ao clicar em qualquer classe, o usuário vê o **código Java descompilado** em tempo real, usando um editor estilo IDE.  
- Arquivos extras como `plugin.yml`, `.json` e `.yml` também podem ser visualizados de forma simples.

## 🛠️ Requisitos Técnicos  
- **Backend:** Pode ser feito com Python (Flask), Node.js (Express) ou Java (Spring);  
- **Frontend:** Criado com React ou outra biblioteca moderna, com tema escuro e foco na legibilidade do código;  
- **Armazenamento:** Nada é salvo no servidor. Tudo acontece em memória, com arquivos temporários, garantindo privacidade e segurança;  
- **Segurança:** Nenhum código é executado. O sistema valida que o `.jar` é realmente um plugin de Minecraft, buscando o `plugin.yml`.

## 🚀 O Nome  
Este projeto ambicioso atende por um nome ousado e criativo: **NesquikDecompiler**.
