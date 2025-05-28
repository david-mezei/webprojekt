# Utazás az időben - Oldtimer blog
A weboldalra látogató egy Oldtimer Blogon találja magát, ahol jelenleg három bejegyzés olvasható.

## Funkciók: 
- blogbejegyzések megtekintése, 
- értékelése csillagokkal,
- blogbejegyzésekben képek animálva jelennek meg (Animate on Scroll library)
- kapcsolat oldalon működő email küldő űrlap
- shoelace-css különböző elemeit felhasználtam

## Kódrészlet
```html
<sl-card class="card-overview">
    <img src="imgs/jaguar_e_type_hero.jpg" alt="Jaguar E-Type" slot="image">
        <p>A brit elegancia csúcsa: A Jaguar E-Type</p><br>
            A '60-as évek egyik legszebb sportautója...
        <div slot="footer">
            <sl-button variant="warning" pill href="jaguar-e-type-elegancia.html">Olvasd el</sl-button>
            <sl-rating value="5"></sl-rating>
        </div>
</sl-card>
```

*Kártya elem a blogbejegyzésnek*

```html
<img src="imgs/mustang_engine.jpg" alt="Ford Mustang 289 V8 motor" class="article-image" data-aos="fade-left">
<p class="image-caption">A Ford Mustang 289 köbhüvelykes V8-as motorja</p>
```

*Kép elhelyezés a blogjelegyzésben*

```css
.hero-bar {
    background-image: url(imgs/hero_section.jpg);
    background-size: cover;
    background-position: center;
    color: white;
    padding: 100px 20px;
    text-align: center;
    position: relative;
}
```

*Hero css beállításai*

