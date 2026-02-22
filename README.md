# SCB_API_VardefullaDatamangder

# ============================================================================
# SCB API FÖRETAGSDATAHÄMTARE - VERSION 2.5
# ============================================================================
#
# SYFTE:
#   Hämta företagsdata från SCB:s (Statistiska centralbyråns) API med ett
#   grafiskt användargränssnitt. Användaren kan filtrera på bransch (SNI),
#   juridisk form, omsättning, antal anställda och geografiskt område (län).
#
# FUNKTIONALITET:
#   - Ansluter till SCB:s API med certifikatautentisering
#   - Hämtar dynamiskt filteralternativ från API:et
#   - Räknar träffar per län innan hämtning
#   - Hämtar data med automatisk uppdelning om >2000 träffar
#   - Exporterar resultat till CSV-fil
#
# KRAV:
#   - PowerShell 5.1 eller senare
#   - SCB-certifikat installerat i Cert:\CurrentUser\My
#   - Nätverksåtkomst till https://privateapi.scb.se
#
# VERSIONHISTORIK:
#   v2.4 - Loggning för varje kommun, tydliga kommentarer
#   v2.3 - Ny GUI-layout,Details-egenskap fixad
#   v2.2 - Fixat variabler som arrays, 'Details' property
#   v2.1 - Items.Add fix, GUI-layout förbättrad
#   v2.0 - Dynamisk kategoriinläsning från API
#
# DATUM: 2025-02-21
# ============================================================================
# FÖRFATTARE: [DentronIQ AB](https://www.dentroniq.se) Dev: Dennis Hedberg
# ============================================================================
