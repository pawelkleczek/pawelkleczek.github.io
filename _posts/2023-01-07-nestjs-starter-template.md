---
title: NestJS Starter Template
date: 2023-01-07 14:06:27 +0100
categories: [NestJS]
tags: [nestjs, template]     # TAG names should always be lowercase
---

Here's a fun list of extras to add some flair to your brand new NestJS project created with the NestJS CLI. Think of it as a makeover for your code! Each new change is marked with its own special git tag, so you can keep track of your fabulous upgrades.

## Initialize Project

Install NestJS CLI and running the `new` command.

```shell
npm i -g @nestjs/cli
nest new nestjs-starter-template
```

[Example Init](https://github.com/pawelkleczek/nestjs-starter-template/tree/1-init)

## Project Structure

Let's shake things up and plan our project's fancy new outfit! With Nest Starter, you've got the freedom to arrange your project's folders however you like. Usually, services and controllers are snug as a bug in a rug in the `src/modules` folder and `src/app.module.ts` just acts as the stylish launching pad.

[Example Structure](https://github.com/pawelkleczek/nestjs-starter-template/tree/2-structure)

## App Factory

Let's add some zing to our app setup! Create some factory methods that bring the app to life and add any needed middleware. This keeps things neat and tidy, making it easier to build tests and create lambda handlers. And with these factory methods, `src/main.ts` can just focus on starting the party and getting the server up and running!

[Example Factory](https://github.com/pawelkleczek/nestjs-starter-template/tree/3-factory)

## Validation Pipe

Put some pep in your request validation step! Use the ValidationPipe to ensure that incoming data follows the rules. The built-in ValidationPipe is a great starting point, but for more elaborate needs, you can step up your game with a custom pipe. Check out the [custom pipe docs](https://docs.nestjs.com/pipes#custom-pipes) for more info!

[Example Validation](https://github.com/pawelkleczek/nestjs-starter-template/tree/4-validation)

## Exception Handling

Let's spice up error handling with a custom HTTP exception filter! After all, proper exception handling is the cherry on top of any top-notch application. And while NestJS has some killer built-in solutions, sometimes our apps just need a little extra pizzazz, like condensing error messages into a sweet, single string or crafting custom errors for specific scenarios. So why not throw a global exception handler party in an HTTP exception filter?

[Example Filter](https://github.com/pawelkleczek/nestjs-starter-template/tree/5-filter)

## Logging Interceptor

Get ready for some serious fun with the Logging Interceptor in NestJS! This AOP-inspired tool can add a whole new level of awesomeness to your project. It's perfect for transforming incoming and outgoing data, extending functionality, or even completely overriding functions (just imagine the cache possibilities!). While it may not seem crucial at first, the Logging Interceptor will quickly become your new best friend. So grab your seatbelt and let's start exploring the powerful ArgumentsHost context utility and dreaming up other cool ways to use this amazing tool!

[Example Interceptor](https://github.com/pawelkleczek/nestjs-starter-template/tree/6-interceptor)
