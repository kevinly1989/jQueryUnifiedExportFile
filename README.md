## <a href="https://jqueryunifiedexportfile.codeplex.com/">jQuery Unified Export File</a> ##
=======================

### SUMMARY ###
A jQuery library which enables developers to export file by using jQuery. It includes 3 main features:

<ul>
<li>Export file from the server by three ways: Normal, Progress and ProgressBar.</li>
<li>Ability to calculate the elapsed time and show the progress bar(%) in ProgressBar way.</li>
<li>Ability to customize onSuccessCallBack and onFailCallBack functions in ProgressBar way.</li>
</ul>

### REQUIREMENTS ###
In order to use this library, you must include jQuery 1.7.2 or higher version

### UNIT TESTING ###
Tested OK on almost all browsers such as IE7+, Opera, Firefox, Google Chrome, Safari

### SAMPLES ###
> Here's example code:
`````javascript
   <script src="/Scripts/jquery-1.7.2.min.js"></script>
   <script src="/Scripts/jquery-unified-export-file-1.0.min.js"></script>
   <script type="text/javascript">
       $(function () {
          $.UnifiedExportFile({ action: '/', data: { IsExportExcel: true }, downloadType: 'Progress', ajaxLoadingSelector: '#loading' });
       });
   </script>
`````

### MORE INFORMATION ###
In order to know the further details, please go to the web address (https://exportfilebyjqueryaspnet.codeplex.com/) and (https://jqueryunifiedexportfile.codeplex.com/)
