**Casos de Teste**

Os casos de teste foram realizados com o objetivo de verificar o funcionamento da assinatura eletrônica do gov.br, avaliando o fluxo normal, as entradas inválidas, limites da plataforma e situações alternativas.

| ID | Funcionalidade | Entrada / Passos | Resultado esperado | Resultado obtido | Status |
|---|---|---|---|---|---|
| CT01 | Seleção de documento | Selecionar um documento válido para assinatura | O sistema deve aceitar o arquivo e permitir continuar o processo | O documento foi selecionado normalmente | PASS |
| CT02 | Assinatura individual | Enviar um documento válido, posicionar a assinatura e autorizar a operação | O sistema deve concluir a assinatura e disponibilizar o documento | A assinatura foi realizada com sucesso | PASS |
| CT03 | Envio de vários documentos | Selecionar cinco documentos válidos simultaneamente | O sistema deve permitir o envio de até cinco documentos | Os cinco documentos foram enviados normalmente | PASS |
| CT04 | Limite de documentos | Tentar selecionar mais de cinco documentos | O sistema deve impedir o envio de quantidade superior ao limite permitido | O sistema impediu o envio de mais de cinco documentos | PASS |
| CT05 | Arquivo corrompido | Tentar enviar um arquivo corrompido | O sistema deve identificar o arquivo inválido e impedir sua utilização | O arquivo foi identificado como inválido | PASS |
| CT06 | Arquivo vazio | Tentar enviar um arquivo sem conteúdo | O sistema deve rejeitar o arquivo vazio | O arquivo foi rejeitado pelo sistema | PASS |
| CT07 | Formato inválido | Tentar enviar um arquivo com formato não permitido | O sistema deve rejeitar o arquivo e informar que o formato não é aceito | O arquivo foi rejeitado | PASS |
| CT08 | Limite de tamanho | Tentar enviar um arquivo acima do limite permitido pela plataforma | O sistema deve impedir o envio do arquivo e apresentar uma mensagem informativa | O arquivo acima do limite testado foi rejeitado | PASS |
| CT09 | Download do documento | Concluir uma assinatura e realizar o download do documento | O sistema deve disponibilizar o documento assinado para download | O documento foi baixado normalmente | PASS |
| CT10 | Verificação da assinatura | Abrir o documento baixado e verificar sua autenticidade pelo serviço VALIDAR | O serviço deve reconhecer a assinatura e apresentar as informações correspondentes | A assinatura foi reconhecida pelo serviço de validação | PASS |
| CT11 | Posicionamento da assinatura | Tentar posicionar a assinatura fora dos limites do documento | O sistema deve impedir o posicionamento fora da área permitida | O sistema impediu o posicionamento fora dos limites do documento | PASS |
| CT12 | Assinatura sem representação visual | Utilizar a opção de não exibir a representação visual da assinatura no documento | O sistema deve permitir concluir a assinatura sem exibir a representação visual, conforme a opção selecionada | A assinatura foi realizada sem a representação visual | PASS |
| CT13 | Código de autorização inválido | Informar um código de autorização incorreto durante o processo de assinatura | O sistema deve rejeitar o código e impedir a conclusão da assinatura | O sistema rejeitou o código incorreto e impediu a assinatura | PASS |
