# anki-cards-header

This simple code will create a sort of "header" in your card's header. Something like this:
![image](https://user-images.githubusercontent.com/121182276/215358027-b8585ec6-4bf0-40f7-a0fb-33703d36b5d4.png)

front (first of all: I recommend you to create a new specific field, for example i've created the field and i called it as "Tag")
<div id="rubric">{{Tag}}</div>


style

#rubric {
  text-align: left;
  padding: 4px;
  padding-left: 10px;
  padding-right: 10px;
  margin-bottom: 10px;
  background: #1d6695;
  color: white;
  font-weight: 500;
}
