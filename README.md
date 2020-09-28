# Eddy

Eddy is a HTML output generator for MCNP and SCALE. It was created by Cerberus Nuclear. Cerberus Nuclear accepts no 
responsibility for the accuracy of any results presented with Eddy. 

Eddy taken an MCNP or SCALE output file, extracts the important data, 
and writes it to a user-friendly HTML file. 

All the code within this project is covered by GPLv3, the GNU Public Licence, Version 3, June 2007. A full copy of this 
licence is included with the source code; more information can be found at <https://www.gnu.org/licenses/>.

Eddy can be downloaded as either a pre-compiled executable, from <https://github.com/Cerberus-Nuclear/Eddy>,
or as source code from <https://github.com/Cerberus-Nuclear/Eddy-Source>.

This is the executable version of Eddy. The exectuable itself is the Eddy_beta_
01.exe file found in the top level Eddy folder. It can be run simply by double-clicking on this executable.

Eddy can be run from the command line with the output file and any applicable scaling factor as optional arguments;
if no such arguments are supplied a GUI will appear to request them.

General CLI usage: python3 Eddy.py [-o outputfile] [-sf scaling_factor] ---> outputfile.html 

