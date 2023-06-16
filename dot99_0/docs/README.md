# Structure of the 2022 IECON Demo

During the demo the following webmethods, implementing the P.99.0 cited primitives were shown

## Primitive name: SGI-Discovery-Ind

	Web method: http://127.0.0.1/p1451_99_0/SGI-Discovery-Ind
	Used by: devices to register to a P1451.99.0 Gateway. We will register 2 devices. So please note sgi-discovery-ind.json
	         and sgi-discovery-ind.json reports 2 objects. Theoretically they will come in 2 different "instants". By the way,
			 also this may be not mandatory.
	JSON Posted Objects: sgi-discovery-ind.json
	JSON Replies: sgi-discovery-resp.json
	
## Primitive name: SGI-SendData_Ind

	Web method: http://127.0.0.1/p1451_99_0/SGI-SendData_Ind
	Used by: devices to publish data. We will only have publish requests from the sensor
	JSON Posted Objects: sgi-senddata-ind.json
	JSON Replies: sgi-senddata-resp.json
	
## Primitive name: HARL-Set_Req (only if 1451.99 side is able to trigger this on message reception)

	Web method: http://127.0.0.1/p1451_99_0/HARL-Set_Req
	Used by: 1451.99 side to handle the actuator. We will receive a XMPP message producing the HARL-Set_Req 
	         with that JSON object reporting what we should do at SGI level. Of course since we do not know what the SGI
			 will do, we will simply send to the correct SGIaddr the JSON object with SGIadd instead of JID. I'm not showing the
			 SGI-SendCommand_Req. I think it is not necessary. What do you think?
	JSON Posted Objects: harl-set-req.json
	JSON Replies: harl-set-conf.json
	
# References
	
For more information please refer to:

* [Paper About the IECON 2022 Demonstration](./INTEROP2022-A_New_Architectural_Approach_for_P1451_99_Binding_to_P1451_0.pdf)
* [Presentation held during IECON 2022 Demonstration](./20221018-P1451_99_0-A_First_Proposal.pdf)
