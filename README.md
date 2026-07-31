# N8N — automações e agentes de IA

Coleção de **79 workflows para n8n** voltados a inteligência artificial,
atendimento, conteúdo, produtividade, análise de dados e integrações. Cada
arquivo JSON pode ser importado no n8n e adaptado às credenciais e regras do
seu ambiente.

## Visão geral

| Item | Quantidade |
| --- | ---: |
| Workflows | 79 |
| Workflows com JSON validado | 77 |
| Nós n8n catalogados | 1.334 |
| Tamanho aproximado da coleção | 1,4 MB |

Entre os exemplos disponíveis estão:

- agentes com OpenAI, Gemini, DeepSeek e Perplexity;
- chatbots para WhatsApp, Telegram, Discord e Instagram;
- fluxos RAG com Supabase, Qdrant, PostgreSQL, SQLite e Google Drive;
- automações de e-mail, reuniões, recrutamento e atendimento;
- geração, classificação, tradução e resumo de conteúdo;
- integrações com Google Sheets, Notion, WordPress, Airtable e outras APIs;
- processamento de PDFs, imagens, áudio, vídeo e páginas web.

## Como usar

1. Escolha um dos arquivos `.json` deste repositório.
2. No n8n, abra o menu de workflows e selecione **Import from File**.
3. Importe o arquivo e revise os nós, parâmetros e notas do fluxo.
4. Crie ou selecione as credenciais exigidas por cada integração.
5. Substitua IDs, URLs, destinatários e demais valores de demonstração.
6. Execute o workflow manualmente e valide o resultado antes de ativá-lo.

> [!IMPORTANT]
> Importe primeiro em um ambiente de teste. Versões diferentes do n8n ou de
> community nodes podem exigir ajustes nos parâmetros dos nós.

## Credenciais e segurança

Os exports podem manter nomes e identificadores de referências a credenciais,
webhooks e recursos externos, mas não devem conter os segredos armazenados pelo
n8n. Mesmo assim, revise cada arquivo antes de importar ou publicar.

- Nunca versione arquivos `.env`, bancos locais do n8n, tokens ou chaves de API.
- Troque URLs de webhook e identificadores usados apenas como exemplo.
- Confirme permissões mínimas nas contas conectadas.
- Revise nós de código e requisições HTTP antes da primeira execução.
- Mantenha o workflow inativo até concluir os testes.

## Estado da validação

Uma leitura automatizada confirmou **77 arquivos JSON válidos**. Os dois
exports abaixo contêm conteúdo adicional após o primeiro objeto JSON e precisam
ser revisados antes da importação:

- `AI Agent to chat with Airtable and analyze data.json`
- `Perplexity Research to HTML_ AI-Powered Content Creation.json`

Essa validação verifica apenas a sintaxe do JSON. Ela não garante que
credenciais, community nodes, APIs externas ou versões específicas do n8n
estejam disponíveis.

## Contribuindo

Ao adicionar ou atualizar um workflow:

1. remova dados pessoais, segredos e identificadores desnecessários;
2. use um nome de arquivo que descreva claramente o caso de uso;
3. mantenha notas explicativas dentro do próprio workflow;
4. valide o JSON antes de criar o commit;
5. informe dependências ou configurações especiais na descrição da mudança.

## Aviso

Os workflows são exemplos e podem depender de serviços pagos ou de terceiros.
Revise custos, limites de uso, termos de serviço, privacidade e requisitos de
segurança antes de utilizá-los em produção.

## Autor

Mantido por [George Telles](https://github.com/GeorgeTelles).

## Licença

Este repositório ainda não possui uma licença definida. Entre em contato com o
autor antes de redistribuir ou reutilizar o conteúdo fora dos termos permitidos
pelos serviços e templates de origem.
