zClipboard
==========

This is a ZeroClipboard extension for the Yii Framework.

# Installing

* Download the zClipboard file
* Unzip the file and copy it to the /protected/extensions/ directory in your Yii app

# Usage

	$this->widget('ext.zClipboard.zClipboard, array(
		'tag' => 'a',
		'tagHtmlOptions' => array('class'=>'copy-class'),
		'tagId' => 'copy_button',
		'clipboardText' => 'This is the text that will be copied'
	));

## Options
  
**tag** - the type of tag to use (Default: 'button')  

**tagHtmlOptions** - the htmlOptions for the tag (i.e. 'id', 'class', etc.)  

**tagContent** - the content between the tags    

**closeTag** - whether or not to use a closing tag  

**tagId** - shortcut for the tag ID, could also use tagHtmlOptions   

**zcOptions** - ZeroClipboard options 

example:  
	
	array('moviePath'=>'....')  

**zcEvents** - ZeroClipboard events in an array 

example: 
	
	array('load'=>'onLoad')  

**clipboardText** - the text that will be copied when the user clicks the movie   

**scriptPos** - the position of the scripts (Default: 'END')   
