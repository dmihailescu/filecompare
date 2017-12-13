                
<div class="wikidoc">
<h1>File Compare And Hash extension for Windows explorer tool</h1>
<h2>Description</h2>
This project will add a shell extension for windows explorer allowing for easy binary or text file comparison
<br>
as well as calculating the MD5, SHA1, SHA256 from the selected files.<br>
<br>
This tool was designed for maximum of convenience in mind for these scenarios:<br>
<ul>
<li>To compare 2 text files you highlight them, right click on the selection and from the pop up menu navigate to
<i>&quot;Compare&amp;Hash&quot;-&gt;&quot;Compare text files...&quot;</i>.</li></ul>
<img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=FileCompareAndHash&DownloadId=1477934" alt="textcompare.gif" title="textcompare.gif"><br>
<ul>
<li>If all files to be hashed were in the same folder, you can select them, right click and choose the hashing algorithm. A message box with the selected files and their respective hashes will appear as seen below.</li></ul>
<img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=FileCompareAndHash&DownloadId=1477697" alt="multiselection.gif" title="multiselection.gif"><br>
<br>
*If only one file was selected, then you would have the option to copy the specific hash to the clipboard.<br>
<br>
<img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=FileCompareAndHash&DownloadId=1477696" alt="singleselect.gif" title="singleselect.gif"><br>
<ul>
<li>When the files to compare are in different directories, select the first file, right click on it and select
<i>&quot;Binary/TextCompare with...&quot;</i>. A file dialog will appear in order to select the file to compare to. Select the second file and click
<i>&quot;Open&quot;</i>. </li></ul>
<img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=FileCompareAndHash&DownloadId=1477695" alt="comparefiles.gif" title="comparefiles.gif"><br>
Depending on your selection, a message box will show the text differences or will show you if the files were identical.
<br>
You have to option to continue to check the differences between the selected files like size, modified time or calculate specific the hashes on them.<br>
<h2>Distribution</h2>
This project reuses a part of the <a href="http://sharpshell.codeplex.com">SharpShell</a> source code version 2.2 from
<i>Dave Kerr</i> (it was of tremendous help to me), and for text comparison the controls from
<a href="http://www.codeproject.com/Articles/42007/DeltaScope">DeltaScope</a> (a cool UI presentation). You have the whole source code to rebuild my project for this extension and make the installation script, but anything related with
<b>SharpShell</b> is present only as binaries.<br>
More detailed information about this project and its inner working can be found on
<a href="http://www.codeproject.com/Articles/1016022/File-Compare-And-Hash-extension-for-Windows-explor">
codeproject</a>.<br>
<br>
The release download consists of a zip with an install/uninstall script for your convenience that contains only binaries.<br>
<br>
You can support this project by <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=3UNEYK64HSWTJ">
donating using PayPal</a>.</div>
