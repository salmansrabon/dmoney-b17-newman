# Dmoney — Newman tests and HTML report

Brief test suite for the Dmoney user-management APIs. The collection exercises common flows (send money, deposit, cashout, payments) and produces an HTML report using Newman.

**Tech:** Node.js, Postman, Newman, HTML Report Extra

**Prerequisites:**
- Node.js (LTS recommended)
- `npm` (bundled with Node)
- A Postman API key / secret required by the collection (set via environment)

**Quick start:**
1. Clone the project:
    `git clone <remote_url>

2. Install dependencies:

	`npm install`

3. Run the test collection:

	`npm test`

4. The generated HTML report is written to the `Reports/` folder (for example `Reports/report.html`).

**Environment / Secrets:**
- The collection requires a secret key (API key or similar). Provide it via your Postman environment or an `.env` file depending on how your local setup injects variables into the Newman run. Do not commit secrets to source control.

**API documentation:**
https://documenter.getpostman.com/view/1844288/2sB3dLTr1E

**Reports:**
- Open `Reports/report.html` to view the latest HTML report.

**Contributing:**
- Improve or extend the Postman collection, add environment examples, and update `report.js` or `package.json` scripts if needed.

**Contact / Author:**
- Repository: `salmansrabon/dmoney-b17-newman`

--
Small, focused README to make running tests and finding reports quick and easy.
