![logo](https://cerberusnuclear.com/wp-content/uploads/2020/10/EddyLinkedin.jpg)

Eddy is a HTML output generator for MCNP and SCALE; it imports an MCNP or SCALE output file, extracts the important data, and writes it to a user-friendly HTML file.

This repository contains the the executable version of Eddy. The exectuable itself is the  file found in the top level Eddy folder. It can be run simply by double-clicking on this executable; GUI windows will then request an MCNP/SCALE file and a scaling factor.

Alternatively, Eddy can be run from the command line, and optional parameters can be given: 
the filename of the mcnp output file and a scaling factor to multiply tally resutls by.

General CLI usage:

```bash
>> Eddy_beta_03.exe [-h] [-o FILE] [-sf SCALING_FACTOR]
```

Eddy is also available as [python source code](https://github.com/Cerberus-Nuclear/.Eddy-Source), and on the PyPI Python Package index as eddy-mc, in order to allow easier integration into other programs. More information on these options can be found in the README.md file on the [source code repository](https://github.com/Cerberus-Nuclear/.Eddy-Source).

<details>
  <summary>Example HTML outputs</summary>
  <img src="https://cerberusnuclear.com/wp-content/uploads/2020/10/eddy-screen-shot-2.jpg" name="image-name">
  <img src="https://cerberusnuclear.com/wp-content/uploads/2020/10/Results_Summary-1.jpg" name="image-name">
  <img src="https://cerberusnuclear.com/wp-content/uploads/2020/10/Results_Stats-1.jpg" name="image-name">
  <img src="https://cerberusnuclear.com/wp-content/uploads/2020/10/WarningsComments.jpg" name="image-name">
  <img src="https://cerberusnuclear.com/wp-content/uploads/2020/10/particles-1.jpg" name="image-name">
</details>
