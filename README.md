# GAIA-X Self-Descriptions

## Description

This repository contains the self-descriptions of the GAIA-X core ontology. As language the [DTDL standard](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md) is used. This standard is based on [JSON-LD](https://www.w3.org/TR/json-ld11/) and offers an easy way to use the DTDL without required knowledge about RDF. Please be aware that the actual self-descriptions are still **under heavy development** and are written in pure JSON-LD/RDF. To overcome these shortcomings we plan to add a mapping layer from our DTDL based models to the actual self-descriptions later on.

### State of the models
At the moment we only offer self-descriptions for the data-asset class. We plan to also offer the other self-descriptions once they are in a more stable state.

### References

If you are interested we also open-sourced our internal services that are used to create and manage these models and their instances.


[Tributech Data-Asset Models](https://github.com/tributech-solutions/data-asset-twin)

[Twin-API](https://github.com/tributech-solutions/tributech-twin-api)

[Catalog-API](https://github.com/tributech-solutions/tributech-catalog-api)

### Disclaimer
If you notice any shortcomings, errors or have general feedback please contact us directly or use the GitHub Issues function.