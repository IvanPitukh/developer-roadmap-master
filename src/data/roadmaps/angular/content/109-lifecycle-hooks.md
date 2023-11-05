# Lifecycle hooks

A component instance has a lifecycle that starts when Angular instantiates the component class and renders the component view along with its child views. The lifecycle continues with change detection, as Angular checks to see when data-bound properties change, and updates both the view and the component instance as needed. The lifecycle ends when Angular destroys the component instance and removes its rendered template from the DOM. Directives have a similar lifecycle, as Angular creates, updates, and destroys instances in the course of execution.

Your application can use lifecycle hook methods to tap into key events in the lifecycle of a component or directive to initialize new instances, initiate change detection when needed, respond to updates during change detection, and clean up before deletion of instances.

The following life cycle hooks of angular are :

`OnChanges` , `OnInit` , `DoCheck` , `OnDestroy` , `AfterContentInit` , `AfterContentChecked` , `AfterViewInit` , `AfterViewChecked`

Visit the following resources to learn more:

- [What is Life Cycle Hooks? - Angular.io ](https://angular.io/guide/lifecycle-hooks)
- [The life cycle hooks of angular - Blog ](https://blog.logrocket.com/angular-lifecycle-hooks/)
