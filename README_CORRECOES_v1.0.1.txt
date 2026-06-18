CoreFit v1.0.1 corrigido

Arquivos principais:
- www/index.html corrigido
- package.json em 1.0.1
- .github/workflows/build-apk.yml com versionCode acima das builds antigas

Correções aplicadas:
1. Removida vírgula dupla no array FOODS antes do alimento f80.
2. allFoods() agora ignora itens inválidos e evita quebra de Hoje/Comer.
3. STORE novo: corefit_v1_0_0_state.
4. OLD_STORES mantém corefit_v1_0_48_state e corefit_v1_0_32_state para migração.
5. APP_VERSION e package.json alinhados em 1.0.1.
6. UPDATE_REPO ajustado para Alan-Vieira1/Corefit.
7. Workflow usa offset no versionCode para permitir instalar por cima de builds antigas 1.0.48.

Para usar:
Copie o conteúdo deste pacote para a raiz do repositório e faça git add ., commit e push.
