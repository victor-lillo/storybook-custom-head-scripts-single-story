# Repository demonstrating how to add custom head scripts for a single Storybook story

This repository provides an example of how to dynamically add custom `<script>` tags to the `<head>` of a Storybook page for a single story and for all the views of a component, as opposed to adding the script globally in `previewHead`.

## Setup

1. Clone this repository.
2. Install dependencies:

   ```bash
   npm install
   ```

3. Run Storybook:

   ```bash
   npm run storybook
   ```

## Usage

The example story shows how to add a custom script (`script.js`) to the `<head>` for all component views or just a single story view using decorators.
