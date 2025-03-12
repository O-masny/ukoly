1. Co je JavaScript?
JavaScript je programovací jazyk, který se používá k oživení webových stránek. Umožňuje vytvářet interaktivní prvky, jako jsou tlačítka, formuláře, animace a další dynamické prvky.

2. Jak přidat JavaScript na web?
JavaScript lze přidat třemi způsoby:

Interní skript – kód se píše přímo do HTML souboru uvnitř značky <script>.

Externí soubor – JavaScript se uloží do samostatného .js souboru a připojí k HTML pomocí <script src="soubor.js"></script>.

Inline skript – 
JavaScript je napsán přímo do HTML atributu, například onclick="alert('Ahoj!')".

3. Základní příkaz: Výpis do konzole
Použijte console.log('Ahoj světe!'); k výpisu textu do konzole prohlížeče.

4. Proměnné v JavaScriptu
V JavaScriptu existují tři způsoby, jak deklarovat proměnné:

var – starší způsob, který se dnes již méně používá.

let – moderní způsob deklarace proměnných.

const – používá se pro hodnoty, které se nemění.

Příklad:

let jmeno = 'Petr';
const vek = 25;
console.log(jmeno, vek);

5. Základní operace
JavaScript podporuje matematické operace:

let a = 10;
let b = 5;
console.log(a + b); // 15
console.log(a - b); // 5
console.log(a * b); // 50
console.log(a / b); // 2

6. Funkce
Funkce umožňují opakovaně používat kód.

function pozdrav(jmeno) {
    return 'Ahoj, ' + jmeno + '!';
}
console.log(pozdrav('Pavel'));

7. Události v JavaScriptu
JavaScript umožňuje reagovat na akce uživatele, například kliknutí na tlačítko.

<button onclick="alert('Klikl jsi na tlačítko!')">Klikni na mě</button>

Úkoly:

Otevřete si konzoli prohlížeče a zkuste spustit příkaz console.log('Hello World!').

Vytvořte proměnné jmeno a vek a vypište je do konzole.

Napište funkci, která vypočítá součet dvou čísel a zobrazí výsledek.

Přidejte tlačítko na webovou stránku a pomocí JavaScriptu zajistěte, že po kliknutí zobrazí zprávu.

Bonus:

Vytvořte jednoduchý skript, který po načtení stránky zobrazí uživateli uvítací zprávu pomocí alert().