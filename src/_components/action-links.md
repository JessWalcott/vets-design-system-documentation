---

layout: default
title: Action links 
---

# Action links

![action links]({{site.baseurl}}/images/action-links-updated.png) 

[Interact with this component on Storybook](https://design.va.gov/storybook/?path=/docs/components-action-link--page)

## Guidance

### When to use the Action Link component
The action link is an  eye-catching link to start a digital service. An action link entices users to take action. Example: Starting a benefit application 

**Note:** Action links will be replacing green primary buttons that link to another page.

- Use a primary (green) action link to serve the purpose of the primary call to action on a page or a digital start to a service. 
- Use a secondary (blue) action link to serve the purpose for when there are multiple action links on a page or if actions do not have hierarchy over each other.
- Use a reverse (white) action link when you need to use an action link on a dark background



### When to consider something else
- Do not use an action link for clickable actions, such as, “sign up,” “submit” or “log out.” Use [buttons](https://design.va.gov/components/buttons) instead. 
- Do not use action links to navigate between form pages. Use default and secondary buttons instead. 
- Do not use action links to just link to another page or site. If a link does not need to be prominent on the page see our other link styles below in the “How to use other links” section. 

### Usability guidance: how to use it
- Keep action link content short. Start with a verb. For example: “*Apply for health care benefits*” or “*Register for care*” 
- The icon on the left of the link text can be slightly out of the grid to grab the attention of the user.
- Primary (green) action links and default (blue) action links can exist on the same page. We do not recommend having them side by side. 

### How to use other links 
- If you want to use a link that needs less hierarchy than an action link, we recommend using this active link style. Active link styles can be accompanied by a right facing chevron icon for more emphasis. 
- Active text link style: Source Sans Pro (Bold),  underlined, 16px, #004795

![active link style]({{site.baseurl}}/images/active-link-style-big.png) 

- For links that need even less hierarchy than an action link or active link style, we recommend using a default link style. 
- Default text link style: Source Sans Pro (Regular),  underlined, 16px, #004795)

![default link style]({{site.baseurl}}/images/default-link-style-big.png) 
- Make sure to underline all text links. Underlining text links is important for low-vision users' accessibility. Exceptions to not underlining links are [side nav](https://design.va.gov/components/sidenav) links. 

## Accessibility
- Action Links must have an `href` attribute. 
- Action links should only use an anchor tag `<a>`. The `<a>` element, or anchor element, is used to create a hyperlink to another webpage or another location within the same webpage. 
- For external links or links opening up to a new tab, make sure to add an aria label to let the user know what sort of link they're clicking on.
- It is important to use Action Links for calls to actions that link to another page rather than buttons, because screen readers always say “link” before links, and “button” before buttons. 
- Button and link confusion can be very frustrating for assistive technology users. A user with a screen reader may pull up a list of links and may not find a specific link because it turns out that it has actually been designated as a button in the markup. 
- Using links and buttons intentionally results in a more inclusive experience for assistive technology users. Make sure to read both [buttons](https://design.va.gov/components/buttons) and action link guidance to determine what is needed for a page and when each should be used. 
- Links that point to localized content in another language should have an `hreflang` attribute and a `lang` attribute in the following format:

```
<a
  className="va-action-link--blue"  
  href="#"
  hreflang="es"
  lang="es"
>En Español</a>
```