**Built by:** Mohit Kumar | MIS Executive | Data Analyst

# 📊 Excel Sales Analytics Dashboard

> Skills: VLOOKUP · SUMIF · COUNTIF · Pivot Tables · Charts · Dashboard

## 📁 Project Structure
| Sheet | Description |
|-------|-------------|
| Sales Data | 216 rows, 12 months, 10 products, 4 regions |
| VLOOKUP | Fetches product category & price from reference table |
| COUNTIF & SUMIF | Transaction counts + regional sales totals |
| Pivot Table | Month × Region + Product × Region cross-analysis |
| Dashboard | KPI cards + Line/Bar/Pie charts |

## 💡 Formulas Used
- `VLOOKUP(G3,$A$3:$C$12,2,FALSE)` — product category lookup
- `SUMIF('Sales Data'!C:C,F3,'Sales Data'!H:H)` — regional total
- `COUNTIFS('Sales Data'!E:E,A3,'Sales Data'!C:C,"North")` — conditional count
- `IFERROR(G3/H3,0)` — safe achievement % calculation

## 👤 Author
**Mohit Kumar** | MIS Executive | Data Analyst
📧 Mchahar7@gmail.com
🔗 linkedin.com/in/mohit-kumar-8b6a
