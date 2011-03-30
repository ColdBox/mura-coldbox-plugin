This is a simple plugin that allows you to integrate ColdBox applications throughout your Mura install.

You can use it within templates with some syntax like
    #$.event.getValue('YourRemoteAppKey').call({event="home.index"});#

Or, where the meat of the plugin is, add new display objects to your Mura pages. You can also specify additional parameters to pass along with your call. For example, you can add UserID as a parameter and in the CF input box provide code like:
    $.currentUser("UserID")
    
Here's a short video showing how I'm using the plugin: <http://screencast.com/t/MqpW74pIWPaN>
    
I built this for CF9, so you may have issues if you are using an older CF version. There are definitely some bugs. Please post issues in the "Issues" section of the GitHub repo.

Credit:
*   The plugin is based off of Mura's Remote Connector Plugin: <http://www.getmura.com/blog/new-remote-connector-plugin/>
*   Grant Shepart's Configurable Display Objects in Mura CMS Plugins was very helpful: <http://www.grantshepert.com/post.cfm/configurable-display-objects-in-mura-cms-plugins>
