# Laravel Learning Path

This repository contains the **ordered** list of Laravel topics to learn, step-by-step, with related links.

If you want to add a topic, link, or any other suggestion, please open Issues or Pull Requests.

**Notice 1**: The same table below is also available as a database, so you would be able to transform it to any other format you want - PDF, chart, etc. See file [roadmap.sql](roadmap.sql)

**Notice 2**: This content was filled into an adminpanel generated with our [QuickAdminPanel](https://quickadminpanel.com) - here's a [video demo of that process on Youtube](https://www.youtube.com/watch?v=i2ElUDUDRms). By purchasing QuickAdminPanel, you support my free initiatives, like this Roadmap.

--- 


-----


### Advanced Beginner Demo-Project: Simple CRM

To achieve this Advanced Beginner level, you would need to practice by creating something like [this simple CRM project](https://github.com/LaravelDaily/Laravel-Roadmap-Advanced-Beginner-Challenge).

Inside of the repository above, you will find all the details of the task, with an example solution.

-----

## Mid Level
Master all Laravel features with 3-5 years of practical experience

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links | Mark |
| ----- | ----- | ----- |
| **Routing Extra Features** ||
| Route Caching |:book: [Route Caching](https://laravel.com/docs/8.x/routing#route-caching) <br>| + |
| Rate Limiting |:book: [Rate Limiting](https://laravel.com/docs/8.x/routing#rate-limiting) <br>:clapper: [Laravel: Create Public API with Cache and Rate Limits](https://www.youtube.com/watch?v=vrLcCxWlxOk) <br>|
| Invokable controllers |:book: [Single Action Controllers](https://laravel.com/docs/8.x/controllers#single-action-controllers) <br>|
| **Database/Eloquent Extra Features** ||
| Model Observers |:book: [Eloquent Observers](https://laravel.com/docs/8.x/eloquent#observers) <br>:clapper: [Laravel Model: Check if Any Field Was Changed](https://www.youtube.com/watch?v=_xluet13xxE) <br>:clapper: [Eloquent Observers or Events Listeners? Which is Better?](https://www.youtube.com/watch?v=DvoaU6cQQHM) <br>|
| Raw Database Queries |:book: [Query Builder: Raw Expressions](https://laravel.com/docs/8.x/queries#raw-expressions) <br>|
| All Eloquent Features |:book: [All About Eloquent](https://laravel.com/docs/8.x/eloquent) <br>:capital_abcd: [Eloquent: Expert Level](https://laraveldaily.teachable.com/p/laravel-eloquent-expert-level) <br>:page_facing_up: [20 Laravel Eloquent Tips and Tricks](https://laravel-news.com/eloquent-tips-tricks) <br> :clapper: [Laravel Collections: 5 Methods with Real Examples](https://www.youtube.com/watch?v=isAz2GduuA0) <br> [More videos](videos/all-eloquent-features.md) <br>|
| **Various Extra Laravel Features** ||
| Custom Blade Directives |:book: [Extending Blade](https://laravel.com/docs/8.x/blade#extending-blade) <br>|
| Events and Listeners |:book: [Events and Listeners](https://laravel.com/docs/8.x/events) <br>:clapper: [Laravel: 3 Ways to Send a Welcome Email (Controller vs Observer vs Events)](https://www.youtube.com/watch?v=ZWzH6SOzjhI) <br>:clapper: [Laravel: Why Observers and Event Listeners are "Risky"](https://www.youtube.com/watch?v=A3bmLo77e5M) <br>|
| Laravel HTTP Client and Guzzle |:book: [HTTP Client](https://laravel.com/docs/8.x/http-client) <br>:clapper: [Laravel and External APIs: Get Data with HTTP Client](https://www.youtube.com/watch?v=oEDDZsmMLc0) <br>|
| Login with X: Laravel Socialite |:book: [Laravel Socialite](https://laravel.com/docs/8.x/socialite) <br>|
| Creating Artisan Commands |:book: [Writing Artisan Commands](https://laravel.com/docs/8.x/artisan#writing-commands) <br>:clapper: [How to Create Artisan Commands in Laravel](https://www.youtube.com/watch?v=-r3WnYy7g48) <br>|
| Task Scheduling |:book: [Task Scheduling](https://laravel.com/docs/8.x/scheduling) <br>:clapper: [Laravel Task Scheduling: Run Artisan Command Hourly](https://www.youtube.com/watch?v=r-KrsQ0dN80) <br>|
| Caching |:book: [Cache](https://laravel.com/docs/8.x/cache) <br>:clapper: [Cache Eloquent Query Results to Load Pages Instantly](https://www.youtube.com/watch?v=JhKngeE0XJA) <br>|
| Real-time: Broadcasting, Echo and Pusher |:book: [Broadcasting](https://laravel.com/docs/8.x/broadcasting) <br>|
| **Jobs and Queues** |:capital_abcd: [Queues in Laravel](https://laraveldaily.teachable.com/p/queues-in-laravel) <br>|
| Queueable Classes and Jobs |:book: [Creating Jobs](https://laravel.com/docs/8.x/queues#creating-jobs) <br>:book: [Queueing Notifications](https://laravel.com/docs/8.x/notifications#queueing-notifications) <br>:book: [Queued Event Listeners](https://laravel.com/docs/8.x/events#queued-event-listeners) <br>:book: [Queueing Mail](https://laravel.com/docs/8.x/mail#queueing-mail) <br>:clapper: [Laravel Queues 101: Example with Sending Emails](https://www.youtube.com/watch?v=rVx8xKisbr8) <br>|
| Job Dispatching, Batching and Chaining |:book: [Dispatching Jobs](https://laravel.com/docs/8.x/queues#dispatching-jobs) <br>|
| Processing Failed Jobs |:book: [Dealing with Failed Jobs](https://laravel.com/docs/8.x/queues#dealing-with-failed-jobs) <br>|
| Configuring Queues: Drivers, Redis, Supervisor |:book: [Running the Queue Worker](https://laravel.com/docs/8.x/queues#running-the-queue-worker) <br>:book: [Configuring Supervisor](https://laravel.com/docs/8.x/queues#supervisor-configuration) <br>|
| Laravel Horizon (optional, if you use Redis) |:book: [Laravel Horizon](https://laravel.com/docs/8.x/horizon) <br>|
| **API Advanced** ||
| Upload Files via API |:page_facing_up: [Laravel API: How to Upload File from Vue.js](https://blog.quickadminpanel.com/laravel-api-how-to-upload-file-from-vue-js/) <br>|
| Generate API Documentation |:page_facing_up: [Laravel API Documentation with OpenAPI/Swagger](https://blog.quickadminpanel.com/laravel-api-documentation-with-openapiswagger/) <br>:clapper: [Scribe: New Package for Laravel API Documentation](https://www.youtube.com/watch?v=PjwGI8c2IfA) <br>|
| API Versioning |:page_facing_up: [Versioning your REST API with Laravel](https://codimth.com/blog/web/laravel/versioning-your-rest-api-laravel) <br>:clapper: [Versioning your API: from V1 to V2 and Beyond [video from my course]](https://laraveldaily.teachable.com/courses/how-to-create-laravel-api/lectures/17568998) <br>|
| API with OAuth and Laravel Passport |:book: [Laravel Passport](https://laravel.com/docs/8.x/passport) <br> :clapper: [Laravel API Auth Demo: Passport, oAuth and Sanctum](https://www.youtube.com/watch?v=8myQdPL8I1s)|
| Only-API Projects with Front-end like Vue.js |:capital_abcd: [Vue.js + Laravel: CRUD with SPA](https://laraveldaily.teachable.com/p/vue-laravel-crud-spa) <br>|
| Only-API Projects with Mobile Apps |:page_facing_up: [Using Sanctum to authenticate a mobile app](https://laravel-news.com/using-sanctum-to-authenticate-a-mobile-app) <br>|
| **(optional) Starter Kits: Laravel Jetstream and Fortify** ||
| Laravel Jetstream (requires Livewire/Inertia knowledge) |:book: [Laravel Jetstream](https://jetstream.laravel.com) <br>:capital_abcd: [Laravel Jetstream+Livewire: Real Mini-Project](https://laraveldaily.teachable.com/p/laravel-jetstream-livewire-project) <br>:clapper: [Laravel Jetstream: How it Works and Example How to Customize](https://www.youtube.com/watch?v=d8YgWApHMfA) <br>|
| Laravel Fortify |:book: [Laravel Fortify](https://laravel.com/docs/8.x/fortify) <br>:clapper: [Laravel Fortify: Four Auth Things to Customize](https://www.youtube.com/watch?v=Vr4LJU3kw1g) <br>|
| **Payments** ||
| Laravel Cashier with Stripe/Paddle |:book: [Laravel Cashier (Stripe)](https://laravel.com/docs/8.x/billing) <br>:book: [Laravel Cashier (Paddle)](https://laravel.com/docs/8.x/cashier-paddle) <br>|
| Custom Payment Providers: PayPal, Mollie, etc |:page_facing_up: [Subscription billing with Laravel Cashier for Mollie](https://github.com/laravel/cashier-mollie) <br>:page_facing_up: [How To Integrate Paypal Payment Gateway In Laravel](https://websolutionstuff.com/post/how-to-integrate-paypal-payment-gateway-in-laravel) <br>|
| **Automated Testing Advanced** ||
| TDD: Test-Driven Development |:capital_abcd: [Build A Laravel App With TDD](https://laracasts.com/series/build-a-laravel-app-with-tdd) <br>:capital_abcd: [TDD With Laravel](https://tddwithlaravel.com/) <br>|
| Mocking |:book: [Mocking](https://laravel.com/docs/8.x/mocking) <br>|
| (optional) Laravel Dusk |:book: [Laravel Dusk](https://laravel.com/docs/8.x/dusk) <br>|
| **Full-Text Search** ||
| Laravel Scout |:book: [Laravel Scout](https://laravel.com/docs/8.x/scout) <br>|
| Drivers: ElasticSearch, Algolia or MeiliSearch |:page_facing_up: [ElasticSearch Driver for Laravel Scout](https://laravel-news.com/explorer) <br>:book: [Algolia: Scout Extended](https://www.algolia.com/doc/framework-integration/laravel/getting-started/introduction-to-scout-extended/?client=php) <br>:page_facing_up: [Full-Text Search with MeiliSearch and Laravel Scout](https://tighten.co/blog/full-text-search-with-meilisearch-and-scout/) <br>|
| **Laravel Packages** ||
| Contributing to Packages, making Pull Requests |:clapper: [How to Contribute to Laravel Docs (or any open-source repository)](https://www.youtube.com/watch?v=vEcT6JIFji0) <br>|
| Create Laravel Packages |:book: [Package Development](https://laravel.com/docs/8.x/packages) <br>:capital_abcd: [Laravel Package Development](https://laravelpackage.com/) <br>|


## Senior Level
Responsibility for architecture decisions on large projects

__Link icons: :book: Official Docs :clapper: Video :page_facing_up: Article :capital_abcd: Course__ 

| Topic | Learning Links |
| ----- | ----- |
| **PHP/Laravel Design Patterns** |:clapper: [Laravel Design Patterns - Bobby Bouwmann - Laracon EU 2018 Amsterdam](https://www.youtube.com/watch?v=qpo5KG0vIyE) <br>:capital_abcd: [Laracasts: Design Patterns in PHP](https://laracasts.com/series/design-patterns-in-php) <br>:clapper: [Colin Decarlo - Design Patterns with Laravel [Laracon 2018]](https://www.youtube.com/watch?v=e4ugSgGaCQ0) <br>:clapper: [Matt Stauffer - Patterns That Pay Off [Laracon 2018]](https://www.youtube.com/watch?v=enTb2E4vEos) <br>:capital_abcd: [Design Patterns in PHP](https://refactoring.guru/design-patterns/php) <br>|
| Creational Design Patterns |:page_facing_up: [Design Patterns PHP: Creational](https://designpatternsphp.readthedocs.io/en/latest/Creational/README.html) <br>|
| Structural Design Patterns |:page_facing_up: [Design Patterns PHP: Structural](https://designpatternsphp.readthedocs.io/en/latest/Structural/README.html) <br>|
| Behavioral Design Patterns |:page_facing_up: [Design Patterns PHP: Behavioral](https://designpatternsphp.readthedocs.io/en/latest/Behavioral/README.html) <br>|
| **Well-written Code** ||
| SOLID Code |:clapper: [Becoming a better developer by using the SOLID design principles by Katerina Trajchevska](https://www.youtube.com/watch?v=rtmFCcjEgEw) <br>:page_facing_up: [Writing Maintainable Code: SOLID Principles Explained in PHP (Laravel)](https://geekflare.com/php-solid-principles/) <br>:capital_abcd: [Laracasts: SOLID Principles in PHP](https://laracasts.com/series/solid-principles-in-php) <br>:clapper: [PHP Solid Principles [Playlist]](https://www.youtube.com/watch?v=ARxZV8OZ8Cg&list=PLNuh5_K9dfQ3jMU-2C2jYRGe2iXJkpCZj) <br>|
| Scalable Code |:capital_abcd: [Scaling Laravel](https://courses.serversforhackers.com/scaling-laravel) <br>:clapper: [Enterprise Laravel by Matt Stauffer](https://enterpriselaravel.com/) <br>:page_facing_up: [What the hell is scalable code anyway?](https://blog.sarasarya.com/what-the-hell-is-scalable-code-anyway-f6626ad78227) <br>|
| Maintainable Code |:page_facing_up: [How would you know if you've written readable and easily maintainable code? [forum thread]](https://softwareengineering.stackexchange.com/questions/141005/how-would-you-know-if-youve-written-readable-and-easily-maintainable-code) <br>:page_facing_up: [Crafting maintainable Laravel applications](https://jasonmccreary.me/articles/crafting-maintainable-laravel-applications/) <br>:page_facing_up: [7 Golden Rules of Clean, Simple and Maintainable Code](https://shhetri.github.io/clean-code/#/) <br>|
| Best Practices and Standards |:page_facing_up: [Repository: alexeymezenin / laravel-best-practices](https://github.com/alexeymezenin/laravel-best-practices) <br>:capital_abcd: [PHP: The Right Way](https://phptherightway.com/) <br>:page_facing_up: [Reddit: What are your Laravel best practices?](https://www.reddit.com/r/laravel/comments/f34t86/what_are_your_laravel_best_practices/) <br>|
| **Large Datasets** ||
| Large Database Structures |:capital_abcd: [How to Structure Databases in Laravel](https://laraveldaily.teachable.com/p/how-to-structure-database-in-laravel) <br>|
| NoSQL Solutions |:book: [MongoDB and Laravel Integration](https://www.mongodb.com/compatibility/mongodb-laravel-intergration) <br>:page_facing_up: [MongoDB + Laravel = Love — When to use NoSQL](https://faun.pub/when-to-use-nosql-getting-started-with-mongodb-in-laravel-f5376ceaf545) <br>|
| Eloquent/SQL Query Optimization |:page_facing_up: [18 Tips to optimize laravel database queries](https://dudi.dev/optimize-laravel-database-queries/) <br>:page_facing_up: [Optimizing Laravel Part 2: Improving Query Performance with Database Indexing](https://deliciousbrains.com/optimizing-laravel-database-indexing-performance/) <br>:capital_abcd: [Eloquent Performance Patterns](https://eloquent-course.reinink.ca/) <br>|
| Scaling to Multiple Databases |:page_facing_up: [Scaling Laravel App with Multiple Databases](https://devdojo.com/bobbyiliev/scaling-laravel-app-with-multiple-databases) <br>:page_facing_up: [Multiple DB Connections in Laravel](https://fideloper.com/laravel-multiple-database-connections) <br>|
| **Working with High-Traffic Projects** ||
| Stability and Zero-Downtime Deployments |:book: [Laravel Deployer](https://github.com/deployphp/deployer) <br>:book: [Envoyer - Zero Downtime PHP Deployment](https://envoyer.io/) <br>|
| Performance Optimization and Caching |:capital_abcd: [Performant Laravel](https://serversforhackers.com/laravel-perf) <br>:page_facing_up: [The Ultimate Performance Checklist For Laravel Apps](https://laravel-news.com/performance-checklist) <br>:page_facing_up: [How to Optimize PHP Laravel Web Application for High Performance?](https://geekflare.com/laravel-optimization/) <br>|
| **Ensuring Code Quality** ||
| Writing Testable Code |:page_facing_up: [How to write testable code](https://dev.to/ddarrko/how-to-write-more-testable-code-oi7) <br>:page_facing_up: [Refactoring towards testability](https://madewithlove.com/blog/software-engineering/refactoring-untestable-code-towards-testability/) <br>|
| Continuous Integration and Continuous Delivery (CI/CD) |:page_facing_up: [How to create a CI/CD for a Laravel application using GitHub Actions](https://blog.logrocket.com/how-to-create-a-ci-cd-for-a-laravel-application-using-github-actions/) <br>:page_facing_up: [Configure Laravel 8 for CI/CD with Jenkins and GitHub — Part 1](https://faun.pub/configure-laravel-8-for-ci-cd-with-jenkins-and-github-part-1-58b9be304292) <br>:page_facing_up: [Build, Test, and Deploy Your Laravel Application With GitHub Actions](https://www.twilio.com/blog/build-test-deploy-laravel-application-github-actions) <br>|
