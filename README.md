# data1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TableDetails</title>
</head>
<body>
    <h1>MergedTable Table</h1>
    <h2>Table Structure</h2>
    <ul>
        <li>Column1 - Primary Key</li>
        <li>Column2 - Name</li>
      <li>Column3 - PHONENUMBER</li>
      <li>Column4 - BANK</li>
      <li>Column5 - ACCOUNTNEMBER</li>
      <li>Column6 - Location</li>
      <li>Column7 - Sex</li>
      <li>Column8 - Amount</li>
      <li>Column9 - NewPrimaryKey</li>
      <li>Column10 - ProductID</li>
      <li>Column11 - ProductName</li>
    </ul>
    <h2>Example Queries</h2>
    <pre>
   --All beneficiaries who are female
SELECT * FROM [dbo].[MergedTable]
WHERE SEX='F'
    </pre>
  <pre>
    --Give all beneficiaries who banks with Access Bank
SELECT * FROM [dbo].[MergedTable]
WHERE BANK='Access Bank'
  </pre>
  <pre>
   --Give all beneficiaries who phone number is mtn i.e. starts with 0806 and 0803
SELECT * FROM [dbo].[MergedTable]
WHERE LEFT(PHONENUMBER,4)='0806'OR LEFT(PHONENUMBER,4)= '0803'
  </pre>
    <a href="../index.html">Back to main page</a>
</body>
</html>
