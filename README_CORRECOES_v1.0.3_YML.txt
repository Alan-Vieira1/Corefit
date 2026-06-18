CoreFit v1.0.3 - correção do workflow GitHub Actions

Correção principal:
- Corrigido erro de sintaxe YAML na linha 154 do build-apk.yml.
- O erro vinha de um bloco multiline do Python dentro do YAML com indentação incompatível.
- O workflow foi reescrito separando as etapas e usando blocos seguros.
- Removido extracted.js do pacote, que era apenas arquivo temporário de auditoria.

Mantido:
- app v1.0.3
- package.json v1.0.3
- www/index.html v1.0.3
- versionCode alto calculado automaticamente
- assinatura fixa via keystores/corefit-debug.keystore
