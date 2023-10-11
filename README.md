# Findkit Demo for Vierityspalkki.fi

Live demo <https://vierityspalkki.findkit.com/>

Codesanbox edit <https://codesandbox.io/s/github/findkit/vierityspalkki-demo/tree/main>

Tässä repositoryssa on kaikki koodi mitä kirjoitettu haun luontiin. Crawlerin konfiguraatio löytyy [findkit.toml](/findkit.toml) -tiedostosta ja
käyttöliittymän koodi [index.html](index.html) -tiedostosta.

Haun voi replikoida luomalla uuden projektin
[hub.findkit.com](https://hub.findkit.com/):ssa, vaihtamalla id:n ja publicTokenin
yllä mainittuihin tiedostoihin ja ajamalla crawlin uudestaan Findkit CLI:llä annetulla
findkit.toml tiedostolla.

```
$ findkit deploy --path findkit.toml
$ findkit crawl start
```
