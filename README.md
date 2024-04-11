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
- [ ] When the data is `null` present it as "<null>".
- [ ] Add a "Copy content" button inside every data cell.
  - [ ] Any copied string should be copied with single quote marks around.
  - [ ] Any null value cell should disable the copy content button.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
