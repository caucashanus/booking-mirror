09.07.2025

## Google Cloud Service Account Keys (Důležité)

Tento projekt NEOBSAHUJE žádné citlivé Google Cloud klíče. Pro správné fungování je nutné, aby si každý uživatel vytvořil vlastní service account klíče v Google Cloud Console a vložil je do složky `src/accounts/` pod názvy:

- `modrany.json`
- `hagibor.json`
- `kacerov.json`

**Postup:**
1. Přihlašte se do [Google Cloud Console](https://console.cloud.google.com/).
2. Vytvořte nebo najděte příslušný Service Account.
3. Vygenerujte nový klíč (JSON) a stáhněte jej.
4. Přejmenujte soubor podle potřeby (např. `modrany.json`) a vložte jej do `src/accounts/`.
5. Nikdy neukládejte tyto klíče do veřejného repozitáře!

Pro ukázku struktury klíče použijte přiložené `.json` soubory jako šablonu.
