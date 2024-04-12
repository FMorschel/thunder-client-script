# thunder-client-script

This project is for me to create a script template for the  `Thunder Client`. Thunder Client is a REST API client extension for Visual Studio Code. It is a lightweight and fast client used to test RESTful APIs.

## Usage

The `full_script` file is meant to be copied and pasted into the `Thunder Client` editor. The `inner_html` file is meant to be just a helper to colour inside the IDE correctly. It must be then placed inside the `full_script` html variable.

The `chart_data` variable inside the `inner_html` is given with the second value passed to `tc.chartHTML` inside `chart_data`.

## Roadmap

- [ ] Center all checkboxes and buttons.
- [ ] To be able to reorder all data columns.
- [ ] To be able to filter data.
- [ ] To be able to hide columns.
- [ ] Consider hidden/reordered columns in copying rows data.
- [ ] Present `null` as "<null>".
- [ ] Add a way to visualize inner json data.
  - [ ] If the json has one item that is an array, create a way of visualizing it.
    - [ ] If it's an array of simple data.
    - [ ] If it's a json array.
  - [ ] If the json has an inner json.
- [ ] Add an `Export to` option with some simple cases.
- [ ] Add an `Copy as` option with some simple cases similar to what DBeaver has in its output table.
- [ ] Add a "Copy content" button inside every data cell.
  - [ ] Any copied string should be copied with single quote marks around.
  - [ ] Any null value cell should disable the copy content button.

## Testing

You can test this project by opnening a vscode instance, installing the __Thunder Client__ ([rangav.vscode-thunder-client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)) extension. After that, open the extension tab by clicking at its icon in the Activity Bar, clicking in the "New Request" button at the top, and sending a `GET` to https://jsonplaceholder.typicode.com/users.

The full_script will need to be copied and placed under `Tests` -> `Scripting`. And then when removing `Path.To.Your.Data` from the first line will make the script work as intended with the resulting data from the API.

Any time the script is changed, it is necessary to click on "Send".

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
