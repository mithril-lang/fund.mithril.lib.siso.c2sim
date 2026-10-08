# fund.mithril.siso.c2sim

Versioned C2SIM native XML profile plugin: `OpenC2SIM-SMX-LOX-1.0.1`.
Operations: c2sim-import, c2sim-project. Bundled explicit XPath mapping; native source bytes remain preserved.

`python -m pip install -e .` installs the pinned XML/host dependencies and registers the plugin.

Fetch the pinned public schema with `python scripts/fetch-c2sim-schema.py`; pass its manifest to import for XSD1.1 validation.

Projection does not execute military commands or initialize a simulator.
