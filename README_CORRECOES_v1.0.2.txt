CoreFit v1.0.2 - correções

- Remove modal interno de alarme no APK; o APK passa a depender apenas da notificação/despertador nativo do Android.
- Evita duplicidade entre notificação nativa e verificador interno.
- Adiciona aviso claro sobre atrasos de 5-15 min causados por economia de bateria/alarme exato do Android.
- Mantém verificador interno apenas para HTML/PWA, usando notificação do navegador ou toast, nunca modal.
- Cria acesso direto para a receita Creme diário whey + psyllium em Hoje e Comer.
- Adiciona modal específico com preparo, cuidados e botão para adicionar a receita.
- Reduz poluição visual na aba Comer: resumo compacto, lista curta por padrão e botão para mostrar tudo.
- Mantém modais de múltipla seleção abertos/atualizados ao alternar opções.
- Corrige lista de alimentos e protege allFoods contra itens inválidos.
- Versão atualizada para 1.0.2.

- Workflow usa versionCode com base 2000000 para permitir instalar por cima de builds antigas 1.0.48/1.0.0 sem erro de downgrade.
