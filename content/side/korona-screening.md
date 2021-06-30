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
<noscript>
    <div class="alert alert-danger" role="alert">Din nettleser støtter ikke JavaScript, eller har det skrudd av. <br>Dette skjemaet krever JavaScript</div>
    <style> .jsonly { display: none } </style>
</noscript>
<form name="screening" method="POST" netlify-honeypot="bot-field" data-netlify="true" action="/side/screening-sendt" class="needs-validation" novalidate>
    <p class="hidden">
        <label>Don’t fill this out if you’re human: <input name="bot-field" /></label>
    </p>
    <div class="form-group">
        <label for="navn">Navn</label>
        <input type="text" class="form-control" name="navn" id="navn" required>
        <div class="invalid-feedback">
            Navn er påkrevd
        </div>
    </div>
    <div class="form-group">
        <label for="speidergruppe">Speidergruppe</label>
        <select class="form-control" id="speidergruppe" name="speidergruppe" required>
            <option hidden disabled selected value>---</option>
            <option>1. Batnfjord speidergruppe</option>
            <option>3. Fræna Aureosen</option>
            <option>Hustadvika Eide</option>
            <option>Moldespeiderne</option>
            <option>3. Rauma Isfjorden</option>
            <option>4. Rauma Innfjorden</option>
            <option>Annen</option>
        </select>
        <div class="invalid-feedback">
            Speidergruppe er påkrevd
        </div>
    </div>
    <div class="form-group">
        <label for="patrulje">Patrulje</label>
        <input type="text" class="form-control" name="patrulje" id="patrulje">
        <small id="patruljeHelp" class="form-text text-muted">Skriv "Stab" om du er stab.</small>
    </div>
    <div class="form-group">
        <label for="utfyller">Navn på den som fyller ut skjemaet (Må være over 18 år):</label>
        <input type="text" class="form-control" name="utfyller" id="utfyller" required>
        <div class="invalid-feedback">
            Utfyller er påkrevd
        </div>
    </div>
    <div class="form-group">
        <label for="dato">Dato</label>
        <input type="date" id="datePicker" class="form-control" name="dato" id="dato" disabled min="2021-07-01">
        <div class="invalid-feedback">
          Skjemaet kan ikke fylles ut før 1. juli
        </div>
    </div>
    <fieldset>
        <legend>Har deltakeren, etter å ha tatt en test, fått påvist koronavirus?</legend>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="radio" name="har-korona" id="har-korona-1" value="Ja" required> Ja</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="radio" name="har-korona" id="har-korona-2" value="Ja, men er friskmeldt" required> Ja, men er friskmeldt</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="radio" name="har-korona" id="har-korona-3" value="Nei" required> Nei</label>
            <div class="invalid-feedback">
                Må velge en
            </div>
        </div>
    </fieldset>
     <fieldset>
        <legend>Har deltakeren hatt en eller flere av disse plagene i dag eller i løpet av det siste døgnet? (Hvis ja, kryss av):</legend>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Hoste"> Hoste</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Feber"> Feber</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Følelse av tungpustethet"> Følelse av tungpustethet</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Tett eller rennende nese"> Tett eller rennende nese</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Vond eller sår hals"> Vond eller sår hals</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Tap av smaks- eller luktesans"> Tap av smaks- eller luktesans</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Diaré eller magesmerter"> Diaré eller magesmerter</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Nyoppståtte ryggsmerter som ikke har annen forklaring"> Nyoppståtte ryggsmerter som ikke har annen forklaring</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="checkbox" name="symptomer[]" value="Hodepine"> Hodepine</label></div>
        <div class="form-check"><label class="form-check-label"><input class="form-check-input" type="radio" name="symptomer[]" value="Nei"> Nei, ingen symptomer på koronavirus</label></div>
    </fieldset>
    <fieldset>
        <legend>Gjelder noe av dette for deltakeren?</legend>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="checkbox" id="spredning-1" name="spredning[]" value="Har vært utenfor Norge i løpet av de siste 14 dagene"> Har vært utenfor Norge i løpet av de siste 14 dagene</label></div>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="checkbox" id="spredning-2" name="spredning[]" value="Har vært i nærkontakt med noen som har påvist koronavirus"> Har vært i nærkontakt med noen som har påvist koronavirus</label></div>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="checkbox" id="spredning-3" name="spredning[]" value="Er satt opp til time for testing for koronavirus"> Er satt opp til time for testing for koronavirus</label></div>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="checkbox" id="spredning-4" name="spredning[]" value="Bor i samme husstand som noen som skal testes for koronavirus"> Bor i samme husstand som noen som skal testes for koronavirus</label></div>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="checkbox" id="spredning-5" name="spredning[]" value="Bor i samme husstand som noen som har fått påvist koronavirus og ikke er friskmeldt enda"> Bor i samme husstand som noen som har fått påvist koronavirus og ikke er friskmeldt enda</label></div>
        <div class="form-check">
            <label class="form-check-label"><input class="form-check-input" type="radio" id="spredning-6" name="spredning[]" value="Nei"> Nei, ingen av alternativene gjelder for deltakeren</label>
        </div>
    </fieldset>
    <div class="form-group" id="symptomfri-group">
        <div class="form-check">
            <input class="form-check-input" type="checkbox" value="Ja" id="symptomfri" name="symptomfri" required>
            <label class="form-check-label" for="symptomfri">
                Jeg bekrefter at deltakeren er frisk og symptomfri
            </label>
            <div class="invalid-feedback">
                Deltaker med symptomer kan ikke komme på leir uten vurdering av lege. 
            </div>
        </div>
    </div>
    <br>
    <div>
        <button type="submit" class="jsonly btn btn-primary">Send inn</button>
    </div>
</form>
<script>
    Date.prototype.toDateInputValue = (function() {
        var local = new Date(this);
        local.setMinutes(this.getMinutes() - this.getTimezoneOffset());
        return local.toJSON().slice(0,10);
    });
    let picker = document.getElementById('datePicker');
    picker.value = new Date().toDateInputValue();
    if(picker.value < picker.min){
        picker.classList.add("is-invalid");
    }
    (function() {
        'use strict';
        window.addEventListener('load', function() {
            // Fetch all the forms we want to apply custom Bootstrap validation styles to
            var forms = document.getElementsByClassName('needs-validation');
            // Loop over them and prevent submission
            var validation = Array.prototype.filter.call(forms, function(form) {
            form.addEventListener('submit', function(event) {
                if (form.checkValidity() === false) {
                event.preventDefault();
                event.stopPropagation();
                }else{
                    picker.disabled = false;
                }
                form.classList.add('was-validated');
            }, false);
            });
        }, false);
    })();
</script>

{{</rawhtml>}}

