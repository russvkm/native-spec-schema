# NativeSpec Components (v1)

## Layout Components

## Node
- Each screen will have a node
- Node will be the wrapper of every laout
- requied filds
    - type: "Column"
    - children: array of components

### Column
- Lays out children vertically
- Required fields:
  - type: "Column"
  - children: array of components

### Row
- Lays out children horizontally
- Required fields:
  - type: "Row"
  - children: array of components

### Box
- Overlapping layout container
- Required fields:
  - type: "Box"
  - children: array of components

## Leaf Components

### Text
- Displays text
- Required fields:
  - type: "Text"
  - text: string

### Button
- Displays a clickable button
- Required fields:
  - type: "Button"
  - text: string
- Optional:
  - action

### TextField
- Input field
- Required fields:
  - type: "TextField"
  - id: string
# NativeSpec Components (v1)

## Layout Components

### Column
- Lays out children vertically
- Required fields:
  - type: "Column"
  - children: array of components

### Row
- Lays out children horizontally
- Required fields:
  - type: "Row"
  - children: array of components

### Box
- Overlapping layout container
- Required fields:
  - type: "Box"
  - children: array of components

## Leaf Components

### Text
- Displays text
- Required fields:
  - type: "Text"
  - text: string

### Button
- Displays a clickable button
- Required fields:
  - type: "Button"
  - text: string
- Optional:
  - action

### TextField
- Input field
- Required fields:
  - type: "TextField"
  - id: string
