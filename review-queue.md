# Review Queue Commands

## RestLi Curli's

### reviewItems/criteriaV4

`
curli --dv-auth SELF --pretty-print "https://aanilkum-mn1.linkedin.biz:4398/review-queue/resources/reviewItems?forceQueryDB=true&q=criteriaV4&searchQueryEntities=List((key:QUEUE_ID,occur:MUST,value:SRQ),(key:TARGET_URN,occur:MUST,value:urn%3Ali%3Aucf%3A%28urn%3Ali%3Amail%3AI6341567332523003904_500%2Curn%3Ali%3Amember%3A108273112%29))&sortAscending=false&sortType=SLA_BREACH_TIMESTAMP&start=0&count=1" -X GET -H 'Accept:application/json' -H 'X-RestLi-Protocol-Version:2.0.0'
`