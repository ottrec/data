Do not use the data from this repository directly. See one of the links below.

| Format | Data | Schema | Notes |
| --- | --- | --- | --- |
| JSON (simplified) | <a href="https://data.ottrec.ca/export/latest.json" download="ottrec_simplified_latest.json">data.ottrec.ca/export/latest.json</a> | <a href="https://data.ottrec.ca/export/schema.json" download="ottrec_simplified.schema.json">schema.json</a> | Recommended for most uses, easiest to use. |
| CSV (simplified) | <a href="https://data.ottrec.ca/export/latest.csv.zip" download="ottrec_simplified_latest.csv.zip">data.ottrec.ca/export/latest.csv.zip</a> | <a href="https://data.ottrec.ca/export/schema.csv" download="ottrec_simplified.schema.csv">schema.csv</a> | Recommended for tools which require CSV.
| Protobuf (raw) | <a href="https://data.ottrec.ca/v1/latest/pb" download="ottrec_raw_latest.pb">data.ottrec.ca/v1/latest/pb</a> | <a href="https://data.ottrec.ca/v1/latest/proto" download="ottrec_raw_latest.proto">schema.proto</a> | Best for advanced use cases, least lossy.
| TextPB (raw) | <a href="https://data.ottrec.ca/v1/latest/textpb" download="ottrec_raw_latest.textpb">data.ottrec.ca/v1/latest/textpb</a> | <a href="https://data.ottrec.ca/v1/latest/proto" download="ottrec_raw_latest.proto">schema.proto</a> | Best for manual inspection when testing. |
| JSON (raw) | <a href="https://data.ottrec.ca/v1/latest/json" download="ottrec_raw_latest.json">data.ottrec.ca/v1/latest/json</a> | <a href="https://data.ottrec.ca/v1/latest/proto" download="ottrec_raw_latest.proto">schema.proto</a> | Not recommended. |

I strongly recommend using the simplified data, as it abstracts away changes in the schema, it is much easier to use correctly, and it resolves ambiguity while preserving the raw values where needed.

For more usage information and historical data, see [here](https://data.ottrec.ca).

For technical information about how this data is scraped, see [here](https://github.com/ottrec/scraper).

You can report issues [here](https://github.com/ottrec/scraper/issues).
