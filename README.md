# ScanFlow Conferente — Releases

Repositório público de distribuição do aplicativo **ScanFlow Conferente** (Android), usado na
conferência de embarques e na liberação para faturamento.

Aqui ficam apenas os **APKs publicados**. Não há código-fonte neste repositório.

## Baixar a versão mais recente

Acesse a página de [Releases](../../releases/latest) e baixe o arquivo
`scanflow-conferente-<versão>.apk`.

## Instalação

1. Baixe o APK no aparelho (ou copie para ele).
2. Se o Android pedir, permita a instalação de apps de fontes desconhecidas para o navegador ou gerenciador de arquivos usado.
3. Abra o APK e conclua a instalação.
4. Acesse com um usuário de perfil **Conferente**.

Atualizações seguintes são oferecidas pelo próprio app, que consulta a última release deste repositório.

## Como as releases são geradas

As releases são criadas automaticamente por uma esteira (GitHub Actions) no repositório de código,
sempre que uma tag de versão `vX.Y` ou `vX.Y.Z` é criada. Não crie releases nem tags manualmente aqui,
para não conflitar com o processo automático.

| Item | Valor |
|---|---|
| Aplicativo | ScanFlow Conferente |
| Pacote | `com.rfonte.conferente` |
| Arquivo | `scanflow-conferente-<versão>.apk` |
| Plataforma | Android 5.1 (API 22) ou superior |

> Este repositório precisa permanecer **público**: o aplicativo consulta a API de releases sem autenticação para verificar atualizações.
