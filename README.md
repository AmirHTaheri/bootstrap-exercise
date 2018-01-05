# CSS-ramverk - övning

#### Länkar

* [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
* [Bootstrap Cheat Sheet](https://hackerthemes.com/bootstrap-cheatsheet/)
* [What's new in Bootstrap 4](https://medium.com/wdstack/bootstrap-4-whats-new-visual-guide-c84dd81d8387#.k82cw8n3e)

## Övning del 1

I detta repository finns en färdig sida gjord med Bootstrap. Du ska försöka återskapa hemsidan i detta repo med hjälp av Bootstrap **utan att kolla på källkoden i `index.html`**. Header-elementet får dock se annorlunda ut eftersom det är det enda som inte är helt enligt bootstrap, css-en för headern ligger i `css/main.css`.

Om du fastnar får du titta på koden för att få hjälp använd annars _länkarna_ i början på denna README. Sidan **ska vara responsiv** med hjälp av `column`-klasserna som följer med _Bootstrap_:

* `col-xs-*`
* `col-sm-*`
* `col-md-*`
* `col-lg-*`
* `col-xl-*`

Alla `columns` ska adderas till **12** (12 column grid). För att göra två kolumner på en _Desktop_ gör man alltså följande (`lg/xl`: 996px/1200px):

```html
<div class="container">
    <div class="row">
        <!-- col == column, lg == large screen, 6 == 50% of row -->
        <div class="col-lg-6">
            <!--Content goes here -->
        </div>
        <div class="col-lg-6">
            <!--Content goes here -->
        </div>
    </div>
</div>
```

_`container` är som en wrapper-klass där våra `rows` ska ligga. Den är en av Bootstraps egna klasser._

**Om du vill ha flex på `container` så måste du även lägga till klassen `d-flex`. Det behövs inte på rows men här behövs det.**

## Övning del 2 - Jämföra ramverk

* [CSS-Frameworks | Lista över CSS-ramverk](http://www.cssreflex.com/css-frameworks/)

Du ska nu välja ett annat CSS-ramverk som **inte är Bootstrap, och återskapa sidan**.

Här får du lite friare tyglar eftersom många ramverk inte har lika många inbyggda klasser att använda. Fokus ska ligga på responsiviteten, att hemsidan ska fungera på mobil och desktop. _Om du har använt någon av CSS-ramverken tidigare, ta något ramverk du inte har använt tidigare._

Några populära CSS-ramverk är: _Foundation_, _Pure_, _Skeleton_ och _Materialize_, _Bulma_, _Tailwind_.

Fundera kring följande frågor när du jämför och väljer ett ramverk, du ska kunna motivera ditt val av ramverk.

* Varför finns det så många ramverk? Varför skulle vi inte vilja använda Bootstrap t.ex.?
* Vad är de största skillnaderna mellan de olika ramverken?
* Vad har ramverken gemensamt? Vilka är de gemensamma komponenterna? 
* Vilka motiveringar kan du hitta för att **inte** använda ett ramverk?
* Fundera kring hur pass _opinionated_ ramverken är. Är allting väldigt strikt upplagt med tydliga instruktioner för användning eller kan man enkelt lägga in egen `css`?


