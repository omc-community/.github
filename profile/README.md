<p align="center">
  <img src="https://raw.githubusercontent.com/omc-community/.github/main/avatar.png" width="96" height="96" alt="OMC Community logo">
</p>

<h1 align="center">OMC Community</h1>

<p align="center">
  <a href="https://github.com/WizisCool/oh-my-cpa">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/WizisCool/oh-my-cpa/main/web/src/assets/brand/omc-wordmark-dark.svg">
      <img src="https://raw.githubusercontent.com/WizisCool/oh-my-cpa/main/web/src/assets/brand/omc-wordmark-light.svg" alt="Oh-My-CPA" height="22">
    </picture>
  </a>
</p>

<p align="center">
  Building plugins, integrations, and extensions for the Oh-My-CPA ecosystem.
</p>

---

## Welcome

Welcome to the **OMC Community** organization! This is the official hub for plugins, integrations, adapters, and tools built for [Oh-My-CPA](https://github.com/WizisCool/oh-my-cpa) (OMC) and [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) (CPA).

---

## Relationship with Oh-My-CPA

- **Oh-My-CPA Core Repository**: The primary management control plane, web console, and proxy orchestrator is maintained by [@WizisCool](https://github.com/WizisCool) at [**WizisCool/oh-my-cpa**](https://github.com/WizisCool/oh-my-cpa).
- **OMC Community**: This organization operates as the official extensions and community ecosystem. It hosts the unified plugin registry source ([omc-plugins](https://github.com/omc-community/omc-plugins)), first-party companion plugins, and community-driven integrations.

---

## Plugin Classification & Maintenance

To ensure transparency and software supply chain integrity, plugins in this ecosystem are clearly categorized into two tiers:

### 🛡️ Officially Maintained
Plugins maintained and supported directly by the core Oh-My-CPA team. They adhere to strict security, performance, and versioning standards, and receive continuous updates alongside Oh-My-CPA releases:

| Repository | Purpose & Capability |
| --- | --- |
| [**omc-plugins**](https://github.com/omc-community/omc-plugins) | **Unified Plugin Registry** — The official registry source for Oh-My-CPA and CLIProxyAPI. |
| [**omc-zcode-oauth**](https://github.com/omc-community/omc-zcode-oauth) | **ZCode OAuth Provider** — Dual-portal Z.ai / BigModel OAuth login, model routing, Anthropic Messages execution, and normalized quota. |
| [**omc-qoder-oauth**](https://github.com/omc-community/omc-qoder-oauth) | **Qoder OAuth Provider** — Dual-portal Qoder and Qoder CN OAuth login, model discovery, OpenAI-compatible execution, and normalized quota. |

### 🤝 Community Contributed
Plugins developed, adapted, or maintained by third-party community developers. These plugins are reviewed before inclusion in the registry and can be installed with one click from the OMC Plugin Store:

| Plugin | Author | Description |
| --- | --- | --- |
| `omcpa-codex-candy-eval` | [Yorick-Ryu](https://github.com/Yorick-Ryu) / haowang02 | Evaluation plugin featuring candy reasoning tests, model fingerprint detection, and pelican rendering. |
| *More community plugins coming soon!* | Open Source Community | Contributions and suggestions are always welcome. |

---

## Software Registry Sources for OMC & CPA

The ecosystem publishes two specialized sources (and one combined endpoint):

- **Officially Maintained (`official.json`)**:
  ```
  https://raw.githubusercontent.com/omc-community/omc-plugins/main/official.json
  ```
- **Community Contributed (`community.json`)**:
  ```
  https://raw.githubusercontent.com/omc-community/omc-plugins/main/community.json
  ```
- **Combined All-in-One (`registry.json`)**:
  ```
  https://raw.githubusercontent.com/omc-community/omc-plugins/main/registry.json
  ```

### Usage
- **Oh-My-CPA**: Subscribes to the combined source out of the box under **Settings → Plugins → Plugin Store**. You can add or toggle `official.json` and `community.json` individually.
- **CLIProxyAPI**: Add any of the URLs above to `plugins.store-sources` in your `config.yaml`.

---

## Contributing

Have an idea for a new plugin, provider integration, or tool? We welcome your contributions!
Please see [omc-plugins](https://github.com/omc-community/omc-plugins) for plugin submission guidelines and testing requirements.
