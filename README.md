# OtaKopin nettisivut

## Cheat sheet

Tee muutos GitHubiin ja vähän ajan päästä se näkyy nettisivuilla. Tähän voi myös käyttää GitHubin omaa webbi-editoria.

## Miten tää toimii
* Nettisivut tehdään https://jekyllrb.com/ frameworkkiä käyttäen
* Kun muutokset pusketaan GitHubiin, niin GitHub ajaa Jekyll - komennon omilla palvelimillaan, joka tuottaa tarvittavat HTML sivut, jotka se sitten palvelee käyttäjille. Näitä ajoja voi seurata täältä: https://github.com/otakoppi-ry/otakoppi-ry.github.io/actions

## Lokaali devaus
Tätä tarvitsee jos haluaa iteroida nopeasti esimerkiksi tyylejä.
Tarvitset [rubyn](https://www.ruby-lang.org/en/documentation/installation/)
* `gem install bundler`
* `bundle`
* `bundle exec jekyll serve`
