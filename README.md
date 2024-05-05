### 概要
3dcg(将来的にはvfx)勉強用

### やること
#### 導入
* astro
* webassembly
* WebGPU
* rust
* wgpu
* 3DCG

#### 後回し
* Unity
* C#

#### 議事録
* ~turborepoはjsのみの対応だったのと、vercel依存が嫌なので、rust互換のnxで対応、npm trends的にもnxが良かった。~ monorepo後回し
* ~monorepoと相性の良いpnpmを採用、結構面倒だけど慣れる。~ monorepo後回し
* remixは良い選択肢だが、astroの将来性のほうが高いので、astro/reactで構成組んでみる。

###  Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |