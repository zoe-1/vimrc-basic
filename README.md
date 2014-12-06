#######################
 vimrc-basic
#######################

Description: Project contains a basic .vimrc file.
I kept helping people set up .vimrc files when collaborating
on projects so put this up to help others kick start their vim usage.  

Settings assume you are using Tim Pope's vim-pathogen. 
Install pathogen: https://github.com/tpope/vim-pathogen

-----------------------------------
Commands to Install 
-----------------------------------
mv basic_vimrc_template ~/.vimrc
mkdir ~/.vim-bkup
mkdir ~/.vim-tmp


-----------------------------------
Tab navigation shortcuts
-----------------------------------
	short cut 	vim command		description

  tj            :tabn 					-- go to tab at right of current.  
  tk 						:tabp 					-- go to tab at left of current.  
	th  					:tabfirst				-- go to first tab in window.  
	tl  					:tablast				-- go to last tab in window.  
	
	F4						:w							-- save document  
	F5						:tabp						-- previous tab same as tk shortcut  
	F6						:tabn 					-- next tab same as tj shortcut	  

	-- move tabs around  
	:Ztleft                       -- move current window left in tab list.   
	:Ztright                      -- move current window right in tab list.   


-----------------------------------
Split window shortcuts and commands
-----------------------------------
	-- Key vim commands to split windows:
	:vs				vertical split of current document (left right).
	:split		split current document in middle (top bottom)

	-- Short cuts to navigate split windows.
  short cut  vim command    description
	ctrl+h   		:wincmd h     -- move to view on left
	ctrl+j      :wincmd j     -- move to view below
	ctrl+k      :wincmd k     -- move to view above
	ctrl+l      :wincmd l     --move to view on right 

  -- Shortcuts to resize split windows
	:Zwshrink									-- shrink width by 15 spaces.
	:Zwexpand 								-- expand width by 15 spaces
	:Zhshrink                 -- shrink height by 8 spaces
	:Zhexpand 								-- expand height by 8




