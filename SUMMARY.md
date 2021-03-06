* [Introduction](./intro.md)
* [License](handout/license.md)
* [Why Angular?](handout/why_angular_2.md)

---

* [EcmaScript 6 and TypeScript Features](handout/features/README.md)
  * [ES6](handout/features/es6.md)
       * [Classes](handout/features/classes.md)
       * [Refresher on 'this'](handout/features/refresher_on_this.md)
       * [Arrow Functions](handout/features/arrow_functions.md)
       * [Template Strings](handout/features/template_strings.md)
       * [Inheritance](handout/features/inheritance.md)
       * [Delegation](handout/features/delegation.md)
       * [Constants and Block Scoped Variables](handout/features/constants_and_block_scoped_variables.md)
       * [...spread and ...rest](handout/features/spread_and_rest.md)
       * [Destructuring](handout/features/destructuring.md)
       * [Modules](handout/features/es6_modules.md)
  * [TypeScript](handout/features/typescript.md)
       * [Getting Started With TypeScript](handout/features/getting_started_with_typescript.md)
       * [Working With `tsc`](handout/features/working_with_tsc.md)
       * [Typings](handout/features/typings.md)
       * [Linting](handout/features/linting.md)
       * [TypeScript Features](handout/features/typescript_features.md)
       * [TypeScript Classes](handout/features/typescript_classes.md)
       * [Interfaces](handout/features/interfaces.md)
       * [Shapes](handout/features/shapes.md)
       * [Type Inference](handout/features/type_inference.md)
       * [Type Keyword](handout/features/type_keyword.md)
       * [Decorators](handout/features/decorators.md)
       * [Property Decorators](handout/features/property_decorators.md)
       * [Class Decorators](handout/features/class_decorators.md)
       * [Parameter Decorators](handout/features/parameter_decorators.md)

---

* [The JavaScript Toolchain](handout/tooling/README.md)
   * [Source Control: git](handout/tooling/source_control.md)
   * [The Command Line](handout/tooling/the_command_line.md)
   * [Command Line JavaScript: NodeJS](handout/tooling/command_line_javascript.md)
   * [Back-End Code Sharing and Distribution: npm](handout/tooling/back_end_code_sharing_and_distribution.md)
   * [Module Loading, Bundling and Build Tasks: Webpack](handout/tooling/module_loading_bundling_and_build_tasks.md)
   * [Chrome](handout/tooling/chrome.md)

---

* [Bootstrapping an Angular Application](handout/bootstrapping/README.md)
   * [Understanding the File Structure](handout/bootstrapping/file_structure.md)
   * [Bootstrapping Providers](handout/bootstrapping/bootstrapping_providers.md)

---

* [Components in Angular](handout/components/README.md)
   * [Creating Components](handout/components/creating_components.md)
   * [Application Structure with Components](handout/components/app_structure_with_components.md)
       * [Passing Data into a Component](handout/components/app_structure/passing_data_into_components.md)
       * [Responding to Component Events](handout/components/app_structure/responding_to_component_events.md)
       * [Using Two-Way Data Binding](handout/components/app_structure/two_way_data_binding.md)
       * [Accessing Child Components from Template](handout/components/app_structure/access_child_components_from_template.md)
   * [Projection](handout/components/projection.md)
   * [Structuring Applications with Components](handout/components/structuring_applications_with_components.md)
   * [Using Other Components](handout/components/using_other_components.md)

---

* [Directives](handout/directives/README.md)
    * [Attribute Directives](handout/directives/attribute_directives.md)
        * [NgStyle Directive](handout/directives/ng_style_directive.md)
        * [NgClass Directive](handout/directives/ng_class_directive.md)
    * [Structural Directives](handout/directives/structural_directives.md)
        * [NgIf Directive](handout/directives/ng_if_directive.md)
        * [NgFor Directive](handout/directives/ng_for_directive.md)
        * [NgSwitch Directives](handout/directives/ng_switch_directives.md)
        * [Using Multiple Structural Directives](handout/directives/using_multiple_structural_directives.md)

---

* [Advanced Components](handout/advanced-components/README.md)
   * [Component Lifecycle](handout/advanced-components/component_lifecycle.md)
   * [Accessing Other Components](handout/advanced-components/access_child_components.md)
   * [View Encapsulation](handout/advanced-components/view_encapsulation.md)
   * [ElementRef](handout/advanced-components/elementref.md)

---

* [Observables](handout/observables/README.md)
   * [Using Observables](handout/observables/using_observables.md)
   * [Error Handling](handout/observables/error_handling.md)
   * [Disposing Subscriptions and Releasing Resources](handout/observables/disposing_subscriptions_and_releasing_resources.md)
   * [Observables vs Promises](handout/observables/observables_vs_promises.md)
   * [Using Observables From Other Sources](handout/observables/using_observables_from_other_sources.md)
   * [Observables Array Operations](handout/observables/observables_array_operations.md)
   * [Cold vs Hot Observables](handout/observables/cold_vs_hot_observables.md)
   * [Summary](handout/observables/summary.md)

---

* [Angular Dependency Injection](handout/di/README.md)
   * [What is DI?](handout/di/what_is_di.md)
   * [DI Framework](handout/di/di_framework.md)
   * [Angular's DI](handout/di/angular2/README.md)
       * [`@Inject()` and `@Injectable`](handout/di/angular2/inject_and_injectable.md)
       * [Injection Beyond Classes](handout/di/angular2/injection_beyond_classes.md)
       * [Avoiding Injection Collisions: OpaqueToken](handout/di/angular2/avoiding_collisions_opaque_token.md)
       * [The Injector Tree](handout/di/angular2/the_injector_tree.md)

---

* [Http](handout/http/README.md)
   * [Making Requests](handout/http/making_requests.md)
   * [Catching Rejections](handout/http/catching-rejections/README.md)
       * [Catch and Release](handout/http/catching-rejections/catch_and_release.md)
       * [Cancel a Request](handout/http/catching-rejections/cancel_request.md)
       * [Retry](handout/http/catching-rejections/retry.md)
   * [Search with flatMap](handout/http/search_with_flatmap.md)
   * [Enhancing Search with switchMap](handout/http/search_with_switchmap.md)
   * [Requests as Promises](handout/http/requests_as_promises.md)

---

* [Change Detection](handout/change-detection/README.md)
   * [Change Detection Strategies in Angular 1 vs Angular 2](handout/change-detection/angular_1_vs_angular_2.md)
   * [How Change Detection Works](handout/change-detection/how_change_detection_works.md)
   * [Change Detector Classes](handout/change-detection/change_detector_classes.md)
   * [Change Detection Strategy: OnPush](handout/change-detection/change_detection_strategy_onpush.md)
   * [Enforcing Immutability](handout/change-detection/enforcing_immutability.md)
   * [Additional Resources](handout/change-detection/additional_resources.md)

---

* [Zone.js](handout/zones/README.md)

---

* [Advanced Angular](handout/advanced-angular/README.md)
    * [Directives](handout/advanced-angular/directives/README.md)
        * [Creating an Attribute Directive](handout/advanced-angular/directives/creating_an_attribute_directive.md)
            * [Listening to an Element Host](handout/advanced-angular/directives/listening_to_an_element_host.md)
            * [Setting Properties in a Directive](handout/advanced-angular/directives/setting_properties_in_a_directive.md)
        * [Creating a Structural Directive](handout/advanced-angular/directives/creating_a_structural_directive.md)
            * [View Containers and Embedded Views](handout/advanced-angular/directives/view_containers_and_embedded_views.md)
            * [Providing Context Variables to Directives](handout/advanced-angular/directives/providing_context_variables_to_directives.md)
    * [AoT](handout/aot/README.md)
        * [AoT limitations](handout/aot/aot_limitations.md)
        * [AoT Configuration](handout/aot/aot_config.md)

---

* [Immutable.js](handout/immutable/README.md)
   * [What is Immutability?](handout/immutable/what_is_immutability.md)
   * [The Case for Immutability](handout/immutable/the_case_for_immutability.md)
   * [JavaScript Solutions](handout/immutable/javascript-solutions/README.md)
       * [Object.assign](handout/immutable/javascript-solutions/object_assign.md)
       * [Object.freeze](handout/immutable/javascript-solutions/object_freeze.md)
   * [Immutable.js Basics](handout/immutable/immutable-js/README.md)
       * [Immutable.Map](handout/immutable/immutable-js/maps/README.md)
           * [Map.merge](handout/immutable/immutable-js/maps/map_merge.md)
       * [Nested Objects](handout/immutable/immutable-js/nested-objects/README.md)
           * [Deleting Keys](handout/immutable/immutable-js/nested-objects/deleting_keys.md)
           * [Maps are Iterable](handout/immutable/immutable-js/nested-objects/maps_are_iterable.md)
       * [Immutable.List](handout/immutable/immutable-js/lists.md)
       * [Performance and Transient Changes](handout/immutable/immutable-js/performance_transient_changes.md)
       * [Official Documentation](handout/immutable/immutable-js/official_documentation.md)

---

* [Pipes](handout/pipes/README.md)
   * [Using Pipes](handout/pipes/using_pipes.md)
   * [Custom Pipes](handout/pipes/custom_pipes.md)
   * [Stateful Pipes](handout/pipes/stateful_and_async_pipes.md)

---

* [Forms](handout/forms/README.md)
  * [Getting Started](handout/forms/getting-started.md)
  * [Template-Driven Forms](handout/forms/template-driven/template-driven_forms.md)
    * [Nesting Form Data](handout/forms/template-driven/nested-form-data.md)
    * [Using Template Model Binding](handout/forms/template-driven/template-model-binding.md)
    * [Validating Template-Driven Forms](handout/forms/template-driven/validating_forms.md)
  * [Reactive/Model-Driven Forms](handout/forms/reactive-forms/reactive-forms.md)
    * [FormBuilder Basics](handout/forms/reactive-forms/reactive-forms_basics.md)
    * [Validating FormBuilder Forms](handout/forms/reactive-forms/reactive-forms_validation.md)
    * [FormBuilder Custom Validation](handout/forms/reactive-forms/reactive-forms_custom_validation.md)
  * [Visual Cues for Users](handout/forms/ux/visual_cues_for_users.md)

---

* [Modules](handout/modules/README.md)
   * [What is an Angular Module?](handout/modules/introduction.md)
   * [Adding Components, Pipes and Services to a Module](handout/modules/multiple-elements.md)
   * [Creating a Feature Module](handout/modules/feature-modules.md)
   * [Directive Duplications](handout/modules/directive-duplications.md)
   * [Lazy Loading a Module](handout/modules/lazy-loading-module.md)
   * [Lazy Loading and the Dependency Injection Tree](handout/modules/lazy-load-di.md)
   * [Shared Modules and Dependency Injection](handout/modules/shared-modules-di.md)
   * [Sharing the Same Dependency Injection Tree](handout/modules/shared-di-tree.md)

---

* [Routing](handout/routing/README.md)
   * [Why Routing?](handout/routing/why_routing.md)
   * [Configuring Routes](handout/routing/config.md)
   * [Redirecting the Router to Another Route](handout/routing/redirects.md)
   * [Defining Links Between Routes](handout/routing/routerlink.md)
   * [Dynamically Adding Route Components](handout/routing/routeroutlet.md)
   * [Using Route Parameters](handout/routing/routeparams.md)
   * [Defining Child Routes](handout/routing/child_routes.md)
   * [Controlling Access to or from a Route](handout/routing/route_guards.md)
   * [Passing Optional Parameters to a Route](handout/routing/query_params.md)
   * [Using Auxiliary Routes](handout/routing/aux-routes.md)

---

* [State Management](handout/state-management/README.md)
   * [Redux and @ngrx](handout/state-management/ngrx/README.md)
      * [Adding @ngrx to your Project](handout/state-management/ngrx/adding_ngrx_to_your_project.md)
      * [Defining your Main Application State](handout/state-management/ngrx/defining_your_main_application_state.md)
      * [Example Application](handout/state-management/ngrx/example_application.md)
      * [Reading your Application State using Selectors](handout/state-management/ngrx/reading_your_application_state_using_selectors.md)
      * [Actions](handout/state-management/ngrx/actions.md)
      * [Modifying your Application State by Dispatching Actions](handout/state-management/ngrx/modifying_your_application_state_by_dispatching_actions.md)
      * [Reducers and Pure Functions](handout/state-management/ngrx/reducers_and_pure_functions.md)
      * [Reducers as State Management](handout/state-management/ngrx/reducers_as_state_management.md)
      * [Creating your Application's Root Reducer](handout/state-management/ngrx/creating_your_applications_root_reducer.md)
      * [Configuring your Application](handout/state-management/ngrx/configuring_your_application.md)
      * [Implementing Components](handout/state-management/ngrx/implementing_components.md)
      * [Component Architecture](handout/state-management/ngrx/component_architecture.md)
      * [Side Effects](handout/state-management/ngrx/side_effects.md)
      * [Getting More From Redux and @ngrx](handout/state-management/ngrx/getting_more_from_redux_and_ngrx.md)

---

* [TDD Testing](handout/testing/README.md)
   * [The Testing Toolchain](handout/testing/intro-to-tdd/toolchain.md)
   * [Test Setup](handout/testing/intro-to-tdd/setup/README.md)
       * [Filename Conventions](handout/testing/intro-to-tdd/setup/filename-conventions.md)
       * [Karma Configuration](handout/testing/intro-to-tdd/setup/karma-config.md)
       * [TestBed Configuration (Optional)](handout/testing/intro-to-tdd/setup/testbed-configuration.md)
       * [Typings](handout/testing/intro-to-tdd/setup/typings.md)
       * [Executing Test Scripts](handout/testing/intro-to-tdd/setup/execute.md)
   * [Simple Test](handout/testing/intro-to-tdd/simple-test.md)
   * [Using Chai](handout/testing/intro-to-tdd/using-chai.md)
   * [Testing Components](handout/testing/components/README.md)
       * [Verifying Methods and Properties](handout/testing/components/verify.md)
       * [Injecting Dependencies and DOM Changes](handout/testing/components/injecting-dependencies.md)
           * [Overriding Components for Testing](handout/testing/components/overriding.md)
       * [Testing Asynchronous Actions](handout/testing/components/async.md)
       * [Refactoring Hard-to-Test Code](handout/testing/components/refactor.md)
   * [Testing Services](handout/testing/services/README.md)
       * [Testing Strategies for Services](handout/testing/services/strategies.md)
       * [Testing HTTP Requests](handout/testing/services/http.md)
           * [Using MockBackend](handout/testing/services/mockbackend.md)
           * [Alternative Mocking Strategy](handout/testing/services/alt-http-mocking.md)
           * [Testing JSONP and XHR Back-Ends](handout/testing/services/json-xhr.md)
       * [Executing Tests Asynchronously](handout/testing/services/async-execution.md)
   * [Testing Redux](handout/testing/redux/README.md)
       * [Testing Simple Actions](handout/testing/redux/simple-actions.md)
       * [Testing Complex Actions](handout/testing/redux/complex-actions.md)
       * [Testing Reducers](handout/testing/redux/reducers.md)
       * [Afterthoughts](handout/testing/redux/after-thoughts.md)

---

* [Migrating Angular 1.x Projects to Angular 2](handout/migrate/README.md)
   * [Migration Prep](handout/migrate/migration-prep/README.md)
       * [Upgrading To Angular 1.3+ Style](handout/migrate/migration-prep/upgrade_to_angular_1_3.md)
       * [Using Webpack](handout/migrate/migration-prep/use_webpack.md)
       * [Migrating To TypeScript](handout/migrate/migration-prep/migrate_to_typescript.md)
   * [Choosing an Upgrade Path](handout/migrate/choose_a_path.md)
   * [Avoiding Total Conversion](handout/migrate/total_conversion.md)
   * [Using ng-metadata (Angular 1.x Using 2 Style)](handout/migrate/ng-metadata/README.md)
       * [Bootstrapping ng-metadata](handout/migrate/ng-metadata/bootstrap.md)
       * [Components and Services](handout/migrate/ng-metadata/components-and-services.md)
   * [Using ng-upgrade (Angular 1.x Coexisting With Angular 2)](handout/migrate/ng-upgrade/README.md)
       * [Order of Operations](handout/migrate/ng-upgrade/order_of_operations.md)
       * [Replacing Services with TypeScript Classes](handout/migrate/ng-upgrade/replacing_services.md)
       * [Bootstrapping ng-upgrade](handout/migrate/ng-upgrade/bootstrap.md)
       * [Downgrading Components](handout/migrate/ng-upgrade/downgrade-component.md)
       * [Upgrading Components](handout/migrate/ng-upgrade/upgrade-component.md)
       * [Projecting Angular 1 Content into Angular 2 Components](handout/migrate/ng-upgrade/projection.md)
       * [Transcluding Angular 2 Components into Angular 1 Directives](handout/migrate/ng-upgrade/transclusion.md)
       * [Injecting Across Frameworks](handout/migrate/ng-upgrade/injecting_across_frameworks.md)

---

* [Project Setup](handout/project-setup/README.md)
   * [Webpack](handout/project-setup/webpack.md)
       * [Installation and Usage](handout/project-setup/installation_and_usage.md)
       * [Loaders](handout/project-setup/loaders.md)
       * [Plugins](handout/project-setup/plugins.md)
       * [Summary](handout/project-setup/summary.md)
   * [NPM Scripts Integration](handout/project-setup/npm_scripts_integration.md)

---

* [Angular CLI](handout/cli/README.md)
   * [Setup](handout/cli/setup.md)
   * [Creating a New App](handout/cli/creating-an-app.md)
   * [Serving the App](handout/cli/serving-the-app.md)
   * [Creating Components](handout/cli/creating-components.md)
   * [Creating Routes](handout/cli/creating-routes.md)
   * [Creating Other Things](handout/cli/creating-other-things.md)
   * [Testing](handout/cli/testing.md)
   * [Linting](handout/cli/linting.md)
   * [CLI Command Overview](handout/cli/command-overview.md)
   * [Adding Third Party Libraries](handout/cli/adding-third-party-libraries.md)
   * [Integrating an Existing App](handout/cli/init.md)

---

* [Accessibility in Angular](handout/a11y/README.md)
    * [Why Make my Application Accessible?](handout/a11y/why-a11y.md)
    * [Key Concerns of Accessible Web Applications](handout/a11y/key-concerns/README.md)
        * [Semantic Markup](handout/a11y/key-concerns/semantic-markup.md)
        * [Keyboard Accessibility](handout/a11y/key-concerns/keyboard-accessibility.md)
        * [Visual Assistance](handout/a11y/key-concerns/visual-assistance.md)
    * [Testing for Accessibility](handout/a11y/testing/README.md)
      * [Is my Application Readable?](handout/a11y/testing/readable.md)
      * [Is my Application Predictable?](handout/a11y/testing/predictable.md)
      * [Is my Application Navigable?](handout/a11y/testing/navigable.md)
      * [Testing with Screen Readers](handout/a11y/testing/screen-readers.md)
    * [Additional Resources](handout/a11y/additional-resources.md)

---

* [Internationalization in Angular](handout/i18n/README.md)
    * [What is the process like and how is involved?](handout/i18n/process-and-roles.md)
    * [Marking text in our templates](handout/i18n/marking-text-in-templates.md)
    * [Extracting translation text using the Angular CLI](handout/i18n/translation-text-extraction.md)
    * [How to import the completed translation files](handout/i18n/import-translation-files.md)
        * [Using the AoT Compiler](handout/i18n/import-using-aot.md)
        * [Using the JiT Compiler](handout/i18n/import-using-jit.md)

---

* [Glossary](handout/glossary.md)
* [Further Reading And Reference](handout/further-reading.md)
