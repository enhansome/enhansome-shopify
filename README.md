# Awesome Shopify with stars

[<img src="shopify-logo.svg" align="right" width="120">](https://www.shopify.com/)

> Curated list of awesome Shopify resources, libraries, and open-source projects for developers and designers.

[Shopify](https://www.shopify.com/blog/what-is-shopify) is a leading e-commerce platform that allows you to build and manage online stores.

![GitHub last commit](https://img.shields.io/github/last-commit/julionc/awesome-shopify)
![GitHub Repo stars](https://img.shields.io/github/stars/julionc/awesome-shopify)

## Contents

* [Official Resources](#official-resources)
* [Documentation](#documentation)
* [Themes & Design](#themes--design)
* [Frontend Development](#frontend-development)
* [Mobile](#mobile)
* [Libraries](#libraries)
  * [Ruby](#ruby)
  * [Python](#python)
  * [JavaScript](#javascript)
  * [DotNet](#dotnet)
  * [Elixir](#elixir)
  * [Java](#java)
  * [Golang](#golang)
  * [PHP](#php)
  * [R](#r)
  * [Rust](#rust)
* [Example Apps](#example-apps)
  * [Shopify App Templates](#shopify-app-templates)
  * [JavaScript Examples](#javascript-examples)
  * [PHP Examples](#php-examples)
  * [Python Examples](#python-examples)
  * [Ruby Examples](#ruby-examples)
  * [Elixir Examples](#elixir-examples)
* [Code Snippets](#code-snippets)
* [Developer Tools](#developer-tools)
* [Community](#community)

## Official Resources

* [Developer Changelog](https://shopify.dev/changelog) - Official blog with important updates to APIs and developer products.
* [Developer Guides](https://shopify.dev) - Overview of app development for Shopify.
* [Shopify Partner Account](https://www.shopify.com/partners?ref=vitalogy) - Required to start building apps.

## Documentation

* [OAuth Flow for Authentication](https://shopify.dev/docs/apps/build/authentication-authorization/access-tokens/authorization-code-grant)
* [App Store Requirements](https://shopify.dev/docs/apps/launch/app-requirements-checklist)
* [Development Stores](https://www.shopify.com/partners/blog/development-stores?ref=vitalogy)
* [App Design Guidelines](https://shopify.dev/docs/apps/design)

## Themes & Design

* [Shopify Dawn](https://github.com/Shopify/dawn) ⭐ 3,061 | 🐛 26 | 🌐 Liquid | 📅 2026-08-10 - Official Online Store 2.0 theme.
* [Shopify Horizon](https://github.com/Shopify/horizon) ⭐ 445 | 🐛 28 | 🌐 Liquid | 📅 2026-08-12 - Flagship of Shopify’s next-gen themes.
* [City Ecommerce UI Kit](https://github.com/shopifypartners/City-Ecommerce-UI-Kit) ⭐ 32 | 🐛 0 | 📅 2017-06-16
* [Sketch Shopify Data Populator](https://github.com/shopifypartners/sketch-shopify-data-populator) ⭐ 24 | 🐛 0 | 📅 2017-03-31
* [Figma – Dawn Theme](https://www.figma.com/community/file/1017615468313501249)

## Frontend Development

### Polaris Web Components ✨🚀

* [Polaris Reference](https://shopify.dev/docs/api/polaris)
* [Polaris Web Components](https://shopify.dev/docs/api/app-home/web-components) - Shopify's UI toolkit for building interfaces that match the Shopify Admin design system.
  [Polaris UI Kit - Community](https://www.figma.com/community/file/1554895871000783188/polaris-ui-kit-community) - This UI Kit gives you Figma components that match the Polaris Web Components library.
* [App Bridge Web Components](https://shopify.dev/docs/api/app-home/app-bridge-web-components)

### Polaris React (Deprecated ⚠️)

* [Polaris React](https://polaris-react.shopify.com/) - Legacy React component library. [GitHub](https://github.com/Shopify/polaris-react-archive) ⚠️ Archived
* [Polaris Vue](https://github.com/ownego/polaris-vue) ⭐ 182 | 🐛 10 | 🌐 Vue | 📅 2026-04-02 - Vue 3 implementation.
* [Polaris Design Guidelines](https://shopify.github.io/polaris-react-archive/design)
* [Polaris Icon Explorer](https://shopify.github.io/polaris-react-archive/icons)
* [Polaris Components](https://shopify.github.io/polaris-react-archive/components) - Open-source collection of copy/paste UI components built using Shopify’s Polaris design system. 💡

### Hydrogen (Headless)

* [Hydrogen](https://hydrogen.shopify.dev) - Headless stack for custom storefronts. [Source code](https://github.com/Shopify/hydrogen) ⭐ 2,098 | 🐛 70 | 🌐 TypeScript | 📅 2026-08-21.
* [Fluid](https://github.com/frontvibe/fluid) ⭐ 290 | 🐛 17 | 🌐 TypeScript | 📅 2026-08-17 - Hydrogen + Sanity for structured content management.
* [Hydrogen Demo Store](https://github.com/Shopify/hydrogen-demo-store) ⭐ 235 | 🐛 45 | 🌐 TypeScript | 📅 2026-07-01 - Official Hydrogen + Remix template, with full setup of components, queries and tooling for building a headless Shopify storefront. Deployed at hydrogen.shop. 🚀
* [Pilot (Weaverse Hydrogen Theme)](https://github.com/Weaverse/pilot) ⭐ 191 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-17 - Fully featured Shopify Hydrogen theme crafted for launching modern, high-performance headless storefronts. Includes TypeScript, Tailwind CSS, GraphQL code generation, React Router, Oxygen deployment, and customization via Weaverse Studio. 🚀
* [montalvomiguelo/hydrogen-theme](https://github.com/montalvomiguelo/hydrogen-theme) ⭐ 181 | 🐛 0 | 🌐 Liquid | 📅 2026-08-16 - A port of Hydrogen's default template to Shopify OS 2.0.
* [packdigital/pack-hydrogen-theme-blueprint](https://github.com/packdigital/pack-hydrogen-theme-blueprint) ⭐ 104 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-21 - A fully-featured Shopify Hydrogen starter theme packed with versatile components designed to seamlessly integrate with Pack and Shopify Hydrogen.
* [AEOrank](https://github.com/vinpatel/aeorank/tree/main/packages/shopify) ⭐ 14 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-23 - Hydrogen plugin that generates AI-readable files (llms.txt, ai.txt, CLAUDE.md, schema.json) so ChatGPT and Perplexity can find and cite your products.

### Liquid Template

* [Liquid](https://shopify.github.io/liquid/) - Template language created by Shopify.
* [Liquid Cheat Sheet](https://www.shopify.com/partners/shopify-cheat-sheet) - A resource for building Shopify Themes with Liquid.
* [Liquid template language reference](https://shopify.dev/docs/api/liquid) - Liquid is the backbone of all Shopify themes, and is used to load dynamic content to the pages of online stores.

### Others

* [Shopify Vite](https://github.com/barrel/shopify-vite) ⭐ 458 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-17 - Modern frontend tooling for Shopify theme development using Vite for a best-in-class DX.
* [Shopify UI Extensions](https://github.com/Shopify/ui-extensions) ⭐ 343 | 🐛 445 | 🌐 TypeScript | 📅 2026-08-24 – Repo for the public definition of Shopify’s UI extension APIs. Developers use this to build strongly-typed UI extensions for Shopify surfaces. 🧰

## Mobile

### Buy SDK

You can use the iOS and Android Buy SDK to integrate Shopify checkout into your mobile applications. This lets you sell physical products directly through your app and track sales in your Shopify Admin. [Learn more ›](https://shopify.dev/docs/storefronts/mobile)

* [Shopify Mobile Buy SDK (iOS)](https://github.com/Shopify/mobile-buy-sdk-ios) ⭐ 486 | 🐛 107 | 🌐 Swift | 📅 2026-04-07 - iOS SDK to integrate Shopify checkout within native apps. 🧰
* [Shopify Mobile Buy SDK (Android)](https://github.com/Shopify/mobile-buy-sdk-android) ⭐ 236 | 🐛 113 | 🌐 Java | 📅 2026-05-18 - Android SDK to integrate Shopify checkout within native apps. 🧰
* [Shopify Mobile Apps](https://www.shopify.com/install) - Official Shopify mobile app for merchants.

### Checkout Sheet Kit

Native SDKs for embedding Shopify’s one-page checkout UI directly into mobile apps — supporting styling, lifecycle events, and full checkout integration.

* [Shopify Checkout Sheet Kit (React Native)](https://github.com/Shopify/checkout-sheet-kit-react-native) ⭐ 79 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-24
* [Shopify Checkout Sheet Kit (Swift)](https://github.com/Shopify/checkout-sheet-kit-swift) ⭐ 66 | 🐛 10 | 🌐 Swift | 📅 2026-08-24
* [Shopify Checkout Sheet Kit (Android)](https://github.com/Shopify/checkout-sheet-kit-android) ⭐ 27 | 🐛 15 | 🌐 Kotlin | 📅 2026-08-24

## Libraries

You can use official Shopify libraries or any of the third party libraries below for authenticating and interacting with the Shopify API.

### Ruby

* [A Rails Engine for building Shopify Apps](https://github.com/Shopify/shopify_app) ⭐ 1,925 | 🐛 58 | 🌐 Ruby | 📅 2026-08-23
* [Shopify Ruby API](https://github.com/Shopify/shopify_api) ⭐ 1,103 | 🐛 33 | 🌐 Ruby | 📅 2026-08-04
* [Shopify OAuth2 Strategy for OmniAuth](https://github.com/Shopify/omniauth-shopify-oauth2) ⭐ 92 | 🐛 19 | 🌐 Ruby | 📅 2026-03-27

### Python

* [Shopify Python API](https://github.com/Shopify/shopify_python_api) ⭐ 1,433 | 🐛 24 | 🌐 Python | 📅 2026-04-27
* [django-shopify-auth](https://github.com/discolabs/django-shopify-auth) ⭐ 149 | 🐛 2 | 🌐 Python | 📅 2025-01-17 - A package for adding Shopify authentication to a Django app.
* [Django Shopify Webhook](https://github.com/discolabs/django-shopify-webhook) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2025-02-28 - A package for receiving Shopify Webhooks in Django.

### JavaScript

* [js-buy-sdk](https://github.com/Shopify/js-buy-sdk) ⭐ 1,017 | 🐛 27 | 🌐 JavaScript | 📅 2026-03-27 - Shopify JavaScript Buy SDK. (Check Cart API ⚠️)
* [shopify-api-node](https://github.com/MONEI/Shopify-api-node) ⭐ 978 | 🐛 31 | 🌐 JavaScript | 📅 2025-04-11 - Node.js Shopify connector.
* [Shopify API and app tools for JavaScript](https://github.com/Shopify/shopify-app-js) ⭐ 538 | 🐛 110 | 🌐 TypeScript | 📅 2026-08-21
* [nestjs-shopify](https://github.com/nestjs-shopify/nestjs-shopify) ⭐ 151 | 🐛 22 | 🌐 TypeScript | 📅 2026-08-24 - Packages to develop Shopify application using NestJS.

### DotNet

* [nozzlegear/ShopifySharp](https://github.com/nozzlegear/ShopifySharp) ⭐ 897 | 🐛 226 | 🌐 C# | 📅 2026-08-23 - A .NET library for Shopify.

### Elixir

* [orbit-apps/elixir-shopifyapi](https://github.com/orbit-apps/elixir-shopifyapi) ⭐ 32 | 🐛 15 | 🌐 Elixir | 📅 2026-08-06 - ShopifyAPI and Plug.ShopifyAPI Elixir client.
* [sticksnleaves/exshopify](https://github.com/sticksnleaves/exshopify) ⭐ 13 | 🐛 2 | 🌐 Elixir | 📅 2021-06-02 - Elixir client for the Shopify API. ⚠️

### Java

* [Shopify Java SDK](https://github.com/ChannelApe/shopify-sdk) ⭐ 173 | 🐛 39 | 🌐 Java | 📅 2024-10-18 - Java SDK for Shopify REST APIs.
* [shopify-api-java-wrapper](https://github.com/SevenSpikes/shopify-api-java-wrapper) ⭐ 38 | 🐛 2 | 🌐 Java | 📅 2018-08-09 - The Java wrapper for the Shopify API. ⚠️

### Golang

* [bold-commerce/go-shopify](https://github.com/bold-commerce/go-shopify) ⭐ 394 | 🐛 8 | 🌐 Go | 📅 2026-07-10 - Go client for the Shopify API.
* [gopify](https://github.com/oussama4/gopify) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2022-04-10 - A simple package for developing Shopify applications in Go. ⚠️
* [shoauth](https://github.com/darrenpeters/shoauth) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2015-04-18 - Shopify oauth (oauth2) middleware for Golang. ⚠️
* [go-shopify](https://github.com/kiwih/go-shopify) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2016-05-19 - Golang tool for connecting to Shopify's API. ⚠️

### PHP

* [phpclassic/php-shopify](https://github.com/phpclassic/php-shopify) ⭐ 603 | 🐛 115 | 🌐 PHP | 📅 2026-04-23 - PHP SDK for Shopify API.
* [Kyon147/laravel-shopify](https://github.com/Kyon147/laravel-shopify) ⭐ 492 | 🐛 29 | 🌐 PHP | 📅 2026-07-14 - A full-featured Laravel package for aiding in Shopify App development. ⏱
* [Shopify API Library for PHP](https://github.com/Shopify/shopify-api-php) ⭐ 472 | 🐛 49 | 🌐 PHP | 📅 2026-03-13 - Official library provides support for PHP Shopify apps to access the Shopify Admin API 🚀.
* [ohmybrew/Basic-Shopify-API](https://github.com/osiset/Basic-Shopify-API) ⭐ 249 | 🐛 24 | 🌐 PHP | 📅 2025-01-30 - A simple, tested, API wrapper for Shopify using Guzzle for REST and GraphQL.
* [slince/shopify-api-php](https://github.com/slince/shopify-api-php) ⭐ 132 | 🐛 18 | 🌐 PHP | 📅 2023-10-22 - Shopify API Client for PHP. ⏱
* [ShopifyExtras/PHP-Shopify-API-Wrapper](https://github.com/ShopifyExtras/PHP-Shopify-API-Wrapper) ⭐ 119 | 🐛 31 | 🌐 PHP | 📅 2020-09-24 - Guzzle-based API client. ⏱
* [donutdan4114/shopify](https://github.com/donutdan4114/shopify) ⭐ 85 | 🐛 17 | 🌐 PHP | 📅 2024-08-21 - A simple Shopify PHP SDK for private apps to easily interact with the Shopify API. ⚠️
* [oseintow/laravel-shopify](https://github.com/oseintow/laravel-shopify) ⭐ 71 | 🐛 9 | 🌐 PHP | 📅 2023-08-29 - Laravel Shopify is a simple package which helps to build robust integration into Shopify. ⚠️
* [ZfrShopify](https://github.com/zf-fr/zfr-shopify) ⭐ 36 | 🐛 12 | 🌐 PHP | 📅 2023-07-15 - Guzzle client around Shopify API.
* [bold-shopify-toolkit](https://github.com/bold-commerce/bold-shopify-toolkit) ⭐ 26 | 🐛 9 | 🌐 PHP | 📅 2026-06-22 - A Symfony Based Shopify api wrapper.
* [pizdata/oauth2-shopify-php](https://github.com/pizdata/oauth2-shopify-php) ⭐ 14 | 🐛 0 | 🌐 PHP | 📅 2021-06-24 - Shopify Provider for the OAuth 2.0 Client. ⏱
* [multidimension-al/oauth2-shopify](https://github.com/multidimension-al/oauth2-shopify) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2025-02-26 - Shopify's OAuth 2.0 support for the PHP League's OAuth 2.0 Client. ⏱
* [tothjmt/Laravel-Shopify](https://github.com/tothjmt/Laravel-Shopify) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2016-01-07 - A Laravel / Shopify API Wrapper. ⚠️

### R

* [shopifyr](https://github.com/charliebone/shopifyr/) ⭐ 23 | 🐛 0 | 🌐 R | 📅 2019-08-11 - Aims to provide an easy-to-use interface to the Shopify Admin API within R. ⏱

### Rust

* [Shopify Function Rust](https://github.com/Shopify/shopify-function-rust) ⭐ 47 | 🐛 9 | 🌐 Rust | 📅 2026-08-19
* [Ventmere/shopify](https://github.com/Ventmere/shopify/) ⭐ 19 | 🐛 1 | 🌐 Rust | 📅 2024-12-03 - Shopify API Client for Rust. ⏱⚠️
* [Shopify API Client for Rust](https://github.com/0xtlt/shopify_api) ⭐ 18 | 🐛 8 | 🌐 Rust | 📅 2026-07-28
* [shopify-api-rust](https://github.com/saschabratton/shopify-api-rust) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-08-10 - Rust SDK for the Shopify API.
* [Shopify Rust Client](https://github.com/sinha-sahil/shopify-rust-client) ⭐ 2 | 🐛 2 | 🌐 Rust | 📅 2026-08-13 - A type-safe, async Rust client for the Shopify Admin API.

## Example Apps

### Shopify App Templates

* [Shopify App Template (React Router)](https://github.com/Shopify/shopify-app-template-react-router) ⭐ 194 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-23 - Template for Shopify apps using React Router for routing instead of Next.js or Remix.
* [Shopify Payments App Template (Remix)](https://github.com/Shopify/example-app--payments-app-template--remix) ⭐ 27 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-24 - Remix template for building Shopify apps with payments integration (Payments App API support). 🚀
* [Shopify Credit Card Payments Template (Remix)](https://github.com/Shopify/example-app--credit-card-payments-app-template--remix) ⭐ 16 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-24 - Remix example showing Credit Card Payments integration using Shopify’s Payments API. 🏦
* [Shopify Optional Scopes Example (Remix)](https://github.com/Shopify/example-app--optional-scopes--remix) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-01 - Example showing how to request optional API scopes during app installation, built with Remix.
* [Shopify Address Autocomplete Example (Preact)](https://github.com/Shopify/example-checkout--address-autocomplete--preact) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-07 - Checkout example using Preact to demonstrate address autocomplete enhancements on Shopify checkout.
* [Shopify Firebase App](https://github.com/mksd0398/create-shopify-firebase-app) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-01 - CLI that scaffolds an embedded Shopify app on Firebase Hosting, Cloud Functions and Firestore, as an alternative to the Remix and React Router templates.

### JavaScript Examples

* [Storefront API Examples](https://github.com/Shopify/storefront-api-examples) ⚠️ Archived - Example custom storefront applications built on Shopify's Storefront API. ⚠️
* [Shopify App Node](https://github.com/Shopify/shopify-app-template-node) ⭐ 1,012 | 🐛 50 | 🌐 JavaScript | 📅 2026-08-05 - Boilerplate to create an embedded Shopify app made with Node, Next.js, Shopify-koa-auth, Polaris, and App Bridge React :sunny:.
* [VienDinhCom/next-shopify-storefront](https://github.com/VienDinhCom/next-shopify-storefront) ⭐ 867 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-11 - A shopping cart using TypeScript, Tailwind CSS, Headless UI, Next.js, React.js, Hydrogen, and GraphQL API.
* [Shopify App Template Remix](https://github.com/Shopify/shopify-app-template-remix) ⭐ 555 | 🐛 72 | 🌐 TypeScript | 📅 2026-08-05 - A template for building a Shopify app using the Remix framework.
* [Shopify app with Next.js and Prisma ORM](https://github.com/kinngh/shopify-nextjs-prisma-app) ⭐ 510 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-15 - Starter template for building embedded Shopify apps using Next.js and Prisma ORM, preconfigured with essential integrations.
* [Product Reviews Sample App](https://github.com/Shopify/product-reviews-sample-app) ⭐ 378 | 🐛 28 | 🌐 JavaScript | 📅 2026-02-13 - Sample app was built as a reference for how Shopify Developer tools can be used together to create a fully functional application.
* [Shopify app with Node.js, MongoDB, React.js and Express](https://github.com/kinngh/shopify-node-express-mongodb-app) ⭐ 343 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-15 - Boilerplate embedded app made with Express.js, MongoDB and React.js with webhooks, GDPR routes, monetization and more hooked up and ready to go.
* [Vue Storefront 2](https://github.com/vuestorefront/shopify) ⚠️ Archived - Frontend platform for headless commerce. ⚠️
* [Next.js App with Session Token](https://github.com/ctrlaltdylan/shopify-session-tokens-nextjs) ⭐ 106 | 🐛 2 | 🌐 JavaScript | 📅 2021-10-31 - An example of a Shopify App powered by Next.js with Session Tokens (no custom server necessary). ⚠️
* [Shopify Discount App Components)](https://github.com/Shopify/discount-app-components) ⭐ 87 | 🐛 19 | 🌐 TypeScript | 📅 2026-04-28 - A library of discounts-focused React components to help in building Shopify apps.
* [Shopify App Vue Template](https://github.com/Mini-Sylar/shopify-app-vue-template) ⭐ 86 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-15 - Create a Shopify App with node and vue 3.
* [SmallAwesomeShop](https://github.com/JsssCode/SmallAwesomeShop) ⭐ 43 | 🐛 3 | 🌐 TypeScript | 📅 2018-10-17 - An Angular 7 App example using Shopify's Storefront GraphQL API. ⚠️
* [Shopify App Starter (TypeScript, Mongo, Express, React)](https://github.com/yoMerce/shopify-app-starter) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2022-09-06 - A shopify app starter written in TypeScript. It uses MongoDB, Express and React. ⚠️

### PHP Examples

* [shopify-app-php](https://github.com/Shopify/shopify-app-template-php) ⭐ 337 | 🐛 89 | 🌐 PHP | 📅 2026-08-05 - Example Shopify PHP app (Laravel).

### Python Examples

* [shopify\_django\_app](https://github.com/shopify/shopify_django_app) ⭐ 505 | 🐛 15 | 🌐 Python | 📅 2025-05-13 - Shopify Django App Example.

### Ruby Examples

* [Shopify App Template (Ruby)](https://github.com/Shopify/shopify-app-template-ruby) ⭐ 154 | 🐛 9 | 🌐 Ruby | 📅 2026-08-05 - A Rails + React template for building Shopify apps with OAuth, GraphQL & REST APIs, webhooks, and embedded support. 🧰
* [Shopify Fulfillment Integration](https://github.com/Shopify/shopify-fulfillment-integration) ⚠️ Archived - Example Fulfillment Service Integration with Shopify. ⚠️
* [Hosted Payment Simulator](https://github.com/Shopify/hosted-payment-sim) ⚠️ Archived - Example of using the [Hosted Payment SDK](https://shopify.dev/apps/payments/hosted-payment-sdk). ⚠️
* [partner-metrics](https://github.com/forsbergplustwo/partner-metrics) ⭐ 64 | 🐛 11 | 🌐 Ruby | 📅 2026-08-17 - Metrics Dashboard for Shopify Partners, on Rails. ⚠️
* [Shopify app starter kit](https://github.com/ASoftCo/shopify-app-starter-kit) ⭐ 42 | 🐛 0 | 🌐 Ruby | 📅 2019-04-23 - A Shopify app boilerplate written in Ruby on Rails with appropriate tools to get your Shopify app up and running quickly. ⚠️
* [shopify-tax-receipts](https://github.com/kevinhughes27/shopify-tax-receipts) ⚠️ Archived - Shopify app for automatically sending tax receipts when specified products are purchased. ⚠️
* [Shopify Surge Pricing](https://github.com/kevinhughes27/shopify-surge-pricing) ⚠️ Archived - A demo of surge pricing for Shopify based on cart update webhooks. ⚠️

### Elixir Examples

* [Elixir Shopify App (Phoenix)](https://github.com/orbit-apps/elixir-shopify-app) ⭐ 20 | 🐛 14 | 🌐 Elixir | 📅 2025-03-04

## Code Snippets

* [freakdesign/shopify-code-snippets](https://github.com/freakdesign/Shopify-code-snippets) ⭐ 599 | 🐛 8 | 🌐 Liquid | 📅 2020-10-04 - Shopify Code Snippets examples and tips.
* [vikrantnegi/shopify-code-snippets](https://github.com/vikrantnegi/shopify-code-snippets) ⭐ 261 | 🐛 0 | 🌐 Liquid | 📅 2023-12-31 - A compilation of code snippets for Shopify developers.
* [gocomet/snippets](https://github.com/gocomet/snippets) ⭐ 127 | 🐛 0 | 🌐 Liquid | 📅 2017-03-06 - A collection of code snippets, generally for use with Shopify.
* [PROPS!](http://props.tools/) - Copy-paste customizable, theme-agnostic\* custom liquid sections.

## Developer Tools

### CLI Tools

* [Theme Kit](https://github.com/Shopify/themekit) ⭐ 1,318 | 🐛 113 | 🌐 Go | 📅 2025-11-20 - Shopify theme development command line tool. ⚠️
* [Shopify CLI](https://github.com/Shopify/cli) ⭐ 733 | 🐛 146 | 🌐 TypeScript | 📅 2026-08-24 - CLI to build apps, themes, and hydrogen storefronts for Shopify 🚀.
* [Theme Check](https://github.com/Shopify/theme-check) ⚠️ Archived - The Ultimate Shopify Theme Linter. ⚠️

### CI/CD & Deployment

* [Shopify Online Store (GitHub Marketplace)](https://github.com/marketplace/shopify-online-store) - Automates Shopify theme deployments from GitHub pushes, streamlining your CI/CD workflow.

### Editors

* [vim-liquid](https://github.com/tpope/vim-liquid) ⭐ 132 | 🐛 4 | 🌐 Vim Script | 📅 2025-07-12
* [zed-shopify-liquid](https://github.com/TheBeyondGroup/zed-shopify-liquid) ⭐ 26 | 🐛 3 | 🌐 Tree-sitter Query | 📅 2026-04-07
* [Shopify Liquid for VS Code](https://marketplace.visualstudio.com/items?itemName=Shopify.theme-check-vscode)

### AI tools

* [Agent plugins/extensions for CLIs and IDEs](https://github.com/shopify/shopify-ai-toolkit) ⭐ 511 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-19

### Services

* [ShopSavvy](https://github.com/shopsavvy/shopify-shopsavvy) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-01 - Shopify app for competitor price monitoring and real-time price comparison across thousands of retailers.
* [Ngrok](https://ngrok.com) - A tool that makes it easy to expose your development environment to Internet.
* [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) - To configure local server using cloudflare.
* [RequestBin](https://requestbin.net/) - It gives you a bucket to capture external requests. This is useful for seeing what the content of a [Shopify Webhook](https://shopify.dev/docs/api/webhooks) are.
* [Hookdeck](https://hookdeck.com/) - Tool for monitoring, managing and debugging Shopify Webhooks with custom retry logic, alerts, and filtering.
* [DeployHQ](https://www.deployhq.com/shopify) - Shopify integration in DeployHQ is a great way to streamline the development, review, and deployment of your store themes.
* [Calcmatic Shopify Payment Calculator](https://calcmatic.app/calculators/ecommerce/shopify-payments) - Calculate your Shopify payment processing fees instantly.

### Browser Extensions

* [Shopify App Detector](https://chrome.google.com/webstore/detail/shopify-app-detector-by-f/lhfdhjladfcmghahdbcmlceajdlbkale) - Detect which apps and what theme a Shopify store is using. [GitHub](https://github.com/feracommerce/shopify_app_detector) ⭐ 111 | 🐛 3 | 🌐 JavaScript | 📅 2024-02-01
* [Shopify Theme Inspector for Chrome](https://chrome.google.com/webstore/detail/shopify-theme-inspector-f/fndnankcflemoafdeboboehphmiijkgp) - Profile and debug Liquid template on your Shopify store.
* [Shopify Theme Wizard](https://chrome.google.com/webstore/detail/shopify-app-detector-by-e/fhkelfkhcaokghlkckfgjoejhanelped) - Detect which theme a Shopify store is using.
* [Shopify Theme Detector](https://podifai.com/tools/shopify-theme-detector/) - Free tool to identify what Shopify theme any store is using, including theme version, customizations, and technology stack.

### Raycast Extension

* [Shopify Liquid Docs Search](https://www.raycast.com/maximedaraize/search-shopify-liquid-documentation) - Search and preview Shopify Liquid docs.
* [Developer Changelog](https://www.raycast.com/sandypockets/shopify-developer-changelog) - View the latest Shopify developer changelog.

### Utilities

* [Shopify Product CSVs](https://github.com/shopifypartners/product-csvs) ⭐ 404 | 🐛 2 | 📅 2023-03-30 - Get your Shopify development stores started with great product data.
* [Shopify Product CSVs and Images](https://github.com/shopifypartners/shopify-product-csvs-and-images) ⭐ 136 | 🐛 0 | 📅 2017-03-31 - Get your Shopify development stores started with great product data.

## Community

* [Shopify Devs on X](https://x.com/ShopifyDevs)
* [Reddit – /r/shopify](https://www.reddit.com/r/shopify/)
* [Reddit – /r/shopifyDev](https://www.reddit.com/r/shopifyDev/)
* [Shopify Figma Community](https://www.figma.com/@Shopify)
* [Developer Forums](https://community.shopify.dev) - Shopify Developer Community Forums.
* [Developers Discord](https://discord.com/invite/shopify-developers-597504637167468564) - Official Shopify Developers Discord server.
* [Merchants Community](https://community.shopify.com/) - Discussing eCommerce best practices and how to have a successful online store.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/julionc/awesome-shopify/blob/main/contributing.md) ⭐ 1,269 | 🐛 6 | 📅 2026-08-13 first.

Thanks to all [contributors](https://github.com/julionc/awesome-shopify/graphs/contributors) ⭐ 1,269 | 🐛 6 | 📅 2026-08-13 — you're awesome and this wouldn’t be possible without you! 🙌

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
