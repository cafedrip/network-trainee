# ospf settings

conf t

interface $(interface)
 ip ospf authentication-key $(key)
 ip ospf cost $(cost)
 
router ospf $(process-ID)
 network $(address) <wildcard mask> area $(area (ex. 0.0.0.1))
end

