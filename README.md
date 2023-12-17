# Resumo da Ata do Grupo QuarenteNA

Este é um projeto que utiliza o Google Apps Script para automatizar a geração de resumos a partir de uma planilha do Google Sheets e enviar esses resumos via Telegram e WhatsApp.

## Como Funciona

O script lê os dados da planilha 'Form Responses 1' no Google Sheets e gera um resumo com informações relevantes. Em seguida, envia esse resumo para um grupo no Telegram e também para um número ou grupo no WhatsApp usando a EvolutionAPI.

## Pré-requisitos

Antes de executar este projeto, você precisará:

- Ter uma conta no Google.
- Ter acesso a uma planilha do Google Sheets.
- Criar um bot no Telegram e obter um token de acesso.
- Obter um token de acesso da EvolutionAPI.

## Vídeos Instrutivos

[![Como instalar a EvolutionAPI](https://img.youtube.com/vi/ZLBwNiDtfwU/0.jpg)](https://youtu.be/ZLBwNiDtfwU)

[![Como utilizar a EvolutionAPI](https://img.youtube.com/vi/jv-5N0mPRro/0.jpg)](https://youtu.be/jv-5N0mPRro)

## Configuração

1. Faça uma cópia da planilha de exemplo fornecida ou crie sua própria planilha com os dados relevantes.

2. No script `resumoDaAta.gs`, substitua o token de acesso do bot do Telegram, o chat ID e o token da EvolutionAPI pelos seus próprios.

3. Configure um gatilho de execução para que a função `resumoDaAta` seja acionada automaticamente ao enviar o formulário.

## Execução

Após configurar tudo corretamente, o script será executado automaticamente conforme configurado no gatilho. Ele lerá os dados da planilha, gerará o resumo e o enviará para o grupo no Telegram e o número ou grupo no WhatsApp.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas, propor melhorias ou enviar solicitações de pull.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).

---

**Nota:** Este é um projeto de exemplo e pode precisar de personalizações adicionais para atender às suas necessidades específicas.
