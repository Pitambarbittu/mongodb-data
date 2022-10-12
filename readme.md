# Q1-  Create a database , give it name like "Human-Resource". Create a collection inside this named "employee".

```
 show dbs
Human_Resource  40.00 KiB
admin           40.00 KiB
config          72.00 KiB
local           40.00 KiB
test            40.00 KiB
 use Human_Resource
switched to db Human_Resource
Human_Resource> db.employee.inserMany([
...   {
...
...     firstName: 'John',
...     lastName: 'Doe',
...     salary: '25000',
...     department: 'HR',
...     lastCompany: 'X',
...     lastSalary: '10000',
...     overallExp: '2',
...     contactInfo: '1234567890',
...     yearGrad: '2016',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'roh',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   }
... ])
TypeError: db.employee.inserMany is not a function
Human_Resource> db.employee.insertMany([
...   {
...
...     firstName: 'John',
...     lastName: 'Doe',
...     salary: '25000',
...     department: 'HR',
...     lastCompany: 'X',
...     lastSalary: '10000',
...     overallExp: '2',
...     contactInfo: '1234567890',
...     yearGrad: '2016',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'roh',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   },
...   {
...
...     firstName: 'Rohan',
...     lastName: 'Jame',
...     salary: '30000',
...     department: 'Technical',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '1',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '20000',
...     overallExp: '1',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'ECE'
...   },
...   {
...
...     firstName: 'Sao',
...     lastName: 'Avika',
...     salary: '30000',
...     department: 'Sales',
...     lastCompany: 'Y',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '1234567860',
...     yearGrad: '2015',
...     gradStream: 'CSE'
...   },
...   {
...
...     firstName: 'Jame',
...     lastName: 'Doe',
...     salary: '35000',
...     department: 'Accounts',
...     lastCompany: 'Z',
...     lastSalary: '15000',
...     overallExp: '2',
...     contactInfo: '123567890',
...     yearGrad: '2019',
...     gradStream: 'EEE'
...   }
... ])
{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId("6346ef20371f1650e33dbfae"),
    '1': ObjectId("6346ef20371f1650e33dbfaf"),
    '2': ObjectId("6346ef20371f1650e33dbfb0"),
    '3': ObjectId("6346ef20371f1650e33dbfb1"),
    '4': ObjectId("6346ef20371f1650e33dbfb2"),
    '5': ObjectId("6346ef20371f1650e33dbfb3"),
    '6': ObjectId("6346ef20371f1650e33dbfb4"),
    '7': ObjectId("6346ef20371f1650e33dbfb5"),
    '8': ObjectId("6346ef20371f1650e33dbfb6"),
    '9': ObjectId("6346ef20371f1650e33dbfb7"),
    '10': ObjectId("6346ef20371f1650e33dbfb8"),
    '11': ObjectId("6346ef20371f1650e33dbfb9"),
    '12': ObjectId("6346ef20371f1650e33dbfba")
  }
}
Human_Resource> db.employee.find().pretty()
[
  {
    _id: ObjectId("6346ef20371f1650e33dbfae"),
    firstName: 'John',
    lastName: 'Doe',
    salary: '25000',
    department: 'HR',
    lastCompany: 'X',
    lastSalary: '10000',
    overallExp: '2',
    contactInfo: '1234567890',
    yearGrad: '2016',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfaf"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb0"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb1"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb2"),
    firstName: 'Jame',
    lastName: 'roh',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb3"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb4"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb5"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb6"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb7"),
    firstName: 'Rohan',
    lastName: 'Jame',
    salary: '30000',
    department: 'Technical',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '1',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb8"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '20000',
    overallExp: '1',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'ECE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfb9"),
    firstName: 'Sao',
    lastName: 'Avika',
    salary: '30000',
    department: 'Sales',
    lastCompany: 'Y',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '1234567860',
    yearGrad: '2015',
    gradStream: 'CSE'
  },
  {
    _id: ObjectId("6346ef20371f1650e33dbfba"),
    firstName: 'Jame',
    lastName: 'Doe',
    salary: '35000',
    department: 'Accounts',
    lastCompany: 'Z',
    lastSalary: '15000',
    overallExp: '2',
    contactInfo: '123567890',
    yearGrad: '2019',
    gradStream: 'EEE'
  }
]

```