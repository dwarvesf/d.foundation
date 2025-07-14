# d.foundation

---

Pull and install our web engine to preview the website locally:

```bash
git clone git@github.com:dwarvesf/web-engine.git
```

Clone this content repository:

```bash
git clone git@github.com:dwarvesf/d.foundation.git
```

Then, go to the web-engine directory, create `.env` in `/app` then point the content to the source directory:

```bash
# app/.env
CONTENT_DIR="../d.foundation"
```

Then, install packages and run the web engine:

```bash
pnpm install
pnpm dev
```

The website should be available at `http://localhost:3000`.
