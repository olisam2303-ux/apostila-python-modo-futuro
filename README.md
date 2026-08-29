# Formação Python — MODO FUTURO

Apostila interativa da **MODO FUTURO — Escola Técnica Online** para o curso
_Formação Python — Do Zero aos Projetos_.

> Ative seu talento. Construa sua profissão.

## O que é

Página única (`index.html`, sem dependências de build) com:

- **58 capítulos guiados**, **8 revisões** e **7 projetos completos**;
- **Python de verdade no navegador** (Pyodide) — o aluno executa o código sem instalar nada;
- **tela inicial / painel** com proposta de valor, números do curso e retomada de onde parou;
- **onboarding** que registra o nome do aluno (só no navegador) para personalizar a apostila;
- **certificado de conclusão** liberado ao terminar os 73 módulos, com código de verificação e opção de imprimir em PDF;
- **narrador em voz alta** (Web Speech API) que lê o conteúdo da tela atual;
- **tema claro/escuro** e progresso persistente.

## Como publicar

O site é servido pelo **GitHub Pages** a partir da branch `main` (raiz).
Qualquer `git push` para `main` atualiza a apostila em poucos minutos.

## Personalização

As informações da marca ficam no objeto `BRAND`, no topo do `<script>` em
`index.html` (nome da escola, lema, nome do curso, carga horária, canal de
suporte e o emissor do certificado).

## Versão presencial

A versão usada pelos alunos do curso técnico presencial fica em outro
repositório: `apostila-python-interativa` (sem o painel comercial e sem
certificado; com aviso de conclusão por WhatsApp para o professor).
