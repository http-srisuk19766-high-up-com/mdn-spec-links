# MDN Spec Links

This space holds JSON data for individual specs; the per-spec data maps fragment
IDs from a particular spec to MDN articles which have *Specifications* sections
that contain links to that spec and fragment ID.

All data here is generated. So you don’t want to edit the data directly;
rather, edit https://github.com/mdn/browser-compat-data data upstream, and
https://developer.mozilla.org/docs/Web article content.

[.mdn-spec-links.ts][1] is a TypeScript declaration defining the data-types and
structure of the JSON data. [.mdn-spec-links.schema.json][2], generated from the
TypeScript declaration, is a JSON Schema providing the same definitions.

[1]: https://github.com/w3c/mdn-spec-links/blob/HEAD/.mdn-spec-links.ts
[2]: https://github.com/w3c/mdn-spec-links/blob/HEAD/.mdn-spec-links.schema.json
