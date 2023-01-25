<script>
	import Quote from "./Quote.svelte";
</script>

<h3 class="text-2xl font-bold mb-4">Erfaring fra frivilligheten:</h3>

<Quote 
    name="Morten Skjæveland"
    title="Kommunikasjonsrådgiver"
    organization="Frivillighet Norge"
    avatar="https://avatars.githubusercontent.com/u/1162160?v=4"
    logo="images/fn-logo.svg"
    email="mortens@frivillighetnorge.no"
>
    Daniel har høy <mark>integritet</mark> og kompetanse. Jeg kan på det varmeste anbefale hans tjenester.
</Quote>

<Quote 
    name="Birgitte Heneide"
    title="Senior kommunikasjonsrådgiver"
    organization="Frivillig.no"
    avatar="https://avatars.githubusercontent.com/u/1162160?v=4"
    email="birgitteh@frivillighetnorge.no"
    logo="images/frivillig-logo.svg"
>
    Helst skulle jeg hatt Daniel med på alle prosjekter. <mark>Når han er med, så sover jeg lettere</mark>.
</Quote>

<Quote 
    name="Eivind Mølster"
    title="Leder for Digital Innovasjon"
    organization="Posten Norge"
    avatar="https://avatars.githubusercontent.com/u/1162160?v=4"
    logo="images/Posten-Norge-Logo.svg"
    email="mortens@frivillighetnorge.no"
>
    Fantastisk <mark>evne til å sette seg inn i nye problemstillinger</mark> og levere stor verdi på kort tid
</Quote>

<Quote 
    name="Linn Tomasdotter"
    title="Co-founder"
    organization="Kobler"
    avatar="https://avatars.githubusercontent.com/u/1162160?v=4"
    email="linn_tomasdotter@hotmail.com"
    logo="images/kobler-logo.svg"
>
    Det var en glede å jobbe med Daniel som er <mark>såååå dyktig på sitt område</mark> og samtidig klarer å styre to sterke personligheter midt i et prosjekt som betyr enormt for begge.

    <img
        slot="logo"
        src={"images/kobler-logo.svg"}
        alt={"Kobler"}
        class="h-7 w-fit mt-1"
    />
</Quote>

<Quote 
    name="Ove Kenneth Nodland"
    title="Co-founder"
    organization="Kobler"
    avatar="https://avatars.githubusercontent.com/u/1162160?v=4"
    email="ovekenneth@gmail.com"
>
    Kan som tidligere kunde bare lovprise Daniel Jackson som  <mark>kombinerer det beste fra design med det beste fra programmering</mark>. Hjalp oss innse at teknologien vi trodde vi ønsket ikke passet det reelle behovet. Verdifullt!
    
    <img
        slot="logo"
        src={"images/kobler-logo.svg"}
        alt={"Kobler"}
        class="h-7 w-fit mt-1"
    />
</Quote>


<p>Morten, Frivillighet Norge</p>
<p>Bjørn, Frivillighet Norge</p>
<p>Ida Marie, Frivillighet Norge</p>
<p>Birgitte, Frivillig.no</p>
<p>Martine, generalsekretær LNU</p>
<p>Kim K., prosjektleder LNU</p>
<p>Leieboerforeningen</p>
<p>Kobler</p>
<p>Samla</p>
