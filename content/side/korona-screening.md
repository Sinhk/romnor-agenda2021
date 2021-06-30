---
title: Korona-screening
author: ''
date: 
draft: false
---
# Koronascreening - FØR oppmøte på leir
Dette er et screeningverktøy som brukes til å vurdere om en person potensielt kan være smittet med koronavirus. Hensikten med denne screeningen er å redusere sannsynlighet for at noen som er bærere av viruset kommer på leir - dette må vi unngå.
Ved positivt svar på et eller flere av spørsmålene som er listet opp, skal deltaker vurderes av lege og ikke møte opp før det er gjort.
Dette skjemaet fylles ut før deltakeren møter opp. Alle som skal delta på leiren skal fylle ut skjemaet, både speidere, ledere, rovere, stab og gjester/instruktører. Hvis det mistenkes koronasmitte under leiren vil deltakeren sendes til testing og settes i karantene på leiren til deltakeren kan transporteres hjem. Ved friskmelding kan deltakeren komme tilbake til leiren.
Vi hjelper hverandre med å holde alle trygge og friske. 

 ---

{{<rawhtml>}}
<form name="screening" method="POST" netlify-honeypot="bot-field" data-netlify="true" action="/side/screening-sendt">
    <p class="hidden">
        <label>Don’t fill this out if you’re human: <input name="bot-field" /></label>
    </p>
    <div class="form-group field-navn">
        <label for="navn">Navn</label>
        <input type="text" class="form-control" name="navn" id="navn" required="required" aria-required="true">
    </div>
    <div class="form-group field-speidergruppe">
        <label for="speidergruppe">Speidergruppe</label>
        <input type="text" class="form-control" name="speidergruppe" id="speidergruppe" required="required" aria-required="true">
    </div>
    <div class="form-group field-patrulje">
        <label for="patrulje">Patrulje</label>
        <input type="text" class="form-control" name="patrulje" id="patrulje" required="required" aria-required="true">
        <small id="patruljeHelp" class="form-text text-muted">Skriv "Stab" om du er stab.</small>
    </div>
    <div class="form-group field-utfyller">
        <label for="utfyller">Navn på den som fyller ut skjemaet (Må være over 18 år):</label>
        <input type="text" class="form-control" name="utfyller" id="utfyller" required="required" aria-required="true">
    </div>
    <fieldset>
        <legend>Har deltakeren, etter å ha tatt en test, fått påvist koronavirus?</legend>
        <div><label><input type="radio" name="har-korona" value="Ja"> Ja</label></div>
        <div><label><input type="radio" name="har-korona" value="Ja, men er friskmeldt"> Ja, men er friskmeldt</label></div>
        <div><label><input type="radio" name="har-korona" value="Nei"> Nei</label></div>
    </fieldset>
    <fieldset>
        <legend>Har deltakeren hatt en eller flere av disse plagene i dag eller i løpet av det siste døgnet? (Hvis ja, kryss av):</legend>
        <div><label><input type="checkbox" name="symptomer[]" value="Hoste"> Hoste</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Feber"> Feber</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Følelse av tungpustethet"> Følelse av tungpustethet</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Tett eller rennende nese"> Tett eller rennende nese</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Vond eller sår hals"> Vond eller sår hals</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Tap av smaks- eller luktesans"> Tap av smaks- eller luktesans</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Diaré eller magesmerter"> Diaré eller magesmerter</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Nyoppståtte ryggsmerter som ikke har annen forklaring"> Nyoppståtte ryggsmerter som ikke har annen forklaring</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Hodepine"> Hodepine</label>
        <div><label><input type="checkbox" name="symptomer[]" value="Nei, ingen symptomer på koronavirus"> Nei, ingen symptomer på koronavirus</label>
    </fieldset>
    <fieldset>
        <legend>Gjelder noe av dette for deltakeren?</legend>
        <div><label><input type="checkbox" name="spredning[]" value="Har vært utenfor Norge i løpet av de siste 14 dagene"> Har vært utenfor Norge i løpet av de siste 14 dagene</label>
        <div><label><input type="checkbox" name="spredning[]" value="Har vært i nærkontakt med noen som har påvist koronavirus"> Har vært i nærkontakt med noen som har påvist koronavirus</label>
        <div><label><input type="checkbox" name="spredning[]" value="Er satt opp til time for testing for koronavirus"> Er satt opp til time for testing for koronavirus</label>
        <div><label><input type="checkbox" name="spredning[]" value="Bor i samme husstand som noen som skal testes for koronaviru"> Bor i samme husstand som noen som skal testes for koronaviru</label>
        <div><label><input type="checkbox" name="spredning[]" value="Bor i samme husstand som noen som har fått påvist koronavirus og ikke er friskmeldt enda"> Bor i samme husstand som noen som har fått påvist koronavirus og ikke er friskmeldt enda</label>
        <div><label><input type="checkbox" name="spredning[]" value="Nei, ingen av alternativene gjelder for deltakeren"> Nei, ingen av alternativene gjelder for deltakeren</label>
    </fieldset>
     <fieldset>
        <legend>Jeg bekrefter at deltakeren er frisk og symptomfri</legend>
        <div><label><input type="radio" name="frisk" value="Ja" required="required" aria-required="true"> Ja</label></div>
        <div><label><input type="radio" name="frisk" value="Nei"> Nei</label></div>
    </fieldset>
    <div>
        <button type="submit">IKKE AKTIV ENDA</button>
    </div>
</form>


{{</rawhtml>}}

