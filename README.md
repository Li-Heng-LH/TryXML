# TryXML
Walk through of tutorial: [XML Essential Training](https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fxml-essential-training-2%3Ftrk%3Dshare_ent_url)

&nbsp;
----
### Some Learning Notes ###

##### Proper XML Syntax ##### 
* XML document must have a single root tag. 
* Attribute values cannot be minimised.   
`<option selected>` is illegal, use `<option selected = "selected">`  
There is no way for XML to know if the attribute requires value or not.   
So need to put name of attribute equals to name of attribute as the value. 
* Attribute values must be inside quotes. 

&nbsp;

##### Document Object Model (DOM) #####
* In `<p> Paragraph Text </p>`, "Paragraph Text" is the **child** of "p" node. 
* And to get the value of paragraph text, need to use `.data`. 

&nbsp;

&nbsp;
----
### Useful links ###
