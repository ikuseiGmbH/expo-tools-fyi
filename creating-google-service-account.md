# Creating Google Service Account

Wenn Sie Ihre Android-App im Google Play Store mit `eas submit` einreichen möchten, müssen Sie einen Schlüssel für ein Google-Servicekonto erstellen. Diese Seite wird Sie durch diesen Prozess führen.

1. Öffnen Sie [Google Play Console](https://play.google.com/apps/publish/), Erweitern Sie **Einrichten**, und wählen Sie **API-Zugriff**.

[<img src="./assets/creating-google-service-account/01-open-google-play-console.png" width="800" />](./assets/creating-google-service-account/01-open-google-play-console.png)

2. Wenn Sie die Meldung erhalten, dass der API-Zugriff für Ihr Konto nicht aktiviert ist, müssen Sie zunächst Ihr Google Play-Entwicklerkonto mit einem Google Developer Project verknüpfen. Wählen Sie auf dieser Seite **Wählen Sie ein zu verknüpfendes Projekt** und verknüpfen Sie es dann entweder mit einem bestehenden Projekt, wenn Sie eines haben, oder wählen Sie **Neues Projekt erstellen** und klicken Sie dann auf **Projekt verknüpfen**.

[<img src="./assets/creating-google-service-account/02-api-access.png" width="800" />](./assets/creating-google-service-account/02-api-access.png)

[<img src="./assets/creating-google-service-account/03-create-new-project.png" width="800" />](./assets/creating-google-service-account/03-create-new-project.png)

3. Klicken Sie auf **Weitere Informationen zum Erstellen von Dienstkonten** und folgen Sie dem Link **Google Cloud Platform** im Dialogfeld.

[<img src="./assets/creating-google-service-account/04-create-new-service-account.png" width="800" />](./assets/creating-google-service-account/04-create-new-service-account.png)

[<img src="./assets/creating-google-service-account/05-service-account-dialog.png" width="800" />](./assets/creating-google-service-account/05-service-account-dialog.png)

4. Klicken Sie auf eine weitere Schaltfläche **DIENSTKONTO ERSTELLEN**.

[<img src="./assets/creating-google-service-account/06-google-cloud-platform.png" width="800" />](./assets/creating-google-service-account/06-google-cloud-platform.png)

5. Geben Sie den Namen dieses Dienstkontos in das Feld "Name des Dienstkontos" ein. Wir empfehlen einen Namen, der es Ihnen leicht macht, sich zu merken, dass es sich um Ihr Google Play Console-Konto handelt. Geben Sie außerdem die ID des Dienstkontos und eine Beschreibung Ihrer Wahl ein. Klicken Sie auf die Schaltfläche **Erstellen und Fortfahren**.

[<img src="./assets/creating-google-service-account/07-service-account-name.png" width="800" />](./assets/creating-google-service-account/07-service-account-name.png)

6. Klicken Sie auf **Wählen Sie eine Rolle** und wählen Sie **Dienstkonten > Dienstkontonutzer**. Klicken Sie auf **FERTIG**.

[<img src="./assets/creating-google-service-account/08-service-account-permissions.png" width="800" />](./assets/creating-google-service-account/08-service-account-permissions.png)

7. Wählen Sie **Schlüssel verwalten** aus der Optionsschaltfläche für Ihr neu erstelltes Dienstkonto und dann **Neuen Schlüssel erstellen**. Wählen Sie **JSON** und dann die Schaltfläche **ERSTELLEN**. Laden Sie die `json`-Datei herunter und speichern Sie sie an einem sicheren Ort.

[<img src="./assets/creating-google-service-account/09-a-create-key.png" width="800" />](./assets/creating-google-service-account/09-a-create-key.png)
[<img src="./assets/creating-google-service-account/09-b-create-key.png" width="800" />](./assets/creating-google-service-account/09-b-create-key.png)
[<img src="./assets/creating-google-service-account/10-create-json-key.png" width="800" />](./assets/creating-google-service-account/10-create-json-key.png)

8. Kehren Sie zur **API-Zugangsseite** in der Google Play Console zurück und vergewissern Sie sich, dass Ihr neues Dienstkonto dort angezeigt wird. Klicken Sie auf **Play Console-Berechtigungen verwalten** für das neu hinzugefügte Dienstkonto.

[<img src="./assets/creating-google-service-account/11-grant-access.png" width="800" />](./assets/creating-google-service-account/11-grant-access.png)

9. Klicken Sie auf **Nutzer einladen**.

[<img src="./assets/creating-google-service-account/12-invite-user.png" width="800" />](./assets/creating-google-service-account/12-invite-user.png)

10. Klicken Sie auf **Einladung senden**,

[<img src="./assets/creating-google-service-account/13-send-invitation.png" width="800" />](./assets/creating-google-service-account/13-send-invitation.png)

11. Das war's schon! Von nun an können Sie das generierte Google Service-Konto verwenden, um Ihre App mit `eas submit` hochzuladen.
