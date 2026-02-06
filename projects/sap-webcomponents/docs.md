# SAP Project Documentation Links (UI5 Web Components + OData V4)

> Purpose: A single “source-of-truth map” for this project’s stack: **UI5 Web Components** + **OData V4**.  
> Use these links first when validating APIs, behavior, and examples.

---

## Stack in this project

- UI layer: **UI5 Web Components** (framework-agnostic Web Components) citeturn0search4turn0search1  
- Data/API: **OData V4** services and the OData standard docs for protocol/query semantics citeturn0search8turn0search3

---

## Primary documentation (developer)

### UI5 Web Components (official)

- Main docs site (guides, components, configuration):  
  https://ui5.github.io/webcomponents/ citeturn0search4

- Canonical repository (issues, changelog, source, packages):  
  https://github.com/UI5/webcomponents citeturn0search1

### SAP Design System (design guidelines)

- SAP Web Components overview (design & usage guidance):  
  https://www.sap.com/design-system/fiori-design-web/discover/get-started/web-components-overview citeturn0search14

> Note: The SAP Design System pages are about **design guidelines**; the UI5 Web Components site + GitHub repo are the **developer API** reference. citeturn0search14turn0search4turn0search1

---

## OData V4 (standard)

### OASIS / OData.org

- OData documentation hub (current published references):  
  https://www.odata.org/documentation/ citeturn0search3

- OASIS “Part 1: Protocol” (OData 4.01, normative spec):  
  https://docs.oasis-open.org/odata/odata/v4.01/odata-v4.01-part1-protocol.html citeturn0search8

---

## SAPUI5 OData V4 model docs (only when you use SAPUI5 runtime)

If you are consuming OData V4 via **SAPUI5’s** `sap.ui.model.odata.v4.ODataModel` (even in hybrid setups), these are the authoritative references:

- OData V4 Model (SAP Help):  
  https://help.sap.com/docs/SAPUI5/285985e9cf204697aee91214fc19d95c/5de13cf4dd1f4a3480f7e2eaaee3f5b8.html citeturn0search7

- Samples (Demo Kit):  
  https://sapui5.hana.ondemand.com/#/entity/sap.ui.model.odata.v4.ODataModel/samples citeturn0search10

- Model instantiation & data access (SAP Help):  
  https://help.sap.com/docs/ABAP_PLATFORM_NEW/468a97775123488ab3345a0c48cadd8f/9613f1f2d88747cab21896f7216afdac.html citeturn0search22

- Meta model for OData V4 (SAP Help):  
  https://help.sap.com/docs/ABAP_PLATFORM_BW4HANA/468a97775123488ab3345a0c48cadd8f/7f29fb3ce5964d8090038a9d3cdf5060.html citeturn0search19

---

## Optional / background (good to know)

- SAP Help: Using Web Components in SAPUI5 (integration notes):  
  https://help.sap.com/docs/ABAP_PLATFORM_NEW/468a97775123488ab3345a0c48cadd8f/1c80793df5bb424091954697fc0b2828.html citeturn0search0

---

## “Source of truth” rule for this project

When verifying a claim (API, behavior, limitations), prefer sources in this order:

1. UI5 Web Components docs site + GitHub repo citeturn0search4turn0search1  
2. OASIS/OData standard documents citeturn0search8turn0search3  
3. SAP Help / SAPUI5 Demo Kit (only for SAPUI5 runtime specifics) citeturn0search7turn0search10  
4. Community posts (only as secondary pointers; always re-check against 1–3) citeturn0search9turn0search16

---

## Quick checklist (when answering SAP questions in this project)

- Confirm whether the question is about **UI5 Web Components** or **SAPUI5 runtime** (they’re related, but not the same). citeturn0search4turn0search7  
- For OData semantics (query options, protocol rules) cite the OASIS/OData specs. citeturn0search8  
- For UI components API (properties/events/slots/themes/icons), cite UI5 Web Components docs/GitHub. citeturn0search4turn0search1

