# INSPIRE

The [INSPIRE Regulations 2009](https://www.legislation.gov.uk/uksi/2009/3157/contents) require UK public bodies (central government, local authorities and all other public authorities, as defined in the [Freedom of Information Act 2000](https://www.legislation.gov.uk/ukpga/2000/36/section/3)), to publish data that falls under any of [the 34 INSPIRE themes](https://knowledge-base.inspire.ec.europa.eu/tools/inspire-themes_en).  

Defra is the lead department for the INSPIRE Regulations and enquiries about the legislation should be made to data.governance@defra.gov.uk.

## Publishing INSPIRE metadata
INSPIRE data must be registered on the National Data Library and must be published in the default UK government metadata standard for spatial data, which is [UK GEMINI](https://agiorguk.github.io/gemini/1037-uk-gemini-standard-and-inspire-implementing-rules.html). The INSPIRE knowledge base publishes [data specifications technical guidelines](https://knowledge-base.inspire.ec.europa.eu/data-specifications-technical-guidelines_en) with further details of how to publish data that falls under the INSPIRE themes to ensure interoperability. 

## Harvesting metadata records

Getting your metadata records into the directory is done by [setting up a 'harvester'](../harvest_data). You should run the harvester regularly to ensure that the directory stays in sync when the publisher updates the records.

Occasionally publishers have made the mistake of using an existing record as a template and simply using a text editor to change the key fields. The main problem with this is that you need to generate a new `gmd:fileIdentifier`, or the National Data Library will harvest it and overwrite the record that was the template! To generate a new UUID (universally unique identifier) for this field, just visit <https://www.uuidgenerator.net/>.

*Last updated: 5 Aug 2026*
