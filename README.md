# PlexusOne Design System

Design tokens and brand configuration for PlexusOne properties.

## Structure

```
plexusone-design-system/
├── design-system.json    # Single source of truth
├── package.json
└── README.md
```

## Color Palette

| Token | Value | Role |
|-------|-------|------|
| `dark` | `#0a0e1a` | Primary background |
| `navy` | `#0f172a` | Card backgrounds |
| `cyan` | `#06b6d4` | Primary accent |
| `purple` | `#8b5cf6` | Secondary accent |
| `pink` | `#ec4899` | Tertiary accent |

## Validation

```bash
ajv validate --spec=draft2020 --strict=false \
  -s path/to/design-system.schema.json \
  -d design-system.json
```

## License

MIT
