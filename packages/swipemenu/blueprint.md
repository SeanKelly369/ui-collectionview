{{ load:../../tools/readme/edit-warning.md }}
{{ template:title }}
{{ template:badges }}
{{ template:description }}

{{ template:toc }}

## Installation
Run the following command from the root of your project:

`ns plugin add {{ pkg.name }}`

## Configuration

To install the plugin run:
```typescript
import install from '{{ pkg.name }}';
install();
```

then simply use the `layoutStyle="waterfall"` as a collectionview property

{{ load:../../tools/readme/demos-and-development.md }}
{{ load:../../tools/readme/questions.md }}