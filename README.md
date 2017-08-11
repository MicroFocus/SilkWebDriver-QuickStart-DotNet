# SilkWebDriver-QuickStart-.NET

1. Download & Install [MicroFocus Silk WebDriver][1] for free
2. Start Silk WebDriver
3. Start the recording
   * Select the browser
   * Enter the URL
4. Record any workflow
   * Use the action chooser to select a different action
   * Verify certain states of the application by pressing **ctrl**-**alt** and select the any property of the active object
   * Select the browser icon to record browser actions like Back, Forward, Get
5. Replay the script
   * By pressing play to replay all actions or
   * selecting a single action and than press play or
   * selecting multiple actions by holding down the **ctrl**-key and than press play
6. Modify the script
   * Delect actions or
   * Reorder them
7. Open a [Visual Studio](https://www.visualstudio.com/) solution
   * Use a pre-configured solution: Clone the repository
      ```
      bash
      git clone git://github.com/MicroFocus/SilkWebDriver-QuickStart-DotNet.git
      ```
      and open the C# or Visual Basic solution
      or
   * Create your own solution:
      1. Start Visual Studio
      2. Create a new project: **File**->**New**->**Project...**
      3. Select **Visual Basic** or **Visual C#**
      4. Select the **Test** template
      5. Select **Unit Test Project (.Net Framework)**
      6. Fill in the names for project and solution and click **OK**
      7. Install [Selenium WebDriver](https://www.nuget.org/profiles/selenium) by using the NuGet Package Manager:
         1. Select **Tools**->**NuGet Package Manager**->**Package Manager Console**
         2. In the opened Package Manager console, enter the following commands:
            * ``Install-Package Selenium.WebDriver -Version 3.4.0``
            * ``Install-Package Selenium.Support -Version 3.4.0``
9. Export the script
   * To the clipboard or
   * As a .cs (C#) or .vb (Visual Basic) file, ideally to the created solution's folder
10. Run the created script: **Test**->**Run**->**All Tests**

## License
Scripts provided by Micro Focus are licensed under the [MIT license](LICENSE).

## Contribution
You want to contribute to our sample scripts? Great!

Sample scrips may be contributed after signing the [Micro Focus Individual Contributor License Agreement 1.0](OpenSourceContributionAgreement1_0.pdf).
Signed contributor agreements are to be sent, via PDF, to <licensing@microfocus.com>.
You will be notified via email when the agreement has been accepted by Micro Focus.  

[1]: http://www.microfocus.com/SilkWebDriver
