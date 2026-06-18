# Oração Diária — PWA Católica Familiar

App para leituras católicas do dia + orações compartilhadas entre todos da família.

## Como publicar (2 minutos)

1. Acesse https://app.netlify.com/drop
2. Arraste a pasta `oracao-diaria` inteira
3. Pronto — você terá uma URL para compartilhar com a família

## Como instalar no celular como app

**Android (Chrome):** Menu (⋮) → "Adicionar à tela inicial"  
**iPhone (Safari):** Compartilhar (📤) → "Adicionar à Tela de Início"

## Configurar sincronização da família (5 min, gratuito)

1. Acesse https://console.firebase.google.com
2. Crie um projeto (qualquer nome, ex: "oracao-familia")
3. Vá em **Firestore Database → Criar banco de dados → Modo de teste**
4. Vá em **Configurações do projeto (⚙) → Seus apps → Web (</>)**
5. Registre o app e copie: apiKey, authDomain, projectId, appId
6. No app, abra a aba **⚙ Config** e cole os valores

Após configurar, todas as orações cadastradas aparecem para todos da família automaticamente.

## Leituras do dia

Usa a API https://liturgia.up.railway.app — em português brasileiro, com evangelho, primeira leitura e salmo. Se não houver conexão, exibe link para o Universalis.
