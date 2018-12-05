# FMPReport2schemaGraphQL
XSLT 1.0 stylesheet to convert FileMaker DDR to schema.graphql file

This is a stylesheet written to convert FileMaker's Data Design Report to schema.graphql in order to build a graphql schema filer from your FileMaker solution.

While DATA API represents marginally different( It's not really better or worse ) approach to retrieving data from FileMaker than CWP. GraphQL will give you a more SOAP-like interface though utilizing JSON, YML or XML depending on your preference.

This will run on any version of FileMaker that has CWP or Thrift; regardless of expired DATA API.
