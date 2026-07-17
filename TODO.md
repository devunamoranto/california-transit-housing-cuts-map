# Todo List

## Research
- Clarify requirements
  - Should data be highlighted at city or county level?
  - What kind of filter menu options are they wishing for?

## Stories
Getting started on TS boilerplate for known implementation requirements. Trying to break this up into threads

### Map Layers
Displaying a California map, and geometry layers underneath

#### Geometry persistence (Backend)

- Good table schema for storing such a large number of geometries?
  - Where should the data live?
  - Determine a spec on how the layers should interact with each other?
 

#### Base map layer (Frontend)
- Rendering interactible California map

#### Transit layer (FE)
- Rendering relevant transit geometries, with interaction

#### Municipal layer (FE)
- Rendering relevant county/city geometries, with interaction

### Filter menu (FE)
- Allow users to filter datapoints for easy exploration. Need to clarify with Seamless on what they want the filter menu to look like

### Data entry and persistence for researchers (BE)
Other stakeholder will research and transit and affordable housing projects that have been funded by the programs set to be slashed.
They will need a method for data entry pending this research.

- Need to research a storage solution and align on a standardized input method for them
- Wire this up with the map layers

### Web Hosting (BE)
- Research and decide on a web hosting option for the app
