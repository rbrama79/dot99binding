# JSON Object Exchanges in Primitives

In P1451.99.0 JSON objects are used as the unique data format exchanged in communication 
primitives. Each one of those admits different JSON objects. Some of those have been
showcased during IECON 2022 Demonstration

## HARmonization Layer (HARL)

This layer is used to abstract the binding towards the P.99 network. The XMPP network will 
trigger, by means of a XMPP message, an invocation to one of the HARL primitives towards the
binding gateway. On the other side, if the binding desires to send data towards the P.99 network
it will do that by means of an appropriate primitive receiving a JSON object that will
be translated in the appropriate XMPP stanza. Examples of JSON objects shown during the 
demo are listed below:

* [HARL-Set_Req](harl-set-req.json)
* [HARL-Set_Conf](harl-set-conf.json)
	
##  Specific Gateway Interface (SGI)

This layer abstracts the non-1451 technology that needs to be bound to the 1451 family 
by means of the binding gateway. The binding gateway will invoke specific primitives towards the 
SGI layer requesting a JSON object as argument. The same will be done as soon as one of the abstracted 
non-1451 need to interact with the P.99 network. JSON object shown during the 2022 IECON demo are
listed here below.
	
* [SGI-Discovery_Ind](sgi-discovery-ind.json)
* [SGI-Discovery_Resp](sgi-discovery-resp.json)
* [SGI-SendData_Ind](sgi-senddata-ind.json)
* [SGI-SendData_Resp](sgi-senddata-resp.json)