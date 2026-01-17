# css-theorie-oefening1
# Oefening 2.0 – CSS Syntax & Selectors

## Concept

In deze oefening leer je de **basis van CSS syntax** en hoe je CSS koppelt aan een HTML-bestand.  
Je past eenvoudige stijlen aan en leert werken met **element selectors**, **class selectors** en **commentaar in CSS**.

De focus ligt op:
- correct schrijven van CSS
- begrijpen wat elke selector doet

---

## Commitrichtlijnen

Elke wijziging of toevoeging hoort bij deze oefening.

Gebruik duidelijke commitboodschappen volgens dit patroon:

**Voorbeeld commit messages:**
CSS-2.0-01: HTML bestand aangemaakt
CSS-2.0-02: CSS bestand toegevoegd
CSS-2.0-03: Basis styling toegepast
CSS-2.0-04: CSS selectors aangepast


---

## Algemene instructies

- Werk in **één map**
- Gebruik **twee bestanden**:
  - `index.html`
  - `style.css`
- Koppel het CSS-bestand via een `<link>` in de `<head>`
- Gebruik **geen inline CSS**
- Schrijf **commentaar boven elke CSS selector**

---

## Bestanden

### index.html

Maak in de map het volgende HTML-bestand aan:

```html
<!doctype html>
<html lang="nl">
  <head>
    <meta charset="UTF-8" />
    <title>CSS Syntax Oefening</title>
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <h1>Welkom!</h1>
    <p>Dit is een paragraaf.</p>
    <p class="highlight">Deze paragraaf moet opvallen.</p>
  </body>
</html>
```
style.css

Maak in dezelfde map het volgende CSS-bestand aan:
```/* style.css */
h1 {
  color: darkblue;
  text-align: center;
}

p {
  font-size: 16px;
  color: black;
}

.highlight {
  background-color: yellow;
  font-weight: bold;
}
```
## Opdracht

- Pas de kleur van de `<h1>` aan naar rood
- Maak alle `<p>`-elementen cursief
- Voeg een rand toe aan `.highlight`
- Voeg commentaar toe boven elke selector


## Verwachte aanpak

- Gebruik enkel basis CSS
- Pas bestaande regels aan waar mogelijk
- Voeg nieuwe regels toe waar nodig
- Hou je CSS overzichtelijk en leesbaar

---

## Checklist

- [ ] HTML en CSS staan in dezelfde map
- [ ] CSS-bestand is correct gekoppeld
- [ ] `<h1>` is rood
- [ ] Alle paragrafen zijn cursief
- [ ] `.highlight` heeft een rand
- [ ] Elke selector heeft een commentaar erboven
- [ ] Geen inline CSS gebruikt

---

## Geschatte tijd

**15 – 20 minuten**

---

## Veel succes! 🎉

Deze oefening vormt de basis voor:

- complexere selectors
- layout met CSS
- flexbox en positionering
