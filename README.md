# ngy-tutorial

Ngy-Tutorial is an Angular plugin that gives your app a built-in, customizable, user-friendly, literally "getting started" 🤓 tutorial.

So you've got your killer UI that's intutive, slick and responsive, but will everyone know how to use it? What about some nice shortcuts or features that you want to highlight? Or maybe some UI changes that you want the users to be aware of? No one really want's to read through a long readme file, so how about a interactive, in-app tutorial? Ngy-Tutorial literally adds a step-by-step "tutorial" to your app so you can highlight your cool UI and give every user a head start.

Check out the Demo!

## Highlghts

 - Customizable steps that allows you to add and remove steps on the fly.
 - Per-step adjustable focus that hightlights any revelant elements by DOM id.
 - Ability to allow/disallow interaction with your live app while tutorial is progressing.
 - Programmatic navigation and control allow you to customize the experience to your need.
 - Customizable prompt and button styling.

## Built With

Ngy-Tutorial is built with Angular 6, icons from IonIcons

## Installation

Add the library by using npm with `npm install ngy-tutorial` or yarn with `yarn add ngy-tutorial`

## Getting Started (even the tutorial needs a tutorial)

1. Install the package with npm or yarn.
2. Add the module to your root module with `NgyTutorialModule.forRoot()` under `imports` in your `app.module.ts`.

    ```typescript
        @NgModule({
        declarations: [
            AppComponent
        ],
        imports: [
            BrowserModule,
            NgyTutorialModule.forRoot()
        ],
        providers: [],
        bootstrap: [AppComponent]
        })
        export class AppModule { }
    ```

3. Place element `<ngy-tutorial></ngy-tutorial>` in your app.
4. You can now inject and use `NgyTutorial` service to control the tutorial, see the API for available commands.