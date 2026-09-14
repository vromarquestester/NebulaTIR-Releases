# NebulaTIR — downloads

Vitrine pública do **NebulaTIR**, a interface interna para as execuções do TIR
(testes automatizados do Protheus). Ele é um braço do Gerenciador de Ambientes
e roda na mesma pasta dele.

Aqui só ficam os pacotes prontos para baixar. O código-fonte é privado.

## Baixar

O `.zip` de cada versão está em **[Releases](../../releases)**, na seção
*Assets*. Extraia o `NebulaTIR.exe` na pasta do Gerenciador de Ambientes —
ele pede elevação, necessária para subir instâncias do AppServer.

Só a versão mais recente fica anexada. Versões antigas continuam listadas, com
as notas do que mudou, mas sem o arquivo.

## Atualização

O programa se atualiza sozinho: verifica se há versão nova, baixa em segundo
plano e troca o executável na abertura seguinte. Ele também confere as outras
ferramentas da mesma pasta (o Gerenciador de Ambientes) e deixa a atualização
delas pronta.

Não é preciso voltar aqui a cada versão — este download é só o primeiro.

No botão **Atualização** dá para verificar na hora, desligar a atualização
automática ou voltar à versão anterior.

## `latest.json`

O arquivo na raiz deste repositório é o manifesto que o programa instalado
consulta: versão publicada, link do pacote, `sha256` e o que mudou. Ele é
gravado pela automação de release — não edite à mão.
