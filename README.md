# jyaml
JYaml fork with bug fixes &amp; misc enhancements

*Bug Fixes*

- Fixes an issue where dumping a map (using Yaml.dump) containing an entry with a key of "-" is not properly quoted and will then be subsequently read by Yaml.load() incorrectly.
