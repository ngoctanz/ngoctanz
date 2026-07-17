# Setup

1. Create or open the public profile repository named `ngoctanz`.
2. Upload everything from this package without changing the folder structure.
3. Open **Actions**.
4. Run **Generate 3D contribution calendar** manually once.
5. Refresh the profile after the workflow commits the generated SVG.

## Structure

```text
ngoctanz/
├── README.md
├── assets/
│   ├── hero.svg
│   └── signal.svg
└── .github/
    └── workflows/
        └── profile-3d.yml
```

## Notes

- GitHub removes much inline CSS from README HTML. This design uses SVG assets, tables, badges, and Markdown because these render more reliably.
- The 3D contribution image is generated inside your own repository, so it is more reliable than embedding a separate snake branch.
- Third-party GitHub statistics cards can occasionally be unavailable due to rate limits.
