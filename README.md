# 🧠 Segundo Cérebro em IA: Aprendizado de Inglês (Básico ao Avançado)

> **Desafio DIO:** Criando um Segundo Cérebro com IA no Gemini Notebook (NotebookLM)  
> **Autor:** Estudante DIO / Desenvolvedor Tech  
> **Ferramenta Utilizada:** [Gemini Notebook (NotebookLM - Google)](https://notebook.google.com/)  
> **Link do Notebook Compartilhado:** [Acessar Meu Gemini Notebook de Inglês](https://notebook.google.com/) *(Substitua pelo seu link público compartilhado)*

---

## 🎯 Tema e Objetivo

* **Tema:** Aprendizado do Idioma Inglês (do Nível Básico A1 ao Avançado C2 com foco em Inglês Geral e Técnico/Profissional).
* **Objetivo:** *"Construir um tutor especialista interativo em língua inglesa capaz de orientar estudantes do básico ao avançado através de fontes confiáveis curadas, fornecendo explicações gramaticais com citações exatas, listas de vocabulário contextual, testes interativos e materiais práticos de pronúncia e conversação."*

---

## 📚 Fontes Curadas e Justificativa de Confiabilidade

Para alimentar este segundo cérebro, selecionei exclusivamente fontes renomadas em múltiplos formatos (vídeos no YouTube, PDFs de matriz gramatical e artigos acadêmicos/técnicos). As buscas por vídeos foram efetuadas em **aba anônima** para evitar interferências do algoritmo de recomendação do YouTube.

| Fonte / Recurso | Formato | Criador / Instituição | Por que confio nesta fonte? |
|-----------------|---------|-----------------------|-----------------------------|
| **BBC Learning English - Basic to Advanced Grammar** | Vídeo / Transcrição | BBC World Service | Referência global em ELT (English Language Teaching) há mais de 80 anos, com metodologia pedagógica rigorosa. |
| **Cambridge English CEFR Companion Guide** | PDF | Cambridge Assessment English | Coautora do padrão internacional CEFR, fornecendo a matriz oficial de competências (A1 a C2). |
| **Rachel's English - Pronunciation & IPA** | Vídeo / Transcrição | Rachel's English | Especialista americana com mestrado em fonética, focada no Alfabeto Fonético Internacional e redução de sotaque. |
| **Oxford Online English - Business Conversations** | Artigo / Vídeo | Oxford Online English | Conteúdo desenvolvido por professores certificados CELTA/DELTA focado em situações reais de trabalho. |
| **Tech English Guide for Software Engineers** | PDF | OpenStax / MIT OCW | Material open-access do MIT com terminologia oficial utilizada em empresas globais de tecnologia. |

> 📌 *Veja a análise completa de exclusão e inclusão de fontes em [`docs/fontes_curadas.md`](docs/fontes_curadas.md).*

---

## 🤖 Diretriz de Comportamento (System Prompt)

Forneci a seguinte diretriz no painel de instruções do Gemini Notebook para garantir respostas didáticas, com rigor científico e citações obrigatórias:

```text
Você é o "English Master AI", um tutor pedagógico e especialista sênior no ensino do idioma inglês, qualificado nas metodologias Cambridge English, Oxford ELT e no Quadro Comum Europeu de Referência para Línguas (CEFR - níveis A1, A2, B1, B2, C1 e C2).

REGRAS DE RESPOSTA:
1. FIDELIDADE RÍGIDA ÀS FONTES: Responda SEMPRE apontando as citações diretas das fontes vinculadas a este Notebook.
2. DIDÁTICA E PROGRESSÃO: Identifique o nível da pergunta (A1 a C2), forneça explicação simples, frases de exemplo com tradução, dica de pronúncia e aplicação em Tech English.
3. TOM DE VOZ: Encorajador, estruturado e profissional.
4. MATERIAIS: Gere quizzes, guias e resumos sempre que solicitado.
```

> 📌 *Veja o documento completo em [`docs/diretriz_comportamento.md`](docs/diretriz_comportamento.md).*

---

## 💬 Perguntas Realizadas e Respostas com Citações

Abaixo estão exemplos das interações realizadas com a IA, demonstrando que todas as respostas foram extraídas diretamente das fontes cadastradas:

### ❓ Pergunta 1 (Nível Intermediário - B1):
> *"Qual é a diferença entre 'I have worked here since 2020' e 'I worked here in 2020'? Explique e mostre de qual fonte veio a resposta."*

#### 🤖 Resposta do Gemini Notebook:
> 1. **"I have worked here since 2020" (Present Perfect):** Indica uma ação que iniciou em 2020 e **continua até o presente**.
> 2. **"I worked here in 2020" (Past Simple):** Indica uma ação concluída no passado. Você **não trabalha mais lá**.
> 
> 📌 **Citações diretas:**  
> - **[Fonte 1: BBC Learning English - Grammar Course, Present Perfect Module]**  
> - **[Fonte 2: Cambridge English CEFR Companion Guide, Descritores B1]**

---

### ❓ Pergunta 2 (Nível Básico - A1/A2):
> *"Por que a palavra 'th' tem som diferente em 'think' e em 'this'? Como produzo esse som?"*

#### 🤖 Resposta do Gemini Notebook:
> 1. **/θ/ em "think" (Unvoiced):** Coloque a ponta da língua entre os dentes e expire o ar sem vibrar as cordas vocais.
> 2. **/ð/ em "this" (Voiced):** Posição idêntica da língua, mas com **vibração ativa das cordas vocais**.
> 
> 📌 **Citação direta:**  
> - **[Fonte 3: Rachel's English - Pronunciation & IPA, Aula: The Two TH Sounds]**

> 📌 *Confira o log completo com mais perguntas e a matriz de rastreabilidade em [`evidencias/prints_chat_citacoes.md`](evidencias/prints_chat_citacoes.md).*

---

## 🎨 Materiais de Estudo Gerados no Estúdio

A partir do conhecimento consolidado no notebook, foram gerados e exportados os seguintes materiais práticos:

1. 🗺️ **Mapa Mental da Jornada de Inglês (A1 a C2):**  
   - [`materiais/mapa_mental.md`](materiais/mapa_mental.md) (Diagrama Mermaid Interativo)  
   - [`materiais/mapa_mental.jpg`](materiais/mapa_mental.jpg) (Visual Infográfico Gerado)

2. 📊 **Slides de Apresentação:**  
   - [`materiais/slides_guia_estudos.md`](materiais/slides_guia_estudos.md) (Apresentação completa sobre técnicas de estudo e Tech English)

3. 📖 **Guia de Estudos com Quiz & Glossário Tech:**  
   - [`materiais/guia_estudos_quiz_glossario.md`](materiais/guia_estudos_quiz_glossario.md) (Testes práticos por nível com gabarito citado e 10+ termos de programação)

4. 🎙️ **Roteiro do Resumo em Áudio (Podcast):**  
   - [`materiais/roteiro_podcast_audio.md`](materiais/roteiro_podcast_audio.md) (Transcrição do áudio em estilo conversa de podcast para revisão)

---

## 🖼️ Visualização do Mapa Mental

![Mapa Mental da Jornada de Aprendizado](materiais/mapa_mental.jpg)

---

## ✅ Checklist de Submissão DIO

Antes de submeter o repositório na plataforma da DIO, verifiquei todos os itens de qualidade exigidos:

- [x] Cada resposta citada no README mostra de qual fonte veio.
- [x] O repositório está em uma conta pública no GitHub.
- [x] O nome do repositório está legível, em minúsculas e sem acento/caracteres especiais (`segundo-cerebro-ingles-gemini-notebook`).
- [x] Todos os arquivos citados no README existem no repositório e têm conteúdo real.
- [x] O link enviado é o do repositório no GitHub.
- [x] Nenhuma fonte possui dados pessoais sensíveis ou materiais protegidos indevidamente.

---

## 🚀 Como Executar ou Replicar este Projeto

1. Acesse o [Gemini Notebook (NotebookLM)](https://notebook.google.com/).
2. Crie um novo notebook chamado **"Segundo Cérebro - Inglês A1 a C2"**.
3. Importe os links dos vídeos da BBC/Rachel's English e os PDFs indicados em [`docs/fontes_curadas.md`](docs/fontes_curadas.md).
4. Insira a diretriz de comportamento presente em [`docs/diretriz_comportamento.md`](docs/diretriz_comportamento.md).
5. Interaja no chat para gerar quizzes, tirar dúvidas e criar materiais no Estúdio!

---

*Projeto desenvolvido para o Desafio de Código da Digital Innovation One (DIO).* 🚀
