# sg-pupil-attainment-asn
Number of pupils with additional support needs (ASN) who attained a given number of qualifications by level and stage.

This indicator relates to pupils attending publicly funded secondary schools, it does not include: Pupils attending publicly funded Special Schools; Pupils attending private Independent Schools; Pupils educated outwith the school education system (for example at home) or Adults attending publicly funded secondary schools. Pupil Numbers The number of pupils on the roll is taken from the September Scottish School Census for the relevant year, which was carried out through the Scottish Exchange of Educational Data (ScotXed) project.

The year shown relates to that in which the Census was carried out as opposed to that in which the examinations were taken i.e. the year 2008 is the academic year 2008/09.

More information on the ScotXed project is available on http://www.scotxed.net.

A range of information was collected for each individual pupil, including the pupil home postcode. This has been used to generate the number of pupils at various levels of geographical aggregation. Results here do not include the few pupils with a missing or invalid postcode. Therefore, the national figures may not be the same as national figures published elsewhere.

Additional Support Needs (ASN): Pupils identified in the School Census as having either a Co-ordinated Support Plan, a Record of Needs or an Individualised Education Programme are categorised as having Additional Support Needs.

Exam Results Data on National Qualifications are obtained from the Scottish Qualifications Authority (SQA) and are post-appeals. These data are linked to the pupil information from the Census using pupil's Scottish Candidate Numbers. For a negligible number of pupils it is not possible to make this link for a variety of reasons. For more information please see the background notes to the publication 'SQA Attainment and School Leaver Qualifications in Scotland', available here: http://www.scotland.gov.uk/Topics/Statistics/Browse/School-Education/PubAttainment

Statistics provided by Scottish Government:  http://statistics.gov.scot/data/pupil-attainment-asn

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/sg-pupil-attainment-asn.git
```

Install npm dependencies

```
cd sg-pupil-attainment-asn
npm install
```

Run the API (from the sg-pupil-attainment-asn directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
