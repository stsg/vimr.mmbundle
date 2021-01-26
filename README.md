# vimr.mmbundle

# Installation

Clone this repository and place it in the appropriate directory for Mailmate:

	cd ~/Library/Application\ Support/MailMate/Bundles
	git clone https://github.com/wolfcw/vimr.mmbundle

# License

If not otherwise specified (see below), files in this repository fall under the following license:

	Permission to copy, use, modify, sell and distribute this
	software is granted. This software is provided "as is" without
	express or implied warranty, and with no claim as to its
	suitability for any purpose.

An exception is made for files in readable text which contain their own license information, or files where an accompanying file exists (in the same directory) with a “-license” suffix added to the base-name name of the original file, and an extension of txt, html, or similar.

# Credits

Based on mailmate/macvim.mmbundle by O'Shaughnessy Evans, see https://github.com/mailmate/macvim.mmbundle

Modified for VimR as described by Giovanni Lanzani, see https://lists.freron.com/mailmate/2017-October/008787.html

# Configuration

Edit file "Support/bin/edit" to add the directory, where VimR's vimr CLI tool has been installed, to PATH.

Edit file "Commands/Edit.mmCommand" to change 'keyEquivalent' to the desired hotkey
(default is Ctrl-1, opposed to Mailmate's default of Ctrl-Shift-O for external editors).
