Notice that: Major features are only being developed for ASP.NET Core +
jQuery and ASP.NET Core + Angular versions beginning from v4.1. See
[version comparison table](Version-Differences.md) for more.

### v5.0.0 (2017-11-24)

-   New **Xamarin** mobile application (integrated to backend).
-   New application **setup screen**.
-   New **visual settings** page to personalize colors and positions of
    header, menu, footer and layout of the application.
-   Moved ASP.NET Core + jQuery and ASP.NET Core + Angular to **Metronic
    5** theme.
-   Moved from bower to **NPM** for ASP.NET Core MVC.
-   Bug fixes and improvements.

### v4.6.0 (2017-10-16)

-   Billing for tenant subscriptions
-   Sending files, images via chat
-   Upgraded to ABP 3.1.1
-   Enhancements and bug fixes.

### v4.5.0 (2017-09-08)

-   Migrated solution to **ASP.NET Core 2.0** and Entity Framework 2.0.
-   Upgraded to ABP 3.0.
-   Minor bug fixes and enhancements.

### v4.4.0 (2017-08-25)

-   Possibility to change organization units of a user on user edit.
-   Upgraded Angular, Angular-Cli and Ngx-Bootstrap to their latest
    versions.
-   Bug fixes and enhancements.

### v4.3.0 (2017-08-08)

-   Created a page to demonstrate usage of some **UI components**.
-   Upgraded to latest Angular and ABP packages.
-   Improvements and bug fixes.

### v4.2.0 (2017-07-25)

-   **Google Authenticator** Integration for two-factor authentication.
-   Show **payment history** to tenants.
-   Implement **phone number confirmation**.
-   Change all data tables by [**datatables**](https://datatables.net/)
    jquery plugin for ASP.NET Core & jQuery version.
-   Change all data tables by
    [**PrimeNg**](https://www.primefaces.org/primeng/) for ASP.NET Core
    & Angular version.
-   **Spanish** (Spain) localization.
-   Multiple selection on adding users to Organization Units.
-   Email notification to tenants about approaching subscription expiry
    date.
-   Upgraded to latest Angular, Angular CLI, ASP.NET Core, ABP packages.
-   Enhancements and bug fixes.

### v4.1.0 (2017-06-23)

-   Basic tenant **subscription management** for SaaS applications.
-   **Paypal** integration for tenant subscriptions.
-   **IdentityServer4** integration.
-   **Host dashboard** for edition, tenant & income statistics.
-   **Public web site** is moved to a seperated project (and
    authentication integrated to the main application).
-   Renewed sample **tenant dashboard**.
-   Converted **unit tests** to use **SQLite in memory** database.
-   Upgraded to latest Angular, Angular CLI, ASP.NET Core, ABP packages
    and Metronic.

### v4.0.0 (2017-04-24)

-   **.net core** support to create cross platform web solutions.
-   Moved to **Entity Framework Core** and **ASP.NET Core Identity**.
-   **Docker** files included to deploy as containers.
-   Spanish (Mexico) localization.

### v3.4.0 (2017-04-05)

-   Upgraded to ABP v1.5.1
-   Upgraded to Angular 4.0.
-   Upgraded to angular-cli 1.0
-   Minor enhancements and fixes.

### v3.3.0 (2017-03-13)

-   Migrated ASP.NET Core solution to **Visual Studio 2017** and new
    csproj solution format.
-   Implemented **desktop push notifications** for real time application
    notifications.
-   Minor enhancements and fixes.

### v3.2.0 (2017-03-07)

-   Tenant based UI customizations: Allow tenants to upload **custom CSS
    and logo**.
-   Edition based user count restriction.
-   Upgraded to Angular v2.4.9 and Angular CLI RC.1.
-   Upgraded to ABP v1.5.
-   Updated some translations.
-   Bugfix and enhancements.

### v3.1.0 (2017-02-14)

-   Angular 2.x UI
    -   Angular 2 **AOT** (Ahead Of Time) Compilation, and **HMR** (Hot
        Module Replacement) and **lazy loaded** modules.
    -   Created **tenant registration** view to Angular2 application.
    -   Added URL rewrite configuration to deploy under IIS.
    -   Upgraded to latest Angular and Angular CLI.
-   Angular 1.x UI
    -   Upgraded to Angularjs v1.6.2.
    -   Upgraded other angularjs related packages to latest versions.
-   Common
    -   Added French translation.
    -   Upgraded to ABP v1.4.2.
    -   Upgraded other nuget and client side packages.
    -   Bugfixes and minor improvements.

### v3.0.0 (2017-01-06)

-   **Angular 2.x** version with **ASP.NET Core 1.x** backend.
-   Upgraded to ABP v1.2.
-   Minor improvements and fixes.

### v2.2.0 (2016-12-12)

-   Created a project to serve all application functionality as API
    authenticated/authorized via JWT.
-   Separate tenant change from account forms.
-   User based two factor and lockout setting.
-   Upgraded to ASP.NET Core v1.1.
-   Upgraded to ABP v1.1.3.
-   Many improvements on current features
-   Bug fixes.

### v2.1.0 (2016-10-03)

-   Two factor authentication (Email and SMS implemented, can be
    extendable).
-   User lockout on invalid login attempts.
-   Upgraded to ABP v1.0.
-   Upgraded to Metronic v4.7.
-   Many minor improvements and some bug fixes.

### v2.0.0 (2016-09-05)

-   **ASP.NET Core 1.0** version.
-   Minor improvements and fixes.

### v1.12.0 (2016-08-26)

-   Automatic Cross-Site Request Forgery (CSRF) protection
-   Active Directory Federation Service (ADFS) Authentication
-   Store preferred user culture in database
-   Authorization for hangfire dashboard
-   Chat improvements
-   Upgraded to ABP v0.11.0.2.
-   Other minor improvements and fixes

### v1.11.0 (2016-08-08)

-   Chat between users
-   Password complexity policy
-   Search users by role and permission
-   Search roles by permission
-   Russian translation
-   Upgraded to ABP v0.10.1.3.
-   Upgraded to metronic v4.6
-   Upgraded to SignalR v2.2.1
-   Upgraded to angular ui grid v3.2.1
-   Upgraded to angularjs v1.5.6 and Angular.UI.Bootstrap v1.3.3.
-   Other minor improvements and fixes

### v1.10.1 (2016-05-18)

-   Upgraded to ABP v0.9.1.
-   Upgraded to Angular v1.5.5.
-   Upgraded to Angular-UI bootstrap v1.3.2.
-   Minor improvements and fixes.

### v1.10.0 (2016-05-10)

-   Database per tenant support for multi-tenanct applications.
-   Multiple time zone support and UTC DateTime improvements.
-   Created a Migrator tool (exe) to easily migrate host and tenant
    databases.
-   Upgraded to ABP v0.9.
-   Upgraded to Metronic 4.5.6.
-   Minor improvements and fixes.

### v1.9.1 (2016-04-06)

-   Upgraded to ABP v0.8.4.
-   Upgraded to Metronic 4.5.5.
-   Other minor improvements and fixes.

### v1.9.0 (2016-03-11)

-   New tenant registration page.
-   See and download web logs from the application UI.
-   Logging and showing all success and failed login attempts for a
    user.
-   Enhanced profile picture upload dialog.
-   Sending test email in the email settings page.
-   Integrated Redis caching.
-   Upgraded to ABP v0.8.3.
-   Upgraded other nuget packages.
-   Improvement and bug fixes.

### v1.8.2 (2016-02-29)

-   Localization support for ui-grid.
-   New cache maintenance page.
-   Local fallback for google fonts.
-   Upgraded to ABP v0.8.2.
-   Minor bug fix and enhancements.

### v1.8.1 (2016-02-18)

-   Integrated Swagger UI.
-   Upgraded to Angular v1.5.
-   Upgraded to Angular-UI v1.1.2.
-   Upgraded to ABP v0.8.1.
-   Minor bug fix and enhancements.

### v1.8.0 (2016-02-15)

-   New Real Time Push Notification system.
-   New Background Job system.
-   New Account Linking feature.
-   Hangfire integration for background jobs.
-   SignalR Integration for real time notifications.
-   OData installed by default.
-   Upgraded to ABP v0.8.
-   Upgraded to Metronic 4.5.4.
-   Moved to .NET Framework 4.6.1.
-   Other minor improvements and fixes.

### v1.7.1 (2016-01-08)

-   Changed deprecated angular ui-bootstrap components to new ones.
-   Upgraded ABP and other nuget packages.
-   Minor bugfix and and improvements.

### v1.7.0 (2015-12-23)

-   New Hierarchical Organization Units system.
-   New User and Tenant impersonation feature.
-   Moved to .NET Framework 4.5.2.
-   Upgraded to ABP and Module-Zero v0.7.6.
-   Upgraded to Metronic v4.5.3.
-   Other improvements and fixes.

### v1.6.1 (2015-11-24)

-   Arabic localization (human translate).
-   Localization improvements on all languages.
-   Created a step by step MVC documentation.
-   Upgraded to ABP and Module-Zero v0.7.4.1.
-   Upgraded to Metronic v4.5.2.
-   Upgraded to reCAPTCHA v2.
-   Upgraded to Angular v1.4.8.
-   Minor bugfixes and improvements.

### v1.6.0 (2015-11-12)

-   Database and tenant based dynamic UI localization system and related
    user interfaces.
-   RTL (Right-To-Left) support.
-   Arabic localization (google translation for now).
-   SPA menu enhancement
-   Upgraded to ABP v0.7.4.1.
-   Upgraded to Metronic v4.5.1.
-   Cleared unused Metronic files.
-   Improvements and bugfixes.

### v1.5.0 (2015-10-16)

-   Created an edition/package & feature management system for
    multi-tenant applications.
-   Added Bearer token based authentication.
-   Added Portuguese (Brazilian) localization.
-   Upgraded to latest ABP and other nuget packages.
-   Some minor fixes, improvements and refactors.

### v1.4.1 (2015-09-09)

-   Upgraded to ABP v0.7.
-   Minor fixes.

### v1.4.0 (2015-08-13)

-   Multi-Page Application (MPA) version is created using ASP.NET MVC,
    Web API and jQuery!
-   Added jTable integration.
-   Upgraded all nuget packages.
-   Many minor enhancements and a few fixes.

### v1.3.1 (2015-07-25)

-   Added German localization.
-   Skip register form on social login where basic login info is
    obtained
-   Upgraded to Metronic v4.1.
-   Upgraded to angular-ui-grid v3.0.1.
-   Minor improvements and fixes.

### v1.3.0 (2015-07-20)

-   Social media logins (Facebook, Twitter and Google+). Only Facebook
    is shown on demo.
-   Created MVC application layout with empty controllers and views
    (easiness for who does not prefer SPA-Angular). Will be fully
    implemented in next version.
-   Upgraded all nuget packages.
-   Improvements and fixes on front-end and backend applications.

### v1.2.2 (2015-06-18)

-   Added ready date ranges like today, yesterday, last 7 days..
-   Fix for daterangepicker on audit logs page.

### v1.2.1 (2015-06-15)

-   Minor fixes and improvements.

### v1.2.0 (2015-06-14)

-   Created 'Audit Logs' page to search, list, view and export audit
    logs.
-   Added Chinese localization.
-   Upgraded to Metronic v4.0.
-   Upgraded to AngularJs v1.4.
-   Upgraded to latest ABP.
-   Disabled audit logging for some actions.
-   Added Bootstrap DateTimePicker javascript library and it's AngularJs
    directive.
-   Minor fix and improvements.

### v1.1.0 (2015-06-07)

-   LDAP/Active Directory Authentication/Login support.
-   Upgraded to latest ABP packages.
-   Minor fixes and improvements.

### v1.0.1 (2015-05-28)

-   Upgraded to Metronic v3.9
-   Bugfixes and improvements.

### v1.0.0 (2015-05-17)

-   Initial release.