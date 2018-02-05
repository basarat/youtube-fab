# youtube-fab

> https://material.io/guidelines/components/buttons-floating-action-button.html

The `fab` or `Floating Action Button` is a great UI design pattern that allows you to guide the user a to some key action in your application. 

> https://www.zendesk.com/

The idea of a fab is not new to material design and has actually been used quite extensively by help and chat systems e.g. Zendesk 

Using this design element is not without its risk and one that I want to mention is common to any decition you have about adding a *floating* element to your page. 

***Highlight the content area and the fab on a full screen page***
When you have a large display it is easy to seperate the fab from the main content which is generally max-width limited. 

***Scroll down the page on a small screen***
However when you have a small screen the fab quite commonly ends up overlaying over items in the footer, preventing click navigation to foother pages. The worst case is when you do not have a footer and there is a `next` button right at the end of the page and the fab overlays that button. 

The key message I want to convey here is that whenever you have a floating *forever shown* element on a page like a fab, make sure it is a part of your designs at each breakpoint, otherwise, you might just render your application unuseable. 

> End screen: As always, thanks for watching and have a great day.
