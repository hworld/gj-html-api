gj-html-api
===========

Example usage:

	GJAPI.sendRequest( '/users/auth/?username=tester&user_token=token', function( response ){
		if ( response.success == 'true' ) {
			alert( 'user logged in!' );
		}
	} );