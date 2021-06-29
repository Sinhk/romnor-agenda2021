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
<form name="screening" method="POST" netlify-honeypot="bot-field" data-netlify="true">
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
    </div>
    <div class="form-group field-utfyller">
        <label for="utfyller">Navn på den som fyller ut skjemaet (Må være over 18 år):</label>
        <input type="text" class="form-control" name="utfyller" id="utfyller" required="required" aria-required="true">
    </div>
    <div class="form-group field-har-korona">
        <label for="har-korona"><strong>Har deltakeren, etter å ha tatt en test, fått påvist koronavirus?</strong></label>
        <div class="radio-group">
            <div>
                <input name="har-korona" id="har-korona-0" value="option-1" type="radio">
                <label for="har-korona-0">Ja</label>
            </div>
            <div>
                <input name="har-korona" id="har-korona-1" value="option-2" type="radio">
                <label for="har-korona-1">Ja, men er friskmeldt</label>
            </div>
            <div>
                <input name="har-korona" id="har-korona-2" value="option-3" type="radio">
                <label for="har-korona-2">Nei</label>
            </div>
        </div>
    </div>
    <div class="form-group field-symptomer">
        <label for="symptomer"><strong>Har deltakeren hatt en eller flere av disse plagene i dag eller i løpet av det siste døgnet? (Hvis ja, kryss av):</strong></label>
        <div class="checkbox-group">
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-0" value="option-1" type="checkbox">
                <label for="symptomer-0">Hoste</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-1" type="checkbox">
                <label for="symptomer-1">Feber</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-2" type="checkbox">
                <label for="symptomer-2">Følelse av tungpustethet</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-3" type="checkbox">
                <label for="symptomer-3">Tett eller rennende nese</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-4" type="checkbox">
                <label for="symptomer-4">Vond eller sår hals</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-5" type="checkbox">
                <label for="symptomer-5">Tap av smaks- eller luktesans</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-6" type="checkbox">
                <label for="symptomer-6">Diaré eller magesmerter</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-7" type="checkbox">
                <label for="symptomer-7">Nyoppståtte ryggsmerter som ikke har annen forklaring</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-8" type="checkbox">
                <label for="symptomer-8">Hodepine</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="symptomer[]" id="symptomer-9" type="checkbox">
                <label for="symptomer-9">Nei, ingen symptomer på koronavirus</label>
            </div>
        </div>
    </div>
   <div class="form-group field-spredning">
        <label for="spredning" class=""><strong>Gjelder noe av dette for deltakeren?</strong></label>
        <div class="checkbox-group">
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-0" value="option-1" type="checkbox">
                <label for="spredning-0">Har vært utenfor Norge i løpet av de siste 14 dagene</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-1" type="checkbox">
                <label for="spredning-1">Har vært i nærkontakt med noen som har påvist koronavirus</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-2" type="checkbox">
                <label for="spredning-2">Er satt opp til time for testing for koronavirus</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-3" type="checkbox">
                <label for="spredning-3">Bor i samme husstand som noen som skal testes for koronavirus</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-4" type="checkbox">
                <label for="spredning-4">Bor i samme husstand som noen som har fått påvist koronavirus og ikke er friskmeldt enda</label>
            </div>
            <div class="formbuilder-checkbox">
                <input name="spredning[]" id="spredning-5" type="checkbox">
                <label for="spredning-5">Nei, ingen av alternativene gjelder for deltakeren</label>
            </div>
        </div>
    </div>
    <div class="form-group field-frisk">
        <label for="frisk" class=""><strong>Jeg bekrefter at deltakeren er frisk og symptomfri</strong></label>
        <div class="radio-group">
            <div class="formbuilder-radio">
                <input name="frisk" id="frisk-0" required="required" aria-required="true" value="ja" type="radio">
                <label for="frisk-0">Ja</label>
            </div>
            <div class="formbuilder-radio">
                <input name="frisk" id="frisk-1" value="nei" type="radio">
                <label for="frisk-1">Nei</label>
            </div>
        </div>
    </div>
    <div>
        <button type="submit">IKKE AKTIV ENDA</button>
    </div>
</form>


{{</rawhtml>}}

