Here is a comprehensive, structured, and de-duplicated list of **Angular Interview Questions** organized from **Basic to Advanced**. This is optimized for a GitHub `README.md` file.

***

# Angular Interview Questions

A curated list of Angular interview questions ranging from core architecture to modern features like Signals and Standalone Components.

## 🟢 Part 1: Core Angular Architecture
*Foundational knowledge regarding the framework's building blocks.*

1.  Explain the Angular Architecture and its key building blocks (Modules, Components, Templates, Metadata, Services).
2.  What is the difference between `ngOnInit` and the `constructor`?
3.  Can you explain the purpose of each **Lifecycle Hook** in Angular?
4.  How would you utilize `ngOnChanges` versus `ngDoCheck`?
5.  What are **NgModules**? Why are they optional in modern Angular versions?
6.  What are **Standalone Components** and how do they differ from traditional module-based components?
7.  What is **Data Binding**? Explain One-way vs Two-way binding.
8.  What is the difference between Interpolation `{{}}` and Property Binding `[]`?
9.  What are **Directives**? Explain the difference between Component, Structural, and Attribute directives.
10. Have you created a **Custom Directive**? Give a practical use case (e.g., Tooltip, Permissions).
11. What is ViewEncapsulation? Explain `Emulated`, `Native`, and `None`.

## 🟡 Part 2: Components, Routing & Navigation
*Questions on managing views, navigation, and data flow.*

12. How do you pass data between parent and child components (`@Input`, `@Output`)?
13. How can unrelated components communicate with each other?
14. What is the role of `ng-content` (Content Projection)?
15. How do you implement **Lazy Loading** in Angular?
16. What are **Route Guards**? Explain `CanActivate`, `CanDeactivate`, `CanMatch`, etc.
17. How do you pass dynamic parameters (data) between routes?
18. What is the difference between `routerLink` and `window.location.href`?
19. How does the `Router` handle wildcard routes (`**`)?
20. What is the difference between `ActivatedRoute` and `Router` services?

## 🟠 Part 3: Dependency Injection & Services
*Understanding how Angular manages dependencies and singletons.*

21. What is **Dependency Injection (DI)** in Angular?
22. Explain Angular's hierarchical injector system.
23. What is the difference between `providedIn: 'root'` and providing a service in a specific `providers` array?
24. What are the resolution modifiers: `@Optional()`, `@Self()`, `@SkipSelf()`, and `@Host()`?
25. What is the difference between a Singleton Service and a Component-scoped Service?
26. How do you handle circular dependencies in Angular services?
27. What are `InjectionTokens` and when would you use them?

## 🔴 Part 4: Forms & Validation
*Handling user input using Template-driven and Reactive approaches.*

28. What are the differences between **Template-driven** and **Reactive Forms**?
29. How do you construct a **Dynamic Form** using JSON data?
30. How do you add dynamic validation to a Reactive Form field at runtime?
31. How do you implement **Custom Validators** (synchronous and asynchronous)?
32. What is `FormBuilder` and how does it simplify form creation?
33. How do you handle nested form groups (`FormArray`)?
34. What is the difference between `setValue` and `patchValue`?

## 🟣 Part 5: RxJS & Observables
*Managing asynchronous data streams.*

35. What is the difference between an **Observable** and a **Promise**?
36. What are **RxJS Operators**? Explain `map`, `filter`, and `tap`.
37. Explain the difference between `switchMap`, `mergeMap`, `concatMap`, and `exhaustMap`.
38. What is the difference between `of` and `from` creation operators?
39. What is a **Subject**? How is it different from a standard Observable?
40. Explain the differences between `Subject`, `BehaviorSubject`, `ReplaySubject`, and `AsyncSubject`.
41. How do you manage subscriptions to prevent **Memory Leaks** (e.g., `takeUntil`, `async` pipe)?
42. How would you implement error handling in an Observable pipeline (`catchError`)?
43. What is the advantage of using the `async` pipe in templates?

## 🔵 Part 6: HTTP & Interceptors
*Networking and global request handling.*

44. What is the role of the `HttpClient` module?
45. What are **HTTP Interceptors**? Give three common use cases (e.g., Headers, Logging, Error Handling).
46. How do you handle multiple HTTP requests in parallel (`forkJoin`)?
47. How do you implement global error handling using Interceptors?
48. How do you modify request headers for all outgoing HTTP requests?
49. How do you cancel an ongoing HTTP request?

## 🟤 Part 7: Modern Angular & Performance (Advanced)
*Signals, Zoneless, State Management, and Optimization.*

50. 
51. What are **Angular Signals**? How do they differ from RxJS Observables?
52. How does Angular handle change detection **without Zone.js (Zoneless)**?
53. What is the difference between `Default` and `OnPush` change detection strategies?
54. How does the `trackBy` function improve performance in `*ngFor` (or the new `@for`)?
55. What are the pros and cons of using **NgRx** vs. **Signals/Services** for state management?
56. How do you handle side effects in NgRx?
57. What tools do you use to analyze and improve bundle size (e.g., source-map-explorer)?
58. What is **Server-Side Rendering (SSR)** and how does Angular Universal/Hydration work?
59. What are the new Control Flow syntaxes (`@if`, `@for`, `@switch`) introduced in Angular 17+?

## ⚫ Part 8: Scenario-Based & System Design
*Real-world problem solving and architectural decisions.*

60. **Migration Scenario:** You have a project using PrimeNG, and the client wants to switch to Angular Material mid-project. How do you handle this? (Branching, Strategy, Sprints).
61. **Upgrade Scenario:** What are the steps to upgrade an Angular application from an older version to the latest?
62. **Security:** How do you implement Role-Based Access Control (RBAC) using Guards?
63. **Security:** How do you handle JWT tokens (storage, refreshing, and attaching to requests)?
64. **Architecture:** How would you structure a large-scale Angular application? (Nx Monorepos, Library pattern).
65. **Internationalization:** How do you implement multi-language support (i18n)?
66. **Testing:** How do you mock dependencies in Unit Tests?
67. **Debugging:** Describe a time you had to debug a complex issue. How did you approach it?

***
