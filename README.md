# Chirpy Starter

[![Gem Version](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub license](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

Chirpy Jekyllテーマを使ったブログをすぐに作成できる、最小構成のテンプレートです。
必要なファイルはあらかじめ設定済みなので、数分でブログを立ち上げられます。

## このStarterが存在する理由

ChirpyをRubyGems.org経由でインストールした場合、Jekyllが読み込めるテーマファイルは _data、_layouts、_includes、_sass、assets、_config.yml の一部と、Gemに含まれる限られた設定項目だけです。
そのため、Chirpyが本来提供している「すぐに使える完成された環境（out-of-the-box experience）」をそのまま利用することはできません。

Chirpyのすべての機能を利用するには、以下のファイルやディレクトリがJekyllサイト内に存在している必要があります。

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

このStarterには、最新版のChirpyリリースに含まれる必要なファイル一式と、継続的デプロイ（CD: Continuous Deployment）のワークフローがあらかじめ組み込まれています。
そのため、環境構築に時間をかけることなく、すぐに記事を書き始めることができます。

## 使い方

Chirpyテーマのドキュメントをご覧ください。

## コントリビューション（改善への協力）

このリポジトリは、Chirpyテーマ本体の新しいリリースに合わせて自動的に更新されます。
問題を見つけた場合や改善に協力したい場合は、このStarterリポジトリではなく、Chirpyテーマ本体のリポジトリへフィードバックをお願いします。

## ライセンス

このソフトウェアは MITライセンス のもとで公開されています。

----------

A minimal, ready-to-use template for creating a blog with the [**Chirpy**][chirpy] Jekyll theme. Get up and running in minutes with all critical files pre-configured.

## Why This Starter Exists

When installing Chirpy through [RubyGems.org][gem], Jekyll can only read a subset of theme files (`_data`, `_layouts`, `_includes`, `_sass`, `assets`) and limited `_config.yml` options from the gem. As a result, users cannot enjoy the full out-of-the-box experience that Chirpy offers.

To unlock all features, the following files must be present in your Jekyll site:

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

This starter bundles those files from the latest **Chirpy** release along with a [CD][CD] workflow, so you can start writing immediately.

## Usage

Check out the [theme's docs](https://github.com/cotes2020/jekyll-theme-chirpy/wiki).

## Contributing

This repository is automatically updated with new releases from the theme repository. If you encounter any issues or want to contribute to its improvement, please visit the [theme repository][chirpy] to provide feedback.

## License

This work is published under [MIT][mit] License.

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE
