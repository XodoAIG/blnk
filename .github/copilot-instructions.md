# ✅ Commit Instructions

Generate **one commit at a time** following the **Conventional Commits** specification, enriched with **dynamic icons** for clarity and readability.

---

### 🧩 Format

```

<type>(<scope>): <icon> <short message>

```

**Example:**

```

feat(api): ✅ add authentication middleware

```

---

### 🧠 Body / Description

Use the body to describe **each change in detail**:

- Start each item with `-`
- Be concise but specific
- Use one line per change

**Example:**

```

* Added authentication middleware using JWT
* Updated user model with new token field

```

---

### 🦶 Footer

Include this **only once** at the end of the commit message:

```

Author: Rafael Carvalho

```

---

### 🎨 Dynamic Icons

| Type        | Icon                                     | Description |
| ----------- | ---------------------------------------- | ----------- |
| ♻️ feat     | New feature                              |
| 🐛 fix      | Bug fix                                  |
| 📝 docs     | Documentation update                     |
| 🔧 refactor | Code refactoring without behavior change |
| ⚡ perf     | Performance improvement                  |
| ✅ test     | Adding or updating tests                 |
| 🔧 build    | Build system or dependency change        |
| 👷 ci       | Continuous Integration / Deployment      |
| 🧹 chore    | Maintenance or minor cleanup             |

---

### ⚙️ Guidelines

- Keep the **summary ≤ 72 characters**
- Separate **summary, body, and footer** with **blank lines**
- Use **imperative mood** (e.g., “add” not “added”)
- Focus each commit on **one logical change**

---

### Final Footer

```
Author: Rafael Carvalho

```
