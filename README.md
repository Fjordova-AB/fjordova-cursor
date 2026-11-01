# Fjordova för Cursor

Fråga Cursor om din bokföring och låt den föreslå ändringar via Fjordova. Förslag bekräftas enligt företagets bekräftelsenivå. Logga in med ditt eget Fortnox-konto.

Utgivare: Gobrand och Borggren AB (559605-3032). Support: support@fjordova.com.

## System som stöds

Den generella Fjordova-adressen ger i dag åtkomst till **Fortnox**. Spiris är ännu inte tillgängligt via den här adressen.

Du behöver ett Fortnox-konto och åtkomst till det företag och de moduler du vill använda. Tillgängliga verktyg beror på företagets valda moduler, licenser och dina Fortnox-behörigheter. Läs varje ändringsförslag innan du bekräftar det.

## Anslut

[Lägg till Fjordova i Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=Fjordova&config=eyJ1cmwiOiJodHRwczovL21jcC5mam9yZG92YS5haS9tY3AifQ%3D%3D)

Länken lägger till konfigurationen för Fjordovas MCP-server. Följ OAuth-inloggningen och välj rätt Fortnox-företag. Paketet innehåller ingen API-nyckel eller statisk klienthemlighet.

MCP-server: `https://mcp.fjordova.ai/mcp`

Har du redan en anslutning till `https://mcp.fjordova.ai/fortnox/mcp` behöver du göra en ny OAuth-anslutning för den generella adressen. Enbart ett URL-byte flyttar inte det tidigare samtycket. Kontrollera att den nya anslutningen fungerar innan du tar bort den gamla.

För lokal utvärdering av pluginet: kopiera hela repot till `~/.cursor/plugins/local/fjordova.ai`, ladda om Cursor och öppna Customize. Organisationens inställningar kan begränsa lokala pluginer. Se [Cursors instruktioner](https://cursor.com/docs/plugins#test-plugins-locally).

## Verifieringsstatus

Installation i Cursor, OAuth-inloggning och verktygsanrop behöver verifieras med den generella adressen. Tidigare prov med Fortnox-adressen verifierar inte den här anslutningen. Repot innebär ingen bekräftad listning i Cursor Marketplace.

## Länkar

- [Webbplats](https://fjordova.ai)
- [Anslutning och support](https://fjordova.ai/koppla)
- [Integritetspolicy](https://fjordova.ai/integritetspolicy)
- [Tjänstevillkor](https://fjordova.ai/villkor)
- [Personuppgiftsbiträdesavtal](https://fjordova.ai/personuppgiftsbitradesavtal)
