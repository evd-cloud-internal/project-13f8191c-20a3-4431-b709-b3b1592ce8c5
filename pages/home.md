---
name: Home
assetId: 15f26fe0-5f48-4db2-96d4-216120b0eb49
type: page
---

# Welcome

This is your new project's homepage. Edit this file to get started.

{% area_chart
    data="demo_daily_orders"
    x="date"
    y="sum(total_sales) + 100000"
    date_grain="week" 
/%}