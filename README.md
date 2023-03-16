# WebChatUI
A responsive Web chat UI interface module is a great way to enhance the user experience of your Mendix application. With a Web chat UI interface module, users can communicate with each other and with your application in real time. Easy to use and simple configuration to bring the chat interface within our Mendix application. Even, you can change the theme styles based on your requirement by changing the chatInterface.scss file under the module themesource folder.

Use-case Scenarios :

Internal team communication: An organization may use a Mendix application for internal team communication. With a Web chat UI interface module, team members can communicate with each other in real time within the Mendix application. This can improve collaboration and reduce the need for external communication tools.

Customer support: With a Web chat UI interface module, customers can communicate with support agents directly within the application. This can improve the customer experience by providing fast and convenient support.

Social networking: With a Web chat UI interface module, users can communicate with each other in real time within the application. This can facilitate social interaction and community building, making the application more engaging and sticky.

Dependencies :

1. Mendix modeler version 9.12.10 and above.
2. Set attribute and Javascript snippet widget which is available in Marketplace.
3. Administration module.

How to use it?

1. For profile picture upload, just add Profile_Overview page in your navigation which is inside the USE_ME/Web/Example/Pages folder.
2. Navigate to WebChatUI module _USE_ME/Web/Example/Snippet folder.
3. Just drag and drop the SNIP_ChatUIInterface snippet in your page.
4. For custom styling, you can navigate to themesource/webchatui/web/ folder in your project directory. You can find chatInterface.scss file to customize your own styling.

Note : 

For the background color, you have to add the ".main-bg" class in your parent container of the snippet.


Limitations :

For the Circle profile picture, try to upload square ratio images (1:1). Ex: 200px*200px size images. In upcoming release, we will add this functionality without any constraints.
