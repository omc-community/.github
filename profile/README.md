# OMC Community

> **Building plugins, integrations, and extensions for the Oh-My-CPA ecosystem.**

Welcome to the **OMC Community** organization! This space hosts plugins, integrations, adapters, and tools created for [Oh-My-CPA](https://github.com/WizisCool/oh-my-cpa) and [CLIProxyAPI (CPA)](https://github.com/router-for-me/CLIProxyAPI).

---

## Relationship with Oh-My-CPA / 与 Oh-My-CPA 的关系

- **Oh-My-CPA Core Repository**: The primary control plane application and web console is developed and maintained by [@WizisCool](https://github.com/WizisCool) at [**WizisCool/oh-my-cpa**](https://github.com/WizisCool/oh-my-cpa).
- **OMC Community**: This organization operates as the official extensions and community hub. It hosts the centralized plugin registry ([omc-plugins](https://github.com/omc-community/omc-plugins)), first-party companion plugins, and community-driven integrations.

---

## Plugin Classification / 插件维护分类

To ensure transparency and trust, plugins in this ecosystem are categorized as follows:

### 🛡️ Officially Maintained / 官方维护
Plugins maintained directly by the core Oh-My-CPA maintainers. They are tested against new Oh-My-CPA releases, follow strict security practices, and receive timely updates:

| Repository / 插件仓库 | Description / 描述 |
| --- | --- |
| [**omc-plugins**](https://github.com/omc-community/omc-plugins) | **Unified Plugin Registry** — The official plugin registry source for Oh-My-CPA and CPA. / 统一插件软件源仓库。 |
| [**omc-zcode-oauth**](https://github.com/omc-community/omc-zcode-oauth) | **ZCode OAuth Provider** — Dual-portal Z.ai / BigModel OAuth login, model routing, Anthropic Messages execution, and normalized quota. |
| [**omc-qoder-oauth**](https://github.com/omc-community/omc-qoder-oauth) | **Qoder OAuth Provider** — Qoder and Qoder CN OAuth login, model discovery, OpenAI-compatible execution, and normalized quota. |

### 🤝 Community Contributed / 社区贡献
Plugins authored, adapted, or maintained by third-party community developers. These plugins are reviewed before inclusion in the registry and can be installed directly from the OMC Plugin Store:

| Plugin / 插件 | Author / 作者 | Description / 描述 |
| --- | --- | --- |
| `omcpa-codex-candy-eval` (降智测试) | [Yorick-Ryu](https://github.com/Yorick-Ryu) / haowang02 | Evaluation plugin with candy reasoning, model fingerprints, and pelican rendering. |
| *More community plugins coming soon!* | Community | Contributions are welcome! |

---

## Software Source for OMC & CPA / 软件源订阅

To access all community and official plugins in your OMC console or CPA gateway, register the source URL:

```
https://raw.githubusercontent.com/omc-community/omc-plugins/main/registry.json
```

- **Oh-My-CPA**: Enabled out of the box under **Settings → Plugins → Plugin Store**.
- **CLIProxyAPI**: Add to `plugins.store-sources` in your `config.yaml`.

---

## Contributing / 参与贡献

Have an idea for a plugin or provider integration? We'd love your contributions!
Check out [omc-plugins](https://github.com/omc-community/omc-plugins) to submit your plugin to the store registry.
