# :wave: Die Grundlagen von GitHub

## 🤓 Kursüberblick und Lernziele

Ziel dieses Kurses ist es, dir eine kurze Einführung in Git und GitHub zu geben.
Wir stellen dir auch Materialien für weiteres Lernen und ein paar Ideen für den Einstieg auf unserer Plattform zur Verfügung. 🚀

## :octocat: Git und GitHub

Git ist ein **verteiltes Versionskontrollsystem (VCS)**, oder auf Englisch ein **distributed Version Control System**, was bedeutet, dass es ein nützliches Werkzeug ist, um Änderungen an deinem Code einfach zu verfolgen, zusammenzuarbeiten und zu teilen.
Mit Git kannst du die Änderungen verfolgen, die du an deinem Projekt vornimmst, sodass du immer eine Aufzeichnung deiner Arbeit hast und bei Bedarf problemlos zu einer älteren Version zurückkehren kannst.
Es erleichtert auch die Zusammenarbeit mit anderen – Gruppen von Personen können gemeinsam am selben Projekt arbeiten und ihre Änderungen in eine endgültige Quelle zusammenführen!

GitHub ist eine Möglichkeit, die gleiche Leistungsfähigkeit von Git online mit einer einfach zu bedienenden Oberfläche zu nutzen.
Es wird in der gesamten Softwarewelt und darüber hinaus verwendet, um zusammenzuarbeiten und die Historie von Projekten zu pflegen.

GitHub beherbergt einige der fortschrittlichsten Technologien der Welt.
Egal, ob du Daten visualisierst oder ein neues Spiel entwickelst, auf GitHub gibt es eine ganze Community und eine Reihe von Tools, die dich zum nächsten Schritt bringen können.
In diesem Kurs wirst du die Grundlagen von Git und GitHub kennenlernen.

## :octocat: Den GitHub-Flow verstehen

Der GitHub-Flow ist ein Workflow, der es dir ermöglicht, einfach an deinen Projekten zu experimentieren und mit anderen zusammenzuarbeiten, ohne das Risiko, deine bisherige Arbeit zu verlieren.

### Repositories

Ein Repository ist der Ort, an dem deine Projektarbeit stattfindet – betrachte es als deinen Projektordner.
Es enthält alle Dateien deines Projekts und die Revisionshistorie, also alle Versionen, die du bisher erstellt hast.
Du kannst innerhalb eines Repositories alleine arbeiten oder andere einladen, mit dir an diesen Dateien zusammenzuarbeiten.

### Klonen

Wenn ein Repository mit GitHub erstellt wird, wird es remote in der ☁️ gespeichert.
Du kannst ein solches Repository herunterladen, um eine lokale Kopie auf deinem Computer zu erstellen.
Dies wird **klonen** genannt.
Die beiden Kopien werden dann mit Git synchronisieren.
Wenn mehrere Leute an dem Projekt arbeiten, können alle das Projekt klonen und haben dann ihre eigene Kopie auf ihrem Computer.
Dies erleichtert das Beheben von Problemen, das Hinzufügen oder Entfernen von Dateien.
Du kannst auch das Bearbeitungswerkzeug deiner Wahl anstelle der GitHub-Benutzeroberfläche verwenden.
Das Klonen eines Repositories lädt auch alle Repository-Daten herunter, die GitHub zu diesem Zeitpunkt hat, einschließlich aller Versionen jeder Datei und jedes Ordners für das Projekt!
Dies kann hilfreich sein, wenn du mit deinem Projekt experimentierst und dann feststellst, dass dir eine frühere Version besser gefallen hat.
Um mehr über das Klonen zu erfahren, lies ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committing und Pushing

Wenn du den aktuellen Stand deiner Arbeit als neue Version in der Historie speichern willst, musst du deine Änderungen **committen**.
Es genügt nicht, die Datei nur zu speichern.
Jeder **Commit** stellte einen Zeitpunkt in der Entwicklung des Projektes dar.
Alle committede Änderungen können dann in das Remote-Repository auf GitHub hochgeladen werden.
Dies nennen wir Änderungen **pushen**.
Auf diese Weise können dein Lehrer und/oder deine Teamkollegen deine neueste Arbeit sehen, wenn du bereit bist, sie zu teilen.
Wenn du einen **Commit** erstellst, solltest du eine hilfreiche **Commit-Nachricht** hinzufügen, um dich selbst oder deine Teamkollegen daran zu erinnern, welche Arbeit du erledigt hast.
Ein Beispiel wäre "README mit Informationen über unser Projekt hinzugefügt", oder "Fehler im Design des Kontaktformulares behoben".

## 💻 Wichtige GitHub-Begriffe

### Repositories

Du kannst dir alle deine Repositories auf deinem ["GitHub-Dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ansehen.
Stelle sicher, dass du angemeldet bist, um drauf Zugreifen zu können.

Repositories enthalten auch **README**-Dateien. 
Hierbei handelt es sich um eine Datei, die dein Projekt beschreibt.
Du bist gerade dabei, die README-Datei dieses Repositories zu lesen. 😄
Um mehr über Repositories zu erfahren, lies ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) und ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches (Zweige)

Du kannst Branches auf GitHub verwenden, um Arbeiten zu isolieren, die du noch nicht in dein endgültiges Projekt zusammenführen möchtest.
Branches ermöglichen es dir, Funktionen zu entwickeln, Fehler zu beheben oder sicher mit neuen Ideen in einem abgegrenzten Bereich deines Repositories zu experimentieren.
Dies erlaubt es dir, ganz einfach an mehreren Versionen gleichzeitig zu arbeiten, ohne Kopie zu erstellen.
In der Regel erstellst du einen neuen Branch aus dem Standard-Branch deines Repositories – `main`. Dadurch wird eine neue Arbeitskopie deines Repositories erstellt, mit der du experimentieren kannst.
Sobald du mit den neuen Änderungen zufrieden bist, kannst du deine Änderungen in die Hauptversion, also den Standard-Branch deines Repositories integrieren, oder **mergen**.
Es ist auch möglich, von einem bestehenden Branch abzuzweigen.
So kann ein ganzer Baum von Branches entstehen.
Um mehr über Branching zu erfahren, lies ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Pull Requests (Pull-Anfragen)

Bei der Arbeit mit Branches kannst du eine Pull-Anfrage verwenden, um anderen über die Änderungen zu informieren, die du vornehmen möchtest, und um Feedback zu bitten.
Sobald eine Pull-Anfrage geöffnet ist, kannst du die potenziellen Änderungen mit deinen Mitarbeitern besprechen und überprüfen und bei Bedarf weitere Änderungen hinzufügen.
Wenn die Änderungen aktzeptiert werden, können diese gemerged werden.
Um mehr über Pull-Anfragen zu erfahren, lies ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues (Probleme)

Issues sind eine Möglichkeit, Verbesserungen, Aufgaben oder Fehler für deine Arbeit auf GitHub zu verfolgen.
Issues sind eine großartige Möglichkeit, alle Aufgaben zu verfolgen, an denen du für dein Projekt arbeiten möchtest, und andere wissen zu lassen, woran du zu arbeiten planst.
Du kannst Issues auch verwenden, um ein Open-Source-Projekt über einen Fehler zu informieren, den du gefunden hast, oder über eine Funktion, die deiner Meinung nach eine großartige Ergänzung wäre!

Du kannst auch Pull-Anfragen und Issues miteinander verknüpfen, um zu zeigen, dass eine Korrektur in Arbeit ist, und das Issue automatisch zu schließen, wenn jemand die Pull-Anfrage mergt.
Um mehr über Issues und deren Verknüpfung mit deinen Pull-Anfragen zu erfahren, lies ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Markdown auf GitHub verwenden

Du hast es vielleicht schon bemerkt, aber du kannst deinen Issues, Pull-Requests und Dateien ein paar lustige Formatierungen hinzufügen.
["Markdown"](https://guides.github.com/features/mastering-markdown/) ist eine einfache Möglichkeit, deine Issues, Pull-Requests und Dateien mit einer einfachen Syntax zu gestalten.
Dies kann hilfreich sein, um deine Informationen zu organisieren und sie für andere leichter lesbar zu machen.
Du kannst auch GIFs und Bilder einfügen, um deine Aussagen zu verdeutlichen!
Um mehr über die Verwendung der GitHub-eigenen Markdown-Variante zu erfahren, lies ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

## ![Git](https://git-scm.com/images/logo.png)

Git kannst du sowohl für Windows, Linux und MacOS herunterladen und installieren.
Es handelt sich um ein Kommandozeilenprogramm, wird also über eine Kommandozeile benutzt und besitzt keine graphische Oberfläche.

Git kann auf folgender Seite heruntergeladen werden: ["Git Downloads"](https://git-scm.com/downloads)

### Befehle

Alle Befehle, die du mit Git benutzts beginnen mit `git`!

#### Klonen

Um ein Repository auf deinen Rechner zu Klonen, benutzt du den Befehl `git clone` gefolgt von der URL des Remote-Repositories und dem Ordner, in den die Dateien heruntergeladen werden sollen.
Wenn du keinen Ordner angibst, wird ein neuer Ordner mit dem Namen des Repositories erstellt.

```bash
git clone <Remote-URL> [<Local-Repository>]
```

Diesen Befehl führst du in der Regel nur einmal pro Rechner und pro Repository aus!

Die URL findest du auf der Startseite des Repositories auf GitHub:

![GitHub Clone URL](01-github-clone-url.png)

Der Befehl zeigt dir an, wo die Dateien heruntergeladen werden und um wieviele Dateien es sich handelt:

![Git-bash clone](01-gitbash-clone.png)

#### Status

Um während der Arbeit zu sehen, welche Dateien gerade bearbeitet werden, auf welchem Branch man sich befindet, was die Unterschiede zum Remote-Repository sind, ... kann man den Befehl `git status` benutzen.
Dieser Befehl ist sehr vielseitig.
In seiner einfachsten Form zeigt er nur einige Informationen zum aktuellen Stand des Repositories.
Erfahre mehr über diesen Befehl in der [status-Referenz](https://git-scm.com/docs/git-status).



## 📝 Nächste Schritte

* 
* Öffne eine Pull-Anfrage und lass deinen Lehrer wissen, dass du diesen Kurs abgeschlossen hast.
* Erstelle eine neue Markdown-Datei in diesem Repository. Teile mit, was du gelernt hast und was du noch nicht verstehst! Experimentiere mit verschiedenen Stilen!
* Erstelle deine Profil-README. Lass die Welt ein wenig mehr über dich wissen! Woran bist du interessiert? Woran arbeitest du? Was ist dein Lieblingshobby? Erfahre mehr über das Erstellen deiner Profil-README im Dokument ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Gehe zu deinem Benutzer-Dashboard und erstelle ein neues Repository. Experimentiere mit den Funktionen in diesem Repository, um dich damit vertraut zu machen.
* [Lass uns wissen, was dir an den Inhalten dieses Kurses gefallen oder nicht gefallen hat](https://support.github.com/contact/education). Was würdest du gerne mehr sehen? Was wäre interessant oder hilfreich für deine Lernreise?

## 📚 Ressourcen

* [Ein kurzes Video, das erklärt, was GitHub ist](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Lernmaterialien zu Git und GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Das GitHub-Flow verstehen](https://guides.github.com/introduction/flow/)
* [So verwendest du GitHub-Branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interaktive Git-Schulungsmaterialien](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Forum der Education-Community](https://education.github.community/)
* [GitHub-Community-Forum](https://github.community/)
