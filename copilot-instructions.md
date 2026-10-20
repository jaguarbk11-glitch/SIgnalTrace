# SignalTrace AI contributor guidance

- Preserve evidence provenance: never fabricate facts, URLs, publication dates, reporting periods, calculations, or findings.
- Treat search snippets as discovery leads. A fetched page is not automatic claim verification.
- Keep retrieved source text separate from interpretation, and preserve uncertainty in reports.
- Use sector-specific indicators from `signaltrace/universe.py`; do not apply one formula to every track.
- Every calculation must preserve formula, units, inputs, periods, and source URLs, and reject missing or incomparable inputs.
- Keep network access bounded and failures visible. Do not report a company as researched unless a run was attempted and its source coverage is shown.
- Run `py -m pytest -q` after changes to research logic or calculations.
