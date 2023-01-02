---
title: NestJS Starter Template
date: 2021-01-27 14:06:27 +0100
categories: [NestJS]
tags: [nestjs, template]     # TAG names should always be lowercase
---

Here's a fun list of extras to add some flair to your brand new NestJS project created with the NestJS CLI. Think of it as a makeover for your code! Each new change is marked with its own special git tag, so you can keep track of your fabulous upgrades.

## Initialize new project

Install NestJS CLI and running the `new` command.

```shell
npm i -g @nestjs/cli
nest new nestjs-starter-template
```

[Example Init](https://github.com/pawelkleczek/nestjs-starter-template/tree/init-service)

## Project structure

Let's shake things up and plan our project's fancy new outfit! With Nest Starter, you've got the freedom to arrange your project's folders however you like. Usually, services and controllers are snug as a bug in a rug in the `src/modules` folder and `src/app.module.ts` just acts as the stylish launching pad.

[Example Structure](https://github.com/pawelkleczek/nestjs-starter-template/tree/structure)

## App factory

Let's add some zing to our app setup! Create some factory methods that bring the app to life and add any needed middleware. This keeps things neat and tidy, making it easier to build tests and create lambda handlers. And with these factory methods, src/main.ts can just focus on starting the party and getting the server up and running!

[Example factory](https://github.com/pawelkleczek/nestjs-starter-template/tree/factory)

## Validation

Put some pep in your request validation step! Use the ValidationPipe to ensure that incoming data follows the rules. The built-in ValidationPipe is a great starting point, but for more elaborate needs, you can step up your game with a custom pipe. Check out the [custom pipe docs](https://docs.nestjs.com/pipes#custom-pipes) for more info!

[Example validation](https://github.com/pawelkleczek/nestjs-starter-template/tree/validation)