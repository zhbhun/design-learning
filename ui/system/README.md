## 背景

| Tailwind 用法 | CSS Token | 色值 | 用途 |
|---|---|---:|---|
| `bg-background` | `--background` | `#FFFFFF` | 应用主画布、主要内容区域 |
| `bg-background-secondary` | `--background-secondary` | `#FAFAFA` | 侧栏、分区、次级页面区域 |
| `bg-background-tertiary` | `--background-tertiary` | `#F5F5F5` | 嵌套区域、弱化填充、低强调区域 |
| `bg-background-elevated` | `--background-elevated` | `#FFFFFF` | 浮层、高层级表面；通过边框和阴影体现层级 |
| `bg-background-inverse` | `--background-inverse` | `#171717` | 反色区域、高对比强调区域 |

---

| 设计系统 | Primary | Secondary | Tertiary | Disabled | Inverse |
|---|---|---|---|---|---|
| [Fluent 2](https://fluent2.microsoft.design/color-tokens/) | `Foreground1` `#242424` | `Foreground2` `#424242` | `Foreground3` `#616161` | `ForegroundDisabled` `#bdbdbd` | `ForegroundInverted` `#fff` |
| [Carbon](https://carbondesignsystem.com/elements/color/tokens/) | `$text-primary` `#161616` | `$text-secondary` `#525252` | `$text-helper` `#6f6f6f` | `#161616` 25%，白底约 `#c5c5c5` | `$text-inverse` `#fff` |
| [GitHub Primer](https://primer.style/product/primitives/color/) | `--fgColor-default` `#1f2328` | `--fgColor-muted` `#59636e` | 无独立层级 | `--fgColor-disabled` `#818b98` | `--fgColor-onInverse` `#fff` |
| [Ant Design](https://ant.design/docs/react/customize-theme/) | `colorText` `rgba(0,0,0,.88)` ≈ `#1f1f1f` | `colorTextSecondary` `.65` ≈ `#595959` | `colorTextTertiary` `.45` ≈ `#8c8c8c` | `colorTextDisabled` `.25` ≈ `#bfbfbf` | `colorTextLightSolid` `#fff` |
| [Atlassian](https://unpkg.com/@atlaskit/tokens@15.5.0/dist/esm/artifacts/token-default-values.js) | `color.text` `#292a2e` | `color.text.subtle` `#505258` | `color.text.subtlest` `#6b6e76` | `#080f214a`，白底约 `#b7b9bf` | `color.text.inverse` `#fff` |
| [Material 3](https://m3.material.io/styles/color/roles) | `onSurface` | `onSurfaceVariant` | 无独立层级 | 通常为 `onSurface` + disabled opacity | `inverseOnSurface` |

## 文字

| Tailwind 用法 | CSS Token | 色值 | 用途 |
|---|---|---:|---|
| `text-foreground` | `--foreground` | `#242424` | 标题、正文、主要信息 |
| `text-foreground-secondary` | `--foreground-secondary` | `#666666` | 描述、元信息、辅助内容 |
| `text-foreground-tertiary` | `--foreground-tertiary` | `#8A8A8A` | 时间戳、弱提示、非关键信息 |
| `text-foreground-disabled` | `--foreground-disabled` | `#B3B3B3` | 不可用、禁用内容 |
| `text-foreground-inverse` | `--foreground-inverse` | `#FAFAFA` | 放在反色背景上的主要文字 |

---

| 设计系统 | Primary | Secondary | Tertiary | Disabled | Inverse |
|---|---|---|---|---|---|
| [Fluent 2](https://fluent2.microsoft.design/color-tokens/) | `Foreground1` `#242424` | `Foreground2` `#424242` | `Foreground3` `#616161` | `ForegroundDisabled` `#bdbdbd` | `ForegroundInverted` `#fff` |
| [Carbon](https://carbondesignsystem.com/elements/color/tokens/) | `$text-primary` `#161616` | `$text-secondary` `#525252` | `$text-helper` `#6f6f6f` | `#161616` 25%，白底约 `#c5c5c5` | `$text-inverse` `#fff` |
| [GitHub Primer](https://primer.style/product/primitives/color/) | `--fgColor-default` `#1f2328` | `--fgColor-muted` `#59636e` | 无独立层级 | `--fgColor-disabled` `#818b98` | `--fgColor-onInverse` `#fff` |
| [Ant Design](https://ant.design/docs/react/customize-theme/) | `colorText` `rgba(0,0,0,.88)` ≈ `#1f1f1f` | `colorTextSecondary` `.65` ≈ `#595959` | `colorTextTertiary` `.45` ≈ `#8c8c8c` | `colorTextDisabled` `.25` ≈ `#bfbfbf` | `colorTextLightSolid` `#fff` |
| [Atlassian](https://unpkg.com/@atlaskit/tokens@15.5.0/dist/esm/artifacts/token-default-values.js) | `color.text` `#292a2e` | `color.text.subtle` `#505258` | `color.text.subtlest` `#6b6e76` | `#080f214a`，白底约 `#b7b9bf` | `color.text.inverse` `#fff` |
| [Material 3](https://m3.material.io/styles/color/roles) | `onSurface` | `onSurfaceVariant` | 无独立层级 | 通常为 `onSurface` + disabled opacity | `inverseOnSurface` |
