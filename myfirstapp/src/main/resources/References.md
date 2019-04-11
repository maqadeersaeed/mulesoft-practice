MEL Implicit Objects
	message	=> Mule Message
	payload => message.payload
	server	=> server specific details, ref ServerContext
	mule	=> Mule instance specific details, ref MuleInstanceContext
	app		=> Application specific details, ref AppContext
	flowVars	=> Variables available in the Flow Only
	sessionVars	=> session variables