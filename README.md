# MCCES HTML

This repository contains an interactive, browser-based digital copy of DD Form 2983: Recruit/Trainee Prohibited Activities Acknowledgment. It is designed to support completion, validation, export, and printing of the form in a streamlined web interface while preserving the official signed paper form as the record of record.

## Repository contents

- `DD_FORM_2983_v6.html` — the complete interactive form in a single HTML file
- `LICENSE` — MIT license for the project
- `README.md` — project overview and usage instructions

## What the form includes

The current version includes:

- A printable DD Form 2983 layout styled for browser and PDF output
- Editable recruit and approver fields
- Required-item validation and stage-based progress tracking
- Recruit stage and approver stage workflow indicators
- Signature and initials capture via drawing pad or typed signature
- Auto-fill support for today's date
- Data export/import in JSON format
- Local browser save-progress behavior
- Clear/reset controls for the full form
- Print and PDF export actions
- Responsive layout for desktop and smaller screens

## How to use it

1. Open `DD_FORM_2983_v6.html` in a modern web browser.
2. Complete the required recruit information and signatures.
3. Use the toolbar to:
   - enable local saving on the device
   - auto-fill the date
   - print the form
   - export the form as PDF
   - export data to JSON
   - import previously saved data
   - clear the form
4. Move through the form using the on-page progress and required-item indicators.
5. Complete the approving official section and finalize the form when all required items are satisfied.

## Notes

- This is an unofficial convenience copy of the form intended for digital completion and export.
- It is not a replacement for the official signed paper form required for filing.
- If the local save option is enabled, progress is stored in the browser on the device in use.
- The PDF and print features rely on browser support and loaded client-side libraries.
- There is no build step or package installation required for the static HTML version.

## Technical details

- Technology: HTML, CSS, and JavaScript
- Single-file static web app
- Uses browser APIs plus client-side libraries for PDF export and canvas capture
- Works in modern desktop and mobile browsers with JavaScript enabled

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
