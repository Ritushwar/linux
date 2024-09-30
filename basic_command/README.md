<!DOCTYPE html>
<html lang="en-US">
	<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta charset="utf-8" />
		<title>
		</title>
		<style>
			body { widows:0; orphans:0; font-family:'Liberation Serif'; font-size:12pt }
			p { margin:0pt }
			li { margin-top:0pt; margin-bottom:0pt }
			.Caption { margin-top:6pt; margin-bottom:6pt; widows:0; orphans:0; font-size:12pt; font-style:italic }
			.Heading { margin-top:12pt; margin-bottom:6pt; page-break-after:avoid; widows:0; orphans:0; font-family:'Liberation Sans'; font-size:14pt }
			.Index { widows:0; orphans:0; font-size:12pt }
			.List { margin-top:0pt; margin-bottom:7pt; line-height:115%; widows:0; orphans:0; font-size:12pt }
			.Standard { widows:0; orphans:0; font-size:12pt }
			.Textbody { margin-top:0pt; margin-bottom:7pt; line-height:115%; widows:0; orphans:0; font-size:12pt }
			span.BulletSymbols { font-family:OpenSymbol }
@media (max-width: 900px) { 
img { 
   max-width: 100%;
   height: auto;
}

.table-container {
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
}

table {
    width: 100%;
    border-collapse: collapse;
}

td, th {
    padding: 8px;
    text-align: left;
    border: 1px solid #ddd;
}
}	


		</style>
	</head>
	<body>
			<p class="Standard" style="font-size:18pt">
				<strong><u>Linux Basic Commands For Beginner</u></strong>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				<strong>man command_name</strong>: <u>to know more about the command in terminal</u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">1) </span><strong>pwd command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">present working directory</span></u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">2) </span><strong>cd command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">change directory</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cd directory_name</strong>: goes inside the directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cd ..</strong> : get outside the directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cd /</strong> : root directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cd ~</strong> : home directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cd *My Book*</strong> : to enter inside the directory which have space
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">3) </span><strong>ls command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">list out the directory and files</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0; <strong>[ls option file/directory]</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ls /</strong> : root directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ls ..</strong> : list out from the one step back from present
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ls ../..</strong> : two step back
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong><u>in option</u></strong>
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-l</strong> : in long format
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-a</strong> : show hidden files
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-al</strong> : hidden in long format
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-lS</strong> : short by size
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>/*.html</strong> : file which have have only html extension
			</p>
			<p class="Standard" style="margin-left:36pt">
				/*.* : all file with all extension
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-ls &gt; output_file</strong> : save the output in file
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-d */</strong> : only directory
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">4) </span><strong>cp command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">to copy the files and directory</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0; <strong>[ cp options sources destination]</strong>
			</p>
			<p class="Standard">
				<strong><u>in option</u></strong>
			</p>
			<p class="Standard">
				&#xa0; <strong>-i</strong> : prompts you before overwriting.
			</p>
			<p class="Standard">
				&#xa0;<strong>-n</strong> : avoids overwriting without prompting.
			</p>
			<p class="Standard">
				&#xa0;<strong>-R</strong> : recursive copy(copying the directory)
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">5) </span><strong>cat command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">related to text file (display, combining, creating)</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0; <strong>[cat option files_name]</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat</strong> : echo the input
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat file_name</strong>: to print the content of file in terminal
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat -E file_name</strong> : add $ at each of the end of line
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ctrl + D</strong> : to get out of the cat command
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">6) </span><strong>I/O redirection</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">capturing output from the file, command or program and sending it to another file, command or the program as input</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0; <strong>[output &gt; file_name]</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat &gt; file_name.txt</strong> : (creating the file) convert enter text from terminal into text file
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat &gt;&gt; file_name.txt</strong>:&#xa0; to append
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat file1 file2 &gt; combined_file</strong>: combined_file = file1 + file2(&gt;&gt; → for appending)
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat file1&gt;&gt; file2</strong> : file2 = file1 + file2
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">7) </span><strong>mkdir command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">making directory</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>mkdir directory_name: </strong>creating the directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>mkdir directory_name/ sub_directory_name </strong>: create sub directory inside the existing dir
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>mkdir -p directory/sub_directory_name </strong>: even though directory doesn’t exist
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>mkdir -p directory/ {sub_directory_lists}</strong>: to create multiple sub directory
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">8) </span><strong>rm and rmdir command</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">remove the file and directory</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-r</strong> : recursive remove
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">9) </span><strong>mv command</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">to move files from one location to another</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>[mv options source destinations]</strong>
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>in options</strong>
			</p>
			<p class="Standard" style="margin-left:36pt">
				&#xa0; <strong>-i</strong> : for overwritten or not
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">10) </span><strong>less command </strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">to read the file</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>less file_name.txt</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>q </strong>: get back to the terminal
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">11) </span><strong>touch command </strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">to create new empty file and change the time stamping in existing file</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>touch file_name</strong>
			</p>
			<p class="Standard" style="margin-left:36pt">
				&#xa0; 1) <strong>if not exist</strong> : create the new empty file
			</p>
			<p class="Standard" style="margin-left:36pt">
				&#xa0; 2) <strong>if already exist</strong> : change the time stamp
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">12) </span><strong>nano command </strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">text editor for search, replace,……</span></u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">13) </span><strong>sudo command </strong><span style="font-size:12pt">:</span>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo passwd </strong>: <u>to set password in the user</u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">14) </span><strong>top command</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">dynamic and the real time view of the system</span></u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">15) </span><strong>kill command</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">to kill the current process</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt; font-size:14pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:11pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>kill -flags pid</strong>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; <strong>to know about the pid</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ps -ux</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ps -aux</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ps -U user_name</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>ps -C</strong>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">16) </span><strong>echo command</strong><span style="font-size:12pt"> :</span>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>var_name=“ value “ </strong>: for creating the variable
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>echo $var_name</strong> : print the variable
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>echo -e</strong> : for escape sequence
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>echo -e \t </strong>: horizontal tab
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>echo -e</strong><strong>&#xa0; </strong><strong>\n</strong> : new line
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">17) </span><strong>file permission</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">control the access that users have to files and directories. Each file and directory has three types of permissions for three different categories of users.</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0; <strong>chmod [who][+/-][permission] [file_or_directory]</strong>
			</p>
			<p class="Standard">
				<strong>&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </strong><strong>In who:</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-u (user or owner), -g(group), -o(others), a(all)</strong>
			</p>
			<p class="Standard">
				<strong>&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </strong><strong>+ for add and – for remove the permission</strong>
			</p>
			<p class="Standard">
				<strong>&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </strong><strong>In permission</strong>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-r (read), -w(write), -x(execute)</strong>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">18) </span><strong>directory permissions</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">it is same as but for the directory</span></u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">19) </span><strong>octal and numerical permission </strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">giving the permission using the number</span></u>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; <strong>r</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>w</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>x</strong>&#xa0; 
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; <strong>1</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>1</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>1</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>(1→ yes)</strong>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; <strong>4</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>2</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>1</strong><strong>&#xa0;&#xa0;&#xa0; </strong><strong>(0 → no)</strong>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; <strong>4+2+1 = 7 (for rwx permission)</strong>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				20) <strong>Bash scripting </strong>: <u>Script is the a test file that contains sequence of command</u>. Its is better to give .sh extension for scripting file. Ex: my_script.sh . Inside the scripting file first line should be
			</p>
			<p class="Standard">
				&#xa0;<strong>#! location of the bash </strong>then interpreter notice that is a scripting file. To find the location of bash use <strong>which bash</strong> inside the other new terminal.
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>./my_script.sh</strong> : to execute the bash script
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>to execute the bash script you must have the execute permission</strong>
			</p>
			<p class="Standard">
				&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; Note: <u>after script execute, the working directory return to where the script was initially called</u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">21) </span><strong>which and whatis command </strong><span style="font-size:12pt">:</span>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>which [command/file_name]</strong> : return the path of a file_name or command and it is better to use the full location of a command
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>whatis</strong> : return the short description of command
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">22) </span><strong>useradd commands</strong><span style="font-size:12pt"> : </span><u><span style="font-size:12pt; ">Is used to create a new user account on the system</span></u><span style="font-size:12pt">. It allows you to specify various options for the new user, such as the home directory, shell, and user ID.</span>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo useradd name_user flags </strong>:
			</p>
			<p class="Standard" style="margin-left:36pt">
				in flags
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span> <strong>-m</strong> : create default home directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-s</strong> : default shell
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-g</strong> : default user
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>-c</strong> : to add comment in the user
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">23) </span><strong>userdel commands</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">to delete the user</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo userdel user_name</strong>:
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo userdel -r user_name</strong>: also delete home directory
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<strong><span style="font-family:OpenSymbol; font-weight:normal">●</strong></span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo rm -r /home/user_name</strong>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">24) </span><strong>Basic group management</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">to create, modify, and delete groups of users.</span></u>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>groups </strong>: gives groups added with user
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>cat /etc/group</strong> : all the group in system
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo groupadd group_name </strong>: to add group
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo groupdel group_name </strong>:
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>sudo gpasswd -a user_name group_name</strong> : to assign a user to a particular group
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-a</strong>→ <u>adding group</u>
			</p>
			<p class="Standard" style="margin-left:36pt">
				<strong>-d</strong>→ <u>removing group</u>
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard">
				&#xa0;
			</p>
			<p class="Standard" style="font-size:14pt">
				<span style="font-size:12pt">25) </span><strong>.bashrc file</strong><span style="font-size:12pt">: </span><u><span style="font-size:12pt; ">bash script runs whenever a user opens a new interactive non-login shell</span></u><span style="font-size:12pt">.</span>
			</p>
			<p class="Standard" style="margin-left:36pt; text-indent:-18pt">
				<span style="font-family:OpenSymbol">●</span><span style="width:12pt; font:7pt 'Times New Roman'; display:inline-block">&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0; </span><strong>nano .bashrc</strong> : to see/edit the contain inside the bashrc file
			</p>
			<p class="Standard">
				&#xa0;&#xa0; 
			</p>
	<p style="bottom: 10px; right: 10px; position: absolute;"><a href="https://wordtohtml.net" target="_blank" style="font-size:11px; color: #d0d0d0">Converted to HTML with WordToHTML.net</a></p>
<script defer src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon='{"rayId":"8cb153c56e83249f","version":"2024.8.0","r":1,"token":"4581d6a58cf94e929fad52deda295622","serverTiming":{"name":{"cfExtPri":true,"cfL4":true}}}' crossorigin="anonymous"></script>
</body>
</html>