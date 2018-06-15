# Metalab Vereinsstatuten

## Änderungen

Statutenänderungen werden bei der Metalab Generalversammlung beschlossen.

Wenn du einen Änderungsantrag stellen möchtest:
* Bearbeite die Datei Metalab_statuten.md
* Stelle einen Pullrequest
* Füge den Antrag in die jeweilige Metalab-Wikiseite hinzu.
  * Z.B. https://metalab.at/wiki/Generalversammlung_2018
  * Bitte verlinke dabei auf den Pullrequest.
* Stelle deinen Anrag zur Diskussion.
* Reiche deinen Antrag fristgerecht beim Vorstand ein wenn du glaubst, dass der Antrag mehrhreitsfähig ist.

Bitte beachte:
* Änderungsanträge müssen fristgerecht beim Vorstand schriftlich oder per Email eingereicht werden. (Siehe §9 Abs. 5 der Statuten)
* Änderungsanträge müssen ausformuliert sein. (Am besten in Form eines Pullrequests)
* Bitte stelle deinen Antrag schon im Vorfeld zur Diskussion, um die Generalversammlung kurz zu halten.
* Bitte füge keine nicht beschlossenen Änderungsvorschläge zum master Branch hinzu. Dort soll nur die offiziell gültige Fassung der Statuten liegen.


## PDF erzeugen

Nach der Generalversammlung müssen Statutenänderungen der Polizei angezeigt werden. Diese können mit PDF mehr als mit Markdown anfangen.

* dieses Repo klonen
* pandoc installieren
* Zum Beispiel: <code>pandoc Metalab_statuten.md -V geometry:"a4paper,top=1.9cm,bottom=1.9cm,left=1.8cm,right=1.8cm" -o Metalab_statuten.pdf</code>


