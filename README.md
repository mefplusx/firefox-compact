### In Firefox

- Open _`about:config`_:
  - `toolkit.legacyUserProfileCustomizations.stylesheets`: `true`
  - `browser.compactmode.show`: `true`
  - `extensions.pocket.enabled`: `false`
- Go to Menu > More Tools > Customize Toolbar...: use compact density, auto-hide downloads button, remove all flexible space and unnecessary items.
- Open _`about:support`_, copy Profile Folder

### In terminal

```sh
Перейти в папку профиля, найти тут _`about:support`_
git clone https://github.com/mefplusx/firefox-compact chrome
```

Then restart Firefox.
