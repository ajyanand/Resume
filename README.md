# My Current Resume
<object data="https://github.com/ajyanand/Resume/blob/main/ATS%20Resume%20Ajay%20May%202023%20Full_JnJ.pdf" width="700px" height="700px">
    <embed src="https://github.com/ajyanand/Resume/blob/main/ATS%20Resume%20Ajay%20May%202023%20Full_JnJ.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/ajyanand/Resume/blob/main/ATS%20Resume%20Ajay%20May%202023%20Full_JnJ.pdf">Download PDF</a>.</p>
    </embed>
</object>

for d in *.pdf ; do inkscape --without-gui --file=$d --export-plain-svg=${d%.*}.svg ; done
