

# Your Home Work Assignment
### #(_read through this note and then use what you learned_ to make another template file that will serve as your daily note)
# Metadata (_The Key To Rule Them All_...)

##  YASL - **_The Best Language & Format To Write Your Metadata in... * The ONLY structure you should write it in ( Out or inside Obsidian - It's Universal)_

### Make sure you read this, I am about to show you how to write your Metadata. 

	Always start and end your YASL with three dashes 
	and then you should always leave 2 lines of vertical whitespace from the dashes and your key values ()
	
	TheKey: #and-I-am-the-value #each-hashtage-represents 
	
	"Each key will store the values in a list. Each hashtag represents a new
	 value in that list. And as I know you know - the collective is stored as a list of arrays"

---

Aliases: #Alternative-File-Name #Or-File-Namesss
Tags: #yasl #essential-obsidian
ID:
Title:

---

You can place it on the bottom or top of the pages (best practice is top. And when you put it on top, you will see it instantly gets rendered into "Properties" which is the same exact thing, its just a function of obsidians that does absolutely nothing other than make it easier by deducting a 3 second step)

Lastly - I am sure you would come to the conclusion of how you might use templar and properties together

I personally just use the output of this Title:<% tp.date.now("YYYY-MM-DD") %> as my title for logs

And I always use the longer - concatenated ID: <% tp.date.now("YYYYMMDDHHMMSS") %> as a ID: that I add in the metadata 

ID: <% tp.date.now("YYYYMMDDHHMMSS") %>
Title:<% tp.date.now("YYYY-MM-DD") %>
















