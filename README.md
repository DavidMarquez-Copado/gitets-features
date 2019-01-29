# Acceptance tests
| Action | Description                                                  | DX   | Artifact   | Source metadata (Before deploy)              | Target metadata (Before deploy)              |
| ------ | ------------------------------------------------------------ | ---- | ---------- | -------------------------------------------- | -------------------------------------------- |
| Deploy | Deploy **new custom object** with a DX flow involved         | Yes  | Artifact_1 | **Custom Object**                            | -                                            |
|        |                                                              |      |            | **Layout related to the object**             | -                                            |
| Deploy | Deploy **new** **permision set full** with a DX flow involved | Yes  | Artifact_1 | Custom Object                                | Custom Object                                |
|        |                                                              |      |            | Layout related to the object (retrieve only) | Layout related to the object (retrieve only) |
|        |                                                              |      |            | **Permision set full**                       |                                              |
| Deploy | Deploy **new** **normal permision set** and a **new** **Custom field** (all in the same deployment) | Yes  | Artifact_1 | Custom Object                                | Custom Object                                |
|        |                                                              |      |            | Layout related to the object (retrieve only) | Layout related to the object (retrieve only) |
|        |                                                              |      |            | Permision set full                           | Permision set full                           |
|        |                                                              |      |            | **Permision set normal**                     |                                              |
|        |                                                              |      |            | **Custom field**                             |                                              |
| Deploy | Deploy **new profile** with a **YAML rule, configured on Copado**,  to delete all the USER_PERMISSIONS | Yes  | Artifact_1 | Custom Object                                | Custom Object                                |
|        |                                                              |      |            | Layout related to the object (retrieve only) | Layout related to the object (retrieve only) |
|        |                                                              |      |            | **Profile** related to the custom object     |                                              |
