In this chapter the following recipes will be covered:
    1.Writing Hello World with Vue.js
    2.Writing lists
    3.Creating a dynamic and animated list
    4.Reacting to events such as clicks and keystrokes
    5.Choosing a development environment
    6.Formatting your text with filters
    7.Debugging your application with mustaches (for example, a JSON filter)
    8.X-raying your application with Vue developer tools
    9.Upgrading to Vue.js 2

To give your migration a head start; Chris Fitz (a member of the Vue core team) created a little helper app
that will scan your code and guide you in the migration:
1. Install Vue Migration Helper with the following npm command:
npm install -g git://github.com/vuejs/vue-migration-helper.git
2. Navigate to your app folder.
3. Run the program with the following command:
vue-migration-helper
All the lines in which a change is necessary will be highlighted. Once you are finished updating, or if you
still have doubts, you should take a look at the official documentation migration page at https://rc.vuejs.org/guide
/migration.html.