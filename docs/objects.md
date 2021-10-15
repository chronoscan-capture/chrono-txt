# Objects

This objects gives access to objects that allows to do main tasks in ChronoScan.

To start using this API, a client will usually create a CSAClient object.

## Automation objects

### Command Line interface (ChronoCMD)

|Object|Description|
|---|---|
|[ChronoCMD](./ChronoCMD)|Command line access to API functions|

### API Main objects

|Object|Description|
|---|---|
|[CSAClient](./objects/CSAClient)|Give access to a ChronoScan client configuration|
|[CSAJob](./objects/CSAJob)|The job object contain user fields, document types and working parameters|
|[CSABatch](./objects/CSABatch)|This object gives access to a job batch, a "Batch" is a set of documents in ChronoScan|
|[CSADocument](./objects/CSADocument)|Control a Document object in a batch|
|[CSADocumentType](./objects/CSADocumentType)|Document type definition in a job|
|[CSATrigger](./objects/CSATrigger)|Trigger object definition|
|[CSAPage](./objects/CSAPage)|Control a Page in a document|

### Data definition objects

|Object|Description|
|---|---|
|[CSAUserField](./objects/CSAUserField)|User field definition in a job|

### Text&Data extraction objects

|Object|Description|
|---|---|
|[CSABarcode](./objects/CSABarcode)|Barcode object|
|[CSAHOCRParser](./objects/CSAHOCRParser)|Access to OCR data of a CSAPage|
|[CSAPageFullTextBlock](./objects/CSAPageFullTextBlock)|Block of text object in a page|
|[CSAPageFullTextLine](./objects/CSAPageFullTextLine)|Line in a block of text object|


