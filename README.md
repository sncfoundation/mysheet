<p align="center">
  <img src="https://sncfoundation.github.io/logos/mysheet.svg" width="96" alt="MySheet logo">
</p>

<h1 align="center">MySheet</h1>

<p align="center"><b>The relational store, MySQL flavour — simple, ubiquitous, on a tab.</b><br>
A <a href="https://sncfoundation.github.io">Sheet-Native Computing Foundation</a> project · the spreadsheet-native <b>MySQL / MariaDB</b></p>

---

**Status:** 📝 Unsaved Draft &#183; **design only**. Data & Storage TAG. This repository holds the design below and no code, no release, no reconcile loop. Implementation is tracked in [sncfoundation/sheeternetes#50](https://github.com/sncfoundation/sheeternetes/issues/50). Until then the Sheet is merely a spreadsheet, which we admit is embarrassing.

## The mapping

- Same tabs-as-tables model as Sheetgres, `QUERY()` for SQL; positioned as the lightweight/compatible SQL engine.
- Speaks the MySQL dialect via the SheetWire gateway so `mysql` clients connect.

## Honest limit

Same honest gaps as any Sheet-SQL: no ACID transactions, weak JOINs, capped scale.

## Connect with real clients

Once [SheetWire](https://github.com/sncfoundation/sheetwire) exists, real MySQL / MariaDB clients will be able to connect to a Google Sheet over the native wire protocol. Both halves are design-only for now.

- 🗺️ [SNCF Landscape](https://sncfoundation.github.io/landscape.html) · 🧩 [Projects](https://sncfoundation.github.io/projects.html) · 🎓 [Certification](https://sncfoundation.github.io/certification.html)

---

<sub>Apache-2.0. Do not run production data on a spreadsheet. If you do, please film the query plan.</sub>
