CoreFit v1.0.3

Correções principais:
- Conflito de pacote: workflow agora força versionCode alto e injeta assinatura fixa no Gradle.
- Importante: se o app instalado foi assinado com outra chave, o Android exige desinstalar uma vez. Exporte backup antes.
- Alarmes: remove repetição diária antiga, cancela pendentes antigos e agenda apenas avisos futuros por 2 dias.
- O verificador interno de alarmes não roda no APK, evitando notificação/modal ao abrir app.
- Versão do app e backup atualizados para v1.0.3.
