## <span style="color: blue;">How to Cancel Sent Friend Requests on Facebook</span>

You can easily cancel sent friend requests on Facebook without using third-party applications or extensions. Follow these simple steps:

### Step 1: Open Your Preferred Browser

First, open any web browser of your choice.

### Step 2: Go to the Facebook Friend Requests Page

Visit the following link: [https://m.facebook.com/friends/center/requests/outgoing/#friends_center_main](https://m.facebook.com/friends/center/requests/outgoing/#friends_center_main)

### Step 3: Inspect the Page

Right-click on the page and choose "Inspect" from the options menu, or simply press `F12` to open the browser's developer tools.

### Step 4: Access the Console

Within the developer tools, navigate to the "Console" tab.

### Step 5: Execute the JavaScript Code

Copy and paste the following JavaScript code into the console and press `Enter`:

```javascript
var inputs = document.getElementsByClassName('_54k8 _52jg _56bs _26vk _2b4n _56bt');
for(var i = 0; i < inputs.length; i++) {
    inputs[i].click();
}
