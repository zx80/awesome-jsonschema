<!-- ATTENTION! This file is auto-generated. Do not edit this file directly.
Instead, edit `data.yaml` and re-generate this file as per the README's
instructions -->

# Awesome JSON Schema [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Join Slack](https://img.shields.io/badge/Slack-Join%20Slack-blue.svg?style=flat-square)](https://json-schema.slack.com)
[![OpenCollective](https://img.shields.io/opencollective/all/json-schema?label=OpenCollective&style=flat-square)](https://opencollective.com/json-schema)

> A curated list of awesome JSON Schema resources, tutorials, tools, and more.

JSON Schema is a JSON-based format to annotate and validate JSON documents with
a vibrant community. JSON Schema is defined by a set of IETF specifications and
it is the industry-standard for defining the structure and meaning of JSON
documents.

## Contributing

If you know of a resource discussing JSON Schema or have created a tool or
website about JSON Schema, [open a GitHub
issue](https://github.com/jviotti/awesome-jsonschema/issues/new?assignees=&labels=awesome-link&template=link.md&title=)
or add it directly to
[`data.yaml`](https://github.com/jviotti/awesome-jsonschema/blob/master/data.yaml)
and send a pull request. The README is auto-generated from `data.yaml`. You can
locally render the README as follows:

```sh
npm install
npm start
```

## Table of Contents

- [Adoption](#adoption)
- [Articles](#articles)
- [Specifications](#specifications)
- [Books](#books)
- [Courses](#courses)
- [Videos](#videos)

## Adoption

*Awesome products and companies that adopted JSON Schema. Did we miss any? [Let
us
know!](https://github.com/jviotti/awesome-jsonschema/issues/new?assignees=&labels=awesome-link&template=link.md&title=)*

- [Amazon EventBridge Schema Registry](https://aws.amazon.com/about-aws/whats-new/2020/09/amazon-eventbridge-schema-registry-announces-support-for-json-schema/) - Amazon EventBridge Schema Registry has support for JSON Schema, allowing customers to validate, annotate, and manipulate JSON documents conforming to JSON Schema Draft 4 specification
- [Assertible](https://assertible.com/json-schema-validation) - Assertible provides a free-to-use API to validate a JSON document against a JSON Schema and a service to test and monitor web services using JSON Schema
- [IBM App Connect](https://www.ibm.com/docs/en/app-connect/11.0.0?topic=schema-json-requirements-message-maps) - The Graphical Data Mapping editor can be used to create and transform JSON messages with the data model defined from a JSON schema
- [KrakenD](https://www.krakend.io/docs/endpoints/json-schema/) - KrakenD endpoints receiving a JSON object in its body can apply automatic validations using the JSON Schema vocabulary before the content passes to the backends
- [MongoDB](https://docs.mongodb.com/manual/reference/operator/query/jsonSchema/) - MongoDB 3.6 and later support JSON Schema for querying data and defining collection constraints
- [MySQL](https://dev.mysql.com/doc/refman/8.0/en/json-validation-functions.html) - MySQL 8.0.17 supports table constraints to validate a JSON document against a JSON Schema

## Articles

- (2020) [An introduction to JSON Schema](https://medium.com/swlh/an-introduction-to-json-schema-8eaea643fcda) - An introduction to JSON Schema covering its history, common keywords and how to use the AJV validator
- (2021) [Introduction to JSON Schema in Java](https://www.baeldung.com/introduction-to-json-schema-in-java) - A short introduction to validating JSON documents with JSON Schema in Java
- (2020) [Azure Pipelines autocomplete in PyCharm, IntelliJ, WebStorm, CLion, and Rider](https://tonybaloney.github.io/posts/azure-pipelines-autocomplete-in-pycharm.html) - Setting up PyCharm, IntelliJ, WebStorm, CLion and Rider to have auto-complete, syntax highlighting and validation support of Azure Pipelines workflows
- (2020) [Building a No-Code JSON Schema Form Builder with ReactJS](https://www.ginkgobioworks.com/2020/10/08/building-a-no-code-json-schema-form-builder/) - An update on the additional features implemented in the react-json-schema-form-builder open-source JSON Schema form builder project
- (2020) [How to Integrate &quot;React JSON Schema Form&quot; into a Redux and Typescript Project](https://www.xtivia.com/blog/how-to-integrate-react-json-schema-form-into-a-redux-and-typescript-project/) - Adding a form using &quot;React JSON Schema Form&quot; and integrating it with Redux and Typescript
- (2020) [JSON Schema Tutorial](https://www.w3resource.com/JSON/JSON-Schema.php) - A tutorial of JSON Schema that discusses validation, documentation and hyperlinking
- (2020) [Using the JSON Schema standard for scientific applications?](https://cerfacs.fr/coop/json-schema-for-sci-apps) - A discussion on how to use JSON Schema to validate input, add precise documentation, auto-fill missing parts, and create graphical user interfaces in the context of scientific applications
- (2020) [Validating and documenting JSON with JSON Schema](https://www.mscharhag.com/api-design/json-schema) - Introduce JSON Schema by example by showing an annotated JSON Schema that validates an example document
- (2019) [PHP With MySQL](https://elephantdolphin.blogspot.com/2019/07/json-schema-validation-with-mysql-8017.html) - A practical tutorial on expressing JSON Schema table constraints on MySQL
- (2019) [REST API Tutorial: JSON Schema](https://restfulapi.net/json-schema/) - An short introduction to JSON Schema validation
- (2019) [Saved by the Schema: Using JSON Schema to Document, Test, and Debug APIs](https://blog.heroku.com/json-schema-document-debug-apis) - Learn how Heroku uses JSON Schema to test and document their Platform API, and how it helped them uncover an unexpected bug, rooted in the way the Oj gem parses Big Decimals.
- (2018) [JSON Schema Validation &amp; Expressive Query Syntax in MongoDB 3.6](https://www.sitepoint.com/json-schema-validation-expressive-query-syntax-in-mongodb-3-6/) - An in-depth discussion about using JSON Schema to define collection validation on MongoDB
- (2018) [JSON Schema Validator, Generator &amp; Editor Guide](https://stoplight.io/json-guide/) - How the JSON and JSON Schema standards are defined and how to put them to use in your code and in your APIs
- (2013) [TutorialsPoint: JSON Schema](https://www.tutorialspoint.com/json/json_schema.htm) - A short introduction to JSON Schema Draft4 validation

## Specifications

- (2021) [JSON Schema in RDF](https://www.w3.org/2019/wot/json-schema) - This document introduces an RDF vocabulary for JSON schema definitions. This vocabulary provides a stable namespace IRI for JSON schema keywords, as well as simple axioms, defined against schema.org&#x27;s meta-model. Various examples on how to use the vocabulary are also introduced, e.g. to annotate schemas with JSON-LD metadata or to embed schema annotations inside RDF graphs

## Books

- (2017) [JSON at Work](https://www.oreilly.com/library/view/json-at-work/9781491982389/) - A comprehensive overview of the JSON ecosystem, including JSON Schema
- (2014) [Using JSON Schema](https://books.apple.com/us/book/using-json-schema/id903248630) - Learn and Apply JSON Schema by Example, with Javascript (Node.js) and Python Programs

## Courses

- (2017) [JSON Schema - Crash Course for Beginners](https://www.udemy.com/course/json-schema-crash-course-for-beginners/) - Learn JSON &amp; JSON Schema in a Quick 30-40 minutes &amp; use it for the rest of your life for complex projects
- (2017) [Processing and Interchanging JSON Data](https://www.linkedin.com/learning/processing-and-interchanging-json-data) - An in-depth guide to working with JSON and the JSON ecosystem including using JSON Schema for validation purposes

## Videos

- (2021) [Configuring Umbraco on .NET Core - JSON Schema](https://www.youtube.com/watch?v=rpUg-oySw8g) - Configuring Umbraco on .NET Core with JSON Schema-powered autocompletions for appsettings.json using SchemaStore
- (2021) [JSON Schema Validation in Postman](https://www.youtube.com/watch?v=8BfshV5n6ac) - An tutorial of performing JSON Schema validation in Postman in API tests
- (2020) [What is JSON Schema](https://www.youtube.com/watch?v=kK-_gL7Vsc0) - A basic introduction to JSON Schema showing how to auto-generate JSON Schema document from an existing JSON document
- (2019) [JSON Schema Validation: How to Validate JSON Schema with Postman?](https://www.youtube.com/watch?v=X072eKtOIio) - An introduction to JSON Schema and how to use it in Postman
- (2019) [What is a JSON Schema? Generate, Modify, and Understand a JSON Schema: Example](https://www.youtube.com/watch?v=hGXxXyJmaUo) - An in-depth introduction to JSON Schema including auto-generating JSON Schema documents using QuickType.io

## Tools

- (JavaScript) [chai-json-schema](https://www.chaijs.com/plugins/chai-json-schema/) - Chai plugin with assertions to validate values against JSON Schema v4
- (Rust) [jsonschema](https://docs.rs/jsonschema/0.8.0/jsonschema/) - A crate for performing fast JSON Schema validation. It is fast due to schema compilation into a validation tree, which reduces runtime costs for working with schema parameters

## Credits

Special thanks to [@kinlane](https://github.com/kinlane) for curating the
initial version of this list.
