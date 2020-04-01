# Sub-Namespace for DataSpecificationTemplates according to IEC 61360 
(Release 2.0 of the AAS Metamodel)

see [Details of the Asset Administration Shell - Part 1 - Version 2.0]() Section 4.8.2 :

## Predefined Templates for Property and Value Descriptions
Conformant to the rules in Clause 5.2.2 the following data specification template should be referenced via the id
"http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0" (in hasDataSpecification/dataSpecification).


## todo


*`<AAS Unique Concept Identifier>`* ::= (`<Namespace>` | `<Namespace Qualifier>`)"/"`<AAS Concept Identifier>`


`<Namespace>` ::= ( `<AAS Namespace>`|`<Data Specification Namespace>` )


`<AAS Namespace>` ::= `<Shell-Namespace>`"/aas/"`<Version>`

`<Data Specification Namespace>` ::=`<Shell-Namespace>`"/DataSpecifications/"`<idShort of Data Specification>`/`<Version>`

`<Shell-Namespace>` ::= "http://admin-shell.io/"

`<Version>` ::= `<Digit>`/`<Digit>`

`<Digit>` ::= 1 | 2 | 3 | 4 | 5 | 6 | …

`<Namespace Qualifier>` ::= `<AAS Namespace Qualifier>`| Data Specification Qualifier>`

`<AAS Namespace Qualifier>` ::= "AAS:"

`<Data Specification Qualifier>` ::= defined per Data Specification

`<AAS Concept Identifier>` ::= `<AAS Class Name>`[(`<AAS Attribute>`|`<AAS Enumeration>`)]

`<AAS Attribute>` ::= "/"`<AAS Attribute Name>`[{"/"`<AAS Attribute Name>`}*]

`<AAS Enumeration>` ::= [{"/"`<AAS Attribute Name>`}*]"/"`<AAS Enumeration Value>`


## DataSpecificationIEC61360


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360) - The DataSpecificationIEC61360, a subclass of aas:DataSpecificationContent, as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/dataType


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/dataType](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/dataType) - The `dataType` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/definition


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/definition](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/definition) - The `definition` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/levelType


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/levelType](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/levelType) - The `levelType` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/preferredName


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/preferredName](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/preferredName) - The `preferredName` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/shortName


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/shortName](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/shortName) - The `shortName` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/sourceOfDefinition


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/sourceOfDefinition](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/sourceOfDefinition) - The `sourceOfDefinition` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/symbol


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/symbol](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/symbol) - The `symbol` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/unit


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/unit](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/unit) - The `unit` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/unitId


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/unitId](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/unitId) - The `unitId` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/value


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/value](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/value) - The `value` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/valueFormat:


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueFormat](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueFormat) - The `valueFormat` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/valueId


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueId](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueId) - The `valueId` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataSpecificationIEC61360/valueList


[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueList](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataSpecificationIEC61360/valueList) - The `valueList` attribute of the class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## DataTypeIEC61360
 Enumeration of all IEC 61360 defined data types.

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360) The DataTypeIEC61360 class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE) The DataTypeIEC61360 BOOLEAN_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/DATE_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/DATE_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/DATE_IEC6360_DATATYPE) The DataTypeIEC61360 DATE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE) The DataTypeIEC61360 RATIONAL_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE) The DataTypeIEC61360 RATIONAL_MEASURE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_COUNT_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_CURRENCY_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_MEASURE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/STRING_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/STRING_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/STRING_IEC6360_DATATYPE) The DataTypeIEC61360 STRING_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE) The DataTypeIEC61360 STRING_TRANSLATABLE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE) The DataTypeIEC61360 TIMESTAMP_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/TIME_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/TIME_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/TIME_IEC6360_DATATYPE) The DataTypeIEC61360 TIME_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0

## DataTypeIEC61360/URL_IEC6360_DATATYPE
 

 [http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/URL_IEC6360_DATATYPE](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DataTypeIEC61360/URL_IEC6360_DATATYPE) The DataTypeIEC61360 URL_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0


## ValueList
A set of value reference pairs.

[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueList](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/DValueList) - The ValueList class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## ValueList/valueReferencePairType
A pair of a value together with its global unique id.

[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueList/valueReferencePairType](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueList/valueReferencePairType) - The `valueReferencePairType` attribute of the class ValueList class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.



## ValueReferencePair
A value reference pair within a value list. Each value has a global unique id defining its semantic.

[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair) - The ValueReferencePair class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.


## ValueReferencePair/value
the value of the referenced concept definition of the value in valueId.

[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair/value](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair/value) - The `value` attribute of the ValueReferencePair class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.


## ValueReferencePair/valueId
Global unique id of the value.

[http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair/valueId](http://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/2/0/ValueReferencePair/valueId) - The `valueId` attribute of the ValueReferencePair class DataSpecificationIEC61360 class as defined in `Details of the Asset Administration Shell - Part 1 - Version 2.0`.


