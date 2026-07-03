# ai-email-lead-responder
# AI Email Lead Responder

KI-gestützter E-Mail-Automatisierungs-Workflow, entwickelt mit n8n.

## Beschreibung
Dieser Workflow empfängt eingehende E-Mail-Anfragen, klassifiziert sie automatisch mithilfe einer KI-API (z. B. ChatGPT), und generiert passende, personalisierte Antworten. Alle Anfragen werden zusätzlich in einer Tabelle protokolliert.

## Verwendete Tools
- n8n (Workflow-Automatisierung)
- OpenAI / ChatGPT API (Klassifizierung & Textgenerierung)
- Gmail (Trigger & Versand)
- Google Sheets / Airtable (Protokollierung)

## Funktionsweise
1. Gmail Trigger erkennt neue eingehende E-Mail
2. KI analysiert Inhalt und klassifiziert die Anfrage (z. B. Preisanfrage, Beschwerde, allgemeine Frage)
3. KI generiert einen passenden Antwortentwurf
4. Anfrage und Antwort werden protokolliert
5. Antwort wird automatisch gesendet oder als Entwurf gespeichert

## Autor
Mohammad Aburdan
