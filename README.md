# NCSNotes


Reset link - Requirement 
1. link sent to mail 
2. link will be valid for one time password change
3. password should be 8 characters - minimum one uppercase, one special character ($,*,@) - users gets messages stating - "Password successfully changed"
4. launch the application and login to orange hrm using new login will be used


OH_SC_08
	TC1 --> Mail sent (Subject: "Orange HRM reset password link" - validates the mail contain necessary details for resetting the password)
	TC2 --> check url working or not --> (should navigate to reset password page of orange HRM)
	TC3 --> Reset password page UI Component --> (logo, textbox, label as "New Password" , Updated password button) 
	TC4 --> valid password and update password --> "Password successfully changed"
	TC5 --> invalid password - (previous password checks - "New password cannot be previous used password")
	TC6 --> invalid password - (<8 & >8 characters) --> password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC7 --> invalid password - (skip uppercase) --> password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC7 --> invalid password - (skip special character ($,*,@)) --> password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC7 --> invalid password - (use special character other than ($,*,@) ex: &,space) --> password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC8 --> invalid password - (only numbers) -- password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC9 --> invalid password - (space should not be allowed )-- password should be 8 characters - minimum one uppercase, one special character ($,*,@)
	TC10 -->invalid password - blank 
	TC11 --> login page - new password should access the portal 
	TC12 --> login page - try with old password and login - invalid credential 
	
