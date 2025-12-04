# AI Security Audit Dashboard

![Status](https://img.shields.io/badge/Status-Audited-success)
![Security](https://img.shields.io/badge/Security-Robust-brightgreen)
![Tech](https://img.shields.io/badge/Stack-React_Zero_Build-blue)

Dashboard interativo desenvolvido para documentar e visualizar auditorias de segurança em Modelos de Linguagem (LLMs). Este relatório foca na resiliência técnica contra ataques de Prompt Injection, Engenharia Social e Alucinação de Integridade.

## Acesso Online (Live Demo)

Para visualizar o relatório diretamente no navegador, acesse o link abaixo:

> [**Clique aqui para acessar o Dashboard de Auditoria**](https://SEU-USUARIO.github.io/NOME-DO-REPO)

---

## Sobre o Projeto

Este projeto demonstra a validação de segurança de um sistema de IA aplicado ao contexto administrativo (Prefeitura Municipal de SP). O objetivo foi submeter o modelo a uma bateria de testes de penetração ("Red Teaming") para garantir a priorização de dados oficiais e a manutenção da integridade contra comandos maliciosos externos.

A interface foi construída para ser portátil e independente (arquitetura *single-file*), rodando inteiramente no navegador (*client-side*) para facilitar a distribuição do relatório de auditoria entre stakeholders.

## Funcionalidades do Relatório

* **Visualização de Matriz de Risco:** Exibição consolidada dos status de aprovação/reprovação dos testes.
* **Logs de Evidência:** Detalhamento técnico dos vetores de ataque utilizados e a resposta do modelo.
* **Framework LEVA:** Implementação visual da metodologia de Limitar, Especificar, Verificar e Acompanhar.
* **Exportação:** Layout otimizado para impressão nativa e geração de PDF.

## Tecnologias Utilizadas

O projeto utiliza uma arquitetura **Zero-Build** para máxima portabilidade:

* **React 18:** Via CDN (UMD).
* **Tailwind CSS:** Via CDN.
* **Babel Standalone:** Compilação em tempo de execução.
* **SVG Icons:** Vetores inline.

---

*Desenvolvido como parte de uma auditoria de conformidade para sistemas de IA Generativa.*
