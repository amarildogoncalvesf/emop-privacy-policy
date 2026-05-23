# Política de Privacidade — EMOP Planos de Estudo: ENEM e Médio

**Última atualização:** 23 de maio de 2026
**App:** EMOP Planos de Estudos
**Identificador:** com.emop.planner
**Plataformas:** iOS e Android

---

## 1. Resumo

O EMOP é um aplicativo de planejamento de estudos voltado para estudantes do Ensino Médio brasileiro. **Praticamente todos os dados que você insere ficam armazenados apenas no seu próprio dispositivo.** Não temos servidores que armazenam suas informações de estudo, não enviamos seu cronograma para nenhum lugar e não usamos ferramentas de análise de comportamento, rastreamento ou publicidade.

A única exceção é o envio automático de **relatórios de erros e travamentos** (descritos na seção 8), usados exclusivamente para descobrir e corrigir bugs que afetem você.

Em uma frase: o que você digita no app fica no seu celular; se o app travar, recebemos um relatório técnico anônimo para consertar.

## 2. Quais dados o app armazena (localmente, no seu aparelho)

O EMOP guarda no armazenamento local do seu dispositivo (`AsyncStorage` no Android / iOS) as seguintes informações que você fornece voluntariamente durante o uso:

- Suas configurações de estudo (objetivo, dias disponíveis, horário de aulas, atividades fixas, dias livres, horário de dormir, deslocamento, refeições);
- A lista de matérias e conteúdos que você escolhe estudar, com suas preferências de tópicos;
- Seu cronograma semanal gerado pelo app, incluindo cronogramas multi-semana para prova escolar com data;
- Seu progresso (blocos de estudo concluídos, sequência de dias consistentes, congelamentos de sequência usados);
- Configurações de simulado (frequência, áreas, dias preferidos) e resultados de simulados que você optar por registrar;
- Notas do ENEM ou de vestibulares, e dados de provas escolares (matérias, data, dificuldade), se aplicáveis ao seu objetivo;
- Rascunho do onboarding em andamento, para retomar caso você feche o app no meio;
- Marcação interna de uma pergunta única sobre permissão de notificação e de quando o sistema operacional já solicitou avaliação do app.

**O EMOP não coleta:** seu nome, e-mail, número de telefone, foto, contatos, localização, dados de contas em outros serviços, identificadores publicitários ou qualquer outro dado pessoal sensível.

## 3. Como esses dados são usados

Os dados ficam no seu aparelho exclusivamente para o app funcionar — montar seu cronograma, mostrar seu progresso, lembrar suas configurações entre sessões. Eles não são lidos, transmitidos ou processados por nós em nenhum momento.

## 4. Compartilhamento com terceiros

O EMOP **não compartilha dados pessoais com terceiros para fins comerciais.**

Há dois pontos em que o app interage com serviços externos, sempre por iniciativa sua:

- **Compartilhar semana no Instagram:** ao tocar em "Compartilhar semana", o EMOP gera uma imagem do seu progresso e a entrega ao app do Instagram para ser publicada como Story. Essa imagem é entregue diretamente ao Instagram via mecanismo nativo do sistema operacional; o EMOP não envia nada por internet. A partir do momento em que a imagem entra no Instagram, ela passa a ser tratada pela política de privacidade do Instagram (Meta Platforms, Inc.).
- **Exportar meus dados (Configurações → Dados e privacidade):** ao tocar nesse botão, o EMOP gera um arquivo JSON com a cópia dos seus dados locais e abre o menu nativo de compartilhamento do sistema operacional. Você escolhe para onde enviar (e-mail, Google Drive, iCloud, etc.). O EMOP não envia esse arquivo para lugar algum por conta própria.

## 5. Permissões solicitadas pelo app

O EMOP **não pede permissões sensíveis** (câmera, microfone, localização, contatos, fotos, calendário).

O app solicita **apenas uma permissão opcional**:

- **Notificações:** após você terminar o onboarding, o app pergunta se pode enviar lembretes de estudo (1 por dia, 30 minutos antes do seu primeiro bloco) e avisos quando sua sequência estiver em risco. Você pode recusar e usar o app normalmente, ou desativar a qualquer momento em Configurações → Lembretes ou nas configurações do próprio sistema.

## 6. Crianças e adolescentes

O EMOP é destinado principalmente a estudantes de Ensino Médio (geralmente 14–18 anos). Como o app não coleta nem transmite dados pessoais identificáveis, não há informações sobre menores sendo enviadas a terceiros. Recomendamos, ainda assim, que pais ou responsáveis acompanhem o uso do aplicativo por menores de idade.

Em conformidade com a LGPD (Lei nº 13.709/2018, art. 14), o tratamento de dados de crianças e adolescentes pelo EMOP se limita ao armazenamento local de informações fornecidas voluntariamente pelo próprio usuário, sem qualquer transferência a terceiros com finalidade comercial ou publicitária.

## 7. Seus direitos (LGPD)

Como praticamente todos os dados ficam no seu dispositivo, você tem controle total sobre eles:

- **Acesso:** todos os dados armazenados são visíveis dentro do próprio app, nas abas Cronograma, Conteúdos, Progresso e em Configurações.
- **Correção:** você pode editar suas informações a qualquer momento dentro do app.
- **Portabilidade:** você pode exportar uma cópia completa dos seus dados em formato JSON em **Configurações → Dados e privacidade → Exportar meus dados**.
- **Exclusão:** você pode apagar permanentemente todos os seus dados em **Configurações → Dados e privacidade → Apagar todos os dados**, ou simplesmente desinstalando o aplicativo.

Em relação aos relatórios de erro enviados ao Sentry (seção 8), você pode solicitar a exclusão entrando em contato pelo e-mail abaixo.

## 8. Análise, anúncios e relatórios de erro

O EMOP **não usa**:

- Google Analytics, Firebase Analytics ou qualquer outra ferramenta de análise de comportamento ou métricas de uso;
- Nenhuma rede de anúncios;
- Nenhum SDK de rastreamento publicitário (não há *App Tracking Transparency* ativado porque não há rastreamento);
- Nenhum cookie, nenhum identificador persistente para fins comerciais.

O EMOP **usa, apenas em compilações de produção**:

- **Sentry** (sentry.io, operado por Functional Software, Inc., EUA) para receber relatórios automáticos quando o app trava ou encontra um erro. Esses relatórios contêm: tipo e modelo do aparelho, versão do sistema operacional, versão do app, rastreamento técnico (stack trace) do erro, endereço IP aproximado da requisição e, em caso de corrupção de dados locais, uma pequena amostra (até 200 caracteres) do trecho corrompido para diagnóstico. Os relatórios **não contêm** o conteúdo do seu cronograma, suas notas, seus tópicos de estudo, seu progresso ou qualquer informação pessoal identificável fornecida por você. O propósito exclusivo é descobrir e corrigir bugs.

Em compilações de desenvolvimento e na versão web, nenhum relatório é enviado.

## 9. Segurança

Os dados que ficam no seu aparelho estão armazenados no sistema de armazenamento padrão do dispositivo, protegido pelo próprio sistema operacional (sandbox de aplicativos do iOS e do Android). Não há transmissão pela internet do seu conteúdo de estudo.

Os relatórios de erro enviados ao Sentry trafegam por conexão criptografada (HTTPS/TLS) e ficam sujeitos à política de segurança e retenção do próprio Sentry.

## 10. Alterações nesta política

Caso esta política precise ser atualizada (por exemplo, se uma futura versão do app passar a usar um servidor de contas, sincronização entre dispositivos ou um novo recurso), avisaremos no próprio app e atualizaremos a data no topo deste documento. O uso continuado do EMOP após a atualização significa concordância com a nova política.

## 11. Contato

Se você tiver dúvidas sobre esta Política de Privacidade ou sobre como seus dados são tratados pelo EMOP, entre em contato:

**E-mail:** apgfdinho@gmail.com

---
---

# Privacy Policy — EMOP Study Planner (English)

**Last updated:** May 23, 2026
**App:** EMOP Study Planner
**Identifier:** com.emop.planner
**Platforms:** iOS and Android

---

## 1. Summary

EMOP is a study-planning app for Brazilian high-school students. **Almost all data you enter stays on your own device.** We do not have servers that store your study information, we do not send your schedule anywhere, and we do not use behavior analytics, tracking, or advertising services.

The only exception is the automatic sending of **crash and error reports** (described in section 8), used exclusively to find and fix bugs that affect you.

In one sentence: what you type into the app stays on your phone; if the app crashes, we receive an anonymous technical report so we can fix it.

## 2. What data the app stores (locally, on your device)

EMOP stores the following information you voluntarily provide while using the app, in your device's local storage (`AsyncStorage` on Android / iOS):

- Your study settings (goal, available days, class schedule, fixed activities, free days, bedtime, commute, meals);
- The list of subjects and topics you choose to study, with your topic preferences;
- The weekly schedule generated by the app, including multi-week schedules for school exams with a fixed date;
- Your progress (completed study blocks, streak of consistent days, used streak freezes);
- Mock exam configuration (frequency, areas, preferred days) and mock exam results you choose to record;
- ENEM or college entrance exam scores, and school exam data (subjects, date, difficulty), if applicable to your goal;
- An in-progress onboarding draft, so you can resume if you close the app mid-flow;
- Internal flags marking that we already asked once for notification permission and tracking when the OS already prompted you for an app rating.

**EMOP does not collect:** your name, email, phone number, photo, contacts, location, account credentials for any other service, advertising identifiers, or any other sensitive personal data.

## 3. How this data is used

The data lives on your device solely to make the app work — to build your schedule, show your progress, remember your settings between sessions. It is never read, transmitted, or processed by us at any point.

## 4. Sharing with third parties

EMOP **does not share personal data with third parties for commercial purposes.**

There are two places where the app interacts with external services, always at your initiative:

- **Share my week on Instagram:** when you tap "Share my week," EMOP generates an image of your progress and hands it off to the Instagram app to post as a Story. The image is handed directly to Instagram via the operating system's native mechanism; EMOP does not send anything over the internet. Once the image is inside Instagram, it is governed by Instagram's privacy policy (Meta Platforms, Inc.).
- **Export my data (Settings → Data and Privacy):** when you tap this button, EMOP generates a JSON file with a copy of your local data and opens the operating system's native share sheet. You choose where to send it (email, Google Drive, iCloud, etc.). EMOP does not send this file anywhere on its own.

## 5. Permissions requested by the app

EMOP **does not request sensitive permissions** (camera, microphone, location, contacts, photos, calendar).

The app requests **only one optional permission**:

- **Notifications:** after you finish onboarding, the app asks if it may send study reminders (1 per day, 30 minutes before your first block) and warnings when your streak is at risk. You may decline and use the app normally, or disable them at any time in Settings → Reminders or in the system settings.

## 6. Children and teenagers

EMOP is primarily intended for high-school students (typically ages 14–18). Because the app does not collect or transmit personally identifiable information, no such information about minors is sent to third parties. We still recommend that parents or legal guardians supervise minors' use of the app.

In compliance with Brazil's LGPD (Law 13.709/2018, art. 14), EMOP's processing of data from children and adolescents is limited to local storage of information voluntarily provided by the user, with no transfer to third parties for commercial or advertising purposes.

## 7. Your rights (LGPD / GDPR-equivalent)

Since almost all data lives on your device, you are in full control:

- **Access:** all stored data is visible inside the app itself, under the Schedule, Topics, Progress tabs and in Settings.
- **Correction:** you can edit your information at any time inside the app.
- **Portability:** you can export a full copy of your data in JSON format under **Settings → Data and Privacy → Export my data**.
- **Deletion:** you can permanently delete all your data under **Settings → Data and Privacy → Delete all data**, or simply by uninstalling the app.

Regarding the crash reports sent to Sentry (section 8), you may request deletion by contacting the email below.

## 8. Analytics, ads, and error reporting

EMOP **does not use**:

- Google Analytics, Firebase Analytics, or any other behavior or usage analytics tool;
- Any advertising network;
- Any advertising tracking SDK (no *App Tracking Transparency* prompt is shown because there is no tracking);
- No cookies, no persistent identifier for commercial purposes.

EMOP **does use, in production builds only**:

- **Sentry** (sentry.io, operated by Functional Software, Inc., USA) to receive automatic reports when the app crashes or encounters an error. These reports contain: device type and model, operating system version, app version, technical stack trace of the error, approximate IP address of the request, and — in case of local data corruption — a small sample (up to 200 characters) of the corrupted snippet for diagnosis. The reports **do not contain** the contents of your schedule, your scores, your study topics, your progress, or any personal information you provided. The sole purpose is to find and fix bugs.

In development builds and on the web version, no reports are sent.

## 9. Security

Data stored on your device sits in the operating system's standard local storage, protected by the OS itself (iOS and Android app sandboxing). Your study content is not transmitted over the internet.

Crash reports sent to Sentry travel over encrypted connections (HTTPS/TLS) and are subject to Sentry's own security and retention policy.

## 10. Changes to this policy

If this policy needs to be updated (for example, if a future version of the app starts using a server for accounts, cross-device sync, or a new feature), we will notify you within the app and update the date at the top of this document. Continued use of EMOP after the update indicates acceptance of the revised policy.

## 11. Contact

If you have questions about this Privacy Policy or about how your data is handled by EMOP, contact:

**Email:** apgfdinho@gmail.com


