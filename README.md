🎯 Objective:
To test a RESTful API that fetches vaccination certificate details and ensures data integrity through comprehensive validations.

📋 Key Highlights:
✅ Setting up the Base URI using a properties file
✅ Sending GET requests with path parameters
✅ Validating fields like vaccineName, doseCount, vaccinationDate
✅ Handling error scenarios like invalid certificate IDs
✅ Asserting status codes, response time, and headers
✅ Adding new values to test robustness

🧾 API Fields Tested:
• certificateId
• fullName
• vaccineName (Covishield, Covaxin, Sputnik)
• doseCount
• vaccinationDate
• location
