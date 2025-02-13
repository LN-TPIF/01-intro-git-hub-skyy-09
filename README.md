# :wave: Die Grundlagen von GitHub

## 🤓 Kursüberblick und Lernziele

Ziel dieses Kurses ist es, dir eine kurze Einführung in GitHub zu geben. Wir stellen dir auch Materialien für weiteres Lernen und ein paar Ideen für den Einstieg auf unserer Plattform zur Verfügung. 🚀

## :octocat: Git und GitHub

Git ist ein **verteiltes Versionskontrollsystem (VCS)**, was bedeutet, dass es ein nützliches Werkzeug ist, um Änderungen an deinem Code einfach zu verfolgen, zusammenzuarbeiten und zu teilen. Mit Git kannst du die Änderungen verfolgen, die du an deinem Projekt vornimmst, sodass du immer eine Aufzeichnung deiner Arbeit hast und bei Bedarf problemlos zu einer älteren Version zurückkehren kannst. Es erleichtert auch die Zusammenarbeit mit anderen – Gruppen von Personen können gemeinsam am selben Projekt arbeiten und ihre Änderungen in eine endgültige Quelle zusammenführen!

GitHub ist eine Möglichkeit, die gleiche Leistungsfähigkeit von Git online mit einer einfach zu bedienenden Oberfläche zu nutzen. Es wird in der gesamten Softwarewelt und darüber hinaus verwendet, um zusammenzuarbeiten und die Historie von Projekten zu pflegen.

GitHub beherbergt einige der fortschrittlichsten Technologien der Welt. Egal, ob du Daten visualisierst oder ein neues Spiel entwickelst, auf GitHub gibt es eine ganze Community und eine Reihe von Tools, die dich zum nächsten Schritt bringen können. Dieser Kurs beginnt mit den Grundlagen von GitHub, aber wir werden uns später mit dem Rest befassen.

## :octocat: Das GitHub-Flow verstehen

Der GitHub-Flow ist ein leichtgewichtiger Workflow, der es dir ermöglicht, einfach an deinen Projekten zu experimentieren und zusammenzuarbeiten, ohne das Risiko, deine bisherige Arbeit zu verlieren.

### Repositories (Projekte)

Ein Repository ist der Ort, an dem deine Projektarbeit stattfindet – betrachte es als deinen Projektordner. Es enthält alle Dateien deines Projekts und die Revisionshistorie. Du kannst innerhalb eines Repositories alleine arbeiten oder andere einladen, mit dir an diesen Dateien zusammenzuarbeiten.

### Klonen

Wenn ein Repository mit GitHub erstellt wird, wird es remote in der ☁️ gespeichert. Du kannst ein Repository klonen, um eine lokale Kopie auf deinem Computer zu erstellen und dann Git zu verwenden, um die beiden zu synchronisieren. Dies erleichtert das Beheben von Problemen, das Hinzufügen oder Entfernen von Dateien und das Pushen größerer Commits. Du kannst auch das Bearbeitungswerkzeug deiner Wahl anstelle der GitHub-Benutzeroberfläche verwenden. Das Klonen eines Repositories lädt auch alle Repository-Daten herunter, die GitHub zu diesem Zeitpunkt hat, einschließlich aller Versionen jeder Datei und jedes Ordners für das Projekt! Dies kann hilfreich sein, wenn du mit deinem Projekt experimentierst und dann feststellst, dass dir eine frühere Version besser gefallen hat.
Um mehr über das Klonen zu erfahren, lies ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committing und Pushing

**Committing** (Festschreiben) und **Pushing** (Hochladen) sind die Methoden, mit denen du die Änderungen, die du auf deinem lokalen Rechner vorgenommen hast, zum Remote-Repository in GitHub hinzufügen kannst. Auf diese Weise können dein Lehrer und/oder deine Teamkollegen deine neueste Arbeit sehen, wenn du bereit bist, sie zu teilen. Du kannst einen Commit erstellen, wenn du Änderungen an deinem Projekt vorgenommen hast, die du "prüfen" möchtest. Du kannst auch eine hilfreiche **Commit-Nachricht** hinzufügen, um dich selbst oder deine Teamkollegen daran zu erinnern, welche Arbeit du erledigt hast (z. B. "README mit Informationen über unser Projekt hinzugefügt").

Sobald du einen oder mehrere Commits hast, die du deinem Repository hinzufügen möchtest, kannst du den Befehl `push` verwenden, um diese Änderungen zu deinem Remote-Repository hinzuzufügen. Das Committing und Pushing mag sich anfangs neu anfühlen, aber wir versprechen dir, dass du dich daran gewöhnen wirst 🙂.

## 💻 Wichtige GitHub-Begriffe

### Repositories

Wir haben Repositories bereits erwähnt, sie sind der Ort, an dem deine Projektarbeit stattfindet, aber lass uns ein wenig mehr über die Details sprechen! Wenn du mehr auf GitHub arbeitest, wirst du viele Repositories haben, was sich anfangs verwirrend anfühlen kann. Glücklicherweise hilft dir dein ["GitHub-Dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard), einfach zu deinen Repositories zu navigieren und nützliche Informationen über sie zu sehen. Stelle sicher, dass du angemeldet bist, um es zu sehen!

Repositories enthalten auch **README**-Dateien. Du kannst eine README-Datei zu deinem Repository hinzufügen, um anderen Leuten mitzuteilen, warum dein Projekt nützlich ist, was sie damit machen können und wie sie es verwenden können. Wir verwenden diese README, um dir die Grundlagen von Git und GitHub zu vermitteln. 😄
Um mehr über Repositories zu erfahren, lies ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) und ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches (Zweige)

Du kannst Branches auf GitHub verwenden, um Arbeiten zu isolieren, die du noch nicht in dein endgültiges Projekt zusammenführen möchtest. Branches ermöglichen es dir, Funktionen zu entwickeln, Fehler zu beheben oder sicher mit neuen Ideen in einem abgegrenzten Bereich deines Repositories zu experimentieren. In der Regel erstellst du einen neuen Branch aus dem Standard-Branch deines Repositories – `main`. Dadurch wird eine neue Arbeitskopie deines Repositories erstellt, mit der du experimentieren kannst. Sobald deine neuen Änderungen von einem Teamkollegen überprüft wurden oder du zufrieden damit bist, kannst du deine Änderungen in den Standard-Branch deines Repositories mergen.
Um mehr über Branching zu erfahren, lies ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks (Abzweigungen)

Ein Fork ist eine andere Möglichkeit, ein Repository zu kopieren, wird aber normalerweise verwendet, wenn du zu einem Projekt einer anderen Person beitragen möchtest. Das Forken eines Repositories ermöglicht es dir, frei mit Änderungen zu experimentieren, ohne das Originalprojekt zu beeinflussen, und ist sehr beliebt, wenn du zu Open-Source-Softwareprojekten beiträgst!
Um mehr über das Forken zu erfahren, lies ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull Requests (Pull-Anfragen)

Bei der Arbeit mit Branches kannst du eine Pull-Anfrage verwenden, um anderen über die Änderungen zu informieren, die du vornehmen möchtest, und um Feedback zu bitten. Sobald eine Pull-Anfrage geöffnet ist, kannst du die potenziellen Änderungen mit deinen Mitarbeitern besprechen und überprüfen und bei Bedarf weitere Änderungen hinzufügen. Du kannst bestimmten Personen als Reviewer deiner Pull-Anfrage hinzufügen, um zu zeigen, dass du ihr Feedback zu deinen Änderungen wünschst! Sobald eine Pull-Anfrage fertig ist, kann sie in deinen Haupt-Branch gemergt werden.
Um mehr über Pull-Anfragen zu erfahren, lies ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues (Probleme)

Issues sind eine Möglichkeit, Verbesserungen, Aufgaben oder Fehler für deine Arbeit auf GitHub zu verfolgen. Issues sind eine großartige Möglichkeit, alle Aufgaben zu verfolgen, an denen du für dein Projekt arbeiten möchtest, und andere wissen zu lassen, woran du zu arbeiten planst. Du kannst Issues auch verwenden, um ein Open-Source-Projekt über einen Fehler zu informieren, den du gefunden hast, oder über eine Funktion, die deiner Meinung nach eine großartige Ergänzung wäre!

Bei größeren Projekten kannst du viele Issues auf einem Projektboard verfolgen. GitHub Projects hilft dir, deine Arbeit zu organisieren und zu priorisieren, und du kannst mehr darüber im Dokument "About Project boards" lesen. Du wirst wahrscheinlich kein Projektboard für deine Aufgaben benötigen, aber sobald du zu noch größeren Projekten übergehst, sind sie eine großartige Möglichkeit, die Arbeit deines Teams zu organisieren!
Du kannst auch Pull-Anfragen und Issues miteinander verknüpfen, um zu zeigen, dass eine Korrektur in Arbeit ist, und das Issue automatisch zu schließen, wenn jemand die Pull-Anfrage mergt.
Um mehr über Issues und deren Verknüpfung mit deinen Pull-Anfragen zu erfahren, lies ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Dein Benutzerprofil

Deine Profilseite erzählt die Geschichte deiner Arbeit anhand der Repositories, an denen du interessiert bist, der Beiträge, die du geleistet hast, und der Gespräche, die du geführt hast. Mit deiner Profil-README kannst du der Welt auch einen einzigartigen Einblick in deine Person geben. Du kannst dein Profil nutzen, um zukünftigen Arbeitgebern alles über dich zu erzählen!
Um mehr über dein Benutzerprofil und das Hinzufügen und Aktualisieren deiner Profil-README zu erfahren, lies ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Markdown auf GitHub verwenden

Du hast es vielleicht schon bemerkt, aber du kannst deinen Issues, Pull-Requests und Dateien ein paar lustige Formatierungen hinzufügen. ["Markdown"](https://guides.github.com/features/mastering-markdown/) ist eine einfache Möglichkeit, deine Issues, Pull-Requests und Dateien mit einer einfachen Syntax zu gestalten. Dies kann hilfreich sein, um deine Informationen zu organisieren und sie für andere leichter lesbar zu machen. Du kannst auch GIFs und Bilder einfügen, um deine Aussagen zu verdeutlichen!
Um mehr über die Verwendung der GitHub-eigenen Markdown-Variante zu erfahren, lies ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interaktion mit der GitHub-Community

Die GitHub-Community ist riesig. Es gibt viele Arten von Menschen, die GitHub täglich nutzen – Studenten wie du, professionelle Entwickler, Hobbybastler, die an Open-Source-Projekten arbeiten, und Entdecker, die gerade in die Welt der Softwareentwicklung einsteigen. Es gibt viele Möglichkeiten, mit der größeren GitHub-Community zu interagieren, aber hier sind drei Orte, an denen du beginnen kannst.

#### Repositories mit Sternen versehen

Wenn du ein Repository interessant findest oder es verfolgen möchtest, gib ihm einen Stern! Wenn du einem Repository einen Stern gibst, wird dies auch als Signal verwendet, um bessere Empfehlungen auf github.com/explore anzuzeigen. Wenn du zu deinen mit Sternen versehenen Repositories zurückkehren möchtest, kannst du dies über dein Benutzerprofil tun.
Um mehr über das Versehen von Repositories mit Sternen zu erfahren, lies ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars).

#### Benutzern folgen

Du kannst Personen auf GitHub folgen, um Benachrichtigungen über ihre Aktivitäten zu erhalten und Projekte in ihren Communities zu entdecken. Wenn du einem Benutzer folgst, werden seine öffentlichen GitHub-Aktivitäten auf deinem Dashboard angezeigt, sodass du all die coolen Dinge sehen kannst, an denen er arbeitet.
Um mehr über das Folgen von Benutzern zu erfahren, lies ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### GitHub Explore durchsuchen

GitHub Explore ist ein großartiger Ort, um genau das zu tun ... zu erkunden :smile: Du kannst neue Projekte, Veranstaltungen und Entwickler finden, mit denen du interagieren kannst.

Du kannst die GitHub Explore-Website unter [github.com/explore](https://github.com/explore) besuchen. Je mehr du mit GitHub interagierst, desto besser wird deine Explore-Ansicht auf dich zugeschnitten.

## 📝 Optionale nächste Schritte

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
