# Setup Guide

## 1. Create the profile repository

Create a **public** GitHub repository named exactly:

```text
ngoctanz
```

GitHub uses the README in this special repository as your profile page.

## 2. Upload the files

Preserve this structure:

```text
ngoctanz/
├── README.md
└── .github/
    └── workflows/
        └── snake.yml
```

## 3. Enable the snake animation

1. Open the repository's **Actions** tab.
2. Enable GitHub Actions when prompted.
3. Open **Generate contribution snake**.
4. Choose **Run workflow**.
5. Wait for the workflow to create the `output` branch.
6. Refresh your GitHub profile.

## 4. Replace missing project links

Search `README.md` for:

```text
Coming_Soon
```

Replace it when the Trello repository is available.

## 5. Optional customization

The main neon colors are:

```text
Cyan:    00C9FF
Purple:  7B2FFF
Pink:    FF2E93
Dark:    0D1117
```

Change these values in badge, header, stats, and graph URLs to create another theme.

## Notes

- External cards and animations rely on third-party SVG services.
- Some cards may temporarily fail because of rate limits or service downtime.
- Keep the project descriptions accurate and avoid publishing private client information.
