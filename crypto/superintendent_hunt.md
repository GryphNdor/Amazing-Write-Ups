# Superindent Hunt

### Basic Info

We are looking for a Virginia School Superintendent but the problem is their last name is hashed. We know that Herron is 89e7bf773f902f7764a48b0b5cf8fa5042d3251988dab10ef7c44c7de41bf0b75265eb4c03b3933657abd443f48cd6c5c2ac3009af8e888dc2bbdbec8a636c8d, Newman is b6ef1fbc9baccb654b7d26c1a0e74d484cf6ea5673e9a00b2f634e25e7946d70c1314b8f341a068cbd8e774b101778535f8270dcab9f0809956803f4397f5f55, and Ratliff is a3ba8188e47cc42473c4756850c573be7a0ce78a506840516448412db9a95d4ea2b44247642702242e70843cc94a2a79086865f487ea1fd920542fd839c200ea. Who is this? be865ba7adac653c60abc1f360c7808bb924c55c9d55c0dba4ef20a881eff2e809737e0105b6fc2742f01f5807b7ef2eb99f4391e218b46f78181745d626d9e1. 

Flag is in normal format with their last name and phone number without dashes

#### Hint:
> What is that hash?

### The Breakdown

Oops a bit of broken puzzle! So if you got it before the patch congrats! If not here is how you would do it.

First identify the hash, I used [CyberChef](https://gchq.github.io/CyberChef/) and identified it as a SHA-512

Go here: [list of super intendents](https://www.va-doeapp.com/SuperintendentBySchoolDivisions.aspx?w=true)

Put all the last names into an Excel spreadsheet and use Python or your language of choice to encrypt all the names to a SHA-512 then use Ctrl + f to find your man.

In this case it was Dr. McDade re-reference the sheet to find his phone number.

### Solution
flag{mcdade7033358854}