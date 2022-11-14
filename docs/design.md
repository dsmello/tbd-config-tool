# The project proposal - Alpha

A simple cli tool to help me to handle with different formats of configuration files as JSON, YAML, TOML and XML. Allow to override values instead of using complex bash lines. 
To keep simple this project will grow as the goals be going archived.

## Alpha

Supported file formats:
- json;
- yml; yaml;
- toml;

Commands:
--in string "The name of the file. Can be used multiple times. And the values will be override.
--yaml or --json or --toml string "Will be the same as the 'in' entry but as the string input instead of a file."
--string string "a line of the path with the value to override. Same of jq. Ex.: example.name="tbd" "
--strategy string "The strategy of what to do with list fields. Default: replace . Values (replace, add)"
--out string "The file format of the out put, by default will be the same of the first file, of yaml if for some reason any format was defined."