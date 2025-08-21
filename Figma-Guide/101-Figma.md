### Overviews:
Simple straight-forward guide to Start a figma project from the Blank state.

### 101:
Each project can contains several pages. Pages contains all the design specific to that page. All design elements are organized into each page by `Layers`

Each page comes with a blank canvas state. Elements can be drawn on blank canvas. But UI elements should be place inside of a frame.

Frame (parent) mimics the actual device frame and boundary in real life. Frames can also be nested inside of a parent frame to arrange design into different sections or group/

### Colors and Typography Variable ( Library ):
Instead of raw color hex code, create color variables ( and all other variables, ie, fonts sizes, Onboarding Texts, etc )

- Clicking on a blank canvas will show the option for variables. Upon clicking the variable panel will pop into the editor. Variables can also be created while clicking on style properties and pressing the `+` icon right of the `library` button.

* All created variables can be accessed from anywhere in the project. 


### Guides and Margins:
While selecting a frame, right panel > Layout guide (at the bottom) and select either `grid` or `columns` or `rows`. For columns, set how many columns and set the margin (safe area for iOS)

### Auto Layout:
Select 2 elements and  click auto layout button (right icon of `layout` prop in right sidebar), or `shift + a`.

Creating an auto layout will put those element in a `frame`. And positioning of the elements are done in the auto layout panel (under layout section)

* Tricks: Sometimes auto layout doesn't provide desired result for fine tuned positioning. In that case wrap the element in a frame, position the element inside the `frame` to make sure it is in the correct position. And then make auto layout again. 

### Creating Component (Reusable Element):
Anything that will be copied should be made component first (outside of the frame). To create a component 
    - create or move a or a group of elements outside of the working frame, and create component from the right panel.
    - component variance can also be created form there
    - keeping the actual component outside help us modify that component.
    - After creating, assess the component from asset (left panel, next to file button), drag and drop it into the working frame for first time use. 

A component can be a part of multiple component group together as a component. Like Header/Footer bar, usually every page has a header bar, footer bar, etc.

### State Variants (Click/Hover):
After creating a variance of the component, (change the desired appearance), then mouse drag the bottom middle circle of the default variance to the desired variance's. A pop-up will appear with all the options for the state variation, (Hover, Click, etc).

### Click/Tap Actions (Navigation):
While an element being selected, go to prototype tab, and add interaction. 
There is a tap interaction and navigation interaction. Another frame can be set up as navigation destination. 

### Move elements (top/back) in layers stacks:
`]` - move the selected layer to the last layer of the stack


### Things to have hand on experience and observation of examples:
- Wireframe
- Design system analysis
    - how to tokens are defined
    - how components are defined in various ui kits
    - must check, Material UI Kit, iOS UiKit, and some others
    - must check some readily available design system (search figma)



### Helper plugins:
- Iconify - to get quick icons
- unplash - to get free images
- Contrast: for checking contrast ratios, and it’s easy to use
- Beautiful shadows
- User profile | avatar
- Magician for placeholder copy instead of lorem ipsum
- Token Studio - For more complex token management (has github sync). this will give more control over managing complex variable tokens (instead of Figma variables)
- Batch styler: to quickly style any uikit/design system based on changed tokens (by avoiding the one by one manual change) all at once
- Zeplin: design to developer handover (documentation, components details/measurements, components usages, etc)
- Simple sort: Adjust/order/re-order components based on criterial given to the plugin
- Measure: for documentation of a design system (Measurements)
- Design Lint: when run, it will provide all the error on all components, and provide option for fixing those all at once
- Style organizer: similar to Design Lint. 