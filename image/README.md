#### Example Code Case
```javascript
case "jomok": {
  let acak = Math.floor(Math.random() * 99) + 1; // acak 1 - 90
  let url = `https://raw.githubusercontent.com/HanX-ID/data/refs/heads/main/image/jomok/${acak}.jpg`;

  conn.sendMessage(m.chat, {
    image: { url },
  }, { quoted: m });
}
break;
```
