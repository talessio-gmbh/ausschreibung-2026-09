# Coding Challenge: Rette Sandras Montagmorgen

*Bewerbung Werkstudent:in Software-Entwicklung – talessio GmbH*

---

## Das Problem

Sandra leitet HR Operations bei der Hallberg Maschinenbau GmbH, einem Industrieunternehmen mit rund 800 Mitarbeitenden an zwei Standorten. Jeden Montag verbringt sie zwei Stunden damit, aus Excel-Exporten den Stand der Pflichtschulungen zusammenzupuzzeln: Wer ist überfällig? Wo muss sie nachhaken, wo eskalieren? Was kommt auf sie zu, bevor das nächste Audit ansteht?

Sie hasst diese zwei Stunden.

## Deine Aufgabe

Baue eine Web-Anwendung, die Sandras Montagsroutine überflüssig macht – oder zumindest drastisch verkürzt.

Was sie sehen muss, wie sie damit arbeitet, was wichtig ist und was weggelassen werden kann: **deine Entscheidung.**

Es gibt keine Musterlösung und keine versteckte Feature-Checkliste, die du erraten sollst. Uns interessiert, welche Fragen du an das Problem und an die Daten stellst, was du zuerst baust – und was bewusst nicht.

## Die Daten

Heute ist **Montag, der 2. November 2026**. Rechne alle zeitbezogenen Auswertungen mit diesem Stichtag, nicht mit dem echten Datum.

Du bekommst drei CSV-Dateien (UTF-8, Komma-getrennt, Datumsangaben im Format `YYYY-MM-DD`) mit fiktiven Daten:

| Datei | Inhalt |
|---|---|
| `employees.csv` | Mitarbeitende mit Abteilung, Standort, Funktion, Vorgesetztem (`manager_id`) und Eintrittsdatum |
| `trainings.csv` | Trainingskatalog mit Kategorie, Pflicht-Kennzeichen, Gültigkeitsdauer in Monaten (leer = unbegrenzt) und Zielgruppe |
| `assignments.csv` | Zuweisungen von Trainings an Mitarbeitende mit Zuweisungs- und Fälligkeitsdatum, Status (`Zugewiesen`, `In Bearbeitung`, `Abgeschlossen`) und Abschlussdatum |

Die Struktur ist an echte Exporte aus Learning-Management-Systemen angelehnt – inklusive der Unschärfen, die solche Exporte haben.

**Schau genau hin.** In den Daten steckt mehr als Durchschnittswerte.

## README (Pflichtteil – ersetzt dein Anschreiben)

Beantworte in deinem README kurz:

1. Wie bist du an das Problem herangegangen?
2. Welche zwei, drei Entscheidungen waren die wichtigsten – und warum?
3. Was hast du bewusst weggelassen?
4. Was würdest du mit mehr Zeit als Nächstes bauen?

Dazu eine kurze Anleitung, wie wir deine Anwendung lokal starten.

## Rahmenbedingungen

- **Technologie:** frei wählbar. Unser Stack ist C#/Blazor – ein Plus, aber eine gute Lösung in React, Vue oder etwas anderem zählt genauso.
- **KI-Tools:** ausdrücklich erlaubt, wir nutzen sie selbst. Im Gespräch gehen wir gemeinsam durch deinen Code – du solltest jede Entscheidung erklären können.
- **Zeitbudget:** ca. 6–8 Stunden. Ein guter, fokussierter Ausschnitt schlägt ein halbfertiges Alles.
- **Abgabe:** Link zu einem Git-Repository (öffentlich oder für uns freigegeben), optional Screenshots oder ein kurzes Demo-Video.

## So bewerten wir

| Kriterium | Gewicht |
|---|---|
| Problemverständnis und Priorisierung | 35 % |
| UX und Verständlichkeit | 25 % |
| Code-Qualität | 25 % |
| Reflexion im README | 15 % |

## Ablauf

Repo und Lebenslauf einreichen → Rückmeldung innerhalb einer Woche → 60-minütiges Gespräch inklusive Walkthrough durch deine Anwendung → Entscheidung.

Fragen zur Aufgabe? Schreib uns an **[jobs@talessio.com]**.

Viel Spaß – und danke, dass du Sandra hilfst.
