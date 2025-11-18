---
title: "What Is A Widget, Token, Customer, Client And A Layout"
source: "https://constellation1.na3.teamsupport.com/knowledgeBase/14399776"
tags: ["Administration"]
version: "1.0"
last_updated: "2025-11-18"
short_description: "What Is A Widget, Token, Customer, Client And A Layout Token A token is a short piece of text that you place on a web page and when the page is loaded"
long_description: "What Is A Widget, Token, Customer, Client And A Layout Token A token is a short piece of text that you place on a web page and when the page is loaded, the system recognizes the text and replaces it with the data or HTML that is tied to the token. A Value Token will be replaced by a simple value like your first name. Value tokens are in the format {{Widget.System.Value Type=’SomeValue’}} A Widget Token will be replaced by the widget that is stored in the system. Widget Tokens are in the format {"
---

# What Is A Widget, Token, Customer, Client And A Layout

**Token**

A token is a short piece of text that you place on a web page and when the page is loaded, the system recognizes the text and replaces it with the data or HTML that is tied to the token.

A **Value Token** will be replaced by a simple value like your first name. Value tokens are in the format _{{Widget.System.Value Type=’SomeValue’}}_

A **Widget Token** will be replaced by the widget that is stored in the system. Widget Tokens are in the format _{{Widget.System Type=’SomeValue’}}_

Tokens always have beginning and ending braces (curly brackets).

**Widget**

Widget is a generic term that represents a chunk of HTML or website functionality. A widget can be used by placing its Widget Token into a web page and saving the page. When the system loads the web page it finds the Widget Token and replaces it with the HTML or website functionality stored in the widget. For example if you use the Widget Token for the Quick Search module then when the web page loads, the system will swap out the Widget Token for the actual Quick Search module.

There are actually 2 types of widgets:

**System Widgets** (SW) are built into the system that any company can use. SWs are usually complex functionality that the development team has built. Some SWs have configuration options like height and width that you can set before using it in your web page. SWs cannot be edited because they are custom built programming that is stored at the system level. SWs are in the format {{Widget.System Type='SomeWidgetName'}}.

Examples: Agent Featured Property, Quick Search, RSS Feed Reader, Cyberhomes Market Trends.

Note: due to a complication with the WYSIWYG content editor, System Widgets with a URL in their configuration options will need to be pasted into the editor while in HTML mode (Figure 4) because RAD Editor adds an HTML anchor tag (<a href=””>)around the URL if it’s done in Design mode.

**Custom Widgets** (CW) are ones that a company can build on their own and store in the system. CWs are built using HTML, CSS and JavaScript. Typically a company would build a CW when they intend to use it in several places on the website. CWs are in the format {{Widget.Custom WidgetID='123'}}.

**Widget Token Generator** (WTG)

The Widget Token Generator (WTG)  (Figure 3)  is a tool that allows you to easily retrieve the token for a widget so that you can place it in your content. The WTG is available on the Content Edit page for east access. This is a feature for advanced users that are comfortable with HTML and a little programming.

**Custom Widget Editor** (CWE)

The Custom Widget Editor is a page in the admin website that allows you to create and edit your own Custom widgets. At present the CWE is only available to company administrators with the permission “Can Administer Company Web Content”.

**What’s the difference between a Token and a Widget?**

A token is a small piece of text that when placed in a web page will be replaced by the system with the HTML or functionality that is tied to that token. Widgets are themselves the functionality that a token represents. To use a widget on your website you will take that widget’s token and place it in a web page.

**What’s the benefit of using widgets?**

An example illustrates the point. You have a feature that you built for your website using HTML and JavaScript, if you’re adventurous maybe even a little jQuery. You’d like to be able to use that feature on your website in several different spots. Maybe this feature is something that you want to show on the homepage for all your agent websites. With widgets what you do is you take the HTML and JavaScript that you created and plunk it into the widget editor and save it. The system gives you back a one liner piece of code that you then place on the homepage of all your agents. All the agents now have the feature. Take it a step further – you realize that you’re using the wrong color inside the feature’s HTML. Prior to widgets you’d have to go to each agent website and change that color. But now with widgets you go into one place – the widget editor – and change the color… bingo, all agent websites are updated. Cool, huh?

**RECo**

Short for Real Estate Company.

**Layout**

A block of HTML, JavaScript and CSS that defines the look and feel a page or a section of a page. Layouts can contain widgets and tokens. For example, the map control has a section used to show the search criteria and that section is stored as a layout in the system. Layouts are editable in the admin website using the Layout Editor. This is an advanced feature that is only available to company administrators with the permission “Can Administer Company Web Content”.

**Customer**

A public website user that has created an account with a company’s website and who does not have a relationship with an agent or office as their client. See also: client.

**Client**

A public website user that has created an account with a company’s website and who does have a relationship with an agent or office. See also: customer. In practice, when a client logs into the company website they are redirected to the website of the agent or office that they are