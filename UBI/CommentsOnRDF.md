Comments on contents of RDF file
======================================

Superflous rdf:about
-----------------------

Following statement generates superflous triple:

```
<ieee1451:NCAP rdf:about="http://iml.ubi.pt/2022/ieee1451/#NCAP">
```

as it says that `http://iml.ubi.pt/2022/ieee1451/#NCAP` is a `http://iml.ubi.pt/2022/ieee1451/#NCAP`.


Generated Triples
-------------------

The RDF generates the following triples:

```
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#NCAP>
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#BlockManufactureID>	"0"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#BlockModelNumber>	"UBIBlock_1"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#BlockSoftwareVersion>	"sv001"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#NCAPManufactureID>	"INTERPOP 2023"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#NCAPModelNumber>	"0.3"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#NCAPSerialNumber>	"6"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#NCAPOSVersion>	"0.5"
_:tim1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#TIM>
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#timId>	"1"
_:metateds1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#MetaTEDS>
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#TEDSLength>	"59"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#tedsID>	"1"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#UUID>	"91B3501A6905F982DA79"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#oHoldOff>	"1"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#sHoldOff>	"1"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#testTime>	"1"
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#MaxChan>	"1"
_:n4dd21f8c-e60e-4447-9e74-1fa87227f0ad	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#grpType>
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#cGroup>	_:n4dd21f8c-e60e-4447-9e74-1fa87227f0ad
_:na650bad9-5c29-4d56-87fc-ec8ce273cd89	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#memList>
_:metateds1	<http://iml.ubi.pt/2022/ieee1451/#cGroup>	_:na650bad9-5c29-4d56-87fc-ec8ce273cd89
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#hasMetaTEDS>	_:metateds1
_:transducerteds1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#TransducerChannelTEDS>
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#TEDSLength>	"99"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#tedsID>	"3"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#calKey>	"0"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#chanType>	"0"
_:phyunits1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#PhyUnits>
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#unitType>	"1"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#radians>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#sterRad>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#meters>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#kilogram>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#seconds>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#amperes>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#kelvins>	"129"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#moles>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#candelas>	"128"
_:phyunits1	<http://iml.ubi.pt/2022/ieee1451/#unitsExt>	"3"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#hasPhyUnits>	_:phyunits1
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#lowLimit>	"233.15"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#hiLimit>	"398.15"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#oError>	"1"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#selfTest>	"0"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#mRange>	"0"
_:sample1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#Sample>
_:sample1	<http://iml.ubi.pt/2022/ieee1451/#datModel>	"0"
_:sample1	<http://iml.ubi.pt/2022/ieee1451/#modLenth>	"0"
_:sample1	<http://iml.ubi.pt/2022/ieee1451/#sigBits>	"0"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#hasSample>	_:sample1
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#updateT>	"2"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#rSetupT>	"1"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#sPeriod>	"10"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#warmUpT>	"1"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#rDelayT>	"1"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#testTime>	"2"
_:sampling1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#Sampling>
_:sampling1	<http://iml.ubi.pt/2022/ieee1451/#sampMode>	"0"
_:transducerteds1	<http://iml.ubi.pt/2022/ieee1451/#hasSampling>	_:sampling1
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#hasTransducerChannelTEDS>	_:transducerteds1
_:userstransducernameteds1	<http://www.w3.org/1999/02/22-rdf-syntax-ns#type>	<http://iml.ubi.pt/2022/ieee1451/#UsersTransducerNameTEDS>
_:userstransducernameteds1	<http://iml.ubi.pt/2022/ieee1451/#TEDSLength>	"29"
_:userstransducernameteds1	<http://iml.ubi.pt/2022/ieee1451/#tedsID>	"12"
_:userstransducernameteds1	<http://iml.ubi.pt/2022/ieee1451/#format>	"0"
_:userstransducernameteds1	<http://iml.ubi.pt/2022/ieee1451/#tCName>	"Temperature"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#hasUsersTransducerNameTEDS>	_:userstransducernameteds1
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#TEDSLength>	"20"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#tedsID>	"13"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#radioType>	"4"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxBPS>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxCDev>	"10"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxRDev>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#encryption>	"0"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#authent>	"0"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#minKeyL>	"0"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxKeyL>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxSDU>	"10"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#minALat>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxTLat>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxXAct>	"1"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#batery>	"0"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#radio>	"0"
_:tim1	<http://iml.ubi.pt/2022/ieee1451/#maxRetry>	"2"
<http://iml.ubi.pt/2022/ieee1451/#NCAP>	<http://iml.ubi.pt/2022/ieee1451/#hasTIM>	_:tim1
```

Use of blank nodes for TIMs
------------------------------

Use of Blank Nodes in RDF does not allow for addressing TIMs individually. The TIMS are
physical objects (right?) that should be adressable using linked data directly. As blank
nodes they are only addressable in a specific context (as the RDF document itself).


On identity of NCAP
-----------------------

The RDF document begins with defining `http://iml.ubi.pt/2022/ieee1451/#NCAP`. Is this
assumed to be an example identity? Or are all NCAPs reporting the same URI?


Use of xml:base
------------------

Use of xml:base should be used, esp. since document is not retrieved using HTTP GET (where
base URI is implicit). By using xml:base in all such RDF documents, you avoid any concerns
of genering documents that are not well-defined.

has-properties
-----------------

### ieee1451:hasTIM

The name of predicate `ieee1451:hasTIM` is counter-intuitive. Sounds like a Boolean property,
but is a collection of TIM blank node objects. Name Suggestion: `ieee1451:TIMs`.

### ieee1451:hasUsersTransducerNameTEDS

The name of predicate `ieee1451:hasUsersTransducerNameTEDS` is counter-intuitive. Sounds like a Boolean property,
but is a collection of User Transducer Name TED blank node objects. Name Suggestion: `ieee1451:UsersTransducerNameTEDS`.

### ieee1451:hasTransducerChannelTEDS

The name of predicate `ieee1451:hasTransducerChannelTEDS` is counter-intuitive. Sounds like a Boolean property,
but is a collection of Transducer Channel TED blank node objects. Name Suggestion: `ieee1451:TransducerChannelTEDS`.

### ieee1451:hasMetaTEDS

The name of predicate `ieee1451:hasMetaTEDS` is counter-intuitive. Sounds like a Boolean property,
but is a collection of Meta TED blank node objects. Name Suggestion: `ieee1451:MetaTEDS`.

