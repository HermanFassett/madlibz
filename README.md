#Madlibz API
A madlibs api for random madlibs templates
##Get a Random Madlib Template
The base url to get a random madlib template, is as follows:<br>
```
http://madlibz.herokuapp.com/api/random
```
The url query options are as follows:
<table>
  <thead>
    	<tr>
        <th>Query</th>
        <th>Type</th>
        <th>Description</th>
    	</tr>
  </thead>
  <tbody>
		<tr>
        <td>minlength</td>
        <td>Number</td>
        <td>The min number of user inputs in template</td>
    	</tr>
    	<tr>
        <td>maxlength</td>
        <td>Number</td>
        <td>The max number of user inputs in template</td>
    	</tr>
  </tbody>
</table>
#Get a Random Verb
Here is an example call:
```
http://madlibz.herokuapp.com/api/random?minlength=5&maxlength=25
```
Example output:
```
{
    "blanks": 
    [
        "foreign country",
        "adverb",
        "adjective",
        "animal",
        "verb ending in 'ing'",
        "verb",
        "verb ending in 'ing'",
        "adverb",
        "adjective",
        "a place",
        "type of liquid",
        "part of the body",
        "verb"

    ],
    "value":
    [
        "If you are traveling in ",
        " and find yourself having to cross a piranha-filled river, here's how to do it ",
        ": \n* Piranhas are more ",
        " during the day, so cross the river at night.\n* Avoid areas with netted ",
        " traps--piranhas may be ",
        " there looking to ",
        " them!\n* When ",
        " the river, swim ",
        ". You don't want to wake them up and make them ",
        "!\n* Whatever you do, if you have an open wound, try to find another way to get back to the ",
        ". Piranhas are attracted to fresh ",
        " and will most likely take a bite out of your ",
        " if you ",
        " in the water!",
​        0
    ],
    "title": "How To Cross a Piranha-Infested River"
}
```
