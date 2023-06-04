{
  "$schema": "http://json-schema.org/draft-07/schema#",
  "type": "object",
  "properties": {
    "properties": {
      "type": "object",
      "properties": {
        "Photo": {
          "type": "string",
          "format": "uri",
          "pattern": ".*\\.(jpg|jpeg|png|gif)$"
        }
      },
      "required": ["Photo"]
    }
  },
  "required": ["properties"]
}
