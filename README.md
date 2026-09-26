# Engenharia de IA Aplicada — Pós-Graduação (UNIPDS)

Repositório de estudos, exercícios e projetos práticos da Pós-Graduação em **Engenharia de Software em IA Aplicada** pela UNIPDS.

## Sobre o curso

Formação prática voltada para desenvolvedores que querem aplicar Inteligência Artificial em produtos de software reais: LLMs, agentes autônomos, RAG, MCP, DevOps com IA, arquitetura de sistemas AI-first e um projeto integrador (Capstone) do zero à produção.

## Estrutura dos módulos

1. **Fundamentos de IA e LLMs para Programadores**
   História e evolução da IA, fundamentos de ML/DL/LLMs, transformers, embeddings, attention, Web Machine Learning, criação de uma rede neural do zero em JavaScript, prompt engineering, ferramentas de IA para devs (Cursor, Vibe Coding), MCPs, RAG e busca semântica, modelos open-source vs. proprietários (OpenRouter, Ollama) e introdução a agentes.

2. **APIs de IA Generativa e Prompt Engineering**
   Panorama do mercado de IA como serviço, principais provedores (OpenAI, Anthropic, Hugging Face, Gemini), prompt chaining e templates, redução de alucinações, custo-eficiência, RAG avançado (LangChain), integração de LLMs a back-ends existentes e modelos multimodais (texto, imagem, áudio, vídeo).

3. **MCP — Model Context Protocol**
   Visão geral e motivação do MCP, integração padronizada de LLMs com APIs/bancos/serviços, MCP vs. tools tradicionais, implementação em JavaScript/TypeScript, exposição de sistemas corporativos via MCP, segurança e governança (auth, rate limiting, WAF), e hands-on de criação de um MCP server em produção.

4. **Criação de Agentes Autônomos**
   Arquitetura de agents (planner, executor, memory, toolbox), padrões de raciocínio (ReAct, Plan-and-Execute, Reflection), function calling e tool use, memória e reflexão, gerenciamento de contexto, orquestração com LangGraph, observabilidade e limites de autonomia (guardrails, human-in-the-loop), projeto prático de agente autônomo e sistemas multiagente (Supervisor, Hierarchical, Group Chat, Delegation, Consensus).

5. **Ferramentas de IA para UX & UI**
   AI-driven UX/UI, geração de wireframes e UI a partir de linguagem natural (Text-to-UI), Firebase Studio (Figma → código), agentes de codificação e Gemini CLI, automação de testes E2E com MCP, e integração de lógica de IA no cliente/servidor com Firebase AI Logic.

6. **Ferramentas de IA para DevOps**
   IA generativa aplicada a infraestrutura: IaC Copilot (Terraform, Pulumi, Helm, Policy-as-Code), agentes para Kubernetes (deploy, autoscaling, GitOps), troubleshooting assistido (ReAct, RCA), AIOps e observabilidade (PromQL/LogQL, detecção de anomalias), ChatOps com aprovação humana, segurança e compliance (Snyk, Trivy, Checkov), CI/CD Copilot, FinOps, RAG de runbooks/post-mortem, auto-remediação com guardrails e projeto integrador.

7. **Ferramentas de IA para Gestão de Projetos**
   Requirements Copilot, priorização inteligente de backlog (RICE, WSJF, MoSCoW), cronogramas e capacidade assistidos por IA, estimativas e previsões (Monte Carlo), AIOps de projeto para riscos, reuniões turbinadas (transcrição/resumo), status reports automatizados, governança e compliance, automação em Jira/Asana/Trello/Notion/Slack, e portfólio/OKRs com IA.

8. **Arquitetura de Sistemas com IA**
   Fundamentos de arquitetura AI-first, arquiteturas single-agent e multi-agent, padrões de design AI-específicos (RAG avançado, roteamento inteligente, caching semântico, HITL), e arquitetura enterprise (API Gateway, orquestração, observabilidade, model tiering).

9. **Processamento de Dados e Fine-Tuning de Modelos**
   Decision framework para fine-tuning, preparação de datasets (JSONL), fine-tuning via API (OpenAI/Gemini), LoRA e PEFT, avaliação de modelos fine-tunados e projeto final com modelo customizado para domínio específico.

10. **Segurança e Governança em IA**
    Governança, interpretabilidade e explicabilidade, vieses e responsabilidade, gerenciamento de riscos (aspectos humanos/éticos, segurança/dados, legais/regulatórios) e custos financeiros em IA.

11. **Projeto Integrador — Capstone Project**
    Desenvolvimento de um Micro-SaaS completo: ideação e arquitetura, RAG e agentes, orquestração e back-end com MCP habilitado, front-end em Angular com CI/CD, e apresentação final com defesa técnica.

12. **Carreira e Entrevistas para Engenheiros de IA Aplicada**
    Otimização de LinkedIn, networking, marca pessoal, portfólio no GitHub, expectativas por nível, entrevistas de RH, negociação salarial, live coding, system design para sistemas de IA e diferenciação profissional.

## Organização do repositório

```
├── modulo-01-fundamentos-ia-llms/
├── .env
├── .gitignore
├── package.json
├── tsconfig.json
└── README.md
```

Cada pasta `modulo-XX-*` reúne anotações, exercícios e projetos práticos referentes ao módulo correspondente. Novas pastas serão adicionadas conforme o avanço no curso.

## Configuração

```bash
npm install
```

Preencha as variáveis de ambiente no arquivo `.env` (ignorado pelo Git) com suas chaves de API.
