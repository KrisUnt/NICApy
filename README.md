<!DOCTYPE html><html><head><meta charset="utf-8"><title>NICApy.md</title><style></style></head><body id="preview">
<h1 class="code-line" data-line-start=0 data-line-end=1><a id="NICApy_0"></a>NICApy</h1>
<h2 class="code-line" data-line-start=1 data-line-end=2><a id="A_Pythonbased_GUI_application_for_fNIRS_signal_analysis_1"></a>A Python-based GUI application for fNIRS signal analysis</h2>
<p class="has-line-data" data-line-start="4" data-line-end="5">NICApy is a software for fNIRS signal analysis. It allows to load the data files recorded with the NIRScout measurement device of NIRx and performs processing steps including filtering and artefact correction on single measurement data. After a single analysis a modified t-test can be performed in order to verify the presence of a signal. Furthermore, NICApy allows to perform a Grand Average analysis to obtain group specific results for further statistical analysis.</p>
<h2 class="code-line" data-line-start=7 data-line-end=8><a id="Features_7"></a>Features</h2>
<ul>
<li class="has-line-data" data-line-start="9" data-line-end="10">Loading hdr and xdf files</li>
<li class="has-line-data" data-line-start="10" data-line-end="11">Apply different filter methods</li>
<li class="has-line-data" data-line-start="11" data-line-end="12">Remove physiological induced artefacts on fNIRS signals</li>
<li class="has-line-data" data-line-start="12" data-line-end="13">Perform a modified one-sample t-test</li>
<li class="has-line-data" data-line-start="13" data-line-end="14">Allow Grand Average analysis</li>
<li class="has-line-data" data-line-start="14" data-line-end="16">Saves all output files for further use</li>
</ul>
<h2 class="code-line" data-line-start=16 data-line-end=17><a id="Requirements_16"></a>Requirements</h2>
<p class="has-line-data" data-line-start="18" data-line-end="19">NICApy uses the following packages available in Python:</p>
<ul>
<li class="has-line-data" data-line-start="20" data-line-end="21"><a href="https://pypi.org/project/pyxdf/">pyXDF</a> - pyXDF is a Python importer for XDF files.</li>
<li class="has-line-data" data-line-start="21" data-line-end="22"><a href="https://pypi.org/project/scipy/1.6.2/">SciPy</a> - Fundamental algorithms for scientific computing in Python</li>
<li class="has-line-data" data-line-start="22" data-line-end="23"><a href="https://pypi.org/project/heartpy/">HeartPy</a> - Python Heart Rate Analysis Toolkit</li>
<li class="has-line-data" data-line-start="23" data-line-end="24"><a href="https://pypi.org/project/numpy/1.19.1/">NumPy</a> - NumPy is the fundamental package for array computing with Python.</li>
<li class="has-line-data" data-line-start="24" data-line-end="25"><a href="https://pypi.org/project/matplotlib/3.2.2/">matplotlib</a> - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.</li>
<li class="has-line-data" data-line-start="25" data-line-end="26"><a href="https://pypi.org/project/XlsxWriter/1.4.4/">XlsxWriter</a> - XlsxWriter is a Python module for writing files in the Excel 2007+ XLSX file format.</li>
<li class="has-line-data" data-line-start="26" data-line-end="28"><a href="https://pypi.org/project/PyQt5/5.15.4/">PyQt5</a> - PyQt5 is a comprehensive set of Python bindings for Qt v5.</li>
</ul>
<h2 class="code-line" data-line-start=28 data-line-end=29><a id="Installation_28"></a>Installation</h2>
<p class="has-line-data" data-line-start="30" data-line-end="32">NICApy requires at leats Python 3.7 to run.<br>
Install the requirements by running the requirements.txt file inside the terminal or and IDE.</p>
<pre><code class="has-line-data" data-line-start="34" data-line-end="36" class="language-sh">python <span class="hljs-number">3</span> pip install -r requirements.txt
</code></pre>
<p class="has-line-data" data-line-start="36" data-line-end="37">Then run the file <a href="http://NICApy.py">NICApy.py</a> in the same environment.</p>
<pre><code class="has-line-data" data-line-start="38" data-line-end="40" class="language-sh">python3 NICApy.py
</code></pre>
<h2 class="code-line" data-line-start=41 data-line-end=42><a id="Development_41"></a>Development</h2>
<p class="has-line-data" data-line-start="43" data-line-end="44">Want to contribute? Great!</p>
<p class="has-line-data" data-line-start="45" data-line-end="47">NICApy uses github for future development.<br>
Contribute your suggestions to this github page.</p>
<h2 class="code-line" data-line-start=48 data-line-end=49><a id="License_48"></a>License</h2>
<p class="has-line-data" data-line-start="50" data-line-end="51">GNU General Public Licencse, Version 3</p>
</body></html>