# Qwik Icons

Include popular icons easily in your Qwik projects with `@qwikest/icons` 🚀

Currently included libraries (with icon prefix):

- `Bs`: [Bootstrap Icons](https://icons.getbootstrap.com/)
- `Go`: [Octicons](https://primer.style/design/foundations/icons/) by GitHub
- `Hi`: [Heroicons](https://heroicons.com/) by Tailwind
- `In`: [Iconoir](https://iconoir.com/)
- `Io`: [Ionicons](https://ionic.io/ionicons) by Ionic
- `Lu`: [Lucide](https://lucide.dev/) [superset of feather icons]
- `Mo`: [Mono Icons](https://icons.mono.company/)
- `Si`: [Simple Icons](https://simpleicons.org/) [icons for popular brands]
- `Tb`: [Tabler Icons](https://tabler-icons.io/)

## Installation

Simply install the package with your package manager of choice:

```bash
npm i @qwikest/icons
yarn add @qwikest/icons
pnpm add @qwikest/icons
```

## Usage

```tsx
import { LuRocket } from "@qwikest/icons/lucide";

export const MyComponent = component$(() => {
  // Icon size and color are inherited by default ⬇️
  return (
    <div style={{ color: "red", fontSize: "40px" }}>
      <LuRocket />
    </div>
  );
});
```

## Available Libraries

```tsx
import { Bs1Circle } from "@qwikest/icons/bootstrap";
import { HiAcademicCapMini } from "@qwikest/icons/heroicons";
import { In1StMedal } from "@qwikest/icons/iconoir";
import { IoAirplaneOutline } from "@qwikest/icons/ionicons";
import { LuRocket } from "@qwikest/icons/lucide";
import { MoAdd } from "@qwikest/icons/monoicons";
import { GoFlame24 } from "@qwikest/icons/octicons";
import { Si1Password } from "@qwikest/icons/simpleicons";
import { Tb123 } from "@qwikest/icons/tablericons";
```

> **Missing a library?** Feel free to [open an issue](https://github.com/qwikest/icons/issues/new?title=Add%20Icon%20Pack:) or even a MR 🤝

## Upcoming

- 🖌️ Configurable stroke width for supported packages
- 🎁 Additional icon libraries
- 🎨 Built-in company based colors for [simple icons](https://simpleicons.org/)
