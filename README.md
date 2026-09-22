# File: README.md

# Construction Quotation Calculator

A simple tool for calculating Jua Kali job quotations.
Logs material cost, labor and VAT then calculates total cost of the planned work.

## What It Does

- Logs the key construction recquirements in shillings (material cost, labor, VAT)
- Calculates the total cost of the work
- prints a well organised job quotation


## Setup

```bash
npm install -r requirements.txt
```

## Usage

```javascript
jobs.forEach(q => {
  console.log(`Job: ${q.job}`);
  console.log(`  Materials: KES ${q.materials.toLocaleString()}`);
  console.log(`  Labour: KES ${q.labour.toLocaleString()}`);
  console.log(`  VAT (16%): KES ${q.vat.toLocaleString()}`);
  console.log(`  TOTAL: KES ${q.total.toLocaleString()}`);
```

## Sample Output

```

Job: Floor tiling (45 sqm)
  Materials: KES 8,100
  Labour: KES 5,000
  VAT (16%): KES 2,096
  TOTAL: KES 15,196
```

## Stack

JavaScript
