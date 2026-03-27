---
title: "Kontakt & Anfragen"
date: 2026-03-27
description: "Planen Sie Ihre private Stadtführung in Prag. Nutzen Sie das Formular für unverbindliche Anfragen zu meinen Touren."
layout: "single"
menu: "main"
weight: 50
---

Haben Sie Fragen zu meinen Touren oder möchten Sie ein individuelles Angebot für Ihren Prag-Besuch? Ich freue mich auf Ihre Nachricht!

Füllen Sie einfach das folgende Formular aus. Ich antworte Ihnen in der Regel innerhalb von 24 Stunden.

<form action="https://deine-mailygo-instanz.de/send" method="POST" class="contact-form">
    <input type="text" name="_honeypot" style="display:none !important" tabindex="-1" autocomplete="off">

    <div class="form-group">
        <label for="name">Ihr Name</label>
        <input type="text" name="name" id="name" placeholder="Vor- und Nachname" required>
    </div>

    <div class="form-group">
        <label for="email">Ihre E-Mail-Adresse</label>
        <input type="email" name="email" id="email" placeholder="beispiel@mail.de" required>
    </div>

    <div class="form-group">
        <label for="tour">Welche Tour interessiert Sie?</label>
        <select name="tour" id="tour">
            <option value="allgemein">Allgemeine Anfrage</option>
            <option value="altstadt">Altstadt & Jüdisches Viertel</option>
            <option value="nacht">Prag bei Nacht</option>
            <option value="ostern">Ostermärkte Spezial</option>
            <option value="individuell">Individuelle Führung</option>
        </select>
    </div>

    <div class="form-group">
        <label for="message">Ihre Nachricht / Wunschtermin</label>
        <textarea name="message" id="message" rows="6" placeholder="Wann sind Sie in Prag und was möchten Sie gerne sehen?" required></textarea>
    </div>

    <div class="form-checkbox">
        <input type="checkbox" name="privacy" id="privacy" required>
        <label for="privacy">Ich stimme zu, dass meine Angaben zur Beantwortung meiner Anfrage erhoben und verarbeitet werden. (Details siehe <a href="/datenschutz">Datenschutzerklärung</a>).</label>
    </div>

    <input type="hidden" name="_replyto" value="%email%">
    <input type="hidden" name="_subject" value="Neue Tour-Anfrage von TagInPrag.de">
    <input type="hidden" name="_success" value="https://www.taginprag.de/danke/">

    <button type="submit" class="btn-submit">Unverbindlich anfragen</button>
</form>

---
### Andere Wege mich zu erreichen
Falls Sie lieber direkt schreiben möchten:
**E-Mail:** [hallo@taginprag.de](mailto:hallo@taginprag.de)
