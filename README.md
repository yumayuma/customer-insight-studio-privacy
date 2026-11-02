# Customer Insight Studio — Privacy Notice

Publisher: 3DANALYTICS

## Analysis

All 16 analysis modules run offline on the computer. The application does not upload imported data, tables, saved projects, fitted models, or reports. Analysis does not require an internet connection or an application account.

The desktop interface loads bundled resources and communicates with the Python engine internally. It starts no HTTP/WebSocket listener. No application advertising or usage-analytics collection is implemented.

## File and clipboard access

Users select files to import and destinations for exported Excel, HTML and PDF files. Parsing and report generation occur locally. Copy and paste use the operating-system clipboard after a user action. The application does not control exported files or clipboard contents after they are shared outside it.

## Storage

Explicitly saved projects, fitted model artifacts and diagnostic logs use the application's writable data directory. Portable installations use a data folder beside the executable; MSIX installations use per-user package LocalState; macOS uses Application Support. The working session is temporary and separate from saved snapshots.

Changing functions or replacing populated working data requires the applicable Save/Discard/Cancel decision. Deleting or discarding files performs ordinary filesystem deletion, not secure erasure. Application reset or removal may delete app-managed data. Exported files remain at the destinations selected by the user.

## Diagnostics and access

Logs can contain local paths and error details. They remain local and are not automatically transmitted. Review files before voluntarily sharing them. Access to stored files is controlled by operating-system permissions. Installation and update services operate separately from the application analysis engine.

Sample datasets are synthetic. Imported customer data remains under the user's control and should be stored with appropriate access restrictions.

## Educational use and support

Customer Insight Studio is an educational application. No individual technical support is provided. This does not limit rights that cannot lawfully be excluded.
