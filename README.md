# Newsletter Generator's built-in demo template

This is a publicly accessible version (a mirror) of the "build-in-demo" HTML email template file, that is used inside Newsletter Generator application.

![Template used in application](https://static.newslettergenerator.app/screenshot-demo-template.webp)

This email template should not be used as a basis for other templates, since it was not thoroughly tested in email testing software, such as Litmus or Email on Acid.

The purpose of this repository and email template is to show how the template works in Newsletter Generator in reference to top-level tables, marked with `id` attributes, and comment-variables (enclosed in HTML comment tags: `<!--` and `-->`).

Newsletter Generator processes template files in following way:

- all top-level tables with an identifier will become available to use inside the application;
- likewise, all variable names (with correct syntax), enclosed in HTML comments will become available inside the application.

The template is located in index.html file and a copy of this file is being used directly in application's internals.

To learn more, refer to the "[Authoring templates](https://newslettergenerator.app/manual.html#email-templates)" section in the manual.
