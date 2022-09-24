# just download the jar file 
and import into anypointstudio
deploy the application  or 
directly deploy into runtime manager 

protocol:htttp
host:localhost
pass uriparams  and queryparams

note 
  the uriparam is the the key (what you want to change key )
  
  example: 
  the end point is http:localhost:8083/renamekeys/emptyseats?seat=seats
  the payload is { seats:45}
           the result payload is {emptyseats:45}
           
   explanation:
     from the above endpoint the uriparam is the key  in the result payload 
     
     and queryparams helps to query the key is present or not
     
     
 note 
     only one key we can change at a time
           
    
  
