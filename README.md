HTML Email Framework
====================
A cross-client compliant HTML email framework.

## Basic Usage...
Use the template to build your email. Then, run it through a css inliner tool like [Premailer][Premailer] to bring the styles inline. Then, embed the contents of the `embedded-css.html` file in the head of the freshly inlined email and edit those styles if you please, __being sure to remove all comments when you are done__.


## Snippets
If you use Sublime Text 2, drop the included snippets into your `/Packages/User` folder in your Sublime Text 2 application files to start building HTML emails with ease. It's like Zen Coding for HTML email! Simply type the trigger (i.e. ":table") and hit tab to insert the associated HTML, which can make for some rapid HTML email development.

I've tried to include some of the most basic building blocks and components used for crafting an HTML email such as tables, spacers, links, and images. They are coded with cross-client best practices built in &ndash; just fill out your desired attribute values, insert your content, and be on your merry way. I'd encourage you to edit the snippets to suit your specific needs and even add your own.

### Triggers
These trigger keywords are simply what I have set, I'd encourage you to edit them to suit your own preferences. They are set to only trigger within the HTML scope (that way they won't accidentally get triggered when typing symbols in ruby, for example, since I chose to prefix them with a ":").

- `:email` - inserts the full, pre-inlined, email template
- `:embedded`- inserts the post-inlining, embedded styles template
- `:table` - inserts a table
- `:table/xy` - inserts a table with a height attribute.
- `:td` - inserts a table cell
- `:td/xy` - inserts a table cell with a height attribute.
- `:spacer` - inserts a "spacer" table
- `:td/spacer` - inserts a "spacer" table cell
- `:a` - inserts a hyperlink
- `:img` - inserts an image


## Aknowledgemnts & Resources
In addition to my own testing and findings, this framework was built largely on top of the code and best practices put forth in the below resources. You would be wise to check them out. This framework would not have been possible without them.

### Code & Templates
- [HTML Email Boilerplate][Email BP]
- [Email on Acid Boilerplate][Email on Acid BP]
- [Campaign Monitor Templates][CM Templates]
- [Mail Chimp Templates][MC Templates]

### Knowledge & Info
- [Campaign Monitor Resources][CM Resources]
- [Mail Chimp Resources][MC Resources]
- [Litmus Blog][Litmus Blog]
- [Smashing Magazine article on mobile email development][smashing article]
- [Spamhaus email marketing best practices][Spamhaus]

### Tools
- [Premailer][Premailer]
- [Litmus][Litmus]


## TODO
- Add snippets and styling for lists
- Improve inline comment documentation
- Create "verbose", "lite", and "bare" versions with regards to the amount of inline comment documentation
- Create wiki with tips and best practices
- Include pre-built templates for various layout configurations
- Build command line tool to streamline development workflow




<!-- References -->

[Premailer]: http://premailer.dialect.ca/
[Email BP]: http://htmlemailboilerplate.com/
[Email on Acid BP]: http://www.emailonacid.com/blog/details/C13/emailology_-_the_science_of_looking_good_in_the_inbox
[CM Templates]: http://www.campaignmonitor.com/templates/
[MC Templates]: http://mailchimp.com/resources/html-email-templates/

[CM Resources]: http://www.campaignmonitor.com/resources/
[MC Resources]: http://mailchimp.com/resources/
[Litmus Blog]: https://litmus.com/blog/
[smashing article]: http://mobile.smashingmagazine.com/2011/08/18/from-monitor-to-mobile-optimizing-email-newsletters-with-css/
[Spamhaus]: http://www.spamhaus.org/faq/section/Marketing%20FAQs

[Litmus]: https://litmus.com/