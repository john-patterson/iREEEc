class App
{
	let connection  = []; /* array of conection objects */
	let window	= []; /* connection wide windows suchas about window */
	let setting	= new Setting(); /* setting singleton */
}

class Connection
{
	let server 	= '';
	let port	= 0;
	let mode	= 0x0; /* mode in octals */
	let unused	= '*'; /* unused in IRC but it is part of logging in process */

	/* this is wrong */
	let connection = '';


	constructor(url, port, username, realWorldName)
	{
		
	}

	/* sends string to irc */
	dispatch(string)
	{
		let reply = ;
		if (!reply) /* if no reply or error or whatever do that here */
			throw "Bad Reply";
		else
		{	/* do proper tasks here */
			switch(n)
			case:
			default:
			break;
		}
	}

}

/* this is based on what is returned from server */
class User
{
	let host     = '';
	let ip       = '';
        let username = '';
	let flags    = '';
	let 
}

class Utility
{
	testFlag(flagString)
	{
		if(flagString.includes(flagString))
			return true;
		else
			return false;

		return;
	}

	setFlag(flagString, flagStringToInsert)
	{
		let stringArray = flagStringToInsert.split();
		
		stringArray.foreach(x => {
			if(!flagString.includes(x))
				flagString += x;
		});
	}

}

class Admin extends User
{
	
}

class Message
{
	let recipitent  = ''; /* in case of channels recipitent is channel name */
	let sender 	= ''; /* in case of channels whomever sent the message */
	let flags	= ''; /* some flags */
}

/* Channel is different in that it contains a user list */
class Channel extends Message
{
	let userList 	= [];	/* contains list of User objects */
}
