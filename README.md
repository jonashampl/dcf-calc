# DCF Kalkulačka

Průvodce výpočtem vnitřní hodnoty akcie metodou diskontovaného cash flow (DCF). Kalkulačka tě provede osmi kroky: klikneš do vzorce, napíšeš číslo a Enter tě posune dál. Je určená pro začátečníky i zkušené investory.

## Spuštění

Stačí otevřít `index.html` v prohlížeči. Nic se neinstaluje. Export do PDF potřebuje připojení k internetu, protože si stahuje pomocné knihovny z cdnjs.cloudflare.com. Ostatní funguje i offline.

## Co umí

- Výpočet volného cash flow firmy (FCFF) dvěma cestami: z výkazu peněžních toků (CFO + úroky × (1 − t) − CapEx) nebo od tržeb přes marži, daně, investice a pracovní kapitál.
- Projekci na 3 až 20 let se stálým, postupně zpomalujícím nebo vlastním růstem pro každý rok.
- Diskontní sazbu přes CAPM a WACC, nebo vlastní požadovanou návratnost.
- Terminální hodnotu z normalizovaného roku N+1 (Gordonův model) nebo přes násobek při prodeji.
- Přepočet na akcii včetně přebytečné hotovosti, menšinových podílů a zředění.
- Verdikt se dvěma závěry: o kolik je cena pod nebo nad hodnotou a jestli splňuje požadovanou bezpečnostní marži.
- Scénáře pesimistický, základní a optimistický s relativními váhami a kontrolou výsledných parametrů.
- Nápovědu ke každému vstupu: co znamená, kde ho najdeš ve výkazech a jestli jde o údaj, nebo odhad.
- Ukládání analýz, zálohu a obnovu přes JSON a export do CSV a PDF.
- Češtinu a angličtinu, tmavý a světlý režim.

## Omezení

- Model je určený pro běžné nefinanční firmy. Pro banky, pojišťovny a úvěrové firmy cenu nepočítá, protože u nich FCFF a WACC nedávají smysl.
- Výsledek je jen tak dobrý jako zadané předpoklady. Kalkulačka slouží ke vzdělávání a k vlastním odhadům, nejde o investiční doporučení.

## Soubory

- `index.html` – celá kalkulačka v jednom souboru
- `logo.svg` – logo, barvu přebírá z okolního textu
- `logo dcf kalk.pdf`, `logo dcf kalk.vectorcraft` – zdrojové soubory loga
