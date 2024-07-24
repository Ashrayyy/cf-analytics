<div align="center">
  <img width="20%" src="https://github.com/user-attachments/assets/1fd5d45d-149b-4c59-a3d4-fc0e09f16c7c"/>

  <h1>CF Analytics</h1>

  An improved extension to analyse Codeforces profiles better!
  <br>
  <br>

</div>

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/license/gpl-3-0)

CF analytics is a browser extensions that utilizes Codeforces API to help you analyze your CF profiles better.

Enhance Your Codeforces Experience with CF Analytics. It unlocks valuable insights into your problem-solving journey. Visualize Your Progress with

* **Problem Rating Graph**: A clear and concise bar chart showcasing the problems you've solved, categorized by rating.
* **Tags Solved Graph**: An interactive doughnut chart displaying the tags you've mastered, along with a detailed count for each.
* **Unsolved Problems**: Get a comprehensive list of problems you've attempted but haven't quite cracked yet, along with a handy count.

You'll gain a deeper understanding of your strengths and weaknesses, helping you optimize your learning strategy and improve your coding skills.

## The Original Repo
[ApoorvaRajBhadani/cf-analytics](https://github.com/ApoorvaRajBhadani/cf-analytics)

## My Fork

Along with the original features. I have added some new features, that i personally wanted and I hope people might like it too.
### More Tables
<table>
  <tr>
    <td width="50%">
      <p size="1">
        <b>3 Detailed Charts to Supercharge Your Analysis</b>
        
* <b>Official Submissions</b>: Problems solved during contests.
* <b>Unofficial Submissions</b>: Problems solved outside of contests.
* <b>All Submissions</b>: All the problems solved, regardless of source.
      </p>
    </td>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/c13a786b-430c-48fe-9755-01bbd9181de3" width="100%" />
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/431e8aa4-0a56-45b5-a692-2eb0e57acf44" width="100%" />
    </td>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/302e5826-867e-48f3-b68c-f600c773e1bb" width="100%" />
    </td>
  </tr>
</table>



##### NOTE: Solved problems during virtual contests will appear in the Solved during contest table.




### Interactive Bar Graphs


Now you can click on bar graphs to get list of all the problems in the particular category. 

**Works for all 3 graphs seperately.**

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/b9a08f2b-d8a1-4778-b568-94802fe8e6b7" />
    </td>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/4785cdc7-0ca6-4dbe-b703-54aa88d44445" width="100%" />
    </td>
  </tr>
</table>

### Improved Usability with Logarithmic Scale 

Hovering and clicking on smaller bars was challenging.

Toggling the Log Scale allows the users to easily hover and click anywhere 

<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/d46bccfa-2d8a-467b-b752-029328e36d05" />
    </td>
    <td width="50%">
      <img src="https://github.com/Ashrayyy/cf-analytics/assets/101005702/0c687f29-e6e9-4d18-a90d-ce60c3e30df4" width="100%" />
    </td>
  </tr>
</table>

## Installation

Steps: If you have git installed

* Clone this repo by using ```git clone https://github.com/Ashrayyy/cf-analytics.git```
* Go to your browser -> settings -> extensions -> Manage extensions -> Enable Developer Mode
* Select Load Unpacked Extension
* Select the source folder where you cloned the repo

If you dont have git, head over to the release section.

##### [Video Tutorial for installation](https://drive.google.com/file/d/1XRtMr9Y9VwaVi_YAidWEVOce8gcpHbnK/view?usp=sharing)

## How does it works?
The extension runs entirely on the browser and communicates only with the [Codeforces API](https://codeforces.com/apiHelp) to get the raw data.

It processes the raw data to create charts/graphs and lists.
