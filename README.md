# SpaceX-Launch programs
Gives a brief information on various launches done by SpaceX as part of their space exploration.

# How does it work
Initial render will show the launch programs done by SpaceX since 2006 till date. Result is limited to 100 programs by default.

**There are 3 types of filters that can be applied to modify the records.**

- Launch Year: Ranging from 2006-2020.
- Successful Launch: Boolean value on whether the launch was a success or not.
- Successful Landing: Boolean value on whether the landing of the resuable component was success or not.

Filter combinations are : successful_launch, successful_launch && successful_landing, successful_launch && successful_landing && launch_year.

Filters can be reset to their initial value ( data without any filters ) by clicking on **Reset Filters** button.

All the selected filters can be viewed at the bottom of **Filters** card.

**The layout of the application based on devices are as follow:**

- Mobile View: Only one column until 700px.
- Tablet View: Two columns until 992px .
- Desktop View: Four columns.


# Usage
1. Clone the repository
```shell
git clone URL
```
2. `cd` into the repository folder
```shell
npm start
```

3. Open the index.html file using modern web browser or launch using live server in VSCode.

# App Performance
![Desktop App Performance](https://github.com/22mayank/SpaceX-program/blob/master/spacex-program/src/images/Desktop-Analysis.png)
![Mobile App Performance](https://github.com/22mayank/SpaceX-program/blob/master/spacex-program/src/images/Mobile-Analysis.png)
![Desktop App Performance](https://github.com/22mayank/SpaceX-program/blob/master/spacex-program/src/images/SpaceX.png)
