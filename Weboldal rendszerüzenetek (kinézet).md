# Weboldal rendszerüzenetek (kinézet)

**DEMO: http://bit.ly/1LL9rdV**

Rendszerüzenetek weboldalra, modern kinézettel.

```html
<div id="message" class="info">
  A regisztrációd majdnem kész!
</div>

<div id="message" class="error">
  A művelet nem hajtható végre!
</div>

<div id="message" class="success">
  A művelet sikeresen végrehajtva!
</div>

<div id="message" class="warning">
  Figyelem, valami hiba történt!
</div>
```

CSS:

```css
@import url(http://fonts.googleapis.com/css?family=Roboto+Condensed);

#message {
  padding:13px 13px 13px 43px;
  font-family: 'Roboto Condensed', sans-serif;
  border-radius:8px;
  background-position:5px center;
  margin:10px;
}

#message.info {
  background-color:#3498db;
  background-image:url('http://i.imgur.com/gGDzzyZ.png');
  background-repeat:no-repeat;
  color:#2676ab;  
}

#message.error {
  background-color:#e74c3c;
  background-image:url('http://i.imgur.com/Tuf9nv8.png');
  background-repeat:no-repeat;
  color:#b12c2c;  
}

#message.success {
  background-color:#2ecc71;
  background-image:url('http://i.imgur.com/8Jmzs5p.png');
  background-repeat:no-repeat;
  color:#239a55;  
}

#message.warning {
  background-color:#f1c40f;
  background-image:url('http://i.imgur.com/21BgxGG.png');
  background-repeat:no-repeat;
  color:#e59413;  
}
```

(by AdamS)
