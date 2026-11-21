# StandBy Manaus (Android)

Protetor de tela inspirado no **StandBy do iPhone**, ativado automaticamente **somente ao carregar**, com suporte a **paisagem e retrato**, **6 paisagens estreladas embutidas** (troca suave a cada 3 minutos), **previsão de chuva constante de Manaus**, **controle de música prioritário**, **Bitcoin (BTC/BRL)**, **maiores altas e baixas da B3** e **notificações estilo iPhone**.

## Como gerar o arquivo `.apk`

### Opção 1 — Sem precisar instalar Android Studio (pelo GitHub grátis, direto do navegador/celular)
1. Crie uma conta gratuita no [GitHub](https://github.com) e crie um novo repositório (pode ser privado).
2. Envie todos os arquivos de dentro da pasta `StandByManaus` para o repositório (incluindo a pasta oculta `.github/workflows/build-apk.yml`).
3. Abra a aba **Actions** no repositório e aguarde ~3 minutos a compilação finalizar com o ícone verde.
4. Clique na execução concluída e baixe o arquivo **StandByManaus-APK** em **Artifacts** — dentro dele está o `app-debug.apk` pronto para instalar no Android.

### Opção 2 — Pelo Android Studio (no PC)
1. Extraia o arquivo `.zip`.
2. Abra o **Android Studio** -> **Open** -> selecione a pasta `StandByManaus`.
3. Aguarde o Gradle sincronizar as dependências.
4. No menu superior, clique em **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
5. Copie o arquivo gerado em `app/build/outputs/apk/debug/app-debug.apk` para o celular e instale.

## Como ativar no celular após instalar
1. Abra o app **StandBy Manaus**.
2. Toque em **1. Permitir acesso às notificações e música** e habilite o app.
3. Toque em **2. Ativar Protetor de Tela ao Carregar**, escolha **StandBy Estrelado** e selecione **Quando iniciar -> Ao carregar**.
4. Use o botão **Visualizar tela StandBy agora (Prévia)** para testar o visual imediatamente.
