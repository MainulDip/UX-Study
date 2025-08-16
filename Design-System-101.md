### 60/30/10 Color rules | Surface(BlankSpace)/Primary/Secondary (Non material):
Surface (Blank/White/Neutral/bg) should should contain 60%
Primary Color Should Be 30% of total usages per page
Secondary (Call to action / button / accent color) should be 10%

### Material Colors Roles:
- `Surface` – A role used for backgrounds and large, low-emphasis areas of the screen. Use surface roles for more neutral backgrounds, and surface-container colors for components like cards, sheets, and dialogs.
- `Primary`, `Secondary`, `Tertiary` – Accent color roles used to emphasize or de-emphasize foreground elements.
- `Container` – Roles used as a fill color for foreground elements like buttons. They should not be used for text or icons.
- `On` – Roles starting with this term indicate a color for text or icons on top of its paired parent color. For example, on primary is used for text and icons against the primary fill color.
- `Variant` – Roles ending with this term offer a lower emphasis alternative to its non-variant pair. For example, outline variant is a less emphasized version of the outline color

    `Primary` roles are for important actions and elements needing the most emphasis, like a FAB (Floating Action Button) to start a new message.

    `Secondary` roles are for elements that don’t need immediate attention and don’t need emphasis, like the selected state of a navigation icon or a dismissive button.

    `Tertiary` roles are for smaller elements that need special emphasis but don't require immediate attention, such as a badge or notification.

### Typography:
Material 3 has one type scale containing two sets of type styles: 15 baseline and 15 emphasized.

* Each contains Large/Medium/Small (L/M/S) variants + same with emphasized version
    Display - `md.sys.typescale.display.l` or m/s
    Headline - `md.sys.typescale.headline.l` and `md.sys.typescale.emphasized.headline.l`
    Title
    Body
    Label

### Design token:
Design token's are raw numbers into a variable, so that management/customization will be easier.

Design tokens can be different types
- Color
- Typography
- Shadow
- Spacing
- Radius
- Borders
- Animation
- Grid

* Design token naming convention for Defining/Creating 
1. Raw Collection (Brand Collection) : Define the base variable (raw collection). Like, for color, `purple = #251256`. There are the direct reference to the actual values.
2. Alias Collection : Then define `Alias` variable, pointing to that raw variable, like, `primaryDefault = purple`
    - The alias collection define the purpose binding with raw variable collection. Like Primary, Secondary, ect
    - The Material Design Theme (After building) comes with the alias defined already. But roles needs to be defined.
        - Some are already defined, ie, Success/Error/Waring etc. But Primary/Secondary/Tertiary/Custom need to be mapped with role
3. Mapped Collection (Defines/Maps roles with the Alias): Define variables here pointing to the Alias variable. like, `headline = primaryDefault`
    - Mapped collection are the final state, which should be used to build the actual ui (both design and development phases)
    - * The Material Design Theme needs to be mapped to with the actual role. 

* Neutral colors are for Texts (Body, Headline)