schemays
========

Simple Schemas for YAML (and JSON)


## Description

JSON Schema is the current schema choice for JSON and YAML.

If we're being honest, it requires a lot of input for very little capability.

YAML is everywhere but almost entirely without associated schemas.

SchemaYS wants to solve this for all YAML in all domains.

It uses YS (yamlscript.org) to define schemas that are tight and powerful.


## Usage

See the examples here for a simple JSON Schema converted to SchemaYS.

SchemaYS can:

* Can validate YAML/JSON files
  * At validation time or for every load if desired
* Generate the JSON Schema if you want to use that for validation
  * Use for SchemaYS for JSON Schema like YAML is used for JSON
* Provides a way to associate YAML files with schema (file or url)
* Can define new complex constraints
  * Anything a programming language could do
* New schemas import and extend existing ones
* Do everything JSON Schema does an
* Define and compose schemas/types inline and externally
* Will soon be optionally available in go-yaml, PyYAML, libyaml based YAMLs
  * Applications using these can choose if and when validation happens
