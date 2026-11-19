# shibin-curriculum

Pre-reads and lecture scripts for all batches, in one standard structure.

## Structure

```
shibin-curriculum/
├── README.md
├── templates/
│   ├── pre-read-template.md
│   └── lecture-script-template.md
└── <batch-id>/                  # same ID as the INI sheet
    └── module-01-<topic>/
        └── lecture-01-<topic>/
            ├── pre-read.md
            └── lecture-script.md
```

## Naming rules
- Lowercase and hyphens only
- Numbered modules and lectures (`module-01-...`, `lecture-01-...`)
- Same two file names everywhere: `pre-read.md` and `lecture-script.md`

## Adding a lecture
1. Create `<batch-id>/module-NN-<topic>/lecture-NN-<topic>/`
2. Copy the two templates from `templates/` into it as `pre-read.md` and `lecture-script.md`
