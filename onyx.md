# Onyx Commands

## Member Token 

`
'mik:token'
`

`
'mik:AwML2w43Bc4JwwAAAXVzoEB4AAABdXPXLvhVAgADtaEAAAVzQUNDRVNTX0NISU5BX0pPQl9QT1NURVJfUkVWSUVXX1FVRVVFLEFDQ0VTU19DUkVBVE9SX0FQUExJQ0FUSU9OX1JFVklFV19RVUVVRSxBQ0NFU1NfTElTVEVOSU5HX1JFVklFV19RVUVVRSxBQ0NFU1NfTUVNRV9SRVZJRVdfUVVFVUUsQUNDRVNTX1BST0ZJTkRFUl9SRVZJRVdfUVVFVUUsQUNDRVNTX1NQQU1fUkVWSUVXX1FVRVVFLEFDQ0VTU19UQUdHSU5fU1BBTV9SRVZJRVdfUVVFVUUsQUNUSVZFLEFERF9BQ0NPVU5UX1JFU1RSSUNUSU9OLEFERF9SRUNPTk5FQ1RfUkVTVFJJQ1RJT04sQk9VTkNFX0VNQUlMLEJVTEtfQ0xPU0UsQ0hJTkFfRUFQX0FDQ0VTUyxDTE9TRV9BQ0NPVU5ULENPUlBfQURNSU4sR1JBTlRfUFJFT1JERVIsSU5CT1hfTUVTU0FHRVNfUkVBRF9QRVJNSVNTSU9OLElOVkFMSURBVEVfQUxMX1NFU1NJT05TLExJU0FfQURfU1VQRVJfQURNSU4sTElTQV9NQU5BR0VfQUQsTElTQV9NQU5BR0VfQURfQUNDT1VOVCxMSVNBX01BTkFHRV9DQVAsTElTQV9NQU5BR0VfQ09NUEFOWSxMSVNBX01BTkFHRV9HUk9VUCxMSVNBX1ZJRVdfQUxMX0FEX0FDQ09VTlRTLExPR0lOX0FTX01FTUJFUl9VTlJFU1RSSUNURUQsTUFOQUdFX0FEUyxNQU5BR0VfQUxDQVRSQVpfTUVNQkVSUyxNQU5BR0VfQ0hJTkFfQ09OVEVOVF9SRVZJRVdfUVVFVUUsTUFOQUdFX0NISU5BX0pPQl9QT1NURVJfUkVWSUVXX1FVRVVFLE1BTkFHRV9DSElOQV9NRU1CRVJTLE1BTkFHRV9DT01QQU5ZX1BBWU1FTlRfQUNDT1VOVFMsTUFOQUdFX0NPTlRFTlRfU0VDVVJJVFlfUE9MSUNZLE1BTkFHRV9DT05URU5UX1NQQU1fVE9PTCxNQU5BR0VfQ09SUF9NRU1CRVJTLE1BTkFHRV9NRU1CRVIsTUFOQUdFX09USEVSX0NTX1VTRVJTLE1BTkFHRV9QUk9GSU5ERVJfUkVWSUVXX1FVRVVFLE1BTkFHRV9ST0xFUyxNQU5BR0VfU1BBTV9SRVZJRVdfUVVFVUUsTUFOQUdFX1NQQU1fUlVMRVMsTUFOQUdFX1NUT1BXT1JELE1BTkFHRV9UQUdHSU5fU1BBTV9SRVZJRVdfUVVFVUUsTUFTU19DTE9TRSxNQVNTX0xPR0lOX1JFU1RSSUNUSU9OLE1BU1NfTkFNRV9WSU9MQVRJT05fUkVTVFJJQ1RJT04sTUFTU19OT1RFUyxNQVNTX1BBU1NXT1JEX0lOVkFMSURBVElPTixNQVNTX1BBU1NXT1JEX1ZBTElEQVRJT04sTUFTU19TUEFNX1JFU1RSSUNUSU9OLE1BU1NfU1VTUEVOU0lPTixNQVNTX1RJRVJFRF9CT1RfUkVTVFJJQ1RJT04sTUFTU19VTlJFU1RSSUNUSU9OLE1FUkdFX0FDQ09VTlQsUkVNT1ZFX0FDQ09VTlRfUkVTVFJJQ1RJT04sUkVNT1ZFX1JFQ09OTkVDVF9SRVNUUklDVElPTixSRVZJRVdfUEhPVE8sU0VDVVJJVFlfTElTVCxTT0xVVElPTl9CVUlMREVSX0FETUlOLFNPTFVUSU9OX0JVSUxERVJfUVVPVElORyxTUEFNX0FETUlOLFVDU19BRE1JTixVQ1NfV0lORE9XU19BRE1JTixWSUVXX1NUT1BXT1JEf-9gYLL9s6bJdUt8wSiMo7S5U1bYhNJCzuCI5GitqW4kEhurrPqtzfz5mM3gBhkGeMYESOqHZCy07BWxoQBlNw'
`
## RestLi Commands
---
### onyxMemberAvailability

```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --ic 'mik:' https://localhost:9443/onyx/api/onyxMemberAvailability\?cluster\=WORKBENCH
```

```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --ic 'mik:' https://localhost:9443/onyx/api/onyxMemberAvailability -X PUT --data '{ "available": true }'
```

### onyxAgent

```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --ic 'mik:' https://localhost:9443/onyx/api/onyxAgent/
```

### onyxTask
```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --ic 'mik:' https://localhost:9443/onyx/api/onyxTask/urn:li:ucf:(urn:li:mail:I6712672945052925952_500,urn:li:member:231148003)
```

### onyxProfile
```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --ic 'mik:' https://localhost:9443/onyx/api/onyxProfile/
```

### onyxContent

```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --li-at-cookie '' https://localhost:9443/onyx/api/onyxTask/urn:li:reviewItem:43752606
```

### presentationConfig
```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --li-at-cookie '' https://localhost:13574/onyx/api/presentationConfig/urn:li:jobPosting:2834562589
```

### Create a review Item

```
curli --insecure -i -H 'X-RestLi-Protocol-Version: 2.0.0' -H 'Accept:application/json' -H 'Content-Type:application/json' --fabric ei-ltx1 --dv-auth SELF --li-at-cookie '' https://localhost:9443/onyx/api/onyxTask/urn:li:reviewItem:-1?action=createByTarget --data-raw '{"target": "urn:li:dummy:123", "assignee": "urn:li:csUser:418005", "author": "urn:li:member:418005" , "notes":"Just testing.", "context" : { "context": { "com.linkedin.onyx.task.ReviewerContext": {  "queueId" : "SRQ" } } } }'

```

--------------------------------------------------------------------------------
## Sample Content

### EI Sample Data

- `
  urn:li:ucf:(urn:li:mail:I6478521261768093696_500,urn:li:member:191029568)
  `
- `
   urn:li:ucf:(urn:li:mail:I6722746642543493120_500,urn:li:member:223412998)
  `
