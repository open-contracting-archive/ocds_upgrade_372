This extension exists to stage the proposal in [#372](https://github.com/open-contracting/standard/issues/372) to deprecate the ```transaction.amount```, ```transaction.providerOrganization``` and ```transaction.receiverOrganization``` fields and replace them with ```transaction.value```, ```transaction.payer``` and ```transaction.payee``` fields to resolve ambiguity and for consistency with terminology elsewhere in the schema.

The extension also updates the reference to "Budget Data Package" in the description of the ```transaction``` block to read "Fiscal Data Package" in line with the discussion in [378](https://github.com/open-contracting/standard/issues/378)

The extension follows the approach to deprecated described in [#401](https://github.com/open-contracting/standard/issues/401)