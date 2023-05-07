Download Link: https://assignmentchef.com/product/solved-lab-program-4-binary-hex-decimal-ascii-a-function-cop3502-cs-1
<br>
The purpose of this lab problem is to print the binary, hex, decimal, and ASCII values of the upper and lower case alphabet.

This problem will only work with the letters A through Z, upper and lower case.

The <em>UPPER </em>case letters will be converted to <em>lower </em>case by invoking the conversion function named <em>ToLower</em>. This function will only use <em>bit manipulation </em>to accomplish the conversion.

<h1>1          Objectives</h1>

1.1     Inputs

The only input is the name of the program – <em>myHexLetters</em>. No other command line parameters are required.

1.1.1      Command Line arguments

The program will be invoked as follows:

<ul>

 <li>myHexLetters</li>

</ul>

<h1>2          Process</h1>

The program <em>myHexLetters </em>will generate and display the upper and lower case letters from A through Z. The conversion will be accomplished on a character basis using bit manipulations described in more detail below.

2.1       char ToLower(char myLetter)

Description: Converts the <em>UPPER </em>case letter to a <em>lower </em>case letter.

Returns: The lower case letter that was passed as input.

Caveat: The conversion must be accomplished using bit manipulation not addition or subtraction. That is the conversion must be accomplished using an <em>AND</em>, <em>OR</em>, <em>XOR</em>, or <em>NOT </em>operation – as appropriate.

<h1>3          Outputs</h1>

The output of the program will be for the upper &amp; lower case letters <em>A through Z</em>. The outputs are shown below.

<table width="343">

 <tbody>

  <tr>

   <td colspan="2" width="183">UPPER</td>

   <td colspan="2" width="159">lower</td>

  </tr>

  <tr>

   <td colspan="2" width="183">binary Hex Dec –</td>

   <td colspan="2" width="159">binary Hex Dec –</td>

  </tr>

  <tr>

   <td width="96">0100 0001</td>

   <td width="88">41 65 A</td>

   <td width="96">0110 0001</td>

   <td width="64">61 97 a</td>

  </tr>

  <tr>

   <td width="96">0100 0010</td>

   <td width="88">42 66 B</td>

   <td width="96">0110 0010</td>

   <td width="64">62 98 b</td>

  </tr>

  <tr>

   <td width="96">0100 0011</td>

   <td width="88">43 67 C</td>

   <td width="96">0110 0011</td>

   <td width="64">63 99 c</td>

  </tr>

  <tr>

   <td width="96">0100 0100</td>

   <td width="88">44 68 D</td>

   <td width="96">0110 0100</td>

   <td width="64">64 100 d</td>

  </tr>

  <tr>

   <td width="96">0100 0101</td>

   <td width="88">45 69 E</td>

   <td width="96">0110 0101</td>

   <td width="64">65 101 e</td>

  </tr>

  <tr>

   <td width="96">0100 0110</td>

   <td width="88">46 70 F</td>

   <td width="96">0110 0110</td>

   <td width="64">66 102 f</td>

  </tr>

  <tr>

   <td width="96">0100 0111</td>

   <td width="88">47 71 G</td>

   <td width="96">0110 0111</td>

   <td width="64">67 103 g</td>

  </tr>

  <tr>

   <td width="96">0100 1000</td>

   <td width="88">48 72 H</td>

   <td width="96">0110 1000</td>

   <td width="64">68 104 h</td>

  </tr>

  <tr>

   <td width="96">0100 1001</td>

   <td width="88">49 73 I</td>

   <td width="96">0110 1001</td>

   <td width="64">69 105 i</td>

  </tr>

  <tr>

   <td width="96">0100 1010</td>

   <td width="88">4a 74 J</td>

   <td width="96">0110 1010</td>

   <td width="64">6a 106 j</td>

  </tr>

  <tr>

   <td width="96">0100 1011</td>

   <td width="88">4b 75 K</td>

   <td width="96">0110 1011</td>

   <td width="64">6b 107 k</td>

  </tr>

  <tr>

   <td width="96">0100 1100</td>

   <td width="88">4c 76 L</td>

   <td width="96">0110 1100</td>

   <td width="64">6c 108 l</td>

  </tr>

  <tr>

   <td width="96">0100 1101</td>

   <td width="88">4d 77 M</td>

   <td width="96">0110 1101</td>

   <td width="64">6d 109 m</td>

  </tr>

  <tr>

   <td width="96">0100 1110</td>

   <td width="88">4e 78 N</td>

   <td width="96">0110 1110</td>

   <td width="64">6e 110 n</td>

  </tr>

  <tr>

   <td width="96">0100 1111</td>

   <td width="88">4f 79 O</td>

   <td width="96">0110 1111</td>

   <td width="64">6f 111 o</td>

  </tr>

  <tr>

   <td width="96">0101 0000</td>

   <td width="88">50 80 P</td>

   <td width="96">0111 0000</td>

   <td width="64">70 112 p</td>

  </tr>

  <tr>

   <td width="96">0101 0001</td>

   <td width="88">51 81 Q</td>

   <td width="96">0111 0001</td>

   <td width="64">71 113 q</td>

  </tr>

  <tr>

   <td width="96">0101 0010</td>

   <td width="88">52 82 R</td>

   <td width="96">0111 0010</td>

   <td width="64">72 114 r</td>

  </tr>

  <tr>

   <td width="96">0101 0011</td>

   <td width="88">53 83 S</td>

   <td width="96">0111 0011</td>

   <td width="64">73 115 s</td>

  </tr>

  <tr>

   <td width="96">0101 0100</td>

   <td width="88">54 84 T</td>

   <td width="96">0111 0100</td>

   <td width="64">74 116 t</td>

  </tr>

  <tr>

   <td width="96">0101 0101</td>

   <td width="88">55 85 U</td>

   <td width="96">0111 0101</td>

   <td width="64">75 117 u</td>

  </tr>

  <tr>

   <td width="96">0101 0110</td>

   <td width="88">56 86 V</td>

   <td width="96">0111 0110</td>

   <td width="64">76 118 v</td>

  </tr>

  <tr>

   <td width="96">0101 0111</td>

   <td width="88">57 87 W</td>

   <td width="96">0111 0111</td>

   <td width="64">77 119 w</td>

  </tr>

  <tr>

   <td width="96">0101 1000</td>

   <td width="88">58 88 X</td>

   <td width="96">0111 1000</td>

   <td width="64">78 120 x</td>

  </tr>

  <tr>

   <td width="96">0101 1001</td>

   <td width="88">59 89 Y</td>

   <td width="96">0111 1001</td>

   <td width="64">79 121 y</td>

  </tr>

  <tr>

   <td width="96">0101 1010</td>

   <td width="88">5a 90 Z</td>

   <td width="96">0111 1010</td>

   <td width="64">7a 122 z</td>

  </tr>

 </tbody>

</table>