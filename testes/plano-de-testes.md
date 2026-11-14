**Plano de Testes**

1. Objetivo dos testes
Verificar o funcionamento da funcionalidade de assinatura eletrônico do gov.br, avaliando se a plataforma apresenta os resultados esperados durante o envio, posicionamento, autorização, download e validação dos documentos assinados. Também serão avaliados arquivos inválidos e o cumprimento das restrições estabelecidas
pela plataforma

2. Funcionalidades que serão testadas
- Upload de documentos de diversos formatos aceitos para assinatura na plataforma
- Assinatura de um ou vários documentos simultaneamente
- Validação da quantidade máxima de documentos
- Validação do tamanho dos arquivos
- Identificação de arquivos corrompidos ou vazios
- Posicionamento visual da assinatura
- Autorização da assinatura pelo aplicativo gov.br
- Download do documento assinado
- Verificação da autenticidade e integridade do documento

3. Funcionalidades que não serão testadas
- Criação/cadastro de contas gov.br
- Recuperação de senhas
- Alteração de dados cadastrais
- Alteração do nível de confiabilidade da conta
- Testes de invasão e vulnerabilidades
- Avaliação de outros serviços disponibilizados no gov.br

4. Ambiente utilizado
- Aplicação: Portal de Assinatura Eletrônica gov.br
- Acesso: Navegador web
- Navegador: Google Chrome
- Sistema Operacional: Windows 11
- Aplicativo auxiliar: aplicativo do gov.br para autorização de assinatura
- Serviço de validação: VALIDAR (https://validar.iti.gov.br)

5. Tipos de testes realizados
- Testes funcionais: verificar se as funcionalidades apresentam resultados esperados
- Testes de validação: verificar se arquivos inválidos são identificados e rejeitados
- Testes de limite: verificar as restrições de quantidade e tamanho dos documentos
- Testes de fluxo normal: verificar a realização de uma assinatura utilizando documentos válidos
- Testes de fluxo alternativo: verificar o comportamento da plataforma diante de situações diferentes do fluxo

6. Critérios de conclusão
- Os testes serão considerados concluídos quando todos os casos planejados forem executados e os resultados forem registrados
- Cada caso de teste receberá uma classificação:
Pass: quando o comportamento observado corresponder ao resultado esperado
Fail: quando o comportamento observado for diferente do resultado esperado
- As capturas de tela serão utilizadas como evidências dos testes realizados
- Problemas temporários de disponibilidade do servidor serão registrados separadamente, para não serem confundidos com defeitos da funcionalidade analisada
  
