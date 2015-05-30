# jyaml
JYaml fork with bug fixes &amp; misc enhancements

*Bug Fixes*

- Fixes issue where dumping a map (using Yaml.dump) containing an entry with a key of "-" is not properly quoted and then is subsequently incorrectly read by Yaml.load.
