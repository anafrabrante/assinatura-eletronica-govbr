**Definição do Escopo**

**Aplicação:** Portal de Assinatura Eletrônica gov.br (acessível via navegador Web, com uso auxiliar do aplicativo móvel gov.br para recebimento de código de autorização)

**Fluxo:** Upload do documento, posicionamento de assinatura, autorização digital, download e verificação de validade de documentos assinados. 

**Objetivo dos Testes:** Validar a funcionalidade, o tratamento de exceções e a conformidade do fluxo de assinatura eletrônica do portal gov.br, garantindo que usuários autenticados (contas nível Prata ou Ouro) consigam realizar o upload de arquivos permitidos, assinar digitalmente via código de autorização e confirmar a validade da assinatura gerada

**O que faz parte do escopo (Dentro do Escopo):**
- Submissão e Upload de Arquivo
- Validação da quantidade máxima de arquivos simultâneos (até 5 documentos)
- Seleção e envio de arquivos via botão "Escolher arquivo".
- Validação de formatos e extensões permitidas (.DOC, .DOCX, .ODT, .JPG, .PNG e .PDF).
- Validação da restrição de tamanho máximo do arquivo (mais de 10 MB).


**Posicionamento e Assinatura Digital:**
Clique e definição visual do local onde a assinatura será inserida no documento.
Acionamento do comando "Assinar digitalmente".
Recebimento e confirmação do código de autorização via notificação no aplicativo gov.br.
Exibição da mensagem de sucesso após a conclusão da assinatura.

**Download e Exportação:** Download do arquivo final contendo a assinatura digitalizada através do ícone de download.

**Consulta e Validação da Assinatura:**
Verificação das assinaturas presencialmente no portal pelo campo "Assinado digitalmente por".
Validação da autenticidade e integridade do documento assinado no serviço de validação externa (https://validar.iti.gov.br ou app VALIDAR).

**O que NÃO faz parte do escopo (Fora do Escopo):**
**Gestão de Identidade e Cadastros:** 
Fluxo de criação/cadastro inicial de novas contas no portal gov.br.
Processo de alteração de nível de confiabilidade da conta (migração de nível Bronze para Prata ou Ouro).
Recuperação de senha ou alteração de dados cadastrais do cidadão.
**Edição e Alteração de Documentos:**
Modificação do conteúdo textual ou visual do arquivo dentro da plataforma.
Impressão Física: testes de impressão em papel (já que o documento impresso perde a validade legal da assinatura digital).

