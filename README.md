#######################
 vimrc-basic
#######################

Description: Project contains a basic .vimrc file.
A basic .vimrc file to kick start your vim usage.

Settings assume you are using Tim Pope's vim-pathogen.
Install pathogen: https://github.com/tpope/vim-pathogen

-----------------------------------
Commands to Install
-----------------------------------
mv basic_vimrc_template &nbsp;&nbsp;&nbsp; ~/.vimrc
mkdir ~/.vim-bkup
mkdir ~/.vim-tmp


-----------------------------------
Tab navigation shortcuts
-----------------------------------
<table>
<tr>
	<td>short cut&nbsp;&nbsp;&nbsp;&nbsp;</td><td>vim command&nbsp;&nbsp;&nbsp;&nbsp;</td><td>description</td>
</tr>
<tr>
  <td>tj </td>	<td>					:tabn 	</td>		<td>		-- go to tab at right of current window.  </td>
</tr>
<tr>
  <td>tk </td>	<td>					:tabp 	</td>		<td>		-- go to tab at left of current window.  </td>
</tr>
<tr>
  <td>th </td>	<td>					:tabfirst 	</td>		<td>		-- go to first tab in tab list.  </td>
</tr>
<tr>
  <td>tl </td>	<td>					:tablast 	</td>		<td>		-- go to last tab in tab list.  </td>
</tr>
<tr>
  <td>  </td>	<td>				 	</td>		<td>		  </td>
</tr>
<tr>
  <td>F4  </td>	<td>				:w 	</td>		<td>		-- save document  </td>
</tr>
<tr>
  <td>F5  </td>	<td>				:tabp 	</td>		<td>		-- previous tab same as tk shortcut  </td>
</tr>
<tr>
  <td>F6  </td>	<td>				:tabn 	</td>		<td>		-- next tab same as tj shortcut  </td>
</tr>
<tr>
  <td></td>
</tr>
<tr>
  <td>-- move tabs around</td>
</tr>
<tr>
  <td>:Ztleft  </td>	<td>				 	</td>		<td>		-- move current window left in tab list.  </td>
</tr>
<tr>
  <td>:Ztright  </td>	<td>				 	</td>		<td>		-- move current window right in tab list.  </td>
</tr>
</table>


-----------------------------------
Split window shortcuts and commands
-----------------------------------

<table>
<tr> <td>:vs</td><td>vertical split of current document (left right) split.</td> <td> </td>
</tr>
<tr><td>:split</td><td>split current document in middle (top bottom) </td>
</tr>
<tr>
	<td> </td> <td> </td> <td> </td>
</tr>
<tr>
	<td>
	-- Short cuts to navigate split windows.
 </td>
</tr>
<tr>
	<td>ctrl+h </td>  <td>		:wincmd h</td> <td>    -- move to view on left</td>
</tr>
<tr>
	<td> ctrl+j </td> <td> :wincmd j</td> <td> -- move to view below</td>
</tr>
<tr>
	<td> ctrl+k </td> <td> :wincmd k</td> <td> -- move to view above</td>
</tr>
<tr>
	<td> ctrl+l      </td> <td> :wincmd l  </td> <td> --move to view on right</td>
</tr>
<tr>
	<td> </td> <td> </td> <td> </td>
</tr>
</table>

-----------------------------------
Essential Buffers Commands
-----------------------------------

command |     description
------- | ------------------
**:ls**                 |   List the current buffers (including their numbers).<br/>
**:b** \<number\>       |   Display the buffer with the given number.<br/>
**:b** \<partial\>      |   Display the first buffer matching the partial name (or press Tab for name completion).<br/>
**:bd**                 |   Delete the current buffer; will fail if unsaved (nothing is deleted).<br/>
**:bd!**                |   Delete the current buffer; will discard any changes (changes are lost).<br/>


-----------------------------------
Resize split windows
-----------------------------------
command     |   description
----------- | ---------------------
**:Zwshrink**  | shrink width by 15 spaces.
**:Zwexpand**  | expand width by 15 spaces
**:Zhshrink**  | shrink height by 8 spaces
**:Zhexpand**  | expand height by 8


#### remove whitespace from end of lines
* F7
* :Trim

#### spellcheck 
* :set spell spelllang=en_us
* :set nospell 
* ]s [s navigates to misspelled words

