#L3NM Meeting 
Date: 16/7/2019
##Assistants:
Oscar Gonzalez de Dios (Telefonica)
Samier Barguil (Telefonica) 
Qin Wu (Huawei)
Luis (Vodafone)

##Material 
Last version published: https://tools.ietf.org/html/draft-aguado-opsawg-l3sm-l3nm-01      
Last version of the Yang module: https://github.com/oscargdd/l3nm/tree/master/yang/02
List of issues available in https://github.com/oscargdd/l3nm/issues
    
##Agenda:

- Changes completed from -01
- Pending issues and open points

##Discussion

    The Site Attachment issue must be added to the Github Repository [Qin] - Done [https://github.com/oscargdd/l3nm/issues/8] : Extra Slot for the Next of the week.

2. Issue related to "Reference from Site Network Accesses" [Luis/Daniel].
3. It is necesary to find an operator where ISIS between CE-PE is requiered. If not this is not an urgent requeriment. 
4. Issue #2 needs further clarification. Luis and Oscar think segment routing is related to the transport and does not need to be in the model.
5. Issue #3. RD/RT no IE-profile reuse.

   Suggestion: Add RD*/RT* as optional under VPN

    IE profile would be mantained 

    If the RD*/RT* is filled the IE Profile is overwritten.

    maybe we can add YANG when/must statement  to make sure the IE profile is not empty.

6. Auto Assigment of the RD/RTs

    In multi-area scenarios the OSS must provide the parameters. 

    The Controller must fill the parameters that are empty

    The RD/RT must be readable under VPN Node. When the controller fills it automatically. 

7. Issue  #7. We can add flexibility in the creation of the sites. But we need to find a use case that can be solved with the group id.

    the origin group-id cames from the L3SM to choose the PE and becomes useless and new access group-id is used to classify

    network acesses based on other criteria.  Introduce vpn-id under each network access is not neccesary since all network accesses belong to the same vpn.


##Next Steps
Prepare Slides for the IETF presentations (OPSAWG and RTWG).

