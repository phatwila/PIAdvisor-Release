# PIAdvisor update repository

PixInsight update repository for **PIAdvisor**, a processing assistant that works inside [PixInsight](https://pixinsight.com). Windows and Linux (x64), PixInsight 1.8.9 or later.

Download page: <https://phatwila.github.io/PIAdvisor-Release/>

## Install

1. In PixInsight, select **Resources > Updates > Manage Repositories**.
2. Click **Add**, paste this URL, then click **OK**:

   ```
   https://phatwila.github.io/PIAdvisor-Release/
   ```

3. Select **Resources > Updates > Check for Updates**. Apply the update, then restart PixInsight.
4. Open **Process > PIAdvisor > PIAdvisor** and set your provider in **LLM Settings**.

## Contents

| Path | Purpose |
| :--- | :--- |
| `updates.xri` | Signed manifest that the PixInsight updater reads |
| `packages/` | Module package for each platform, with the release history |
| `docs/` | Reference documentation, the same pages PixInsight shows |
| `index.html`, `site.css`, `fonts/` | Download page and its theme (Geist fonts, SIL Open Font License) |

## Links

- Website: [piadvisor.net](https://piadvisor.net)
- Changelog: [piadvisor.net/changelog/](https://piadvisor.net/changelog/)
- Documentation: [docs/](https://phatwila.github.io/PIAdvisor-Release/docs/)
- Packages: [packages/](https://phatwila.github.io/PIAdvisor-Release/packages/)

PixInsight is a trademark of Pleiades Astrophoto S.L. PIAdvisor is an independent module and is not affiliated with or endorsed by Pleiades Astrophoto.
