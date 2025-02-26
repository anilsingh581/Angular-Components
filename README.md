# Angular Interview Questions and Answers Examples

A curated list of common Angular interview questions with concise answers and examples.

# Table of Contents

- [Chapter 1: The Basic Concepts of Angular](#chapter-1-the-basic-concepts-of-angular)
- [Chapter 2: Concepts of Components](#chapter-2-concepts-of-components)
- [Chapter 3: Concepts of Templates](#chapter-3-concepts-of-templates)
- [Chapter 4: Concepts of Directives](#chapter-4-concepts-of-directives)
- [Chapter 5: Concepts of Signals](#chapter-5-concepts-of-signals)
- [Chapter 6: Concepts of Dependency Injection (DI)](#chapter-6-concepts-of-dependency-injection-di)
- [Chapter 7: Concepts of Routing](#chapter-7-concepts-of-routing)
- [Chapter 8: Concepts of Forms](#chapter-8-concepts-of-forms)
- [Chapter 9: Concepts of HTTP Client](#chapter-9-concepts-of-http-client)
- [Chapter 10: Concepts of SSR & Hybrid Rendering](#chapter-10-concepts-of-ssr--hybrid-rendering)
- [Chapter 11: Concepts of Pipes](#chapter-11-concepts-of-pipes)
- [Chapter 12: Concepts of NgModules](#chapter-12-concepts-of-ngmodules)
- [Chapter 13: Concepts of Internationalization (i18n)](#chapter-13-concepts-of-internationalization-i18n)
- [Chapter 14: Angular Security](#chapter-14-angular-security)
- [Chapter 15: Concepts of RxJS with Angular](#chapter-15-concepts-of-rxjs-with-angular)
- [Chapter 16: AI Experimental Features](#chapter-16-ai-experimental-features)
- [Chapter 17: Compiler & Build Tools](#chapter-17-compiler--build-tools)
- [Chapter 18: Developer Tools](#chapter-18-developer-tools)
- [Chapter 19: Angular Best Practices](#chapter-19-angular-best-practices)
- [Chapter 20: Angular Testing](#chapter-20-angular-testing)
- [Chapter 21: Angular Material](#[chapter-21 Angular-material(https://github.com/anilsingh581/Angular-Interview-Questions-Answers-Examples/blob/main/Angular-Material-Example)])

### 1. Core Concepts
**Q: What is Angular and its key features?**  
A: Angular is a TypeScript-based framework for building dynamic web apps. Key features: two-way data binding, dependency injection, and component-based architecture.

---

### 2. Components & Templates
**Q: How do you create a component in Angular?**  
A: Use `@Component` decorator with a selector, template, and styles. Example: `ng generate component my-component`.

---

### 3. Directives
**Q: What are structural directives?**  
A: Directives like `*ngIf` and `*ngFor` that modify DOM structure. Example: `<div *ngIf="isVisible">Content</div>`.

---

### 4. Dependency Injection
**Q: How does DI work in Angular?**  
A: Angular’s injector provides services to components. Example: `constructor(private service: MyService) {}`.

---

### 5. Routing
**Q: How do you configure a route in Angular?**  
A: Define routes in `RouterModule` with `path` and `component`. Example: `{ path: 'home', component: HomeComponent }`.

---

### 6. Forms
**Q: What’s the difference between template-driven and reactive forms?**  
A: Template-driven uses directives in HTML; reactive uses FormGroup in TypeScript for more control.

---

### 7. HTTP Client
**Q: How do you fetch data with HttpClient?**  
A: Inject `HttpClient` and use `get()`. Example: `this.http.get('api/data').subscribe(data => console.log(data))`.

---

### 8. RxJS
**Q: What are Observables in Angular?**  
A: Streams of data handled asynchronously. Example: `interval(1000).subscribe(val => console.log(val))`.

---

### 9. Performance & Optimization
**Q: How do you optimize Angular apps?**  
A: Use lazy loading, OnPush change detection, and Ahead-of-Time (AOT) compilation.

---

### 10. Testing
**Q: How do you write a unit test for a component?**  
A: Use Jasmine/Karma. Example: `it('should render title', () => { expect(component.title).toBe('MyApp'); })`.
## How to Run
- Clone this repository:
  ```bash
  git clone [angular-interview-examples](https://github.com/anilsingh581/Angular-Components.git)
  ```
- Navigate into the folder:
  ```bash
  cd angular-interview-examples
  ```
- Install dependencies:
  ```bash
  npm install
  ```
- Run the Angular application:
  ```bash
  ng serve
  ```

