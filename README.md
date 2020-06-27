# Learning Git

I am using this repo to learn and use as a example for Git and GitHub course

![Git_Image](./gitimage.png)

<b>Commands: </b>

<ul>
	<li>Add new files and modified for the next commit <br/>
		<b><i>git add .</i></b></li><br/>
	<li>Register the commit with all the files used in "git add ." <br/>
		<b><i>git commit -m "[message]"</i></b></li><br/>
	<li>Verify status if needs to add and commit some file <br />
		<b><i>git status</i></b></li><br/>
	<li>Verify latest created commits <br />
		<b><i>git log</i></b></li><br/>
	<li>Clone repo <br />
		<b><i>git clone [url]</i></b></li><br/>
	<li>Download updates <br />
		<b><i>git pull [url]</i></b></li><br/>
	<li>Navegate in commits<br />
		<b><i>git checkout [commit] [file]</i></b></li><br/>
	<li>Undo modifications that aren't in stage<br />
		<b><i>git checkout -- [file]</i></b>
			or 	 
		<b><i>git checkout -- .</i></b></li><br/>
	<li>If already added modifications to stage<br />
		<b><i>git checkout HEAD -- [file]</i></b></li><br/>
	<li>crate a new commit reverting another commit especified<br />
		<b><i>git revert [commit]</i></b></li><br/>
	<li>Reset repo for determined commit<br />
		<b><i>git reset [commit]</i></b></li><br/>
	<li>REMOVE ALL MODIFICATIONS (BE F#CKING CAREFULL)<br />
		<b><i>git reset --hard [commit]</i></b><br/>
		--hard (delete the modifications in files)<br/>
		--soft (keep the modifications in files)</li>
	<li>crate a new branch<br />
		<b><i>git branch [branch_name]</i></b></li><br/>
	<li>crate a new branch and already go to it<br />
		<b><i>git checkout -b [branch_name]</i></b></li><br/>
	<li>Delete a branch<br />
		<b><i>git branch -d [branch_name]</i></b></li><br/>
	<li>Change branch<br />
		<b><i>git checkout [branch_name]</i></b></li><br/>
	<li>First push in new branch<br />
		<b><i>git push --set-upstream origin [branch_name]</i></b>
			or
		<b><i>git push -u origin [branch_name]</i></b></li><br/>
	<li>Merge branch (remember to be where you want to merge)<br />
		<b><i>git merge [branch_name]</i></b></li><br/>
	<li>Rebase branch (remember to be where you want to "delete")<br />
		<b><i>git rebase [destine_branch_name]</i></b></li><br/>
		
</ul>		
		