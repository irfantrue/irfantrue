Hi 👋 My name is Irfan Nurul Susilo
===================================

Backend Developer
-----------------


*   🌍  I'm based in Jakarta, Indonesia
*   ✉️  You can contact me at [irfansusilo88@gmail.com](mailto:irfansusilo88@gmail.com)
*   🧠  I'm learning Javascript, Nodejs, Expressjs, MYSQL, Mongodb

### Skills 

<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a>
<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a>
<a href="https://expressjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored.svg" width="36" height="36" alt="Express" /></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" /></a>
</p>
                    

### Socials

<p align="left"> <a href="https://www.github.com/irfantrue" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /></a> <a href="https://www.linkedin.com/in/irfan-nurul-susilo-904854211/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" /></a></p>

# Accounting Invoice Settlement

## Invoice Settlement Header

Type | Value
-----|-------
**HTTP Methode** | GET
**Production**  | https://api.nmwclinic.co.id/
**Sandbox**  | https://api-sandbox.nmwclinic.co.id/

Sample query endpoint

```
https://api-sandbox.nmwclinic.co.id/accounting/invoice-settlement?page=1&limit=5

```

Tipe data

Label | Type | Description
------|------|------------
category | String | -

Sample payload body

```json
{
  "category": "Settlement SBA-4004-1030231181652 20230213534948.xlsx"
}
```
> Default respond if you not give category, page and limit

Sample succuess respond

```json
{
  "status": true,
  "date": "2023-02-22T06:44:24.254Z",
  "result": {
    "page": {
      "size": 10,
      "total": 261,
      "totalPages": 27,
      "currentPage": 1
    },
    "data": [
      {
        "fileName": "Settlement SBA-4004-1030231181652 20230209715093.xlsx",
        "totalAmountPurchase": "2,868,750",
        "totalFee": "65,835",
        "totalPurchase": "14",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "2,802,915",
        "totalTransactions": "14",
        "batch": "B-BSN-0411-5206464580888-SBA-4004-1030231181652-20230208163034948"
      },
      {
        "fileName": "Settlement SBA-4004-1030231181652 20230213534948.xlsx",
        "totalAmountPurchase": "9,017,085",
        "totalFee": "106,695",
        "totalPurchase": "23",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "8,910,390",
        "totalTransactions": "23",
        "batch": "B-BSN-0411-5206464580888-SBA-4004-1030231181652-20230211003012799"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205511901 20230209219083.xlsx",
        "totalAmountPurchase": "756,300",
        "totalFee": "9,080",
        "totalPurchase": "2",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "747,220",
        "totalTransactions": "2",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205511901-20230208163033994"
      },
      {
        "fileName": "Settlement SBA-4004-1030231181652 20230214710467.xlsx",
        "totalAmountPurchase": "12,669,600",
        "totalFee": "212,340",
        "totalPurchase": "43",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "12,457,260",
        "totalTransactions": "43",
        "batch": "B-BSN-0411-5206464580888-SBA-4004-1030231181652-20230211003102193"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205511901 20230213281627.xlsx",
        "totalAmountPurchase": "1,013,345",
        "totalFee": "14,075",
        "totalPurchase": "3",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "999,270",
        "totalTransactions": "3",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205511901-20230211003144130"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205511901 20230214663424.xlsx",
        "totalAmountPurchase": "239,760",
        "totalFee": "9,585",
        "totalPurchase": "2",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "230,175",
        "totalTransactions": "2",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205511901-20230211003102822"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205515343 20230209630752.xlsx",
        "totalAmountPurchase": "632,690",
        "totalFee": "9,080",
        "totalPurchase": "2",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "623,610",
        "totalTransactions": "2",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205515343-20230208163034624"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205517877 20230213041201.xlsx",
        "totalAmountPurchase": "1,043,955",
        "totalFee": "9,535",
        "totalPurchase": "2",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "1,034,420",
        "totalTransactions": "2",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205517877-20230210163027512"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205517877 20230213090963.xlsx",
        "totalAmountPurchase": "1,646,960",
        "totalFee": "22,700",
        "totalPurchase": "5",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "1,624,260",
        "totalTransactions": "5",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221020205515343-20230210163028234"
      },
      {
        "fileName": "Settlement SBS-0008-20221020205517877 20230213182898.xlsx",
        "totalAmountPurchase": "800,530",
        "totalFee": "9,535",
        "totalPurchase": "2",
        "totalAmountRefund": "0",
        "totalRefund": "0",
        "totalSettlementAmount": "790,995",
        "totalTransactions": "2",
        "batch": "B-BSN-0411-5206464580888-SBS-0008-20221024105426682-20230210163027555"
      }
    ]
  }
}
```

Sample error respond

```json
{
  "status": false,
  "date": "2023-02-22T06:53:39.444Z",
  "message": "Category doesnt exist"
}
```

Sample error respond page out of range total page

```json
{
  "status": false,
  "date": "2023-02-22T06:53:39.444Z",
  "message": "Current page must minimum 1 and range of total page"
}
```

## Invoice Settlement body transaction

Type | Value
-----|-------
**HTTP Methode** | GET
**Production**  | https://api.nmwclinic.co.id/
**Sandbox**  | https://api-sandbox.nmwclinic.co.id/

Sample query

```
https://api-sandbox.nmwclinic.co.id/accounting/invoice-settlement/transaction?batch_id=B-BSA
```

Sample success respond

```json
{
  "status": true,
  "date": "2023-02-22T06:13:51.833Z",
  "result": [
    {
      "merchantName": "IGYOLINI INDONESIA",
      "paymentChannelName": "VA BNI",
      "transactionDate": "11-02-2023",
      "invoiceNumber": 201060220231,
      "customerName": "Doku-KURNIASIH",
      "reportCode": "8291300000693372",
      "amount": "269,730",
      "reconCode": "8291300000693372",
      "fee": "4,995",
      "payToMerchant": "264,735",
      "payOutDate": "13-02-2023",
      "transactionType": "Purchase",
      "branch": "Kalimalang",
      "company": "PT Igyolini Indonesia"
    },
    {
      "merchantName": "IGYOLINI INDONESIA",
      "paymentChannelName": "VA BRI",
      "transactionDate": "11-02-2023",
      "invoiceNumber": 201060220231,
      "customerName": "Sumita Ramadhanti ",
      "reportCode": "1236260006494133",
      "amount": "530,800",
      "reconCode": "1236260006494133",
      "fee": "4,540",
      "payToMerchant": "526,260",
      "payOutDate": "13-02-2023",
      "transactionType": "Purchase",
      "branch": "Kalimalang",
      "company": "PT Igyolini Indonesia"
    }
  ]
}
```

Sample error respond

```json
{
  "status": false,
  "date": "2023-02-22T06:53:39.444Z",
  "message": "Parameter id harus ada"
}
```

## Invoice Settlement Transaction Detail

Type | Value
-----|-------
**HTTP Methode** | GET
**Production**  | https://api.nmwclinic.co.id/
**Sandbox**  | https://api-sandbox.nmwclinic.co.id/

Sample query

```
https://api-sandbox.nmwclinic.co.id/accounting/invoice?invoice_number=23322022318
```

Sample success respond

```json
{
  "status": true,
  "date": "2023-02-22T05:00:23.522Z",
  "result": {
    "medicalRecors": null,
    "customer": {
      "name": "KHOIRUL ANWAR",
      "phone": 83877206606,
      "email": "khoerlanwar@gmail.com"
    },
    "branch": {
      "name": "Web NMW",
      "phone": 6281280360370,
      "email": null,
      "address": "Jl. Petogogan II No.29, Rw. 6, Kelurahan Pulo, Kecamatan Kebayoran Baru, Kota Jakarta Selatan, Provinsi DKI Jakarta",
      "province": "DKI Jakarta",
      "district": "Jakarta Selatan",
      "company": "PT. Royal Igyolini Indonesia"
    },
    "items": [
      {
        "name": "NMW SERUM VIT C 20 ML",
        "price": 175000,
        "quantity": 1,
        "subTotal": 131250,
        "discount": [
          {
            "methode": "PERCENTAGE",
            "value": 25
          }
        ]
      }
    ]
  }
}
```

Sample error respond

```json
{
  "status": false,
  "date": "2023-02-22T06:53:39.444Z",
  "message": "Parameter id harus ada"
}
```
