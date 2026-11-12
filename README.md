# NEXORGE Studio workspace

Glass-effect internal-studio dashboard preview, based on the commercial video production, website design and monthly content services at https://nexorge.com.

## Included
- Overview with computed project, lead, invoice and task metrics; labelled illustrative revenue chart.
- Create and update projects, progress, stages and notes.
- Add leads and change their pipeline stages.
- Add tasks and toggle completion.
- Add scheduled events in a production agenda.
- Create invoice tracking records, confirm sent/paid status (does not transmit anything).
- Search projects and leads, activity history, JSON export and confirmed sample-data reset.
- Responsive layout, accessible dialog and keyboard focus, reduced-motion support.

## Hosting
Static HTML/CSS/JavaScript. No build step. GitHub Pages serves the repository root. Run locally with `python3 -m http.server 8087`.

## Important limits
This is a PUBLIC DEMO with fictional clients and sample data. There is no authentication, backend, team synchronization, email sending, invoice delivery or payment processing. Edits are saved in localStorage on the current browser only. Do not add confidential information. Revenue trend is illustrative and not linked to invoice records.

## Next steps for real team use
1. Confirm team members and roles (admin, producer, editor, finance).
2. Add an authenticated backend with database row-level access controls.
3. Migrate validated client/project records and connect only approved services.
4. Deploy behind private access, then configure dashboard.nexorge.com through the domain owner.
5. Test account recovery, backups, permissions and audit history before onboarding the team.

No DNS or changes to nexorge.com were made. Third-party Manrope font license is included in assets.
