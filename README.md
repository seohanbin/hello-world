#markdown ( Github Flavored )

# hello-world

```
fenced code block
GFM also supports fenced blocks
```

###code block text

    int main ()
    {reuturn 0;}

### Keep in mind that, within lists, you must indent non-fenced code blocks eight spaces to render them properly.

        what is it?

###hyperlink test

http://example.com



<br>
###igonore underscore

o_this_and_do_that_and_another_thing.


###strikethough text

~~Mistaken text.~~


###Syntax highlighting

```ruby
WRITE LANG NAME AT FIRST
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

###tables

First Header  | Second Header
----------- | -------------
Content Cell    s | Content Cell
Content Cell  | Content Cell
markdown table can be unparallel column
Note that the dashes at the top don't need to match the length of the header text exactly

###table for anesthetic purpose

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


####You can also include inline Markdown such as links, bold, italics, or strikethrough:
| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

####Finally, by including colons : within the header row, you can define text to be left-aligned, right-aligned, or center-aligned:

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
