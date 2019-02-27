# The Passcode Coding Challenge
<img src="https://www.themarysue.com/wp-content/uploads/2016/03/iphone6-ios9-passcode-entry.jpg" width="120" height="200" />  <img width="200" alt="image 1" src="https://user-images.githubusercontent.com/970324/53515926-f3612b80-3a7f-11e9-94d4-fee068854203.png">
## Goal
Built a numeric passcode view that will grant access to an App. The passcode component needs to be implemented within a universal iOS app. Please see the example screenshot above.
## Requirements
Initial launch: Display the passcode view and ask the user to configure a passcode
#### Passcode Component:
- Should be reusable and self-contained
- The user inputs should use a custom UI to capture number tap by the user (not the native keyboard)
#### Application Flow
- On boot if no passcode has been saved, allow the user to configure a passcode:
    - The passcode should show up and ask the user to configure a passcode.
    - In order to save a passcode, the user must enter the same passcode twice in a row.
    - Persist the passcode where appropriate and display a message to confirm the successful action
- On boot, if a passcode has been configured
    - The passcode should show up and ask the user to enter his passcode.
    - After three incorrect entry, display an error message and lock passcode view for 1min until the user can try again.
    - On successful entry, display a message that grants access.
## Libraries
You are allowed to used third-party libraries when appropriate.
Use your good judgment and please justify the use of any third party library.
## Specifications
- Language: Swift 4.2
- Development environment: Xcode 10 or later
- Target: iOS 12 or later
- Architecture: MVVM
- Tests: All business logic should be Unit-Tested
- Layout: Passcode component should be compatible with both iPhone/iPad
## Submission
When finished, create a public Github repository with your solution.
Don’t hesitate to include any documentation or ramblings to help us better understand your submission and the coding choices you made.
 
## Question?
If you have any questions, do not hesitate at all to ask (tony@peek.com).
