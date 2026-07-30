---
name: documentacao-projeto-frontend
description: "Documenta projetos front-end estaticos em pt-BR com foco em inventario de arquivos, infograficos, arquitetura, stack e informacoes de negocio. Use para atualizar README tecnico de landing pages e sites institucionais."
argument-hint: "Projeto/alvo e foco da documentacao (ex.: arquitetura, infografico, SEO, inventario)."
user-invocable: true
---

# Documentacao de Projeto Front-end

## Quando usar

- Atualizar README de landing page ou site institucional.
- Produzir documentacao em portugues do Brasil.
- Mapear arquitetura e componentes de front-end.
- Criar infografico textual e diagramas Mermaid.
- Registrar informacoes de negocio presentes na interface.

## Resultado esperado

Ao final, o README deve conter:

1. Visao geral do projeto e objetivo de produto.
2. Infografico com indicadores e fluxos.
3. Arquitetura front-end (camadas + diagrama).
4. Inventario completo de arquivos relevantes.
5. Descricao das secoes/componentes da UI.
6. Stack e dependencias externas.
7. Forma de execucao local.
8. Dados de negocio e canais de contato.
9. Sugestoes de evolucao tecnica.

## Procedimento

1. Levantar contexto tecnico

- Ler `index.html`, CSS principal e README atual.
- Listar todos os arquivos do repositorio.
- Ler arquivos auxiliares (manifesto, pacotes visuais, readmes internos).

2. Validar coerencia do estado atual

- Corrigir inconsistencias documentais (ex.: README diz CSS inline, mas existe arquivo CSS).
- Confirmar versoes de framework e bibliotecas usadas.

3. Estruturar o infografico

- Montar tabela de indicadores do projeto.
- Criar pelo menos um diagrama Mermaid de jornada do usuario.
- Criar pelo menos um diagrama Mermaid de arquitetura.

4. Descrever arquitetura e front-end

- Explicar camadas: HTML, CSS, JS/integracoes.
- Listar secoes principais e principais componentes de interface.
- Documentar variaveis de design system (cores, tipografia, estilo).

5. Fechar inventario e operacao

- Incluir arvore de pastas atualizada.
- Documentar execucao local e dependencias.
- Registrar dados de negocio presentes na UI.

6. Revisar qualidade antes de concluir

- Texto em pt-BR consistente.
- Sem referencias a arquivos inexistentes.
- Sem lacunas entre codigo e documentacao.
- README com leitura escaneavel (titulos, listas e tabelas).

## Decisoes e ramificacoes

- Se o projeto tiver build tool (Vite, Webpack, etc.): incluir secao de scripts de build e deploy.
- Se o projeto for 100% estatico: priorizar simplicidade operacional e hospedagem estatica.
- Se houver varios arquivos CSS/JS: separar documentacao por responsabilidade de arquivo.
- Se nao houver dados de negocio explicitos: registrar o que nao foi encontrado e recomendar padrao de cadastro.

## Criterios de conclusao

- README atualizado e tecnicamente fiel ao codigo.
- Infografico presente com indicadores e fluxos.
- Arquitetura descrita com diagrama.
- Inventario de arquivos completo.
- Linguagem final em portugues do Brasil.
