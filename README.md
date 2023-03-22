# Angular Job Interview Iuestions

<details>
  <summary>1. What is Angular Framework?</summary>
  <p>
    Angular is an application-design framework and development platform for creating efficient and sophisticated single-page apps
  </p>
  <p>
    Angular is a development platform, built on Typescript. As a platform, Angular incudes:
  </p>
  <ul>
    <li>A component-based framework for building scalable web applications</li>
    <li>A collection of well-integrated libraries that cover a wide variety of features, including routing, forms management, client-server communication and more</li>
    <li>A suite of developer tools to help you develop, build, test, and update your code</li>
  </ul>
  <p>
    With Angular, you are taking advantage of a platform 
    that can scale form single-developer projects to enterprise-level 
    applications. Angular is design to make updating as straightforward as possible,
    so take advantage of the last developments with minimal effort. Best of all, the Angular
    ecosystem consists of a diverse group of over 1.7 million developers, library
    authors, and content creators.
  </p>
  <div><a href="https://angular.io/docs">source</a></div>
</details>

<details>
  <summary>2. What is the difference between AngularJs and Angular?</summary>
  <ul>
    <li>They are very different frameworks;</li>
    <li>AngularJS support has officially ended as of January 2022 and Angular is still supporting;</li>
    <li>There is no CLI in AngularJS;</li>
    <li>There is no Angular Developer Tools for AngularJS;</li>
    <li>There is no RxJS in AngularJS;</li>
    <li>There is Typescript in Angular but JS in AngularJS</li>
    <li>AngularJS does not provide mobile support while Angular supports mobile;</li>
  </ul>
  <div><a href="https://www.interviewbit.com/blog/difference-between-angular-and-angularjs/#:~:text=The%20main%20difference%20between%20AngularJS,dynamic%20web%20applications%20and%20SPAs.">source</a></div>
  <div><a href="https://angularjs.org/">AngularJS Docs</a></div>
  <div><a href="https://angular.io/docs">Angular Docs</a></div>
</details>

<details>
  <summary>3. What is TypeScript</summary>
  <p>
    TypeScript is a strongly typed programming language that builds on JavaScript. 
    TypeScript allows developer to describe a shape of object and function, create interfaces and types
    to create more safety and reliable code.
  </p>
  <div><a href="https://www.typescriptlang.org/">source</a></div>
</details>

<details>
  <summary>4. Write a pictorial diagram of Angular architecture?</summary>
  <div>
    <img src="https://angular.io/generated/images/guide/architecture/overview2.png"
    alt="Angular architecture"
    style="margin: 10px auto; max-width: 100%" />
  </div>
  <div><a href="https://angular.io/guide/architecture">source</a></div>
</details>

<details>
  <summary>5. What are the key components of Angular?</summary>
  <p>These components are the keys of Angular</p>
  <ul>
    <li>Components - base building block</li>
    <li>Modules - compose the logical boundaries; way to separate logic between parts</li>
    <li>Templates - HTML view where the data is displayed by binding control to properties</li>
    <li>Services - categorical class which has specific set and is used to special purposes: fetching data, calculations, etc.</li>
    <li>Metadata and decorators - helps decorate the class to configure the expected behavior.</li>
  </ul>
</details>

<details>
  <summary>6. What are directives?</summary>
  <p>
    Directives are Angular elements that add additional behaviour to elements in application. 
    There are several directives in Angular and you can create new if you need to. 
  </p>
  <p>
    There are 2 types of directives in Angular. They are attribute directive and structural directives. 
    You can change attribute value using Attribute directive (like width, height), and you can change
    structure using structural directives (like *ngFor, *ngIf). Also Structural directives' names starts with the star sign.
  </p>
</details>

<details>
  <summary>7. What are components?</summary>
  <p>
    Component in Angular is a main building block of application. Component
    contain layout, layout styles and logic to manipulate and interact with it. Each component consist of: 
  </p>
  <ul>
    <li>@Component typescript decorator;</li>
    <li>CSS selector that defines how the component is used in a template;</li>
    <li>Template (html-template);</li>
    <li>Styles or style files array of urls (optional)</li>
  </ul>
</details>

<details>
  <summary>8. What are the differences between Component and Directive?</summary>
  <ul>
    <li>Component has a template and directive doesn't have one;</li>
    <li>Component creates new view and directive only adds behavior to existing view;</li>
    <li>There are different directives used to create Component and Directive;</li>
    <li>There can only be one component per DOM element but there can be more than one directive on a DOM element;</li>
    <li>ViewEncapsulation can be defined in component, but it can't be defined in directives.</li>
  </ul>
</details>

<details>
  <summary>9. What is a template?</summary>
  <p>
    Template is HTML code which is used to display data of component. Angular have data binding syntax
    which helps to set DOM properties dynamically. Template data binding syntax includes
    interpolation, property binding, attribute binding, class nad style binding, event binding, 
    template reference variables, using built-in directives and Inputs and Outputs.
  </p>
</details>

<details>
<summary>10. What is a module?</summary>
  <p>
   Module is angular element and typescript class. Modules are used to separate 
   logic parts of application and organizing code.
  </p>
</details>

<details>
<summary>11. What are lifecycle hooks available?</summary>
  <div><img src="https://lh4.googleusercontent.com/jqfQIpB5PJcoOn8n9fMW466u69Fs-kS4pKMzr3nKPmLRj_T730J9MB3kBRfaI9A_T3T5PFYOsjL0lSJkl_NifKbzhOJgkZKU5bQmiZhXwz8Tcu_uT6rsSlA8gFF5hl-YBRybh0RA" alt="lifecycle hooks flow"></div>
  <p>There are several lifecycle hooks or methods available.</p>
  <p>Lifecycle hooks</p>
  <ul>
    <li>constructor</li>
    <li>ngOnChanges</li>
    <li>ngOnInit</li>
    <li>ngDoCheck</li>
    <li>ngAfterContentInit</li>
    <li>ngAfterContentChecked</li>
    <li>ngAfterViewInit</li>
    <li>ngAfterViewChecked</li>
    <li>ngDoCheck</li>
    <li>ngDestroy</li>
  </ul>
</details>

<details>
<summary>12. What is a data binding?</summary>
  <p>
    Data binding is a mechanism in Angular that allows you to connect 
    template's content, html tags attributes and handle tag's events.
  </p>
  <p>There are 3 types of data binding</p>
  <ul>
    <li>One-way from source to view target - <i>interpolation and attribute binding</i></li>
    <li>One-way from view target to source - <i>event binding</i></li>
    <li>Two-way both from source to view target and from view target to source - <i>two-way binding</i></li>
  </ul>
</details>

<details>
  <summary>13. What is metadata?</summary>
  <p>
    Metadata is used to provide additional information about a class, component, directive, or module. 
    Angular compiler uses this info to understand how to instantiate and use these entities.
  </p>
  <p>
    Metadata is a configuration object that we use when define Angular element with
    decorator like @Component or @Directive etc.
  </p>
  <p>As example. Components have mandatory metadata. There are selector and template.</p>
</details>

<details>
  <summary>14. What is Angular CLI?</summary>
  <p>
    Angular CLI is a command-line interface tool that you use
    to initialize, develop, scaffold, and maintain Angular
    application directly from a command shell.
  </p>
</details>

<details>
  <summary>15. What is the difference between constructor and ngOnInit?</summary>
  <p>
    Constructor method calls at the moment when class is instantiated 
    and ngOnInit calls at the moment after creating class
  </p>
  <p>
    When constructor called input are not available, but they are available when ngOnInit called.
  </p>
</details>

<details>
  <summary>16. What is a service</summary>
  <p>
    Service is Angular element that created to encapsulate and separate  
    calculations, data, request methods etc and component. Services 
    can be injectable and can be defined as dependencies.
  </p>
</details>

<details>
  <summary>17. What is dependency injection in Angular?</summary>
  <p>
    Dependency injection is a design pattern allowing delegate 
    class creating and providing some external dependencies to some external resource.
    Dependency Injection in Angular is a mechanism which allows developers 
    inject defined dependencies in Angular elements (dependency consumer).
  </p>
</details>

<details>
  <summary>18. How is Dependency Hierarchy formed?</summary>
  <img src="https://www.tektutorialshub.com/wp-content/uploads/2021/05/Dependency-Resolution-in-Angular-1.png" alt="Dependency Hierarchy Scheme">
  <ol>
    <li>Checks current component providers</li>
    <li>Checks parent providers</li>
    <li>Checks parent's parent's...parent's parent providers</li>
    <li>Checks parent module providers</li>
    <li>Checks parent's parent's...parent's parent module providers</li>
    <li>Checks root module providers</li>
    <li>Checks platform module providers</li>
    <li>Sets null injector</li>
  </ol>
</details>

<details>
  <summary>19. What is the purpose of async pipe?</summary>
  <p>
  Async pipe purpose is to contain last emitted value of promise or observable.
  In case with observable async subscribe to the observable and shows it last value.
  When component destroys the pipe unsubscribes from the observable, 
  so using async pipes is a good optimizing tool. 
  </p>
</details>

<details>
  <summary>20. What is the option to choose between inline and external template file?</summary>
  <p>
    The options to choose between inline and external template file are:
  </p>
  <ul>
    <li>Developers team rules</li>
    <li>Size of the template</li>
    <li>Personal taste option</li>
    <li>Any other circumstances</li>
  </ul>
</details>

<details>
  <summary>21. What is the purpose of *ngFor directive?</summary>
  <p>
    *ngFor is Angular built-in structure directive. It's purpose is
    to render part of template according to every iterable object element.
    You also can use types Observable with iterable or Promise with Iterable 
    in combination with async pipe.
  </p>
  <p>
    *ngFor has some local variables which can be useful for some cases:
  </p>
  <ul>
    <li>index: number - index of current iteration element;</li>
    <li>count: number - the length of the iterable;</li>
    <li>first: boolean - equal true when index === 0</li>
    <li>last: boolean - equal true when index === count</li>
    <li>even: boolean - equal true when index % 2 === 0</li>
    <li>odd: boolean - equal true when (index + 1) % 2 === 0</li>
  </ul>
</details>

<details>
  <summary>22. What is the purpose of ngIf directive?</summary>
  <p>
    *ngIf is Angular built-in structure directive. It's purpose is
    to show and hide part of template according to the statement boolean value.
    You also can use types Observable with iterable or Promise with Iterable 
    in combination with async pipe.
  </p>
  <p>
    In *ngIf directive you can define template variables using keyword as;
  </p>
  <p><pre><i>*ngIf="(observableValue$ | async) as nonObservableValue"></i></pre>
</details>

<details>
  <summary>23. What happens if you use script tag inside template?</summary>
  <p>
    The script tag is can be placed, but can't be performed. Angular have a 
    mechanism to detect script tags. Then Angular just removes those tags.
  </p>
</details>

<details>
  <summary>24. What is interpolation?</summary>
  <p>
    Interpolation is a part of Angular data-binding. Interpolation
    is a one-way state to template view data binding. It allows
    developer add text to template using component's public properties
    and double curly brackets: 
  </p>
  <p><pre>{{ publicProp }}</pre>
</details>

<details>
  <summary>25. What are template expressions?</summary>
  <p>
    Template expressions are expressions that are allowed to make in component's template.
    For example it can be property value, get property value, method execution result.
  </p>
</details>

<details>
  <summary>26. What are template statements?</summary>
  <p></p>
  <p>
    Template statements are methods or properties that you can use in your HTML to respond to user events.
    For example you can set new value to a variable assignment operator 
  </p>
  <p><pre> some-tag (click)="boolProp = !boolProp"</pre>
  <p>Some of the expressions are not allowed in templates:</p>
  <ul>
    <li>new operator</li>
    <li>++ and --</li>
    <li>+= and -=</li>
    <li>bitwise operator & and |</li>
    <li>the pipe operator</li>
  </ul>
</details>


<details>
  <summary>27. How do you categorize data binding types?</summary>
  <p>Quantity of ways binding</p>
  <ul>
    <li>
      <p>One-way binding</p>
      <ul>
        <li>
          <p>State to template view</p>
          <ul>
            <li>Interpolation</li>
            <li>Attribute binding</li>
          </ul>
        </li>
        <li>
          <p>Template view to template</p>
          <ul>
            <li>Event binding</li>
          </ul>
        </li>
      </ul>
    </li>
    <li>Two-way binding</li>
  </ul>
</details>

<details>
  <summary>28. What are pipes?</summary>
  <p>
    Pipe is Angular element and pipe is a simple function that can be used in
    template expressions. It's defined with @Pipe decorator in it's class
    have to implements transform method. Pipe's purpose is to 
    map values in a template view via special syntax:
  </p>
  <p><pre>valueToMap | myPipe</pre>
  <p>
    There are several pipes built-in in Angular. For example async,
    json, uppercase, keyvalue, date pipe and others.
  </p>
  <p>
    Developers are also can create their own custom pipes.
  </p>
</details>

<details>
  <summary>29. What is a parameterized pipe?</summary>
  <p>
    Parameterized pipe is a pipe that can take arguments to map its value.
  </p>
</details>

<details>
  <summary>30. How do you chain pipes?</summary>
  <p>
    In template expressions we write a statement we want to map using pipe.
    Then we consequently write pipes splitting them with vertical line '|'.
  </p>
  <p><pre>{{ prop | pipe1 | pipe2 | pipe3 }}</pre>
</details>

<details>
  <summary>31. What is a custom pipe?</summary>
  <p>
    Custom pipe is Angular element and a simple function that can be used in
    template expressions. It's defined with @Pipe decorator in it's class
    have to implements transform method.
  </p>
  <p>
    Custom pipe also can be created using Angular CLI command
  </p>
  <p><pre>ng generate pipe [name]</pre>
  <p>or</p>
  <p><pre>ng generate p [name]</pre>

</details>

<details>
  <summary>32. Give an example of custom pipe?</summary>
  <p>Example</p>
<pre>import { Pipe, PipeTransform } from '@angular/core';

@Pipe({
  name: 'reversePipe'
})
export class ReverseStringPipe implements PipeTransform {
  public transform(value: string): any {
    return value.split('').reverse().join('');
  }
}
</pre>
</details>

<details>
  <summary>33. What is the difference between pure and impure pipe?</summary>
  <p>
    Impure pipe rerender it's transformed value every time template where pipe 
    used rerenders. But pure pipes rerender only when pipe input value changed.
    Pipes are pure by default.
  </p>
</details>

<details>
  <summary>34. What is a bootstrapping module?</summary>
  <p>
    Bootstrapping module or the root is a module that loads first,
    and it is responsive for setting up the environment and starting the application. 
  </p>
</details>

<details>
  <summary>35. What are observables?</summary>
  <p>
    Observable is a class of RxJS library that built-in in Angular.
    Observable is a lazy push collection of multiple values.
  </p>
  <p>
    An observable represents a stream, or source of data that can 
    arrive over time. You can create an observable from nearly anything, 
    but the most common use case in RxJS is from events. 
    This can be anything from mouse moves, button clicks, input into 
    a text field, or even route changes. The easiest way to create 
    an observable is through the built-in creation functions. For example, 
    we can use the <i>fromEvent</i> helper function to create an observable of mouse 
    click events.
  </p>
</details>

<details>
  <summary>36. What is HttpClient and its benefits?</summary>
  <p>
    HttpClient is a service provided by HttpClientModule from angular
    common http library. HttpClient is helpful service to work with
    http requests and their handling in RxJS way. It's also
    easy to configure requests params, query params, and their bodies.
  </p>
  <p>Benefits: </p>
  <ul>
    <li>Contains testability features;</li>
    <li>Provides typed request and response objects;</li>
    <li>Intercept request and response;</li>
    <li>Supports Observable APIs;</li>
    <li>Supports streamlined error handling.</li>
  </ul>
</details>

<details>
  <summary>37. Explain on how to use HttpClient with an example?</summary>
  <p>
    At first import HttpClient module to existing module. Then create
    service where you will list your requests methods. In the service inject
    the HttpClient service. Create a typed request your logic needs. 
  </p>
  <pre>
constructor(private http: HttpClient) {}

    public getCats(): Observable<ICat[]> {
      return this.http.get<ICat[]>(this.catBaseUrl + 'images/search', {
        params: {
          api_key: this.catApiKey,
          limit: this.catsQuantityLimit,
          mime_types: 'jpg'
      },
    });
</pre>
</details>

<details>
  <summary>38. How can you read full response?</summary>
  <p>To get full response you have to set parameter like this.</p>
  <pre>
// observe?: 'body' | 'events' | 'response'

public getReq(): MyType {
  return this.http.get(this.reqUrl, { observe: 'response' });
}
</pre>
</details>

<details>
  <summary>39. How do you perform Error handling?</summary>
  <p>We handle errors using RxJS error handling operators:</p>
  <ul>
    <li>catch;</li>
    <li>catchError;</li>
    <li>retry;</li>
    <li>retryWhen.</li>
  </ul>
</details>

<details>
  <summary>40. What is RxJS?</summary>
  <p>
    RxJS library is a library that allows web developer use 
    reactive programming and handle events, requests responses, and others
    in reactive way.
  </p>
</details>

<details>
  <summary>41. What is subscribing?</summary>
  <p>
    Subscribing is a process of creating subscription of observable calling
    observable subscribe method. After call, we get a subscription. 
    It's a disposable object that executes observable and have only
    one method. It's unsubscribe method that stops execution of observable
    for current subscription.
  </p>
</details>

<details>
  <summary>42. What is an observable?</summary>
  <p>
    Observable is a data stream that emits zero or 
    more events over time, and these events can be any type of data 
    such as numbers, arrays, objects, or even functions.
  </p>
</details>

<details>
  <summary>43. What is an observer?</summary>
  <p>
    Observers are set of callbacks that are consumers
    of observable emitted values. There are three types of
    these callbacks in total:
  </p>
  <ul>
    <li>for usual notification (next);</li>
    <li>for errors;</li>
    <li>for completion notification.</li>
  </ul>

</details>

<details>
  <summary>44. What is the difference between promise and observable?</summary>
  <p>
    Observables 
  </p>
  <ul>
    <li>are lazy and can be called only if it has subscription;</li>
    <li>are cancelable;</li>
    <li>emit from zero value to infinity;</li>
    <li>can by synchronous and asynchronous.</li>
  </ul>
  <p>
    Promises
  </p>
  <ul>
    <li>executes immediately;</li>
    <li>aren't cancelable;</li>
    <li>emit only one value;</li>
    <li>always asynchronous.</li>
  </ul>
</details>

<details>
  <summary>45. What is multicasting?</summary>
  <p>
    Multicasting or Hot Observables are Observables
    which emit for all subscribers same value in even in case
    if subscriptions were made in different time periods.
  </p>
  <p>
    There are some operator in RxJS which allows developers create
    hot observables:
  </p>
  <ul>
    <li>publish;</li>
    <li>multicast;</li>
    <li>share;</li>
    <li>shareReplay.</li>
  </ul>
</details>

<details>
  <summary>46. How do you perform error handling in observables?</summary>
  <p>
    Developers handle errors in Observables using error handling RxJS operators:
  </p>
  <ul>
    <li>catch</li>
    <li>catchError</li>
    <li>retry</li>
    <li>retryWhen></li>
  </ul>
</details>

<details>
  <summary>47. What is the shorthand notation for subscribe method?</summary>
  <p>Shorthand notation for subscribe method looks like this</p>
  <pre>
myObservable.subscribe(() => ... );
</pre>
  <p>More full notation for subscribe method can look like this</p>
<pre>myObservable.subscribe(
  x => console.log('Observer got a next value: ' + x),
  err => console.error('Observer got an error: ' + err),
  () => console.log('Observer got a complete notification')
);</pre>
</details>

<details>
  <summary>48. What are the utility functions provided by RxJS?</summary>
  <p>To make beginners' life more difficult 😁</p>
  <p>
    Most useful utility operators in RxJS is tap(). tap() purpose
    is to handle pipe observables, check values and do some
    executions on Observable emit but not with subscription
    arguments.
  </p>
  <p>
    There are some more operators that allowed to create delays,
    repeat emits, call callback when pipe execution ends, map to promise and so on.
  </p>
</details>

<details>
  <summary>49. What are observable creation functions?</summary>
  <p>
    Observable creating function are functions provided RxJs
    that allows developer create observables from some things.
  </p>
  <p>
    For example developer can create an event listener using 
    RxJS operator fromEvent() or create an Observable from array using
    function from()
  </p>
</details>

<details>
  <summary>50. What will happen if you do not supply handler for the observer?</summary>
  <p>
    Nothing will happen. Observables will not emit value for concrete observer
    if there is no handler.
  </p>
</details>

<details>
  <summary>51. What are Angular elements?</summary>
  <p>
    Angular elements are the same as JavaScript Custom Components or Web Components.
    It's Web platform feature that allows you to create your own html tag 
    and control it with JavaScript
  </p>
</details>

<p>What is the browser support of Angular Elements?</p>
<p>What are custom elements?</p>
<p>Do I need to bootstrap custom elements?</p>
<p>Explain how custom elements works internally?</p>
<p>How to transfer components to custom elements?</p>
<p>What are the mapping rules between Angular component and custom element?</p>
<p>How do you define typings for custom elements?</p>
<p>What are dynamic components?</p>
<p>What are the various kinds of directives?</p>

<details>
  <summary>61. How do you create directives using CLI?</summary>
  <pre>$ ng generate directive path/directive-name</pre>
</details>

<p>Give an example for attribute directives?</p>

<details>
  <summary>63. What is Angular Router?</summary>
  <p>
    Angular Router is a service that provides navigation among views 
    and URL manipulation capabilities. Router can be defined
    using RoutingModule with array of Routes in root or in feature modules.
  </p>
</details>

<details>
  <summary>64. What is the purpose of base href tag?</summary>
  <p>Base href tag specifies the base URL for all relative URLs in the page</p>
</details>

<details>
  <summary>65. What are the router imports?</summary>
  <p>
    RouterModule, Routes and others classes are imported from @angular/router library.
  </p>
  <pre>import { RouterModule, Routes } from '@angular/router';</pre>
</details>

<details>
  <summary>66. What is router outlet?</summary>
  <p>
    Router outlet is a special tag in Angular Router which allows
    to view in it nested routes components.
  </p>
  <p>
    Router outlets have input property name. Names can be used to create
    a special route that will render its element in that router-outlet.
  </p>
  <p>
    Router outlets have some outputs: 
  </p>
  <ul>
    <li>activate;</li>
    <li>deactivate;</li>
    <li>attach - Emits an attached component instance when the RouteReuseStrategy instructs to re-attach a previously detached subtree;</li>
    <li>detach - Emits a detached component instance when the RouteReuseStrategy instructs to detach the subtree.</li>
  </ul>
  <p>
    Router outlets have some properties
  </p>
  <ul>
    <li>isActivated;</li>
    <li>component;</li>
    <li>activatedRoute;</li>
    <li>activatedRouteData.</li>
  </ul>
</details>

<details>
  <summary>67. What are router links?</summary>
  <p>
    routerLink is a property like href for anchors, that 
    defines absolute or relative path for Router Service.
  </p>
</details>

<details>
  <summary>68. What are active router links?</summary>
  <p>
    activeRouterLink is property for routerLink that allows to 
    set custom css class for currently used routerLink anchor.
  </p>
</details>

<details>
  <summary>69. What is router state?</summary>
  <p>
    Angular RouterState is the state of the router as a tree of activated routes. 
  </p>
</details>

<details>
  <summary>70. What are router events?</summary>
  <p>
    RouterEvent is a base for events the router goes through, 
    as opposed to events tied to a specific route. 
    Fired one time for any given navigation.
  </p>
</details>

<details>
  <summary>71. What is activated route?</summary>
  <p>
    ActivateRoute is a class that provide access to information 
    about a route associated with a component that is loaded in an outlet. 
    Use to traverse the RouterState tree and extract information from nodes.
  </p>

  <pre>
class ActivatedRoute {
  snapshot: ActivatedRouteSnapshot
  title: Observable&lt;string | undefined&gt;
  url: Observable&lt;UrlSegment[]&gt;
  params: Observable&lt;Params&gt;
  queryParams: Observable&lt;Params&gt;
  fragment: Observable&lt;string | null&gt;
  data: Observable&lt;Data&gt;
  outlet: string
  component: Type&lt;any&gt; | null
  routeConfig: Route | null
  root: ActivatedRoute
  parent: ActivatedRoute | null
  firstChild: ActivatedRoute | null
  children: ActivatedRoute[]
  pathFromRoot: ActivatedRoute[]
  paramMap: Observable&lt;ParamMap&gt;
  queryParamMap: Observable&lt;ParamMap&gt;
  toString(): string
}
  </pre>
</details>

<details>
  <summary>72. How do you define routes?</summary>
  <p>
    Create array typed Route[]. Then I fill it with object with Route interface:
    define path, component, children if we need it. Then we pass this array as argument
    to RoutingModule forRoot method or forChild method.
  </p>
  <pre>
  const routes: Routes = [{ path: 'myPath', component: MyComponent }];&lt;
  @NgModule({
  imports: [RouterModule.forRoot(routes)],
  exports: [RouterModule]
}) </pre>
</details>

<details>
  <summary>73. What is the purpose of Wildcard route?</summary>
  <p>
    Wildcard route is a special type of route
    that used a special paths when defined. For example path "**",
    which can be used for all non-defined URLs. We can use it to show
    visitors who use incorrect link 404 page or redirect them to any defined page.
  </p>
</details>

<p>Do I need a Routing Module always?</p>
<p>What is Angular Universal?</p>
<p>What are different types of compilation in Angular?</p>
<p>What is JIT?</p>
<p>What is AOT?</p>
<p>Why do we need compilation process?</p>
<p>80. What are the advantages with AOT?</p>
<p>What are the ways to control AOT compilation?</p>
<p>What are the restrictions of metadata?</p>
<p>What are the three phases of AOT?</p>
<p>Can I use arrow functions in AOT?</p>
<p>What is the purpose of metadata json files?</p>
<p>Can I use any javascript feature for expression syntax in AOT?</p>
<p>What is folding?</p>
<p>What are macros?</p>
<p>Give an example of few metadata errors?</p>
<p>90. What is metadata rewriting?</p>
<p>How do you provide configuration inheritance?</p>
<p>How do you specify angular template compiler options?</p>
<p>How do you enable binding expression validation?</p>
<p>What is the purpose of any type cast function?</p>
<p>What is Not null type assertion operator?</p>
<p>What is type narrowing?</p>
<p>How do you describe various dependencies in angular application?</p>
<p>What is zone?</p>
<p>What is the purpose of common module?</p>
<p>100. What is codelyzer?</p>
<p>What is angular animation?</p>
<p>What are the steps to use animation module?</p>
<p>What is State function?</p>
<p>What is Style function?</p>
<p>What is the purpose of animate function?</p>
<p>What is transition function?</p>
<p>How to inject the dynamic script in angular?</p>
<p>What is a service worker and its role in Angular?</p>
<p>What are the design goals of service workers?</p>
<p>110. What are the differences between AngularJS and Angular with respect to dependency injection?</p>
<p>What is Angular Ivy?</p>
<p>What are the features included in ivy preview?</p>
<p>Can I use AOT compilation with Ivy?</p>
<p>What is Angular Language Service?</p>
<p>How do you install angular language service in the project?</p>
<p>Is there any editor support for Angular Language Service?</p>
<p>Explain the features provided by Angular Language Service?</p>
<p>	How do you add web workers in your application?</p>
<p>What are the limitations with web workers?</p>
<p>120. What is Angular CLI Builder?</p>
<p>What is a builder?</p>
<p>How do you invoke a builder?</p>
<p>How do you create app shell in Angular?</p>
<p>What are the case types in Angular?</p>
<p>What are the class decorators in Angular?</p>
<p>What are class field decorators?</p>
<p>What is declarable in Angular?</p>
<p>What are the restrictions on declarable classes?</p>
<p>What is a DI token?</p>
<p>130. What is Angular DSL?</p>
<p>What is an rxjs Subject?</p>
<p>What is Bazel tool?</p>
<p>What are the advantages of Bazel tool?</p>
<p>How do you use Bazel with Angular CLI?</p>
<p>How do you run Bazel directly?</p>
<p>What is platform in Angular?</p>
<p>What happens if I import the same module twice?</p>
<p>How do you select an element with in a component template?</p>
<p>How do you detect route change in Angular?</p>
<p>140. How do you pass headers for HTTP client?/p>
<p>What is the purpose of differential loading in CLI?</p>
<p>Is Angular supports dynamic imports?</p>
<p>What is lazy loading?</p>
<p>What are workspace APIs?</p>
<p>How do you upgrade angular version?</p>
<p>What is Angular Material?</p>
<p>How do you upgrade location service of angularjs?</p>
<p>What is NgUpgrade?</p>
<p>How do you test Angular application using CLI?</p>
<p>150. How to use polyfills in Angular application?</p>
<p>What are the ways to trigger change detection in Angular?</p>
<p>What are the differences of various versions of Angular?</p>
<p>What are the security principles in angular?</p>
<p>	What is the reason to deprecate Web Tracing Framework?</p>
<p>What is the reason to deprecate web worker packages?</p>
<p>How do you find angular CLI version?</p>
<p>What is the browser support for Angular?</p>
<p>What is schematic</p>
<p>What is rule in Schematics?</p>
<p>160. What is Schematics CLI?</p>
<p>What are the best practices for security in angular?</p>
<p>What is Angular security model for preventing XSS attacks?</p>
<p>What is the role of template compiler for prevention of XSS attacks?</p>
<p>What are the various security contexts in Angular?</p>
<p>What is Sanitization? Is angular supports it?</p>
<p>What is the purpose of innerHTML?</p>
<p>What is the difference between interpolated content and innerHTML?</p>
<p>How do you prevent automatic sanitization?</p>
<p>Is safe to use direct DOM API methods in terms of security?</p>
<p>170. What is DOM sanitizer?</p>
<p>How do you support server side XSS protection in Angular application?</p>
<p>Is angular prevents http level vulnerabilities?</p>
<p>What are Http Interceptors?</p>
<p>What are the applications of HTTP interceptors?</p>
<p>Is multiple interceptors supported in Angular?</p>
<p>How can I use interceptor for an entire application?</p>
<p>How does Angular simplifies Internationalization?</p>
<p>How do you manually register locale data?</p>
<p>What are the four phases of template translation?</p>
<p>180. What is the purpose of i18n attribute?</p>
<p>What is the purpose of custom id?</p>
<p>What happens if the custom id is not unique?</p>
<p>Can I translate text without creating an element?</p>
<p>How can I translate attribute?</p>
<p>List down the pluralization categories?</p>
<p>What is select ICU expression?</p>
<p>How do you report missing translations?</p>
<p>How do you provide build configuration for multiple locales?</p>
<p>What is an angular library?</p>
<p>190. What is AOT compiler?</p>
<p>How do you select an element in component template?</p>
<p>What is TestBed?</p>
<p>What is protractor?</p>
<p>What is collection?</p>
<p>How do you create schematics for libraries?</p>
<p>How do you use jquery in Angular?</p>
<p>What is the reason for No provider for HTTP exception?</p>
<p>What is router state?</p>
<p>How can I use SASS in angular project?</p>
<p>200. What is the purpose of hidden property?</p>
<p>What is the difference between ngIf and hidden property?</p>
<p>What is slice pipe?</p>
<p>What is index property in ngFor directive?</p>
<p>What is the purpose of ngFor trackBy?</p>
<p>What is the purpose of ngSwitch directive?</p>
<p>Is it possible to do aliasing for inputs and outputs?</p>
<p>What is safe navigation operator?</p>
<p>Is any special configuration required for Angular9?</p>
<p>What are type safe TestBed API changes in Angular9?</p>
<p>210. Is mandatory to pass static flag for ViewChild?</p>
<p>What are the list of template expression operators?</p>
<p>What is the precedence between pipe and ternary operators?</p>
<p>What is an entry component?</p>
<p>What is a bootstrapped component?</p>
<p>How do you manually bootstrap an application?</p>
<p>Is it necessary for bootstrapped component to be entry component?</p>
<p>What is a routed entry component?</p>
<p>Why is not necessary to use entryComponents array every time?</p>
<p>Do I still need to use entryComponents array in Angular9?</p>
<p>220. Is it all components generated in production build?</p>
<p>What is Angular compiler?</p>
<p>What is the role of ngModule metadata in compilation process?</p>
<p>How does angular finds components, directives and pipes?</p>
<p>Give few examples for NgModules?</p>
<p>What are feature modules?</p>
<p>What are the imported modules in CLI generated feature modules?</p>
<p>What are the differences between ngmodule and javascript module?</p>
<p>What are the possible errors with declarations?</p>
<p>What are the steps to use declaration elements?</p>
<p>230. What happens if browserModule used in feature module?</p>
<p>What are the types of feature modules?</p>
<p>What is a provider?</p>
<p>What is the recommendation for provider scope?</p>
<p>How do you restrict provider scope to a module?</p>
<p>How do you provide a singleton service?</p>
<p>What are the different ways to remove duplicate service registration?</p>
<p>How does forRoot method helpful to avoid duplicate router instances?</p>
<p>What is a shared module?</p>
<p>Can I share services using modules?</p>
<p>240. How do you get current direction for locales??</p>
<p>What is ngcc?</p>
<p>What classes should not be added to declarations?</p>
<p>Wat is ngzone?</p>
<p>What is NoopZone?</p>
<p>How do you create displayBlock components?</p>
<p>What are the possible data change scenarios for change detection?</p>
<p>What is a zone context?</p>
<p>What are the lifecycle hooks of a zone?</p>
<p>Which are the methods of NgZone used to control change detection?</p>
<p>250. How do you change the settings of zonejs?</p>
<p>How do you trigger an animation?</p>
<p>How do you configure injectors with providers at different levels?</p>
<p>Is it mandatory to use injectable on every service class?</p>
<p>What is an optional dependency?</p>
<p>What are the types of injector hierarchies?</p>
<p>What are reactive forms?</p>
<p>What are dynamic forms?</p>
<p>What are template driven forms?</p>
<p>What are the differences between reactive forms and template driven forms?</p>
<p>What are the different ways to group form controls?</p>
<p>How do you update specific properties of a form model?</p>
<p>What is the purpose of FormBuilder?</p>
<p>How do you verify the model changes in forms?</p>
<p>What are the state CSS classes provided by ngModel?</p>
<p>How do you reset the form?</p>
<p>What are the types of validator functions?</p>
<p>Can you give an example of built-in validators?</p>
<p>How do you optimize the performance of async validators?</p>
<p>How to set ngFor and ngIf on the same element?</p>
<p>270. What is host property in css?</p>
<p>How do you get the current route?</p>
<p>What is Component Test Harnesses?</p>
<p>What is the benefit of Automatic Inlining of Fonts?</p>
<p>What is content projection?</p>
<p>What is ng-content and its purpose?</p>
<p>What is standalone component?</p>
<p>How to create a standalone component uing CLI command?</p>
<p>How to create a standalone component manually?</p>
# FIN
