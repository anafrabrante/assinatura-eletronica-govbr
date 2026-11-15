**Critérios de aceitação**


**RF01 — Upload e Validação de Documentos**

CA01.1 - Caminho Feliz: Arquivos nos formatos permitidos (.PDF, .DOC, .DOCX, .ODT, .JPG e .PNG), respeitando o limite máximo de tamanho, devem ser aceitos pelo sistema.

CA01.2 - Entrada Inválida: Arquivos com extensões não suportadas devem ser rejeitados pelo sistema.

CA01.3 - Limite de Tamanho: Arquivos acima do limite máximo permitido pela plataforma devem ser rejeitados.

CA01.4 - Arquivo Corrompido: Arquivos corrompidos devem ser identificados e impedidos de prosseguir no processo de assinatura.

CA01.5 - Arquivo Vazio: Arquivos sem conteúdo devem ser rejeitados.

CA01.6 - Limite de Quantidade: O sistema deve permitir o envio de até cinco documentos simultaneamente e impedir o envio de uma quantidade superior.

**RF02 - Posicionamento da Assinatura**

CA02.1 - Caminho Feliz: Ao selecionar uma página do documento, o sistema deve permitir posicionar a representação visual da assinatura no local escolhido.

CA02.2 - Fluxo Alternativo: O usuário deve conseguir reposicionar a representação visual da assinatura antes de confirmar a operação.

CA02.3 - Campo Obrigatório: O sistema deve solicitar o posicionamento da assinatura antes de permitir a continuidade do processo, quando essa etapa for obrigatória.

CA02.4 - Limite de Posicionamento: O sistema deve impedir que a representação visual da assinatura seja posicionada fora dos limites do documento.

CA02.5 - Opção Alternativa: O sistema deve permitir concluir a assinatura sem exibir sua representação visual, quando essa opção for selecionada.

**RF03 - Autorização da Assinatura**

CA03.1 - Caminho Feliz: Ao informar um código de autorização válido, o sistema deve permitir a conclusão da assinatura.

CA03.2 - Entrada Inválida: Ao informar um código incorreto ou expirado, o sistema deve impedir a conclusão da assinatura e apresentar uma mensagem de erro.

**RF04 - Disponibilização e Download**

CA04.1 - Caminho Feliz: Após a conclusão da assinatura, o sistema deve apresentar uma mensagem de sucesso e disponibilizar o download do documento.

CA04.2 - Integridade do Arquivo: O documento baixado deve preservar o conteúdo original e as informações da assinatura eletrônica realizada.

**RF05 - Verificação de Autenticidade e Integridade**

CA05.1 - Validação com Sucesso: Ao enviar o documento assinado ao serviço VALIDAR, o sistema deve reconhecer a assinatura e apresentar as informações correspondentes.

CA05.2 - Detecção de Alterações: Caso o documento seja modificado após a assinatura, o serviço de validação deve identificar alterações que comprometam a integridade do documento.







