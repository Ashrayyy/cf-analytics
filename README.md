# CF Analytics
CF Analytics extension/add-on improves the Codeforces profile webpage to include statistics of problems solved by the user. The Problem Rating graph is a bar chart showing problems solved for each problem rating. The Tags Solved graph is a doughnut chart displaying tags solved across any problem and also lists a count for each tag. The Unsolved Problems shows a count of all problems attempted with not correct verdict and also lists them.

## The Original Repo
[ApoorvaRajBhadani/cf-analytics](https://github.com/ApoorvaRajBhadani/cf-analytics)

## My Fork
Along with the original features. I have added some new features, that i personally wanted and I hope people might like it too.
### More Tables
<table>
  <tr>
    <td width="50%">
      <p>
        Previously, you could only see the overall problems solved, irrespective of it being an official submission or not. Now you get 3 seperate charts to analyze profile better, know what difficulty problems were solved during contest and what not. 
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




### Problem List By Category

Now you can click on bar graphs to get list of all the problems in the particular category. Works for all 3 graphs seperately.
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

### Logarithmic Scale 

Earlier, hovering over smaller bar graphs was very difficult, clicking could not even be thought of (as shown in the first image below). Toggling the Log Scale allows the users to easily hover and click anywhere 

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

## How does it works?
The extension runs entirely on the browser and communicates only with the [Codeforces API](https://codeforces.com/apiHelp) to get the raw data.

It processes the raw data to create charts/graphs and lists.
