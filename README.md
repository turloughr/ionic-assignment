# Calorie Counter Cross-Platform Mobile Application
This cross-platform mobile application helps young professionals to track their daily calorie intake. 
The app displays the calories in common everyday foods that young Irish adults eat from a list of food categories. Users can check to see if their calorie intake exceeds recommended daily allowances based on their gender.

## How to the app works.
The app uses the ionics framework mainly ionic list cards, ionic list and a jquery shopping cart script adapted from "A complete shopping cart built with jQuery and sessionStorage" by Gabriele Romanato as the basis for this. See: https://github.com/gabrieleromanato/jQuery-sessionStorage-shopping-cart.

The workflow is as follows:
1. The user is presented with introductory text and asked to select their gender to check to see if their calorie intake exceeds recommended daily allowances for everyday foods that young Irish adults eat. 
2. They can select a number of food items from a list of food categories. 
3. Users can select the quantity of a particular food item they have eaten for a given day by selecting an add button. This feature uses local storage to store a list of items selected.
4. As items are added, the user can see a total of the amount of calories they have consumed. This is managed via the js/jquery.shop cart.
5. By selecting a "Consumption Report" option, the user can view a report to determine if the calories consumed exceeds recommended daily allowances for their gender. This is achieved by totaling the number of calories consumed and subtracting the daily calorie limit for a particular gender. See the comments in  js/jquery.shop for further information.
								
## Comments 
Each file is extensively commented and hopefully self explanatory. 

## Execution and performance
A local host was used to test the execution and performance of the code. Model view control design principles were applied as best as possible.

## User Interface
An external style sheet was used to manage the UI. Some in-line css was used for the consumption report.

##Complexity
The app makes use of a combination of elements such as local data storage, lists, and cards. 

## Source code
A copy of the source code can by found on https://github.com/turloughr/ionic-assignment.

## References:
1. Icons used in the app from Ionicons: http://ionicons.com/ 
You can clone it using 'git clone <url>' where <url> is the ssh url on the right, or you can click "Download ZIP" on the right and start from there.
2. The calorie counter is in essence a shopping cart. I used "A complete shopping cart built with jQuery and sessionStorage" by Gabriele Romanato as the basis for this. See: https://github.com/gabrieleromanato/jQuery-sessionStorage-shopping-cart 

##Notice:
Images were sourced from the Internet via Google image search. Copyright of images is held by their respective owners.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
