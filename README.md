# hide-extra-separator-lines-below-tableview-empty-cells-
This will hide the extra separator lines below the tableview cells empty space


### This Guide Will Hide these Extra Separator Lines

![alt text](https://i.stack.imgur.com/cFbz5.png)

### Remove these extra Separator By Just using Single line in viewDidLoad

```swift
override func viewDidLoad() {
    super.viewDidLoad()
    self.tableView.tableFooterView = UIView() //this will creta a uiview as a foter under cells to cover empty space and hides separator
}

```
