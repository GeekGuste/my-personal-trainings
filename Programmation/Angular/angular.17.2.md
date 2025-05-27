Module2: Advanced Angular topics

# Angular container and Nested Components

- Container are basic layout element in CoreUI
	+ CoreUI for Angular offers three types of containers: 'c-container' for responsibe maximum width, 'c-container-fluid' for full-width flexibility,and breakpoint-specific containers that adjust width according to specified breakpoints.
In angular component can have a child that have a Child component

## Angular Component input properties
- used to pass data from container component to the nested component
- To use this, use the @Input() decorator

## Angular Component Outoyt Properties
- Child component:
	+ Define input and output properties using Input
	+ @input property emits events to the parent
- Parent component
	+ Set input property using property biding
	+ pass data from parent to child

<ng-container> Directive
- An element that holds structure directives
- results in a cleaner, more efficient DOM structure
- Slightly improves performance by minimizing unnecesary elements
