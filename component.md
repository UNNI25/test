# Components in Angular

___

Components are the basic building blocks of an application. This can be seen as a collection of lego blocks used to create a final product.Generally you have the root component which is the main.Angular applications usually have a lot of components, where each components handles a small part of the UI.

The components consists of three main building blocks.

- Template
- Class
- Metadata

![the architecture ](architecture.png)

### Template 
The template defines the layout and content of the View

### Class
The Class provides the data & logic to the View. It contains the JavaScript code associated with Template.

### Metadata
Metadata Provides additional information about the component to the Angular. This information is then used to process the class. We use the **@Component decorator** to provide the Metadata to the Component.

## To create a component from Angular CLI
- To create an Angular Component, Angular CLI is used. In the terminal, type in the command
 > ng g c component-name

- This will create a folder named component-name with four files. 

suppose login is the name of the component which we created then these files will look like
> login.component.css
> login.component.html
> login.component.ts
> login.component.spec.ts

## Component Decorator Metadata

### Selector
Selector specifies the simple CSS selector. Every component needs a CSS selector this is then used by the angular to load that component whenever this tag is seen in the main *app.component.html*

### Styles/styleUrls
This is the CSS styles or style sheets that the component needs. The styles used here are specific to this component.

### template/templateUrl
This contains the templates for view , this can be either inline or external.
