# cpsc501-assignment-2-fft-optimization-solved
**TO GET THIS SOLUTION VISIT:** [CPSC501 Assignment 2-FFT Optimization Solved](https://www.ankitcodinghub.com/product/cpsc501-assignment-2-fft-optimization-15-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116476&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPSC501 Assignment 2-FFT Optimization Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Assignment policy:

1. Cite all sources of code that you hand in that are not your original work. You can putthe citation into comments in your program. For example, if you find and use code found on a web site, include a comment that says, for example:

# the following code is from https://www.quackit.com/python/tutorial/python_ hello_world.cfm.

Use the complete URL so that the marker can check the source.

3. Discuss and share ideas with other programmers as much as you like, but make surethat when you write your code that it is your own. A good rule of thumb is to wait 20 minutes after talking with somebody before writing your code. If you exchange code with another student, write code while discussing it with a fellow student, or copy code from another person’s console, then this code is not yours.

4. Collaborative coding is strictly prohibited. Your assignment submission must be strictlyyour code. Discussing anything beyond assignment requirements and ideas is a strictly forbidden form of collaboration. This includes sharing code, discussing code itself, or modelling code after another student’s algorithm. You can not use (even with citation) another student’s code.

Instructions:

The goal of this assignment is to optimize, in stages, the performance of a convolution reverb program. Convolution reverb is an audio digital signal processing technique where a “dry” recording of an instrument (i.e. a recording without reverberation) is convolved with the impulse response of an acoustical space such as a concert hall. The result of the convolution is a sound file where the instrument sounds as if it were playing in the actual concert hall. This is a commonly used, but computationally intensive, technique for adding natural-sounding reverberation to recorded sounds.

You are to create a command-line program that takes in a dry recording and an impulse response, and produces the convolved signal. It should be invoked from the command line as follows:

convolve inputfile IRfile outputfile

where convolve is the name of your program, inputfile is the dry recording in .wav format, IRfile is the impulse response in .wav format, and outputfile contains the convolved signal in .wav format. All .wav files should be monophonic, 16-bit, 44.1 kHz sound files (at least initially, before attempting the bonus part of the assignment). Sample audio and impulse response files are available on D2L.

As in the first assignment, you will be using GitLab to maintain version control and to share your final project with the TAs. Your assignment should be kept in a GitLab repository titled “CPSC 501 A2”.

Baseline program: Create an initial version of your program where the convolution is implemented directly in the time domain. You will find this version of your program quite slow. Measure the run-time performance of your program using a dry recording that is at least thirty seconds long and an impulse response that is at least 2 seconds long. You will reuse these same inputs for timing measurements after each optimization that you do in the later stages of the assignment. There are many suitable dry recordings and impulse responses available on the Internet as well as on the course D2L site. You can find various utility programs online to convert sound files of different types (e.g. .aiff or .snd) to the .wav format.

Compiler-level optimization and code-tuning: Use compiler-level optimization and manual code tuning to further optimize the performance of your program. Do your improvements step by step, measuring and testing at each stage. Be sure to test, profile, and commit your code each time you make a change. Use at least 4 different manual code-tuning techniques and at least one compiler optimization.

Notes on regression testing: Rather than writing unit tests for this assignment and comparing the output to some prepared standard, you will be using regression testing to ensure your program remains correct after each optimization step. To do this, you will need to keep the output from your initial baseline program for a particular pair of sound/IR input files. You should be able to check whether your baseline output is correct by simply listening to the output file. Then, after each optimization, compare this baseline output to the output of your modified program on the same input files. If the two outputs are identical, you have confirmed that your optimizations have left the program function unchanged. My recommendation would be to write a bash script that performs the comparison automatically, and to include this in your version control and report.

Bonus (up to 10%): Elaborate your program so that it can handle stereo (i.e. 2-channel) impulse response files, and produce the appropriate stereo (2-channel) output file. In other words, your program will convolve a monophonic dry input sound with a stereo impulse response, and output a stereo sound file. Your program should be able to recognize automatically if the impulse response file has one or two channels. You can either implement the bonus as part of your baseline program, or after all optimizations. If you choose to implement the bonus feature, you need to indicate this clearly in your report. Sample stereo IR files are available on D2L.

Submission instructions:

Rubric (100 pts total):

Version control: Used Git/GitLab properly, Multiple small commits with informative messages (5 pts)

Profiling: Tests are run after each improvement and the results are documented (5 pts)

Regression testing: Tests are run to make sure correctness is preserved between changes (5 pts)

Baseline program: Unoptimized program correctly performs convolution reverb in the time domain (20 pts)

Optimizations: Evidence in version control and report of five clear and systematic optimizations. The first of these must be an algorithmic optimization, implementing the FFT. The remainder must contain a compiler optimization and at least four distinct code tuning optimizations (20 + 5 + 20 = 45 pts)

Report: Description of each of the optimizations described above, with appropriate code excerpts shown. Report is thorough and written in full sentences. (15 pts)

Logistics: Clear, working instructions on how to access GitLab project. Program can be run from the command line using the specified instruction (5 pts)

Bonus: Solution can detect and handle stereo impulse response files (10 pts)

author: jcleahy@ucalgary.ca
