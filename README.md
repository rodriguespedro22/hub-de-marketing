# Hub de Marketing

Plataforma web para o time de marketing de uma rede de varejo. Reúne em um só lugar a criação de peças gráficas, o guia das marcas, os arquivos de campanha e a ajuda para o dia a dia.

> **Estudo de caso.** O código é de uso interno de uma empresa e fica em um repositório privado. Aqui estão o problema, os módulos e as decisões técnicas. O projeto recebeu um destaque em inovação na empresa em julho de 2026.

## O problema

Peças, logotipos, arquivos de campanha e tutoriais ficavam espalhados em pastas e conversas. Cada pessoa montava as peças de um jeito, e achar o material certo dependia de perguntar para alguém.

## Módulos

| Módulo | O que faz |
| --- | --- |
| **Estúdio Criativo** | Editor visual de peças (cards, revistas, banners) no padrão da marca, com geração de layouts por IA |
| **Central das Marcas** | Guia de identidade visual: logotipos, cores, tipografia e tom de voz |
| **Central de Campanhas** | Repositório de arquivos de campanha e calendário mensal de eventos |
| **Central de Apoio** | Tutoriais, perguntas frequentes e contatos do time |
| **Administração** | Usuários, permissões, ofertas e repositórios de arquivos de cada central |

## Arquitetura e decisões

- **React + Vite** em uma aplicação de várias telas, com roteamento próprio e cabeçalho e menu compartilhados entre os módulos.
- **Tailwind CSS** para um visual consistente com a marca em todas as telas.
- **IA generativa (Gemini)** para sugerir layouts de peças dentro do editor.
- **Permissões por perfil.** A área administrativa controla quem vê e edita cada central.
- **Páginas de erro claras** (404 e 403) para o que não existe ou não é permitido.

## Minha parte

Construí o front-end completo: telas, editor de peças, integração com a IA, área administrativa e publicação.

## Tecnologias

React · Vite · Tailwind CSS · JavaScript · Gemini API · Vercel

## Contato

Pedro Rodrigues da Cunha · [LinkedIn](https://www.linkedin.com/in/pedrorodrigues2) · [GitHub](https://github.com/rodriguespedro22)
