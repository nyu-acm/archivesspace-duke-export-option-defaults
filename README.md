# archivesspace-duke-export-option-defaults
An ArchivesSpace plugin that changes default options for EAD exports in the staff interface

Current defaults:
- Include unpublished: false
- Include `<dao>` tags: true
- Use numbered `<c>` tags: false
- EAD3 schema: false

MARC export includes option to include or exclude unpublished.

Be sure not to override export options that may be introduced in subsequent releases.
