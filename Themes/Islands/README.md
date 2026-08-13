# Islands Discord theme

> [!WARNING]
> Work in progress; not everything will be fully functional or polished.

A Discord theme separating UI elements into distinguishable 'islands' for a cleaner and less dense layout. Slightly inspired by Microsoft Fluent UI and iOS Liquid Glass design.

```css
/* Islands theme - @astro_aya */ @import url("https://astro-aya.github.io/ayas-random-css/Themes/Islands/islands%20theme.css");
```

<details>
  <summary>Optional theme settings for more customizability.</summary>
  
```css
/* collapsing member list - @amozeo */ @import url(https://raw.githubusercontent.com/amozeo/discord-css-snippets/refs/heads/main/snippets/compact-memberlist.css);

/* Theme settings */
:root {
  --primary-accent-color: #5865F2 !important;
  --border-radius-strong: 16px !important;
  --border-radius-medium: 12px !important;
  --border-radius-weak: 8px !important;
  --ocean-gap: 8px !important;
}

/* CompactTabs settings */
:root {
  --server-tabs: true !important;
  --dms-tabs: true !important;
}
```
</details>

